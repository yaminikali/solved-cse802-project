Download Link: https://assignmentchef.com/product/solved-cse802-project
<br>



<h1>Dataset</h1>

<ul>

 <li>Select a dataset that has many samples</li>

 <li>Important to consider the number of classes (c) and the number of features (d) in the dataset</li>

 <li>Ideally, you want to select a dataset which has at least 4 classes and</li>

</ul>

50 dimensions

<ul>

 <li>This is an arbitrary number – the point is to work on a “realistic” problem rather than a “toy” problem</li>

 <li>Please review D2L for dataset suggestions</li>

</ul>

<h1>Training Set, Validation Set, Test Set</h1>

<ul>

 <li>Partition your dataset into training set, validation set and test set</li>

 <li>Use the training set to develop the classifier and the validation set to select suitable parameters for the classifier (fine-tuning parameters)</li>

 <li>Use the test set to evaluate the performance of the tuned classifier</li>

 <li>Present your results using a confusion matrix besides reporting the overall classification accuracy</li>

 <li>Which classes are often confused?</li>

 <li>What is the variance in classification accuracy when the partitioning exercise is repeated multiple times?</li>

 <li>What is the impact of imbalanced classes on classification accuracy?</li>

 <li>….</li>

</ul>

<h1>Pre-processing the Dataset</h1>

<ul>

 <li>Data normalization:</li>

 <li>Experiment with different feature normalization schemes</li>

 <li>For example, should features be normalized in the range [0, 1] Or, should they be normalized using the z-score technique</li>

 <li>Is normalization needed at all?</li>

 <li>Dimensionality reduction:</li>

 <li>Experiment with feature extraction (projection) and feature selection (e.g., SFFS) techniques</li>

 <li>You can use already available software to test these options</li>

</ul>

<h1>Experimenting with Different Classifiers</h1>

<ul>

 <li>Test the performance of different classifiers on the dataset</li>

 <li>See D2L for software packages that can be used</li>

 <li>Which classifier results in the best accuracy?</li>

 <li>Write your own code to design a Bayesian Classifier based on the maximum <em>a posteri</em>ori principle</li>

 <li>Estimate class-conditional PDFs assuming a Multi-Variate Gaussian density function (or any other multi-variate density function)</li>

 <li>Estimate class-conditional PDFs assuming that features are independent and that every feature variable can be modeled using a Gaussian (or any other function)</li>

 <li>Use non-parametric density estimation schemes to determine the class-conditional density values of a test sample</li>

</ul>

<h1>The Goal</h1>

<ul>

 <li>Gain insight into the dataset you selected</li>

 <li>Test at least</li>

 <li>2 dimensionality reduction schemes</li>

 <li>3 classifiers from existing software packages</li>

 <li>Bayesian classifiers that you’d designed in homework #2, #3, #4</li>

 <li>Test the impact of changing the training data – do this multiple times in order to obtain the mean and variance of the error rate</li>

 <li>Draw some conclusions about the dataset, the features used, stability of various classifiers, etc.</li>

 <li>Submit the report by May 1, 2020</li>

 <li>Grade will be based on the degree of analysis conducted</li>

</ul>