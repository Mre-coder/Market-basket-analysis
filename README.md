# Market-basket-analysis
Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.

Association Rules are widely used to analyze retail basket or transaction data, and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules. The outcome of this type of technique is, in simple terms, a set of rules that can be understood as “if this, then that”.
An example of Association Rules

Assume there are 100 customers
10 of them bought milk, 8 bought butter and 6 bought both of them.
bought milk => bought butter
support = P(Milk & Butter) = 6/100 = 0.06
confidence = support/P(Butter) = 0.06/0.08 = 0.75
lift = confidence/P(Milk) = 0.75/0.10 = 7.5
Note: This example is extremely small. In practice, a rule needs the support of several hundred transactions, before it can be considered statistically significant, and datasets often contain thousands or millions of transactions.
We are going to use the Apriori algorithm to perform a Market Basket Analysis in this project. Apriori algorithm is a classical algorithm in data mining. It is used for mining frequent itemsets and relevant association rules. It is devised to operate on a database containing a lot of transactions, for instance, items brought by customers in a store.
