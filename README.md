
Purpose
The aim of the documentation is to illustrate how a product which is Web Library Management System is functioning so that the web developer will have an insight to design the real project.
 Overall description of the product
The product is a web based application, its basic functionality is to update and modify user’s account information, show and reserve available books and notify the user the remaining renewal time of their borrowed book. The product is designed to be used by an existing or new user as well as by the librarians.
Target audience (of the document)?
The web site developer, testers, librarians and managers and coordinators.
The situation? Motivation?
The product is designed basically enhance the functionality of the manual library system.
Structure
The structure differ from the group project ; the project template included the system Archtechre, Risk analysys,budget… however the document I review doesn’t include all those contents.
What the system will do?
The system interface will allow the library members to see the information on their account, borrow, reserve and renew book.  While the librarian can set books by order, notify users for renewal….etc.

(Use cases)
 Library members
The member should be provided with the updated information about the books catalog.
The user should have to have access to the books catalog.
The user has to be able to update the details in his/her account.
The user have the ability to explore books by different categories such as title, authors etc. 
The user can renew the bowered book online.
The user can request for the book of his choose to the book shelf even if its unavailable for the moment.
Librarian (administrator)
The librarian can add, delete a book form the shelf and update the catalog.
Can accept or reject a new user according to the library policy or payment methods.
Can accept the renewal or extension period for a borrowed book.
Can access the information of the user who has borrowed a book.
Can notify the user if the deadline has come to an end.
Can arrange the books by categories.
Make and remove reservations.
Use case diagram?


Actors
Librarians and the administrators
How cases are described, how much detail?
Case diagrams are described in a concise way however the use cases for a registered user and a random library user are written in the same use case category under library members. I hope extra use case for random user should be added. E.g.  Sign up (register) field should be provided for a random user.

UI examples / views?
Are the pictures mockups or screenshots from existing system?
The mockups are made for the first time for the specific project not from the existing system; the product version is a new one.
Transitions between views
I think the user interfaces are done layer by layer without skipping the UI from each step in the case of UI for the user but in the case of administrator the UI are not done in detail. 


 Non-functional Requirements
Error handling: WLMS product shall handle expected and non-expected errors in ways that prevent loss in information and long downtime period.
 Performance Requirements: The system shall accommodate high number of books and users without any fault. Responses to view information shall take no longer than 5 seconds to appear on the screen.
Safety Requirements:  System use shall not cause any harm to human users.
Security Requirements: the database functionality of the product is secured with password.
System will have different types of users and every user has access constraints.
Functional requirement 
Librarian: admin signed in
Insert book
Delete / modify book 
Validate user account 
 Delete member: Admin can delete a member due to some specific rules.
Modify member rank: Admin can extend the borrowing time or number of book borrowed 
Simultaneity to a user.

 Return book: Description Admin should confirm the return of books borrowed by users.

 Normal User 
Register: Description when new user enters WLMS for the first time then he has to register 
Title extending borrowing deadline: Description member can extend the borrowing time to some limit decided by Admin
Reset password: Description when a member forgets his password he can claim it back via e-mail.
Edit personal information: Description if some user changes for example his mobile number, he can modify it.
Reset password: when a member forgets his password he can claim it back via e-mail.

Measurable/traceability? 
Yes it can be checked in the requirement specification.
(Process model? [might not exist, some times in a separate document called ‘project plan’])
Not included
Allocation of resources / budget?
Not included
Risk Analysis?
Not given
(Your point of view)

Is it a good/bad document? Why?
 I think it is fair document however I wouldn’t say it is possible to develop real full system out of the documentation. Because the system architecture is not done (not Mentioned at any level), risk analysis is not mentioned. The user interface for the administrator case is not discussed clearly (step by step).but with respect to the UI diagrams it is quite nice one.
B. Start your project
Do you get an idea how and what to write?
Yes
At the content level, is there a part that you would simplify or go into more details?
Perhaps with the functional and nonfunctional requirement.
Do you think that you are able to list functional requirements? Non-functional requirements (and make them measurable)?Yes
What is the importance of the illustrations/diagrams/mock-ups?
By using pictures (mockups) we can minimize the length and complexity of our documentation. System users like having pictures, diagrams, for quick reference.
How much "technical" vocabulary should be? Not much, the 

 Documentation will be written so that anyone with only basic computer skills can read it and learn how to properly use the system. If there is any I will place it in an appendix.
