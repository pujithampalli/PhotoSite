•	Developed a model-view-controller (MVC) architectural pattern web application where a user can share any number of photos and other users can like and comment on it. <br/>
•	The application is developed using Ruby on Rails, SQLite database, other supporting technologies like HTML5, CSS3 and deployed it on Amazon Web Services(AWS).<br/><br/>

Introduction<br/>
The main goal of the project is to develop a photo-sharing website namely, ‘PhotoSite’ in Ruby on Rails using SQLite as database and deploy it on Amazon EC2 instance. The instance is launched in Ubuntu server. By using the host address and key-pair given by AWS login to putty and install the required applications. All the project files are transferred onto the server using FileZilla. Then when we run the server on putty console. Then the URL with the host address works and the PhotoSite application is deployed on AWS EC2 instance.<br/><br/>
Purpose<br/>
The purpose of the project is to learn practically how to use Amazon EC2 instance with real-time applications by deploying a web application where a user can share photos, post comments on others photos and display date of the comment posted.<br/><br/>
Demonstration of the Application<br/>
  This project is a partial implementation of PhotoSite application which has two URL pages developed locally. In this application, a user can post photographs and have comments on them. Other users can comment on any user’s photographs. The date and time of the comment posted and photo posted should be displayed. The two URL’s that are implemented are,<br/>
•	User/index<br/>
•	Photo/index/id<br/>
The application starts functioning when user/index page is referred where all the user details are displayed. By clicking on any user’s first name navigates to (photo/index/id) their page where all their photos, comments on those photos and date posted are displayed. In this second URL, id is the user id passed to the URL.<br/>
