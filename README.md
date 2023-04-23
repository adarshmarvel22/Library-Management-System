# Library-Management-System
Web Technology Academic Project 

Steps, features and building up of this project:
- Created a Django model for books with fields such as title, author, publisher, ISBN, and number of copies.
-Implemented a view to display all books and their details.
- Created a view to add new books to the library's collection.
- Created a view to edit the details of an existing book.
- Implemented a view to delete books from the library's collection.
- Added a model for library members with fields like name, email, and membership status.
- Implemented a view to display all library members and their details.
- Added a view to register new members.
- Created a view to edit the details of an existing member.
- Implemented a view to remove members from the library.
- Created a model to store information about borrowed books, including the member who borrowed it and the due date.
- Implemented views to allow members to borrow books and return them.
- Added a feature to display the borrowing history of a member.
- Implemented a search feature to allow users to find books by title, author, or publisher.
- Added authentication and authorization to restrict access to certain features to authorized users.
- Implemented a feature to send email reminders to members with overdue books.

Tech Stack:
   -Frontend:HTML
            -CSS
            -JavaScript
   -Backend:Django/Python
           -dbsqlite3
          
'''To run the project:'''
- **fork the repo**
- **run python -m venv env command in root directory**
- **run env\Scripts\activate**
- **run python manage.py runserver**

- dummy users for reference:
-      - admin-> username:admin
              -email:admin@gmail.com
              -password:admin
-      - student->username:Adarsh
              -email:adarsh@gmail.com
              -password:Adarsh@123
- 👋@Bundelkhand University
- 📫features: add book,issue book,impose scheduled fine,etc.

''' Screenshots'''
-- Homepage
![lms1](https://user-images.githubusercontent.com/87609950/233839087-5dc1f342-9dcc-4305-ac3e-533adb605022.jpg)

-- Student Profile and Pages
![lms3](https://user-images.githubusercontent.com/87609950/233839120-19880b1e-edce-4745-8ae1-89436217b2ca.jpg)
![lms2](https://user-images.githubusercontent.com/87609950/233839144-062c7a96-9fa2-4ba0-ae64-85526f51d1de.jpg)


-- Admin/Staff Profile and pages
![lms4](https://user-images.githubusercontent.com/87609950/233839152-330dd15d-b8d1-4745-8b0b-061cdafe0419.jpg)

![lms5](https://user-images.githubusercontent.com/87609950/233839130-f90dc333-abaf-4556-bc03-1aea962c1949.jpg)


Folder structure and templates:
![folder struct lms](https://user-images.githubusercontent.com/87609950/233839302-4671b670-557f-41f0-b4a5-67c374f3d24c.jpg)
![templates](https://user-images.githubusercontent.com/87609950/233839304-59d47255-17cc-42a0-8a5a-b98672b4fc8f.jpg)
