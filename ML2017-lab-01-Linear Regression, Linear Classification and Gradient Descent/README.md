**1.** **Topic:**

Linear Regression, Linear Classification and Gradient Descent

**2.** **Time:** 

2017-12-02 9:00-12:00 AM 

**3.** **Reporter:**

​     DW Su

**4.** **Purposes:**

1.Further understand of linear regression and gradient descent.

2.Conduct some experiments under small scale dataset.

3.Realize the process of optimization and adjusting parameters.

**5. Data sets and data analysis:**

1.Linear Regression uses Housing in LIBSVM Data, including 506 samples and each sample has 13 features. You are expected to download scaled edition. After downloading, you are supposed to divide it into training set, validation set. 

2.Linear classification uses australian in LIBSVM Data, including 690 samples and each sample has 14 features. You are expected to download scaled edition. After downloading, you are supposed to divide it into training set, validation set.

**6. Experimental steps:**

The experimental code and drawing are completed on jupyter.

 

Linear Regression and Gradient Descent



1.Load the experiment data. You can use load_svmlight_file function in sklearn library.

2.Devide dataset. You should divide dataset into training set and validation set using train_test_split function. Test set is not required in this experiment.

3.Initialize linear model parameters. You can choose to set all parameter into zero, initialize it randomly or with normal distribution.

4.Choose loss function and derivation: Find more detail in PPT.

5.Calculate gradient G toward loss function from all samples.

6.Denote the opposite direction of gradient G as D .

7.Update model: Wt = Wt-1+ȠD . Ƞ is learning rate, a hyper-parameter that we can adjust.

8.Get the loss Ltrain under the training set and Lvalidation by validating under validation set.

9.Repeate step 5 to 8 for several times, and drawing graph of  as well as  with the number of iterations.



Linear Classification and Gradient Descent

 

1.Load the experiment data.

2.Divide dataset into training set and validation set.

3.Initialize SVM model parameters. You can choose to set all parameter into zero, initialize it randomly or with normal distribution.

4.Choose loss function and derivation: Find more detail in PPT.

5.Calculate gradient G toward loss function from all samples.

6.Denote the opposite direction of gradient G as D.

7.Update model: Wt = Wt-1+ȠD . Ƞ is learning rate, a hyper-parameter that we can adjust.

8.Select the appropriate threshold, mark the sample whose predict scores greater than the threshold as positive, on the contrary as negative. Get the loss Ltrain under the training set and Lvalidation by validating under validation set.

9.Repeate step 5 to 8 for several times, and drawing graph of  as well as  with the number of iterations.