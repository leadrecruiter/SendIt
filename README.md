I want to develop mass mailing web application with name "SendIt" for us it consulting market, I have prepared the structure as below, now i want your help to select appropriate tools and technologies on Sandcodebox.

Here is App information.

App name: SendIT
Type: Mass mailer

Description: Sent, It will start with home page with 2 buttons namely "SignUp " and "SignIn". One user clicks any of them he will be moved to appopriate page for submission form after filling submission forms there will be user dashboard with a sidebar containing models: Compose Email
Database
Resume Writer
Search Resumes
Upload Resumes
User Account
Logout,

Below i have explained for each functions serial wise.

Brief description: 
1. (Homepage Model)
: First page is homepage in beginning with two option buttons (SignUp, SignIn) where "SignUp" is for the new users who are never registered with "Sentit", and "SignIn" is the for the user who are already registered with "Sendit".

Note: If user clicks "SignUp" Button it should move to "SignUp" Model, and if user clicks "SignIn" button it should move to "SignIn" Model.

2. (SingUp Model): "SignUp" page will contain the Submission form with below fields to be filled by the user once user filled all the details he will be able to click the Register button given in the end of submission form to go to the User dashboard:
>Fields for Submission form: 
1. Name (Complete name, First and Last name)
2. Number (Must be 10 digits)
3. Email ID (Must be a registered company domain ID, Yahoo.com, gmail.com or outlook.com should not accept)
4. Company Name (Must match with the given domain email id by user in email id field)
5. Create Password (Must be 8 digits letter with Numbers and alphabets)
6. confirm password( Password entered here must match the apsswork entered in field no. 5 (Create Password).
>Register Button (It will only be clicked once user fill all the submission form fields if any of field user miss and try to click Register button, it should say,  "please fill the complete details".)
NOTE: SignUp Model will only be seen if user clicks signUp Button from homepage).

3.(SignIn Model): "SignIn" page will contain the submission form with below details to be filled by user to login his dashboard, once user clicks "SignIn" button from homepage, user should be in "SignIn Model" with below fields with a "LoginIn' Button to login the dashboard.

> Sign In submission form:
 User name: (It is email id that is entered by user at time of registration with SendIt in signUp model).
Password: (It is password that is given by user at time of registration with SendIt in signUp model).

>LogIn Button: Once user fills the correct information in SignIn Submission form he will be able to click LogIn Button to move to dashboard.

NOTE: If user is not registered yet with" SendIt" and trying to use login option it should tell him that "Sorry you are not yet a member, please Signup to enjoy our services.

4. (Dashboard Model): Dashboard will have a Sidebar with below events.
-Compose Email (Here SendIt User can compose the email from this event to make a mass email, using this compose event user will be able to send a mass email to more than 10K email at a time in cc and bbc.

-Vendor List (Here "SendIt" user can add his/her vendor list using his personal database by importing excel or ,manually adding, a user can add 10K vendor email ids at a time)

-Database (SendIt): (Here only "SendIt" can upload and do any changes and the User only will be able access the data by downloading the excel file uploaded by "SendIt" and can not edit or modify or upload anything in this event.

-Search resume: Here users can Search resume posted by recruiters on daily basis according to his needs.

-Upload Resume: Here users will be able to upload his candidates resumes.

-User Account: Here used can see his personal details he entered in "SignUp" model while registering himself and he can make the changes and modifications if he want

-Logout with logout button user will be logged out and he would need to login again to start where he left.
