<h1>Business Process Definition and Requirements</h1>



# 1.0 Business Objectives #
> In present situation in lot of hospitals scheduling an appointment is done manually ethier by making a call or visiting an hospital ,this process includes lot of disadvantages like the climatic conditions (raining heavily,snowfall) , call may not connect as hospital is a busy place, network problems,etc .
> To avoid this situation a online communication system called scheduling system is proposed between busy people and the hospital management where patient can schedule his/her appointment sitting at home through his pc and also fill all the forms which are mandatory for an hospital.

## 2.0 Business Requirements ##
  * System should be web based.
  * Specific access permissions must be given to different users.
  * Reduction in the time spent by the staff to gather the information & to store it in an organized manner.
  * Registration of patient is mandatory.
  * Software should correctly operate upon the execution of the system.
  * Software should be easily understandable and user friendly.


### 2.1 Process Flows ###

#### 2.1.1 Existing or “As Is” Process Flow and Process Steps ####

![http://scheduling-system.googlecode.com/files/EXISTING%20DIAGRAM.jpg](http://scheduling-system.googlecode.com/files/EXISTING%20DIAGRAM.jpg)
![http://scheduling-system.googlecode.com/files/EXISTING%20TABLE.jpg](http://scheduling-system.googlecode.com/files/EXISTING%20TABLE.jpg)

#### 2.1.2 Proposed or “To Be” Process Flow and Process Steps ####

![http://scheduling-system.googlecode.com/files/PROPOSED%20DIAGRAM.jpg](http://scheduling-system.googlecode.com/files/PROPOSED%20DIAGRAM.jpg)
![http://scheduling-system.googlecode.com/files/PROPOSED%20TABLE.jpg](http://scheduling-system.googlecode.com/files/PROPOSED%20TABLE.jpg)

### 2.2 New Process Requirements ###

#### Business Requirements ####
1.Software should not incur any additional costs related to:
  * Number of persons required
  * Maintanance of database
2.Software should be user friendly.


#### System Requirements ####
The application must run in all operating systems. System must also be available 24 hours and 7 days a week.



#### Data Requirements ####
Data like patientid,patient problem,fee details,doctors working in the hospital,etc should be stored.


#### Security Requirements ####
> Several levels of access permissions are required,for example:
  * Patients should be able to access only patient details.
  * Administer should have global access.


#### Personnel Requirements ####
| **Name**| **Organization**| **Role**|
|:--------|:----------------|:--------|
|sandeep,sangam|Hospital         | administer|
|laxmi,Patlolla|Hospital         | Doctor  |
|sujeet,palle|Hospital         |Tech support|



#### Support Requirements ####
| **Name**| **Organization**| **Role**|
|:--------|:----------------|:--------|
|sandeep,sangam|Hospital         | administer|
|sujeet,palle|Hospital         |Tech support|


### 2.3 Business Impact ###
By using an online system,efficiencies can be gained in maintanance and security.The ease of access will streamline the diagnosis the process by reducing the most time consuming processs and this information can be accessed by various parties and various reports can be generated far easier than the current manual process.


#### 2.3.1 Metrics to Measure Business Impact ####
  * Labor needed for medical records maintenance
  * Budget spent on paper
  * Time spent per patient


#### 2.3.2 Measurable Business Metrics to be used ####
  * Fewer people will be required to maintain records
  * Budgets for forms and paper files will become maintained or reduced even with an increase in patient visits
  * Time per patient will be reduced thus increasing the number of patients seen
  * Reports can be easily generated
  * Doctors can easily recollect patients past problems

#### 2.3.3 Responsibility of Metrics Collection & Analysis ####
Hospital Administration

1. Compare quarterly budgets after one  year of software implementation.

2. Compare quarterly projected time per patients seen to actual time per patient after one year of software implementation.



#### 2.3.4 Business Dependencies ####
  * Training should be given to the users to use the software.



### 2.4 Technology Impact ###

  * Patients can schedule their appointment from anywhere at any time.
  * Usage of computers will increase and become prominent.
  * Reduction in the time.


#### 2.4.1 Technology Dependencies ####
  * This software is dependent on web
  * Security setup between administrator and users
  * Connectivity between the database and browser should be efficiently managed.
  * All operating system should support this system
  * Local Area Network in working order

#### 2.4.2 Technology Risks ####
  * Internet outages
  * Breach in security
  * Local Area Network down

## 3.0 Assumptions ##

The following assumptions further define the scope and deliverables of the Hospital   Management System.
  * Computers with internet is available
  * Increase efficiency
  * Less paperwork



## 4.0 Issues ##
  * System efficiency depends on the network.


## 5.0 Project Success Criteria ##
  * The requirements should be clear and should be understandable.
  * The software should be simple and it should be used by the people even with little or no training.