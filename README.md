# EventIdentification
Problem to Address:
In this project, our group will try to reproduce the data analysis result from Hila Becker, Mor
Naaman, Luis Gravano’s paper of “Learning Similarity Metrics for Event Identification in
Social Media”.
In the paper, the authors developed the similarity metrics of different models to identify
events from the dataset that is extract from social media platforms. we would like to try the
same models with the same parameter that are used in the original research, and expect to get
the same accuracy as they do in the paper.
The Importance of the Reproducing and Verification
First of all, our group believes that the original research is academically influential and
practically significant. The model that is developed in the research can be used in practice.
The original result should be verified before taking any other movement.
Additionally, the reproducibility is an important standard in evaluate the integrity of the
research. If the result cannot be reproduced and verified, the integrity of the data analysis
result and the experiment result might not valid.
Potential Challenge:
There are 270451 records in the original dataset. The memory of personal computer might
not able to deal with such large dataset. We might use external disk, cloud platform or other
professional computers.
Moreover, our result might be different from the result of the original research. Our group
would reevaluate our analysis process and find out the reason behind the difference.
The General Approach:
For learning the similarity metrics for event identification, the problem of identifying events
and their associated social media documents can be casted as a clustering problem.
We will use a single-pass incremental clustering algorithm with a threshold parameter that
can be tuned in a principled manner during a training phase.
Specifically, we will consider each element in turn, and represent each cluster using the
centroid of its documents.
In order to specify a clustering threshold, we will run the clustering algorithm on a subset of
labeled training data, evaluate the algorithm’s performance on the training data using a range
of thresholds, and identify the threshold setting that yields the highest-quality solution
according to a given clustering quality metric.
For learning a similarity metric, we will firstly use the ensemble clustering algorithm, which
combines multiple clustering solutions for a document set. Secondly, we will compute the
documents’ feature-specific similarity metrics directly for documents and cluster centroids.
As an alternative to ensemble-based approach, we can use classification modes to lean
document similarity functions for social media.
Dataset and Sources:
The data of this project comes from Hila Becker’s article, “Learning Similarity Metrics for
Event Identification in Social Media.”(Hila Becker, 2010)
From the description of Becker, these data are the information of users submit on social
media, and it can help us to clustering photos or short comments by different events, which
can supply more accuracy results when other users want to search information about a exact
event.
Author’s website: http://www.cs.columbia.edu/~hila/wsdm-data.html
Article: http://www.cs.columbia.edu/~hila/papers/wsdm10-becker.pdf
Data: http://www.cs.columbia.edu/~hila/upcoming.tar.gz
Reference:
1. Becker, Hila, Mor Naaman, and Luis Gravano. "Learning Similarity Metrics for Event
Identification in Social Media." ACM Digital Library. February 2010. Accessed
March 21, 2018. https://dl.acm.org/citation.cfm?id=1718524.
