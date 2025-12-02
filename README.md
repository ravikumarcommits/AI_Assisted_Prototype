# AI_Assisted_Prototype

**CHEF - Convenient, Healthy, Economical Food**  
**Prepared by: Ravi Kumar Agarwal**  
________________________________________
## **Table of Contents**
1.	Problem Statement
2.	Solution
3.	Prototype Overview
4.	Prototype URL
5.	QR Code Access
6.	Home Page
7.	Account Sign-Up Page
8.	Sign-Up Screen
9.	Invalid Credentials Error
10.	Admin Dashboard
11.	Database API Integration
12.	Database Structure
13.	Pre-Orders Table
14.	User Roles Table
15.	Pages Created
________________________________________
## **Problem Statement**  
People living in large metropolitan cities often struggle to find food that is healthy, affordable, and convenient all at the same time. Most fast-food options fall into only one or two of these categories:  
•	Some are affordable but unhealthy.  
•	Others are healthy but too expensive.  
•	A few may be healthy and affordable, but not convenient for people with busy working schedules.  

## **Solution**     
To address this gap, CHEF, which stands for Convenient, Healthy, Economical Food, is testing a solution by launching a food cart outside the Indiana University campus. They created a simple MVP prototype that allows customers to scan a QR code and order from three healthy salad options directly from their phone.
This AI-assisted prototype aims to validate whether their concept can meet the needs of people seeking quick, nutritious, and reasonably priced meals.
Prototype Overview
The user can click the "Pre-order Now" button for any of the three salad options. In the background, every click is recorded and can later be viewed in the Admin Dashboard.
This data helps the CHEF team test, evaluate, and refine their product or concept before moving into full-scale development.

## **Prototype Overview**  
The user can click the "Pre-order Now" button for any of the three salad options. In the background, every click is recorded and can later be viewed in the Admin Dashboard.
This data helps the CHEF team test, evaluate, and refine their product or concept before moving into full-scale development.  

## **Prototype URL**  
The prototype is accessible at: https://sprout-ready-meals.lovable.app/  

## **QR Code Access**  
The following QR code could be displayed at a conference/event, where people can use their phones to scan the QR code which would take them to the CHEF prototype landing page.  

<img width="284" height="267" alt="image" src="https://github.com/user-attachments/assets/cbb86e7a-e07b-465c-be71-46be64bbeb33" />  

Figure 1: QR Code for accessing the CHEF prototype 

## **Home Page**  
The home page displays the three salad options available for pre-order, with clear images and descriptions of each healthy meal choice.  

<img width="672" height="378" alt="image" src="https://github.com/user-attachments/assets/eeb566ca-9ac8-4835-9be2-ce0a9743fc56" />  

Figure 2: Home page of the CHEF website showing salad options  

## **Account Sign-Up Page**  
First-time users can create an account to access the ordering system and track their preferences.  

## **Sign-Up Screen**  
The registration interface allows new users to create their account credentials.  

<img width="401" height="332" alt="image" src="https://github.com/user-attachments/assets/64a446bc-1e11-4bd2-905d-e461440e91fa" />  

Figure 3: Sign-up screen for new user registration  

## **Invalid Credentials Error**  
When a user tries to log in with invalid credentials, an error is thrown that says "invalid credentials" to inform the user of the authentication failure.  

<img width="565" height="390" alt="image" src="https://github.com/user-attachments/assets/2ba81e62-cb33-40f6-bcbe-d5900cb537b2" />  

Figure 4: Invalid credentials error message  


## **Admin Dashboard**  
The number of clicks on the pre-order now button for each salad option is tracked and displayed on the admin dashboard. This provides real-time analytics on customer preferences and engagement.  


<img width="905" height="454" alt="image" src="https://github.com/user-attachments/assets/0b7f62bf-38db-4f98-bc17-92be2ab13223" />  

Figure 5: Admin dashboard showing pre-order analytics  


## **Database API Integration**  
Each click on the pre-order button for each salad type is stored in the database, and from the database, it is displayed on the admin dashboard via the GET API.  



<img width="618" height="461" alt="image" src="https://github.com/user-attachments/assets/b492d319-92f0-4458-9829-8cc9dc248425" />  

Figure 6: Database API integration for retrieving pre-order data  

## **Database Structure**  
The database has two tables: (i) pre_orders and (ii) user_roles.  


<img width="905" height="389" alt="image" src="https://github.com/user-attachments/assets/a7747fcf-a0fa-44cb-91dd-c85502ecc906" />  


Figure 7: Database structure showing both tables  

## **Pre-Orders Table**
The pre_orders table columns include:  
•	id - unique identifier for each pre-order  
•	salad_name - name of the selected salad option  
•	clicked_at - timestamp of when the pre-order button was clicked  

<img width="849" height="591" alt="image" src="https://github.com/user-attachments/assets/a4432f19-21f7-4ff7-9a49-1404c1b4ab71" />  

Figure 8: Pre-orders table structure and sample data  

## **User Roles Table**  
The user_roles table columns include:  
•	id - unique identifier for each role assignment  
•	user_id - reference to the user  
•	role - assigned role (e.g., admin, customer)  
•	created_at - timestamp of role creation  

<img width="601" height="358" alt="image" src="https://github.com/user-attachments/assets/996ae06f-f240-4bcd-9ed2-aaea39db27d0" />  


Figure 9: User roles table structure  

## **Pages Created**  
The following pages were created as part of the prototype:  
•	/signin - Login page  
https://sprout-ready-meals.lovable.app/signin  

•	/signup - Registration  
https://sprout-ready-meals.lovable.app/signup  

•	/admin - Analytics dashboard (admin-only)  
https://sprout-ready-meals.lovable.app/admin    
(this is accessible only after login with valid admin credentials)  
________________________________________  

## **Thank You !**  
Thank you for reading this document. I appreciate your time and attention to the CHEF AI-assisted prototype project. This innovative solution demonstrates how technology can bridge the gap between health, affordability, and convenience in urban food services.











