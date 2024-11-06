<h2>Salary_Prediction_Using_Simple_Linear_Regression</h2>
<h3>Introduction</h3>
In today’s competitive job market, setting fair, competitive salaries is essential for attracting and retaining talent. A machine learning model that predicts salaries based on years of experience provides HR teams with data-driven insights to make informed compensation decisions. This project aims to build an accurate, interpretable model that streamlines the salary-setting process, ensuring consistency and fairness across the organization.
<br>
<h3>Dataset</h3>
Salary data with respect to the number of years of experience in the company.

<h4>A data of 36 employees with labels:</h4>
<li>First Column of the data is the number of years of experience 
<li>Second Column is the Salary of the Employees
<h4>Defining the data labels: </h4>
<li> Independent Variable: Independent variable is the variable that is manipulated or changed to observe how it affects another variable.<br>
 [Here the independent variable will be the number of years of experience.]
<li> Dependent Variable: The Dependent variable is the variable being tested and measured, and it is expected to change as a result of changes in the independent variable.
 [Here the dependent variable will be the Salary.]
 <h3>Linear Relationship Between Years of Experience and Salary</h3>
  <br>


  
 ![Screenshot 2024-11-06 143201](https://github.com/user-attachments/assets/610e3012-74b7-458a-a560-0ae11e50ba80)
<br>
<h3>Training and Test Data</h3>
<br>


![Screenshot 2024-10-23 170014](https://github.com/user-attachments/assets/704c63b8-232e-4fe3-9188-d5321dde30f3)
<br>
<h3>Visualising the Training set results</h3>
<br>

![Screenshot 2024-11-06 145620](https://github.com/user-attachments/assets/505993e8-16e2-4d80-a5ed-37a1ecbbbd26)

<br>
<h4>Training Set Plot:</h4>
<li>This plot shows the linear regression model fitted on the training data, where years of experience (X-axis) is used to predict salary (Y-axis).
<li>The blue dots represent actual salary values from the training set, while the red line represents the predicted salary values from the model.
<li>The close alignment of the points to the red line indicates that the model has effectively captured the relationship between years of experience and salary in the training data.
<h3>Visualising the Testing set results</h3>
<br>

![Screenshot 2024-11-06 145633](https://github.com/user-attachments/assets/d85a90c1-c91f-4799-b855-e3cb9474d1e5)  

<br>
<h4>Testing Set Plot:</h4>
<li>This plot displays the model's performance on the testing data, which was not used during training.
<li>The blue dots represent actual salaries in the testing set, and the red line shows the model's predictions.
<li>The points are closely aligned with the red line here as well, indicating that the model generalizes well and accurately predicts salaries based on years of experience for new data.
