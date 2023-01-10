# Diabetes-Database-Model
This project displays a database built from its logical model to it's visualization and will also include SQL queries used for data exploration. 



<h2>Description</h2>
I felt it was import to demonstrate a project beyond queries in order to display all that goes into creating a database. I will also include the logical data model complete with tables, their relationships, and their primary keys. Next ill play around with a few queries to discover more information about the dataset to see what story(s) it tells. "This dataset is originally from the National Institute of Diabetes and Digestive and Kidney
Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes,based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females
at least 21 years old of Pima Indian heritage. Secondly, From the dataset in the (.csv) File We can find several variables, some of them are independent
(several medical predictor variables) and only one target dependent variable (Outcome)"

<br />


<h2>Languages and Utilities Used</h2>

- <b>MYSQL</b> 
- <b>SQL</b>

<h2>Environments Used </h2>

- <b>macOS Monterey Version 12.5.1</b>

<p align="center">
  <b>Logical Database Model:</b> <br/>
  <b>Details</b> <br/>
  <b>PatientId:</b> To identify each unique patient <br/>
<b>Pregnancies:</b> To express the Number of pregnancies <br/>
<b>Glucose:</b>To express the Glucose level in blood <br/>
  <b>BloodPressure:</b> To express the Blood pressure measurement <br/>
  <b>SkinThickness:</b> To express the thickness of the skin <br/>
  <b>Insulin:</b> To express the Insulin level in blood <br/>
  <b>BMI:</b> To express the Body mass index <br/>
  <b>DiabetesPedigreeFunction:</b> To express the Diabetes percentage<br/>
  <b>Age:</b> To express the age <br/>
  <b>Outcome:</b> To express the final result 1 is Yes and 0 is no<br/>
<img src="https://i.imgur.com/JfXs70K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  <b>Physical Model Database Model</b> This Screenshot displays all three tables, their columns, datatypes, and relationship to one another.The patient table is the "parent" table. The "outcomes" table is the child and it has a composite key to reflect its relationship between both the "diagnostic_measure" and "patient" tables. At the bottom of this screenshot you can see that there have been constraints listed to make sure that as the "patient" table is updated the "outcomes" table updates as well."No action" was chosen as the default constraint to prevent the data from being deleted. <br/>
<img src="https://i.imgur.com/Mm2SkZA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Physical Database</b> This Screenshot displays the result of the physical model after forward engineering and importing the dataset into the database.Please feel free to see the README file under "forward engineering" to view the details of the script. <br/>
<img src="https://i.imgur.com/GRyFLnq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

