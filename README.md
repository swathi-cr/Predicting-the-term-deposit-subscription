# Predicting-the-term-deposit-subscription
Ensemble Techniques
Leveraged customer information of bank marketing campaigns to predict whether a customer will subscribe to term deposit or not. Different classification algorithms like Decision tree, Logistic Regression were used. Ensemble techniques like Random forest were used to further improve the classification results.

Skills and Tools

Classification, Decision Tress, Ensemble Techniques

Data Description:
The data is related with direct marketing campaigns of a Portuguese banking institution.
The marketing campaigns were based on phone calls. Often, more than one contact to
the same client was required, in order to access if the product (bank term deposit) would
be ('yes') or not ('no') subscribed.
Domain:
Banking
Context:
Leveraging customer information is paramount for most businesses. In the case of a bank,
attributes of customers like the ones mentioned below can be crucial in strategizing a
marketing campaign when launching a new product.
Attribute Information:
1. age (numeric)
2. job : type of job (categorical: 'admin.','bluecollar','entrepreneur','housemaid','management','retired','selfemployed','services','student','technician','unemployed','unknown')
3. marital : marital status (categorical: 'divorced','married','single','unknown';
note: 'divorced' means divorced or widowed)
4. education (categorical:
'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','univers
ity.degree','unknown')
5. default: has credit in default? (categorical: 'no','yes','unknown')
6. balance: average yearly balance, in euros (numeric)
7. housing: has housing loan? (categorical: 'no','yes','unknown')
8. loan: has personal loan? (categorical: 'no','yes','unknown')
9. contact: contact communication type (categorical: 'cellular','telephone')
10.day: last contact day of the month (numeric 1 -31)
11.month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
12.duration: last contact duration, in seconds (numeric). Important note: this
attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet,
the duration is not known before a call is performed. Also, after the end of the
call y is obviously known. Thus, this input should only be included for benchmark
purposes and should be discarded if the intention is to have a realistic predictive
model.
13.campaign: number of contacts performed during this campaign and for this
client (numeric, includes last contact)
14.pdays: number of days that passed by after the client was last contacted from a
previous campaign (numeric; 999 means client was not previously contacted)
15.previous: number of contacts performed before this campaign and for this client
(numeric)
16.poutcome: outcome of the previous marketing campaign (categorical:
'failure','nonexistent','success')
17.target: has the client subscribed a term deposit? (binary: "yes","no")

