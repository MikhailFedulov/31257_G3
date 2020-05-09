# Travel Company CMC Upgrade Proposition Report


* 12910321(Jett Hendry)
* add student number(Matthew Fouad)
* add student number(Marcus Huth)
* 12590143 (Mikhail Fedulov)


## Current Problem and Objectives of the Project

### Background
Travel companies always strive for customer excellence in everything they do. In the dynamic world, customers' behaviour and needs constantly change motivating companies to adapt and go beyond customer expectations in the way they interact and build relationships. Major Travel Company (MTC) desires to improve the operations of their in-house customer management centre (CMC), the “human-face” of the customer service, by developing a new information system. The system will influence Relationship Managers sales and assist with the current and potential customers interactions. The system will be deployed to assist with both, inbound and outbound calls and will be able to communicate with other enterprise systems including, HR and customer profile creation tool Profiler Tool. The system will target a wide range of customer relationship aspects and features call routing, Interactive Voice Response, customer-to-RM matching, customer target list generation, RM skill score calculation, customer score calculation, and data analysis. 


MTC approached us to conduct the project due diligence and develop a business report for the executive team based on the project strategic fit. 



### Objectives
For the project to be successful the following objectives have been extracted from the project debrief and the client’s needs. The client desires a more efficient and robust system which will be able to distribute the CMC load accordingly now and in the future. Based on the information provided by the client, three primary objectives have been identified which will influence the decision making process throughout the project life cycle: 
    1. Improve customer experience which will reflect on 2% lower churn rate after one year of operations of the new system.  
    2. Increase travel packages sales by 5% within the first year of the new system implementation.
    3. Minimise costs of inbound calls by 20% within the first year of the new system implementation. 

This report includes the key information required for successful project delivery including KPIs, stakeholder analysis, project assumptions, system design including workproducts and practical models, and identifies competitive advantages that might be gained in developing the new system.


### Problem definition
## Problem Statement 
Based on the Stakeholder Analysis and POVs of each stakeholder category we have defined an overarching problem statement that incorporates various aspects of the project. 

Currently, the operations of CMC relies on a lot of manual data manipulations from the working staff and its overall performance is challenging to keep a track of. Analysis of each stakeholder group indicates a need for a more robust and reliable system which can be used to better customer service. 
The incremental loss in efficiency means that MTC has not been meeting its sales and portfolio goals over the last 3 years which has pushed the churn rate to alarming levels. 
To reduce the CMC operations costs, increase sales and improve customer satisfaction, a new automated system will be implemented. By replacing the current manual system with a more automated one, MTC will address the existing issues and gain competitive advantage on the market. 


### Assumptions
1. For the purpose of this project, it is assumed that customer profile creation tool Profiler Tool has been implemented, tested, and supports communication with other enterprise systems including the new CMC system. 
2. HR system that creates profiles for Relationship Managers upon hiring and is capable of building matrices for each employee that later can be communicated to other enterprise systems including the new CMC system. 
3. Project is approved and passed financial due diligence.
4. The project rollout is well thought out by the implementation team to minimise CMC downtime.  
5. The existing CMC operations rely on manual input and data manipulation from the users including, Relationship Managers, Business Analysts  and IT. 
6. MTC has had an incremental loss due to low CMC efficiency. Sales and portfolio goals weren’t met in the last 3 years which led the company to reevaluate CMC operations. 



### KPIs
To measure the project success and whether the project objectives have been satisfied, the new system performance needs
to be monitored over a period of 1 year and analysed against the performance of the legacy software.

Improve customer experience
* Customer Satisfaction
* Churn Rate
* Retention Rate

Increase travel packages sales
* Number of packages sold
* Individual RM’s average sales
* Sales Growth Increase

Minimise costs of inbound calls
* Savings
* Cost Reduction
* Cost Avoidance

## Stakeholders

### Internal Stakeholders
* Major travel Company executive team
The head executive team of the major travel company. They will ultimately have the final say over the entire project as they hold the highest authority within the company. They are responsible for ensuring the company investors and shareholders are adequately satisfied with the businesses current projects 

* RM (Relationship Managers)
The employees that currently work in the CMC department. They are tasked with providing support and ensuring sales to customers calling in. The proposed CMC upgrade solution will directly affect these stakeholders day to day work efficiency and therefore they will be high priority points of contact in project solution development feedback. 

* CMC management
The management personnel overseeing the CMC department. They are responsible for the efficient functioning of the travel companies call center operations. As they are also closely associated with the utilization of the finished CMC solution they will be consulted regularly alongside the RMs during project development 

* Project Team 
The project team is a combination of internal and external resources and is responsible for the project implementation. They will be working closely with the other stakeholder during the project development. 


