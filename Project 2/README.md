# Abstract:

Following our previous project in which we studied the network of Count Leo Tolstoy's novel, Anna
Karenina, in this project, we broaden our study on this network by weighing its links with the number
of occurrences of their endpoints (Actors) in the paragraphs. We also utilize a node embedding approach
called Nod2Vec to embed the nodes of the network in an n-dimensional space. Using this embedding
technique and k-means clustering algorithm, we could find a set of clusters resembling the community
structure detected in our network by the Louvain Algorithm. The best and worst Jaccard similarity we
found are 0.808 and 0.387, respectively.

As the second part of our project, **Classifinig Trump's and Biden's Fans' tweets**, we could train three classifiers that represent reasonable accuracy
on the test set. Using the Doc2Vec method, we could train multi-layer neural networks with a 70 percent
accuracy on the test set. Also, as the Doc2Vec benefits from a feature for documents, name tags, we
could use Doc2Vec solely to obtain a simple classifier that borrows its concept from Cosine Similarity.
This simple approach could achieve a 69.8 percent accuracy on the test set. In the end, we used the BERT
framework for our classification task, and we could achieve a good accuracy of 84 percent on the test set.
It's not an exaggeration to say that BERT has significantly altered the NLP landscape.
