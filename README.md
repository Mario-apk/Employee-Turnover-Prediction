# Employee_Turnover_Prediction

Web link : https://emp-turnover-prediction.herokuapp.com/

![](images/exit.png)

Dataset size : 554KB Rows: 15000 columns: 10

Employee Turnover or Employee Turnover ratio is the measurement of the total number of employees who leave an organization in a particular year. Employee Turnover Prediction means to predict whether an employee is going to leave the organization in the coming period.

A Company uses this predictive analysis to measure how many employees they will need if the potential employees will leave their organization. A company also uses this predictive analysis to make the workplace better for employees by understanding the core reasons for the high turnover ratio.

Dependent variable : 'left'

Independent variable : 'satisfaction_level', 'last_evaluation', 'number_project', 'average_montly_hours', 'time_spend_company', 'Work_accident', 'promotion_last_5years', 'sales', 'salary'

![](images/quit.gif)

As we know left is dependent variable and its is discrete value . like 0 & 1 and T & F

as for the prediction we have model options as :

Logistic Regression

Support vector Classifier

## Random forest Classifier

K Neighbours Classifier

Ada Booost Classifier

Gradient Boosting Classifier

XGBoost Classifier


From the above mentioned model as per the basis of f1 score Random Forest Classifier has been working efficiently and more accurately. 


Summary: With all of this information, this is what employer should know about his company and why his employees probably left:

1. Employees generally left when they are underworked (less than 150hr/month or 6hr/day)
2. Employees generally left when they are overworked (more than 250hr/month or 10hr/day)
3. Employees with either really high or low evaluations should be taken into consideration for high turnover rate
4. Employees with low to medium salaries are the bulk of employee turnover
5. Employees that had 2,6, or 7 project count was at risk of leaving the company
6. Employee satisfaction is the highest indicator for employee turnover.
7. Employee that had 4 and 5 yearsAtCompany should be taken into consideration for high turnover rate
8 .Employee satisfaction, yearsAtCompany, and evaluation were the three biggest factors in determining turnover.


"You don't build a business. You build people, and people build the business." - Zig Ziglar

![](images/emp.gif)
