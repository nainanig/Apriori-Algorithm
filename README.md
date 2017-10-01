# Apriori-Algorithm
Data Mining : Association Rules Analysis

DataSet Description- The dataset is about gene expressions (association-rule-test-data.txt) and can be found on
Piazza. Each row stands for a patient/sample. The last column is the disease name. For
the rest columns, they are gene expressions with values Up or Down (Binary Value). For
example, the row “Down Down Down Up ... AML” can be interpreted as “G1_ Down
G2_ Down G3_ Down G4_Up ... AML”, and AML is a disease name.

Required Tasks- 1. Implement the Apriori algorithm to find all frequent itemsets. Report the number
of frequent itemsets for support of 30%, 40%, 50%, 60%, and 70%, respectively.
Please see Template.pdf for details.
You should not directly call any existing function or package that implements
Apriori. Apriori algorithm should be implemented by yourself. If you are not
sure about whether it is OK to use a certain function, please post your question on
Piazza.
2. Generate association rules based on the templates. The following are templates:
Template 1: {RULE|BODY|HEAD} HAS ({ANY|NUMBER|NONE}) OF
(ITEM1, ITEM2, ..., ITEMn)
Template 2: SizeOf({BODY|HEAD|RULE}) ≥ NUMBER.
Template 3: Any combined templates using AND or OR. For example:
HEAD HAS (1) OF (Disease) AND BODY HAS (NONE) OF (Disease)Below is an example illustrating RULE, BODY and HEAD in the templates:
Assume we obtain a RULE {G1_Up, G3_Down}  {G4_Down, G34_Up}.
{G1_Up, G3_Down} is BODY and {G4_Down, G34_Up} is HEAD.
