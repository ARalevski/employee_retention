# Employee Retention

The HR department at a large software company is rolling out a new initiative called 'proactive retention', where they will use data to predict whether an employee is likely to leave the company. Once these employees are identified, HR can be more proactive in reaching out to them before they quit. 

The current method used by HR is exit interviews. This gives the employee the chance to share his/her reasons for leaving. HR then tries to learn insights from the interview and make changes in the company accordingly. However, this approach suffers from three main drawbacks:

1) The approach is haphazard because the quality of insights gained from an interview depends heavily on the skill of the interviewer.
2) HR can't systematically aggregate insights across all employees who have left.
3) HR can't be proactive because they're using exit interviews (i.e. the employee has already made a decision to leave by the time they schedule the interview) to drive changes within the company.

The HR department therefore wants us to build a classification model that will predict which employees are most likely to leave.

They provided us with a dataset of past full-time employees and their status (employed/left) as well as various other data (```employee_data.csv```).

We optimized Logistic Regression, Random Forest Regressors, and Boosted Trees to determine the best model.

The winning Random Forest Model achieved a 0.98 AUC score and 91% accuracy rate with minimal tuning:

<p align="center">
  <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png" width="425"/> <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png" width="374"/>
  </p>
