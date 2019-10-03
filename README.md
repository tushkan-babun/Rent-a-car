# RENT_A_CAR-WEB_APPLICATION :blue_car:

*This Project was done as an assigment in college with* :a:*+ Grade*

## Project Description  

A web application for a rent a car business that has three users:
### 1. General User / Customer:
A user of the application that will only be browsing your application. This user will be a general visitor of the application till he/she logs in and will be able to register, view cars, contact us and browse the application. Once logged in, this user will bea customer and will have the ability to book a car, view profile, change password, and update profile information and view orders along with the basic functions of a general user.
### 2. Administrator:
This user will be able to perform all administrative tasks listed below in the ‘Scenario’ section and would be a super user of the system with access to all functionalities.
### 3. Staff:
This user will be able to perform all staff tasks listed below and would have less access and rights as compared to Administrator for user management.

### The following technologies were using to develop this application:
- Application Front End:

HTML,CSS, JavaScript, Bootstrap, jQuery , AJAX
- Application Back End:

PHPDatabase: MySQL (PHPMyAdmin)
- Social Media:

Social Media Plugins
- Other technologies/addons:

Plotly (for graphing), Google Captcha, Google Maps,SMTP email
### 4. Scenario
Rent_A_Car is a company which provides the service of car rental. Rent_A_Car was established with 3 employees. The development team have decided to develop an online booking application which allows customers to make an online request to rent a car. This web based application based on system requirements specification shown below:

### 1. Basic functions for all usersare:
- Landing page(index.php):
is accessible to all users;
- Register:
customers can register themselves
- Login:
login  to  the  system  for  future  actions;  linked  with Developing Mode Google  Captcha;

inform the user that they are currently logged in;

all users use the same login page and they are redirected to their respective pages depending on the login credentials
- View cars:
all users can view all the available cars  
- View  and  Update  personal  information:  
all  users  should  be  able  to  view  their personal information and update it
- Change Password: old password have to match
- Forgotten Password: Auto email should send to users with new password
- Logout: page redirect to index or login page, hint: session expired, should have session handeling
- View a Google Map which –
..- Has a marker to represent the company’s location
..- Upon  clicking on the marker shows the company’s advertisement video (just use some video from YouTubewhich is suitable for the project scenario; but please reference the video in your document)
..- Any form used on the website should havelogical validations

2.Administrator:
Upon  successful  login,  the  admin  user  will  be  redirected  to Admin  pagewhich  will display all registered users (Users and administrators) in a table.
Only  10  registered  users  will  be  shown  on  one  page  and  for  the  rest  of  the  list, pagination should be implemented. Pagination is recommended.
The last column in the table will have 2 icons, 1 for Edit user and 1 for Delete user.
On clicking Edit user, the admin should have all the user data prefilled in a form where the  admin  can  edit  user  information  and  save  it  back.There  should  be  a  feature  for enabling and disabling users
On clicking Delete user, the admin should be prompted by the system to confirm the delete operation in an alert box and upon confirming, the user would be deleted from thetable and table will be refreshed.
The admin will see an "Add User/admin" button at the bottom of the table to be able to register a new User in the system or add a new system administrator using the same registration form.
Other tasks:Administrator can also do all other tasks done by Staff.

3.Staff:
Add a new car: Staff can add new car  
Modify car information: staff can modify the car information
Remove a car: Staff can remove a car that can’t be used anymore
Accept  or  reject  rental  requests:  Staff  can  accept  or  reject  the  customer’s  rental request.  An  email  will  be  sent  to  the  customer  with  further  information  about  the payment options or rejection reasons.
Reports:
Staff can view different types of reports about available cars,rented cars, and registered customers.
Use Plotly to make your reports graphical and interactive

4.Customer:
Rent a car: Customer should be able to select one of the available cars on certain dates and send a rental request.Auto email to acknowledge the receipt of the request will be sent to the customer.
Enquiry or Feedback: Customers should be able to send enquiry or feedback to the admi
