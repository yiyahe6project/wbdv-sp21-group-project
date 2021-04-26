# Group Final Project - Web Development Class Spring 2021

#### Group: YES WR21
#### Group members: Jiahao Cai, Wenhao Ge, Yiya He

## Project Overview
- **App: Online Shopping Application for Drinks** 

- **Summary**

  We build a web application for all cocktail lovers! Here, not only can you purchase your favorite drinks, but also register as seller and create your own store.
  
- **User Roles**
  - Buyer
  
  - Seller
  
  - Admin
  
- **Overall Strategy**

  We utilize external cocktail APIs to implement some features for our application, such as searching a drink, querying details of drink recipes, etc. The tech stack for the application is **React** framework for frontend, **Node** server for backend to store users’ personal information and shopping activities, and **mongoDB** for database.  

  External Web API: https://www.thecocktaildb.com/api.php 


## Requirements
[Requirements for the final project](https://docs.google.com/document/d/1De-UdZ8LpJt6tftlCsYcZz-BCyh8Nljz7KYO5DY00_8/edit?usp=sharing)


## Usage
- Anonymous User

  On the landing page, you can search drinks. Click on the interested drink directs you to the details of the drink. On the details page, you can click Check Stock button to have all sellers listed for such drink with quantity and price.
  
  eg. search "bumble" -> click "bumble bee" -> click Check Stock button
  
- Buyer

- Seller

- Admin

  Login directs to the Personal Profile.
 
  On Personal Profile, you can edit your personal profile, logout, click My Dashboard button to Admin Page.

  On Admin Page, you have three tables: Product Table, Seller Table, Buyer Table.

  - Product Table 

    Lists all products by drink with its total quantities. Click each drink directs you to the drink details: seller, quantity, and price. On drink details, you can edit quantity and price.
 
  - Seller Table
  
    Lists all sellers with a GO TO STORE button beside each seller. Click each seller directs you to its public profile. On public profile, you can edit and update the seller's personal info. Click GO TO STORE button directs you to the seller's store where you can edit as well.
 
  - Buyer Table
 
    Lists all buyers with orders. Click each buyer directs you to its public profile. On public profile, you can edit and update the buyer's personal info. Click Orders directs you to the order details.
   

## Documentation
React Github Repo: https://github.com/yiyahe6project/wbdv-sp21-final-project-yes-wr21-react 
#
React Deployment on Heroku: https://wbdv-sp21-final-project-react.herokuapp.com/
#
Node Server Github Repo: https://github.com/WenhaoGe/wbdv-sp21-group-node-server 
#
Node Server Deployment on Heroku: https://stark-escarpment-57387.herokuapp.com/

Data Model Diagram: https://lucid.app/lucidchart/27c9ea15-542e-46d4-b066-5580168c1a38/edit?shared=true&page=0_0# 

- Info Only

  [Project Proposal Doc](https://docs.google.com/document/d/1f3nphuXPC9qb5DPpZn0fZS5PNubNFAlvHAIjrfeDlmU/edit?usp=sharing)
  
  [PROTOTYPE](https://docs.google.com/document/d/1cBIIGfY1SELaDxHcgyQDbQm0P2pnOK4YSXP0V9RAzXI/edit#)