* Other CMC employees (Business Analysts, IT department, Cyber Security ect.) 
Difficulty they face when interacting with the system. Current system management, a lot of manual work.  

* Internal resources available for the system development (Software Engineers, Scrum Managers, IT and Security analysts ect)

### External Stakeholders
* Customers 
Customers pertain to any individual who will be utilizing the product upon its release. As these individuals are the companies target for sales, they are paramount to the solutions success from implementation onwards as well as the businesses ongoing success. 

* External developers (contractors, external development company)

* Company Investors and Shareholders
Those that fund the companies ventures and have financial stakes in the ongoings of the travel company. As they are the financial contributors of the company they are the stakeholders that the executive team are most focused on pleasing and therefore their needs must be met by the development teams solution. 

* Competitors
Competitors in the space it is important to analyse the industry landscape and identify other firms practices and how they compare to our clients. How strong is the need for the new system and whether it will bring a competitive advantage. 



### User Stories 
Key | Stakeholder | User Story | Estimates | Priority 
------------ | ------------- | ------------- | ------------- | -------------
101 | Relationship Manager | As a Relationship Manager I would like to be able to see a summary of sales pre day/week/month/year so that I can track my progress and report it to the management. | 1 | Medium 
102 | Relationship Manager | As a Relationship Manager I would like to be able to view customers profiles so that I can understand the customer situation better. | 1 | High
103 |Relationship Manager | As a Relationship Manager I would like to be able to edit customers profiles so that I can keep their profiles up to date. | 1 | High
104 | Relationship Manager | As a Relationship Manager I would like to be able to get a list of potential customers to get in touch with from the system so that I can be more efficient at my work. | 1 | Medium
105 | Relationship Manager | As a Relationship Manager I would like to be able to record a number of successful calls made with proposed customers so that I can track the performance. | 1 | Medium
106 | Relationship Manager | As a Relationship Manager I would like the system to direct customer calls to me based on our compatibility so that I can assist with their queries quicker and customise the answer. | 1 | High
107 | Relationship Manager | As a Relationship Manager I would like the system to assign each customer a score based on likelihood to purchase the product is given to the customer according to some preloaded criteria (repeat customer, customer from particular postcode) so that I get the most perfect match. | 1 | medium
108 | Relationship Manager | As a Relationship Manager I would like the system to retrieve customers details from the database so that I can optimise my time managing customers information. | 1 | High
201 | MTC executives | As a MTC executive team we would like the system to be able to produce high level reports of CMC performance including costs, revenues, profits, and overall portfolio summary so that we can monitor performance and make strategic decisions. | 1 | High
202 | MTC executives | As a MTC executive team we would like the system to direct customer to Interactive Voice Response IVR during busy times so that we can optimise the CMC performance and keep customers on the line and engaged. | 1 | Low
203 | MTC executives | As a MTC executive team we would like the system to prompt options to customers during IVR including reasons for calls and then redirect to the Automatic Call Distributor routing which will assign the first available RM to answer the call. | 1 | Low
204 | MTC executives | As a MTC executive team we would like the system to manage both inbound and outbound calls so that CMC performance is optimized. | 1 | High
205 | MTC executives | As a MTC executive team we would like the system routing and distribution routing that minimizes inbound call costs by reducing per-call handling time so that we can cut unnecessary costs. | 1 | Medium
301 | CMC management | As a CMC management team we would like the system to be able to produce summary reports on Relationship Management performance so that we can analyse what training to provide to them. | 1 | Low
302 | CMC management | As a CMC management team we would like the system to be able to show a summary of all managed Relationship Managers performance so that we can track each team's sales and work hours. | 1 | High
303 | CMC management | As a CMC management team we would like the system to be able to track the working hours of Relationship Managers so that we can track performance and communicate this information with payroll. | 1 | Medium
304 | CMC management | As a CMC management team we would like the system to be able record conversations between customers and Relationship Managers so that it can be used later for training purposes. | 1 | Low
305 | CMC management | As a CMC management team we would like the system to show Relationship Managers individual profiles so that we can view and edit details as necessary. | 1 | Medium
306 | CMC management | As a CMC management team we would like the system to assign each Relationship Manager a skill score from 1-10  calculated based on RM’s previous call duration and profile. | 1 | Medium
307 | CMC management | As a CMC management team we would like the system to access Relationship Managers profiles from Portfolier Tool so that we can communicate information easily with HR. | 1 | High
308 | MTC customer | As a MTC customer I would like to get in touch with a Relationship Manager over phone so that they can assist with  my query. | 1 | High
309 | MTC customer | As a MTC customer I would like my call to be answered as quickly as possible by the Relationship Manager so that my query will be resolved efficiently. | 1 | High







