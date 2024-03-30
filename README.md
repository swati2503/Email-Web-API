# Email-Web-API
This project provides a RESTful API for sending emails using Java Spring Boot. It allows clients to send emails by making HTTP requests to designated endpoints.
Prerequisites
  Java JDK (11 or higher)
  Maven
  IDE (STS)

Requests
Post Request :-
* http://localhost:8080/sendMail
  {
    "recipient":"emial id",
    "msgBody": "message bosy",
    "subject":"Subject"
  }
  
* http://localhost:8080/sendMailWithAttachment
  {
     "recipient":"emial id",
    "msgBody": "message bosy",
    "subject":"Subject"
    "attachment":"document full address"
  }
