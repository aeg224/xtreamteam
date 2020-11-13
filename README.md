# Xtream Team

### Project Name: Secure Food Distribution App

### Team Members<br>
- **Prashant More**: Product Owner / Developer
- **Alexander Giannini**: Scrum Master/ Developer
- **Juan Valladares**: Developer
- **Anup Shetye**: Developer
- **Manav Agarwal**: Developer
- **Davie Wilkie**: Developer

### Product Name: 
The product is an open source using MIT licensed and it is called Supply Line Food.

### Far Vision<br>
Create an app that will leverage Blockchain and QR-Code Technology to enable NonProfits Vendors and Donors to securely distribute of food during the pandemic. 
The idea of a system to distribute food or goods to people in poor countries was originated by the current Covid-19 pandemic. Millions of people are in desperate need of basic things like food, medicine, money, etc. Time is running out and there is a need to find ways to distribute goods faster, with the lowest overhead and as efficient as possible.   

Governments have the responsibility to help their population during periods of crisis. One of the major problems is the lack of food in urban and remote locations.  Their solution is to create gigantic programs to buy large amounts of food and distribute them all over the country. Timing is one of the biggest problems, the logistics required demands the participation of thousands of soldiers, government employees and public institutions trying to deliver the food as fast as they can. However, Governments are not the most efficient organization to carry out this type of endeavor and usually, these tasks are tainted with the perception of corruption or involve acts of corruption. 

Usually, international organizations, donors, and people interested in collaborating in this type of effort are reluctant to donate resources to Governments due to the lack of transparency or the risks the funds are diluted in non-essential activities or the money doesn’t reach the intended people.

To accomplish the goal of delivering food/goods to under-resourced people, we are proposing a solution based on blockchain, mobile apps, and organizations with a reputation that guarantees the people will receive the donations with the lowest overhead, and fastest and most efficient delivery. 

The solution addresses the biggest problem: Massive delivery of food/goods creates a huge bottleneck to reach the people on time.  The second problem is that the food delivered solves the immediate need but may have long term negative health consequences. Also, this solution will help to feed people in need but also will keep the local business open and jobs. 

We believe that the solution requires bringing the access directly to the local families without any intermediary so they can buy the food they need. They have lost the source of income and therefore they can’t buy the right food according to their diet. We cannot give money because a big portion of the population will use the money for other purposes.  The best way to solve this problem would be to create a mechanism that guarantees they can get access to food, but can only be used for the intended purpose. We propose the creation of certificates for this purpose

### Near Vision Create an app that will build a basic framework for the far vision
    - Allow beneficiaries to sign up and receive an ID in the system and use QR Code technology to identify themselves in the system.
    - Allow donors to donate money to the organization. 
    - Allow the Non-Profit organization to assign the money to each beneficiary.

### Stake Holders:
  
  - **Non-Profit**: This stakeholder is any organization who wants to help to distribute food in underdeveloped countries. The organization will raise funds in developed countries and coordinate non-profits in each Country to coordinate food distribution in the communities and use this application to orchestrate the process safely and transparently.

  - **Family in need**: This stakeholder receives the benefits of this process. the Local non-profit will coordinate the food's distribuition and locate those families 
  that require support. 
  - **Donors**: This takeholder provide the funds to finance the process.  
  - **Vendor**: Local vendors give the groceries to the families in exchange of the funds received from the non-profit organization.  

  ### Real Person: 
  
Alejandra, is a mother of two, 31 years old who lives in Tegucigalpa, the capital city of Honduras. She works as office cleaner. Her husband work in construction. During the pandemic, both lost their jobs and have had difficulties to feed their family. Honduras, an underdeveloped country doesn’t have the resources to feed the whole country. This has been in lockdown since March and citizens can only leave their home once every 10 days. Some essential workers can go out, but they can’t because offices are closed, and construction work has been stopped. She has been struggling to feed her family and provide the basic needs. Food is one of the major issues due to the lack of job, money and they have to rely on some government assistance,  when it is possible, or non-profit such as churches or organizations that distribute food from time to time. Sometimes, they have to violate the lockdown to go out and look for groceries, or try to gain some money with temp jobs.

### Real Stakeholder

The beneficiary is a stakeholder that will be using the app but, at the same time, receiving the resources donated by donors.  It will sign up to request financial support, and the Non-Profit organization will give the funds when this person passes a vetting process. This process is essential because they will receive groceries with a monetary value, and it is necessary to make sure that this stakeholder requires financial assistance. 

