# Data Mining Complete Bootcamp
## Dataset Installation

Use `pip` to install the ```dmba``` package from pypi (https://pypi.org/project/dmba/).

```pip install dmba```

Should this not work, for example when you are behind a firewall, download the package from pypi and install from file, e.g.

```pip install dmba-0.0.14.tar.gz``` 

## The Steps in Data Mining

1. Develop an understanding of the purpose of the data mining project
2. Obtain the dataset to be used in the analysis 
3. Explore, clean, and preprocess the data 
4. Reduce the data dimension, if necessary
5. Determine the data mining task (classification, prediction, clustering, etc.) 
6. Partition the data (for supervised tasks)
7. Choose the data mining techniques to be used (regression, neural nets, hierarchical clustering, and so on).
8. Use algorithms to perform the task : This is typically an iterative process—trying multiple variants, and often using multiple variants of the same algorithm (choosing different variables or settings within the algorithm). Where appropriate, feedback from the algorithm’s performance on validation data is used to refine the settings.
9. Interpret the results of the algorithms : This involves making a choice as to the best algorithm to deploy, and where possible, testing the final choice on the test data to get an idea as to how well it will perform. (Recall that each algorithm may also be tested on the validation data for tuning purposes; in this way, the validation data become a part of the fitting process and are likely to underestimate the error in the deployment of the model that is finally chosen.)
10. Deploy the model : This step involves integrating the model into operational systems and running it on real records to produce decisions or actions. For example, the model might be applied to a purchased list of possible customers, and the action might be “include in the mailing if the predicted amount of purchase is > $10.” A key step here is “scoring” the new records, or using the chosen model to predict the outcome value (“score”) for each new record.

The foregoing steps encompass the steps in SEMMA, a methodology developed by the software company SAS:

**Sample** : Take a sample from the dataset; partition into training, validation, and test datasets.

**Explore**: Examine the dataset statistically and graphically.

**Modify**: Transform the variables and impute missing values.

**Model**: Fit predictive models (e.g., regression tree, neural network).

**Assess**: Compare models using a validation dataset.

