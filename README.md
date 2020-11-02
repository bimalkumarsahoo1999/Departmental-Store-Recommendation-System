# Departmental Store Recommending System
It uses __Apriori__ algorithm.

Apriori is an algorithm for frequent item set mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database. The frequent item sets determined by Apriori can be used to determine association rules which highlight general trends in the database: this has applications in domains such as market basket analysis.

Support (M) = (# user watchlists containing M) / (# user watchlists)

Confidence (M1->M2) = (# user watchlists containing M1 & M2)
/ (# user watchlists containg M1)

Lift(M1->M2) = Confidence (M1->M2) / (Support (M2) )
___

## Procedure
1. Set a minimum support and Confidence.
2. Take all the subsets in transactions having higher support than minimum support.
3. Take all the rules of these subsets having higher confidence than minimum confidence.
4. Sort the rules by decreasing lift.
___

The __Apriori__ algorithm is used to build recommendation systems.



![apriori](https://miro.medium.com/max/1200/1*eZ4KmU0phwgVuL8gQ3_brA.png)



