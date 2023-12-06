<h1  align=center><font  size = 6>Book Recommendation with Collaborative Filtering</font></h1>

<br>  

<img  src="https://img-cdn.inc.com/image/upload/w_1920,h_1080,c_fill/images/panoramic/GettyImages-577674005_492115_zfpgiw.jpg"  height=520  width=1000  alt="GitHub">  

<small>Picture Source: <a  href="https://www.inc.com/jessica-stillman/books-reading-intelligence-tyler-cowen.html">Jessica Stillman</a> 

<br>

## Introduction

In the realm of book recommendation with collaborative filtering, Pearson correlation is a fundamental statistical measure employed to quantify the similarity between the preferences of different users. Collaborative filtering, the core technique of this project, aims to predict a user's book interests by leveraging the preferences and behaviors of users with similar tastes.

The Pearson correlation coefficient ($ρ$) is a statistical measure that quantifies the linear relationship between two variables, X and Y. The formula for calculating Pearson correlation is as follows:  

<br> 

$$ \rho = \frac{\sum{(X_i - \bar{X})(Y_i - \bar{Y})}}{\sqrt{\sum{(X_i - \bar{X})^2} \sum{(Y_i - \bar{Y})^2}}} $$  

<br> 

Here's a breakdown of the terms in the formula:  

- $\rho$: Pearson correlation coefficient.

- $X_i$ and $Y_i$: Individual data points in the datasets X and Y.

- $\bar{X}$ and $\bar{Y}$: Mean (average) of the respective datasets X and Y.  

The numerator represents the sum of the product of the differences between each data point and the mean of its respective dataset. The denominator involves the square root of the product of the sums of squared differences from the mean for both datasets.

The resulting Pearson correlation coefficient ranges from -1 to 1:

- $\rho = 1$: Perfect positive correlation.

- $\rho = -1$: Perfect negative correlation.

- $\rho = 0$: No linear correlation.

<br>  

In collaborative filtering for book recommendations, Pearson correlation is commonly used to measure the similarity between user preferences based on their ratings. A positive correlation suggests similar tastes, while a negative correlation implies dissimilar preferences.

<br>

## Getting Started


To kick off this project, start by importing essential libraries like Pandas, NumPy, and warnings. Load the books and ratings dataset using Pandas. In the data cleaning phase, select relevant columns (e.g., 'ISBN,' 'Book-Title,' 'Book-Author,' 'Book-Rating') and eliminate duplicate book titles for improved data quality.

</p>For collaborative filtering, first, implement User-Based Collaborative Filtering by grouping data by 'User-ID,' sorting by book title, calculating Pearson correlation coefficients between users, and selecting the top correlated users. Move on to Item-Based Collaborative Filtering, aggregating ratings, generating recommendations based on weighted scores, and displaying the top book recommendations.

Evaluate the collaborative filtering models for performance metrics and showcase the top recommended books to users. These steps lay the groundwork for a successful implementation of collaborative filtering for personalized book recommendations.

<br>

## Usage

1. Clone the repository to your local machine.
2. Load and preprocess the book and rating datasets.
3. Implement collaborative filtering algorithms to generate book recommendations.
4. Evaluate the performance and present the results.

<br>

## Contribution Guidelines

Contributions to this project are encouraged. Feel free to contribute by optimizing algorithms, improving data preprocessing, or enhancing the recommendation performance.

<br>

<h1>Contact Me</h1>

<p>If you have something to say to me please contact me:</p>  

<ul>
	
   <li>Twitter: <a  href="https://twitter.com/Doguilmak">Doguilmak</a></li>
   <li>Mail address: doguilmak@gmail.com</li>

</ul>