The beneficiary will have an ID in the system, and this ID is used to identify the individual and make sure that the same person requesting help is the same person who will receive the goods at the store.
 
 
## Product Backlog
We are using Jira to manage our backlog and it can be seen this address [Jira Backlog](https://xtremeteam3.atlassian.net/secure/RapidBoard.jspa?rapidView=1&projectKey=SFDA&view=planning&selectedIssue=SFDA-1&epics=visible&issueLimit=100)

### Ordering
<br>
For Product Backlog ordering, we decided to first implement the signup functionality, then the login functionaly, then the core functionality and then the security. We determined that this order will allow us to properly test the application due to technical constraints. Specifically, the creating the signup and login first will allow us to build the technical framework to power the rest of the application.
<br>

## Definition of Ready
Title: Secure Food Distribution Application
User Story Opening Sentence: Given ... When ... Then ...
Additional Details :  listed in the stakeholder information
Acceptance Criteria: THe application should meet all criteria including all business logic and testing requirments. These Include:
    - App should allow beneficiaries to sign up and receive an ID in the system and use QR Code technology to identify themselves in the system. ESTIMATION: 63
    - App should allow donors to donate money to the organization. ESTIMATION: 37
    - App should allow the Non-Profit organization to assign the money to each beneficiary. ESTIMATION: 50
    - App should be reasonable Secure ESTIMATION: 13
    - Contact Page that can be used by any visitor ESTIMATION: 5


### Estimation
#### For Estimation, we used 'Planning Poker' to execute whole-team relative sized estimation. Only developers participated. We met as a group and estimated Story Point's with the following numbers : 1, 2, 3, 5, 8, 13, 21, 34, 55, 89. We discussed each item and determined a general approach as a team. Our conclusions were all unanimous and are listed below.

#### EPIC: Signup Capability
1. Signup capability for NPO - ESTIMATION 21
2. Signup capability for Families - ESTIMATION 21
3. Signup capability for Donors - ESTIMATION 21
#### EPIC: Login Capability
4. Login functionality for NPO - ESTIMATION: 8
5. Login functionality for Families - ESTIMATION: 8
6. Login functionality for Donors - ESTIMATION: 8
#### EPIC: Core Functions
7. Ability to retrieve QR Code For various roles ( stakeholders) - ESTIMATION: 21
8. Unique QR Code should be assigned to Families - ESTIMATION: 13
9. Donor should be able to donate money - ESTIMATION: 8
9. NPO should be able to distribute funds - ESTIMATION: 21
11. Contact Page/ Help form - ESTIMATION: 5
#### EPIC: Security
12. Implement basic web security practices - ESTIMATION: 13
'




# PRODUCT BACKLOG (REVISED)
Create Home Page: ESTIMATION 21
Story: As an App User, I need to find the App through a search engine, and therefore need a home page to land on
Acceptance Criteria: App is hosted on a web server and is serving a static webpage with basic SEO

Create QR Code : ESTIMATION 34
Story: As a Family, I need to get QR Code online to be identified for Humanitarian Relief
Acceptance Criteria: A page is created on the site that displays a unique QR Code every time is is loaded. A database is created to store each QR code and confirm unique ones are being generated

Build Registration Page : ESTIMATION 34
Story: As an app user, I need a page to register and login
Acceptance Criteria: A page must be created that allow the user to register. Upon registration a confirmation email is created.

Build Login Page : ESTIMATION 21
Story: As an app user, I need a page to login
Acceptance Criteria: A page must be created that allow the user to login. Login should not occur if username and password are not in database.

Build View Profile Feature for Families : ESTIMATION 21
Story: As a family, I need to be able to view my QR Code and current balance.
Acceptance Criteria: App allows logged in users to view their account information.

Build Edit Profile Feature : ESTIMATION 21
Story: As a family, I need to be able to edit my profile (in case of contact information change)
Acceptance Criteria: Users can edit their account information on file

Build Donor Page with Unique Account Information : ESTIMATION 21
Story: As a donor, I need to be able to view my account information and view past donations
Acceptance Criteria: Donors must be able to register and increase the amount of funds the NPO has access to

Build NPO Page For Fund Distribution : ESTIMATION 21
Story: As an NPO, I need to be able to register and login to distribute the donated funds to families
Acceptance Criteria: NPOs must be able to register and distribute the funds

Build Vendor Page to Remove Funds from Family Accounts : ESTIMATION 21
Story: As a Vendor, I need to be able to transfer money from the Fmailies Accounts to my own when I provide them goods
Acceptance Criteria: Vendors can registarer and remove funds from a family's account according to the number on their QR Code

Build Contact and Support Page : ESTIMATION 13
Story: As a App User (Families, NPO, Donors), I need to be able to contact someone with any questions about the app
Acceptance Criteria: Page is created with contact form that emails contents of form to dedicated email addresss.

Web Security : ESTIMATION 34
Story: As an App User, I need to know that my personal and financial data is secure
Acceptance Criteria: app is password protected with authorization with https and passes basic security audit.



# Sprint Planning

For our first Spring we forecast being able to complete 75 Story Points.
Rational: While 75 points seems like a lot, we want to be sure to build a good foundation to build upon for the rest of the application. We are hopeful we will be able to complete everything especially considering Veterans Day is Wednesday and we may have a bit more time than normal. 

## Sprint Backlog
The Development Team (alone) chose this Spring Backlog after we refined some the items during Product Backlog Refinment.

Create Home Page: ESTIMATION 21
Story: As an App User, I need to find the App through a search engine, and therefore need a home page to land on
Acceptance Criteria: App is hosted on a web server and is serving a static webpage with basic SEO

Create QR Code : ESTIMATION 34
Story: As a Family, I need to get QR Code online to be identified for Humanitarian Relief
Acceptance Criteria: A page is created on the site that displays a unique QR Code every time is is loaded. A database is created to store each QR code and confirm unique ones are being generated

Build Registration Page : ESTIMATION 34
Story: As an app user, I need a page to register and login
Acceptance Criteria: A page must be created that allow the user to register. Upon registration a confirmation email is created.

## Tasks
PBI #1 Set up AWS Instance w/ security settings
PBI #1 Register SSH Key with Juan's GitHub
PBI #1 Confirm instance has Access and can pull from the repo
PBI #1 Create a Spring Boot App with buil-in server
PBI #1 Allow App to serve static files
PBI #1 Build and run tests for confirm everything is working
PBI #1 Delpoy app to server via gitHub
PBI #1 Build HTML Page with Basic SEO

PBI #2 Create Database or file to store QR Code
PBI #2 Build HTML Page with Bootstrap 
PBI #2 Page displays a QR Code using an API
PBI #2 Build and run tests for confirm everything is working

PBI #3 Build HTML with Bootstrap and a form that receives information
PBI #3 Allow Users to create an user entry in the database/file
PBI #3 Build and run tests for confirm everything is working

Sprint Review - Sunday 6PM 




# 11/11 Daily Scrum
At 6pm our Development had the Daily Scrum

## Past 24 Hours
In the past 24 Hours we all spent time researching different web development approaches that we may want to use:
Alex G - had built a Vue app
Manav had found a Template that uses Spring with Vue
Juan - Created an Angular Project and explored how Spring Works
Anup - Started to work with Spring Board and React JS

## Impediments
Impediment: We have not all agreed on a technology to use
Solution: We will continue to discuss and will build as necessary. We will also see what technology works best as we go.

Impediment: Our Product Backlog Items need to be redone
Solution: We will refine our product Backlog before the end of the meeting today.

Impediment: We do not have an updated burndown chart
Solution: Prashant will add the new product backlog items to the chart once we complete the Product Backlog Revision

## Next 24 Hours
Mob Programming Session to deploy trivial app on Development Environment
Continue building test cases
Continue researching front-end options (Vue, React, Angular)

## Application
Server: http://ec2-54-193-9-226.us-west-1.compute.amazonaws.com:8080/



# 11/13 Daily Scrum
At 6pm our Development had the Daily Scrum.
To start, we generally discussed the tasks and what approach we will to take.

## Past 24 Hours
Alex - Looked at QR Code API options. Considered Agile and Daily Scrum Approaches. Mob Programming for PBI #1.
Manav - Looked at different frontend options and frameworks. Considered login approaches (cookies, jwt w/Spring). Mob Programming for PBI #1.
Juan - Worked on HTML and Markup for Home Page (for PBI #1). Considered design and marketing ideas (logo). Mob Programming for PBI #1.
Prashant - Discussed Spring Application approaches with Anup. Considered test-case approaches. 
Anup - Worked on spring/Boot Application for PBI #1. Worked on Test Cases. Mob Programming for PBI #1.

## Next 24 Hours
Anup - Will continue working on test cases for PBI #1.
Prashant - Will add the updated PBI's to Jira and will work on test cases.
Juan - Will complete the home page and template for login/signup and QR. 
Manav - Will work on the QR Code and research front-end approaches.
Alex - Will take a look at the code and research QR Code approaches. Will Send a gmail invite for our next meeting.

## Impediments
Schedule : Sunday Evening does not work for everyone. We rescheduled our meeting. 

## Other
We changed our scheduled meeting to Sunday from 2-4pm.








