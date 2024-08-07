**Project Name:** Text2Query Results generator

**Context:** A large banking corporation with too many stakeholders, always look out for instant query results to extract and report data to address queries associated with their target users. For example, Virupakshi - who is a loan analyst working for Bank of Baroda is tasked to identify a list of users who defaulted on their loan premium payments for the past 3 months in the district of Warangal Urban, Telangana. She is supposed to share this information with loan field operators Sarika, Radha, and Swaroop so that they can conduct an in-person follow-up exercise for the potential recovery of loan premium payments. Virupakshi is a non-technical banker who always seeks assistance from Soumya, a data analyst who runs queries against the loan database to fetch required details. 
Soumya is fed up handling such requests daily from various bankers across all branches in Telangana. Although Soumya is a workaholic, she is now distressed due to this workload as sharing such query results is beyond her daily tasks. She literally needs help!

You can help Soumya by building a simple Text to query system that can generate an SQL query using plain English text as input and generate results that are not more than 1000 rows in the form of Excel/CSV.

**Input:** Plain English query. Below are a few examples:
* Provide me the top 10 transactions of account number: 201621536989 for July 2024.
* Provide me the list of users who used the ATM on January 1, 2024, between 9:00 am to 12 noon and who withdrew money less than 1000 rupees. 

**Output:** Generate the respective results in Excel or probe more if you don't understand the question.

**Stakeholders:**
* _Virupakshi:_ She asks for inputs in plain English and get the required data in excel/csv
* _Soumya:_ Updates the meta-model of the relational database schema so that Virupakshi can ask the right questions through the Text2Query GUI

**Technology Stack:**
* HTML, CSS, JS for Web site with a Chat GUI for Virupakshi, Meta-model updater for Soumya
* SQL generator in JS so that it can be passed to relational database and obtains data to Web using API or RPC

Chornology of Tasks:
* Define a database of your choice and publish a meta-model of the schema in Web readable format (JSON/XML)
* Populate Junk data generation using pre-populated SQL script
* Develope a Chat GUI to initiate a conversation (open to your interpretation)
* Requestor asks a query in plain english, we 

**Team Size:** 4

**Point of Contact:** Sai Anirudh Karre (saianirudh.karre@iiit.ac.in)
