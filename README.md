
## Rest_API
#### How to Run this project
  - Clone this project
  - Open with Postman/Command Shell
  - Run this Command


To deploy this project run

```bash
newman run Project.postman_collection.json -e Project.postman_environment.json
```
To generate report run this command
```bash
newman run Project.postman_collection.json -e Project.postman_environment.json -r cli,htmlextra
```
#### Technology Used
 - Postman
 - Newman 
 #### Prerequisite:
 - Jdk
 - Node Js
 - Newman 
 - Html report libary
 #### Newman and Report Installation Process:
 - Newman Install Command:
 ```bash
npm install -g newman-reporter-htmlextra
 ```
 - Newman Html Report Install Command:
  ```bash
npm install -g newman-reporter-htmlextra
   ```
#### API Documentation
```bash
https://documenter.getpostman.com/view/32179388/2s9YsNfAy2
   ```
### Test Case List
#### Create Booking 
- Create Data Sets Using the Dynamic Random Variables.
#### Verify created booking details through method get
#### validate the following field values::
- First name
- Lastname
- Total price
- Depositpaid
- Check-in
- Check-out 
- Additional needs
#### Create a Token for Update & Delete
- username & password to get a token
#### Update the values
- Use token in the header section to update the values
#### Automate the whole process by setting the Variables in the environment and use them in the body. To random generate huge number of data use pre-request script and postman predifined Variables. 
![1_summary](https://github.com/SaimaNova12/Basicproject-1/assets/76209488/76474a8b-dea6-49f7-a340-5ccba0edcae3)
![2_new](https://github.com/SaimaNova12/Basicproject-1/assets/76209488/a1c6031b-c951-45f8-81d4-c0de84efc1c7)
