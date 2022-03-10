## Project Name
badBankFull

## Table of Contents
 - [Description & General Info](https://github.com/briennekordis/badBankFull/blob/main/README.md#description--general-info)
 - [Languages & Technologies](https://github.com/briennekordis/badBankFull/blob/main/README.md#languages--technologies)
 - [Features](https://github.com/briennekordis/badBankFull/blob/main/README.md#dfeatures)
 - [Setup & Use](https://github.com/briennekordis/badBankFull/blob/main/README.md#setup--use)
 - [Suggestions for Improvement](https://github.com/briennekordis/badBankFull/blob/main/README.md#suggestions-for-improvement)
 - [Licensing Information](https://github.com/briennekordis/badBankFull/blob/main/README.md#licensing-information)
 
## Description & General Info
This project is a refactored version of the [badBank](https://github.com/briennekordis/badBank/blob/main/README.md#description--general-info) project (bad because it is an online bank simulation with no built in security!) that now includes a back-end. Whereas the original project only used local context, this iteration
is connected to a database (MongoDB) to store users once an account has been created and allows the users to login. 

badBank was the portfolio project for the module on front end development as part of MITxPro's Full Stack Web Development course.

## Languages & Technologies
- HTML
- React / JSX
- Node.js
- Express
- MongoDB
- Bootstrap

## Features 
- The main feature of this iteration of the badBank application is that the "Create Account" page now connects to a database so that user information is stored. 
The user information can then be viewed in the "AllData" tab of the application. The images below display these new features.
- Please see [Suggestions for Improvement](https://github.com/briennekordis/badBankFull/blob/main/README.md#suggestions-for-improvement) for how these features will be improved in the future. 

![Screen Shot 2022-03-10 at 12 20 56 PM](https://user-images.githubusercontent.com/87245718/157723794-49693be8-58b8-4416-8b0b-1ca6f50156c5.png)
![Screen Shot 2022-03-10 at 12 20 46 PM](https://user-images.githubusercontent.com/87245718/157723816-769b469b-25ce-4300-a7fa-ccbdc8e9e74e.png)
![Screen Shot 2022-03-10 at 12 21 08 PM](https://user-images.githubusercontent.com/87245718/157723832-f3518be1-86ab-4a2a-926e-da78dad7d401.png)


## Setup & Use
1. Download or clone the project's repository. 
3. Navigate to the directory of the project from your command line. 
4. Make sure you have all the needed dependencies installed in the root directory of this project, inluding Node, Express, Cors, and MongoDB
5. Run `node index.js` in your commmand line. If the connection was sucsessful, a sucsess message will be logged in the console as well as indicate on which port the application is running.
6. Navigate to the indicated port (localhost:3000) to view the application
7. Click on the  "Create Account" tab and make a few users. 
8. Click on the "AllData" tab to view the accounts that you have created. 

## Suggestions for Improvement
- As mentioned in the description, this application does not currenlty have authentication or authroization built in to the larger functionality to make this online bank simulation more akin to
 an actual bank's website. A future improvement for this application would be including those security measures and limiting what data can be viewed based on the user's login.

## Licensing Information
This code was written for the MITxPro's Full Stack Developer Course.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
