## Infoviz on  Amazon Product Co-Purchasing Network and Ground-Truth Communities

Dataset Link :https://snap.stanford.edu/data/com-Amazon.html  
It is based on Customers Who Bought This Item Also Bought feature of the Amazon website. If a product i is frequently co-purchased with product j, the graph contains an undirected edge from i to j. Each product category provided by Amazon defines each ground-truth community.

### Infoviz using Node-Link diagram:  
We filtered the dataset to focus on key relationships and used NetworkX to create an undirected graph, identifying the most popular product by node degrees. Filtering 1st and 2nd-level co-purchases reduced the dataset to 1,315 nodes and 1,813 edges, simplifying analysis while retaining key patterns. Node-link diagrams were visualized in Gephi using layouts like Force Atlas, Yifan Hu, Fruchterman-Reingold, Radial axis, OpenOrd using Gephi.
