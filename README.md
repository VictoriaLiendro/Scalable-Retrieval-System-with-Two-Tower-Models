# Scalable-Retrieval-System-with-Two-Tower-Models
The Two-Tower model is a deep learning architecture that is used for retrieval tasks, such as search and recommendation. It consists of two towers, one for the query and one for the documents. It is used successfully for variaty of retrieval tasks and it can be train on large datasets.

### Dataset
We wll use the public dataset (https://github.com/amazon-science/esci-data). It consists of three columns, the query, which item was the first recommendation and whether it was exact E or irrelevant I.

### Motivation
We want to find the most relevant product, we could use words match systems that are simpler. However, sometimes a part of the query are more important than others. For example, in "blue running shoes for women" it may be more important the the shoe is for women than the color. With past data we can learn this type of information. 
