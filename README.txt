IDEA- The main idea behind the project is that to help the recruiters to save their time while screening through the resumes and build a model that can screen through
the resumes and give suitable information to the recruiters so that they can choose the right candidate for according to the job description.

ABOUT THE PROJECT - The project will help the recruiter in screening through the resumes of the candidates with the help of a machine learning algorithm,natural
language proccessing and concepts of named entity recognization where it will take the information from the candidate and store it in the database and give the information like 
skills,education,experience,etc to the recruiter.It will help the recruiter to screen through the resumes easily and select the suitable candidate for the job.

REQUIREMENTS-spacy v3.2.1
             All the modules pre installed that are used in the project.
             
 
The source code is in the Resume Screening using machine learning.ipynb file.
 
 PROCEDURE ------------------
STEP 1- First I have imported all the modules used in the project.
STEP 2- I have created a login interface where it will ask the candidate to login or register and based upon there choice it will store their information in a database file 
named 'Login_details.txt'.
STEP 3- Then I have created an interface where  it will input the candidates resume information and store in in the database file named 'data2.xlsx'.It will
 act as a database for the project.We can also increase the input intake and the number of inputs according to our need.
 STEP 4-Then I have imported the modules required for the resume screening.
 STEP 5-I have loaded the training dataset. Here I have taken a sample dataset for training but when applied in real world then it will
 take the data from dataset file 'data2.xlsx'.
 STEP 6-Printing some of the data.
 STEP 7- Taking some of the data from the dataset to train the model.We can also take the whole datset to train the model but  I have taken some part only to train the
 model fast.
 STEP 8-Loading  the trained model.
 STEP 9- Testing the model by taking the information  and predicting the information based on entities.
 STEP 10- Taking a random resume and testing the model.
 
 KNOWN BUGS-1)The program synatx may vary with the different version of modules used.
 2)Write now the program is not predicting resumes very accurately because I have trained a small datset but when we will train a large datset then it will gat trained well and 
 the prediction will be accurate.
  
  
  USAGE- It will help the recruiter to screen through the resumes very easily and store the candidates information in a datbase and choose a suitable candidate for the job.
  
  
  THANK YOU.
