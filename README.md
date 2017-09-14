# Financial-Aid-Replica

This app would be a remake of external servers that would be communicating with the cuny replica app.





# User Stories


* Financial Aid
    * Administrators would have a register page that needs acceptance from another admin
    * Admin would would log in with their credentials
    * Admin could view data from a students account
    * Admin could have toggles for data but cannot directly influence the data because much would be automated







# Wireframes










# MVP Structure

### Databases
* Cuny Database
* Financial Aid Database




### Model
* user
    * t
        * username 
        * email
        * first name
        * last name
        * date of birth
        * emergency contact 
        * password_digest
        * token

* admin < user
    * t
* student < user
    * t

    * has_many financial


* financial
    * t
        * amount
* fafsa < financial
    * t 
    * belongs_to student
* tap < financial
    * t 
    * belongs_to student
* loan < financial
    * t 
    * belongs_to student
* scholarship < financial
    * t 
        * amount
    * belongs_to student











# Technologies
* Front End
    * React
* Back End Server
    * Rails Backend
        * Faker for generating Students and Teachers
    * Authentication O-auth

* Database 
    * Postgresql








# Pre challenges
* Making multiple servers talk to eachother








# License
Copyright © 2017