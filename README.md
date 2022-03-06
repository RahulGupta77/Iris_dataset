## Iris dataset

## Training a Machine Learning model using Stochastic Gradient Descent 

## Problem statement 

   Train a model using Iris dataset in which, sepal length is feature and sepal width is the label. 

    
### Libraries used : 

    1. Scikit-learn
    2. Matplotlib
    3. Pandas
    4. Numpy
    5. Seaborn
    6. Inbulit Iris dataset in Sk-learn

### ALgorithm used : 

     Stochastic Gradient Descent Regressor
   

### Implementation : 
    
    1. Iris dataset consists 4 features (sepal length, sepal width, petal length, petal width) and 3 labels (Setosa, Versicolour, and Virginica)  
    
    2. In this problem statement, Feature was "Sepal length" and had to calculate "Sepal width" which is a continuous number 
    
    3. So the given statement is a regression type problem which is solved using Stochastic Gradient Descent Regressor 
    
    
### Result : 

    1. Mean absolute error = 39%  
    
    2. Mean squared error = 21% 
    
    3. Root mean squared error = 46% 
    
![Screenshot 2022-03-06 at 6 39 12 PM](https://user-images.githubusercontent.com/63935255/156926218-dcbe5a76-58cd-48b0-bef1-ae142e2b78cf.png)


### Conclusion : 

    The reason there is High error because the data (sepal length, sepal width) given to model is bias and is difficult to
    fit the line which statisfies all the points. 

![Screenshot 2022-03-06 at 7 27 34 PM](https://user-images.githubusercontent.com/63935255/156926433-ff84c068-aa9c-4da1-8b74-66ce11a95030.png)


     It is almost impossible to fit a line in the above datapoints. 


