# Data Analysis Study Project
### Task 1. A/B testing

#### 1.1 Condition

One of the main tasks of an analyst is to conduct experiments correctly. To do this, we apply the A/B-testing method. During the testing of one hypothesis, a new mechanics of payment for services on the site was offered to the target group, and the control group had the basic mechanics remaining. You need to analyze the results of this experiment and conclude whether it is worth launching the new payment mechanics on all users.

#### 1.2 Input data

* groups.csv - a file with information about the users' group (A - control group, B - target group)
* groups_add.csv - an additional file with users that was sent to you two days after
* active_studs.csv - a file with information about users who logged in to the platform during the days of the experiment
* checks.csv - a file with information about users' payments during the days of the experiment


### Task 2. SQL

#### 2.1 Diligent Students

#### Condition

Educational courses consist of various lessons, which, in turn, consist of several small tasks. Each such small task is called a "pea".

A diligent student is a user who solved 20 peas correctly at least once during the current month.

It is necessary to write an optimal query which provides information about the number of diligent students. NB! By diligent student, we mean a student who has correctly solved 20 problems in the current month.

#### 2.2 Funnel optimization

#### Condition

The educational platform offers students to take courses based on the trial model: a student can solve only 30 peas a day for free. To have unlimited access to assignments, the student must purchase full access. The team conducted an experiment where they tested a new payment screen.

It is necessary to show the following information about user groups in one request:

* ARPU 
* ARPAU 
* CR
* СR for active users  
* CR for active math users (subject = ’math’) 

An active user is a user who has solved more than ten tasks correctly in all disciplines.
An active math user is a user who has solved two or more problems correctly in mathematics all the time.

### Task 3. Python

* Implement a function that automatically loads information from an additional groups_add.csv file (headers may vary) and recalculate metrics based on new parameters.
* Implement a function that plots graphs based on the resulting metrics.
