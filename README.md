<div align="center">
<div id="top"></div>
<h2 align="center">Bank Customer Prediction</h3>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#genereal-idea-and-approach">Genereal idea and approach</a></li>
    <li><a href="#data-exploration">Data Exploration</a></li>
    <li><a href="#results-with-imbalanced-dataset">Results with imbalanced dataset</a></li>
    <li><a href="#results-with-balanced-dataset">Results with balanced dataset</a></li>
    <li><a href="#interpretation-of-results">Interpretation of results</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## Genereal idea and approach
The purpose of this project is to explore the best way to classify a dataset consisting of bank customers on whether or not they plan to leave the bank. Each customer is attributed a set of features such as age, salary, location etc.. A big issue with this dataset is the fact that it is imbalanced. Therefore we explore various ways to tackle such a problem, more of which will be talked about below. The classifier we have chosen for this task is a simple ANN consisting of 4 layers, with input of 12 neurons since each customer has a set of 12 features. 

<p align="right">(<a href="#top">back to top</a>)</p>

## Data Exploration
The dataset used can be found on Kaggle through this link [[1]](#1). The original data consists of 10000 entries, with 14 columns (or features each). We only make use of 11 of them, since we don't deem the others useful for our classification. We have included 5 samples from the dataset below. 
![alt text](https://github.com/reyrobs/Bank-Customer-Prediction/blob/main/images/df_samples.png?raw=true)

It is noteworthy to see that the dataset is imbalanced. A problem which we will tackle further on.  Please refer to the histogram below to see the imabalance between both classes. 
<br>
![alt text](https://github.com/reyrobs/Bank-Customer-Prediction/blob/main/images/imbalance_histo.png?raw=true)
<br>
We have done further data exploration analysis, in order to try and find some useful information in the dataset which would help us with our classification. Given that the data is imbalanced, it was hard to find such information. Our results from the data analysis can be found below.
<br>
![alt text](https://github.com/reyrobs/Bank-Customer-Prediction/blob/main/images/all_pictures.png?raw=true)
<br>
The main information that we can take from this analysis, is the spread of the customers across different countries, since the imbalanced dataset doesn't affect this information. 

<p align="right">(<a href="#top">back to top</a>)</p>

## Results with imbalanced dataset


<p align="right">(<a href="#top">back to top</a>)</p>


## Results with balanced dataset

<p align="right">(<a href="#top">back to top</a>)</p>


## Interpretation of results

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Robert Rey - [LinkedIn](https://www.linkedin.com/in/robert-rey-36689a103/)

Project Link: [Expectation-Maximization](https://github.com/reyrobs/Expectation-Maximization-Algorithm)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

## References
<a id="1">[1]</a> 
Bank Dataset Kaggle,
https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling
