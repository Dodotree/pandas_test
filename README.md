# pandas_test
test for airbnb

We want to get answers to a few questions

(1) Using unique_host_id, how many unique hosts are there in Vancouver?

(2) How many unique hosts are there by neighborhood (i.e. how many distinct unique_host_id values by neighborhood)?

(3) We will consider any two listings with the same unique_host_id or the same external_property_id to be managed by the same host. How many unique hosts are there? (Build a graph where the nodes are the listings and the edges are defined as having the same unique_host_id OR the same external_property_id then count the connected components.)

Please write this up as a jupyter notebook using pandas.

#########################

host->property break apart clusters by (host OR property)

Test contained chained clusters and obscure data like properties without hoste and vise versa

Chained:

A->X (A=X)

B->Y (B=Y)

A->Y (A=Y=B=X) All in the same cluster
