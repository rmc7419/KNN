# KNN
The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.
The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.
KNN captures the idea of similarity (sometimes called distance, proximity, or closeness) with some mathematics— calculating the distance between points on a graph. The straight-line distance (also called the Euclidean distance).
Euclidean distance[dist(P,Q)]= √((P1-Q1)^2+(P2-Q2)^2+⋯+(Pn-Qn)^2)
The KNN Algorithm:-
	Load the data
	Initialize K to your chosen number of neighbors
	For each example in the data:
	Calculate the distance between the query example and the current example from the data.
	Add the distance and the index of the example to an ordered collection
4. Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances
5. Pick the first K entries from the sorted collection
6. Get the labels of the selected K entries
7. If regression, return the mean of the K labels
8. If classification, return the mode of the K labels


Data Used 
	Zoo dataset :- Implementing a KNN model to classify the animals in to categories.
	Glass dataset :- Preparing a model for glass classification using KNN.

Programming:- Python
The Codes regarding  KNN with  business problem Zoo dataset , Glass dataset  are present in this Repository in detail.
