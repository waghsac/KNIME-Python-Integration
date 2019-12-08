# KNIME-Python-Integration
This repository contains KNIME workflow for document matching using cosine similarity. This also illustrates use of Python code in KNIME. KNIME has python extension where we can code in python in KNIME nodes that are provided by the python extension.

Document similarity is mainly used in scenarios where we need to cluster the documents having similar topic/content together or to detect plagiarism. Cosine similarity technique is one of the ways to achieve this.
In this implementaton, the cosine similarity code is written in python and this code is integrated with KNIME using the KNIME Python extension. Scikit learn library of python has been used for computing the cosine similarity.

<b>KNIME workflow</b>
![alt text](https://github.com/waghsac/KNIME-Python-Integration/blob/master/CosineSimilarityWorkflow.PNG)

<b>The concept of Cosine Similarity</b>
![alt text](https://github.com/waghsac/KNIME-Python-Integration/blob/master/CosineSimilarity.PNG)

<b>Python Node</b>
![alt text](https://github.com/waghsac/KNIME-Python-Integration/blob/master/KNIMEPythonNode.PNG)

<b>Results</b>
Lesser the value of the angle, more the value of the cosine and hence higher the match of the two documents.
Document 1 is being matched with three other documents in this example.

![alt text](https://github.com/waghsac/KNIME-Python-Integration/blob/master/ResultsTable.PNG)
