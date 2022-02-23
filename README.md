## Apriori_algorithm_to_make_association_rules
Apriori algorithm is used for finding the frequent itemsets in dtaset. It is named as apriori because it uses prior knowledge of frequent itemsets for making association rules.This works on databasess whcih contains transactions.
## Problem Statement
We hve to design a business case in which we have to frame associate rules by creating our own dataset.
The associate rules were comprised of 3 matrices called support, confidence, lift values.
## Approach
I satrted framing my own dataset called material data. In that I made 7 columns named as order id,order date,material,quantity,unit price,customer segment.The numerical columns were orde id, quantity, unit price and the categorical data is material and customer segment. The shape of the data were 200*7.
The created datasets we grouped by using the material column which has 4 material types aluminium,copper, iron and zinc.The most frequently purchase item were aluminium.We applied apriori algorithm on the above dataset and framed the rules by using minimum support value as 0.08 with min_threshold as 1.
## outcome
The associate rule incresed the frequency of customer product recommendation as the customer who buys the material for their business how frequently he can buy other items too alongwith it.
