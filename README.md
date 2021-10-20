# Laptop-Price-Predicition-

<p align="middle">
    <img src="https://miro.medium.com/max/1400/0*XmAiY1Zac-OcaF6U" width="770" height="570">
  </p>
  
 "The good news about computers is that they do what you tell them to do. The bad news is that they do what you tell them to do." — Ted Nelson
 ----
  
  This a project of "Laptop-Price-Predicition" using 'Machine Learning'algorithms.
  
 A laptop, laptop computer, or notebook computer is a small, portable personal computer (PC) with a screen and alphanumeric keyboard. These typically have a clamshell form factor, typically having the screen mounted on the inside of the upper lid and the keyboard on the inside of the lower lid, although 2-in-1 PCs with a detachable keyboard are often marketed as laptops or as having a laptop mode. Laptops are folded shut for transportation, and thus are suitable for mobile use. Its name comes from the lap, as it was deemed practical to be placed on a person’s lap when being used. Today, laptops are used in a variety of settings, such as at work, in education, for playing games, web browsing, for personal multimedia, and general home computer use.
 
 GOAL:
 ----
 Minimize the "loss error".

Analysis:
-----
Here we use plotly for analysis.

1.**Bar Plot on Distribution of Companies of Laptop:**
![UI](1.png)
We can see that the distribution of Lenovo, Dell, HP laptops are almost. It means that those are the highest selling laptops currently.

2.**The histogram on Ram vs Price in Euros:**
![UI](2.png)

3.**Scatter Plot on RAM vs Price vs Company:**
![UI](3.png)
The memory size is inversely proportional with the price of euros and the selling rate of higher price laptops is very less.

4.**Scatter Plot on CPU vs Price vs Company:**
![UI](4.png)
![UI](5.png)
The generation of the processor is proportional to the price. Laptops with Intel, AMD processors are the highest selling laptops here.

5.**Bar Plot on Distribution of Operating Systems of Laptop:**
![UI](6.png)

6.**Pie Chart on Company vs Operating System vs Price:**
![UI](7.png)

7.**Scatter Plot on Company vs Ram vs Operating System vs Price vs CPU vs Memory:**

This a moving graph but due to some unavoidable circumstances moving graph is not able to upload.
![UI](8.JPG)

Machine Learning Algorithms:
-----
**Linear Regression:**

Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting. Different regression models differ based on — the kind of relationship between dependent and independent variables, they are considering and the number of independent variables being used.

Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression. y=ax+c
<p align="middle">
    <img src="https://miro.medium.com/max/2000/0*OsEmBJIRKfZKRCmf.jpeg" width="770" height="570">
  </p>
  
 **Random Forest:**
 
Random forests or random decision forests are an ensemble learning method for classification, regression, and other tasks that operates by constructing a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees. For regression tasks, the mean or average prediction of the individual trees is returned. Random decision forests correct for decision trees’ habit of overfitting to their training set 587–588 Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees. However, data characteristics can affect their performance.
<p align="middle">
    <img src="https://miro.medium.com/max/700/0*pKTTkYeiG9V_C6f2.png" width="770" height="570">
  </p>
