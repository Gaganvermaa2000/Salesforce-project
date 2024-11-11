CRM APPLICATION FORWHOLESALERICE MILL

Overview
 The Rice Mill CRM Application is a comprehensive solution designed to streamline and simplify how much rice per day,how many were sold that rice and which type of rice all reports send to owners daily wise. It leverages the power of customer relationship management (CRM) to enhance customer experiences, optimize store operations, and improve overall efficiency in the rice mill factory. This project aims to develop a user-friendly and feature-rich application that addresses the specific needs of a rice mill factory. 

Features and Functionality 

Reporting and Dashboards 

 Daily Sales and Production Reports: Generates detailed reports on how much rice is produced & sold each day. 
 Revenue Reports: Provides insights into daily revenue generated.
  Customer Analytics: Tracks popular rice types and most frequent buyers.
  Resource Allocation: Helps owners understand data for better resource allocation and future planning. 

Rollup Summary Field 
 Purpose: Summarizes data from a child object to a parent object that shares a master-detail relationship.
  Functions: Can use COUNT, SUM, MIN, and MAX functions. 

Cross-Object Formula Field
  Purpose: References fields from another object in Salesforce.
  Function: Calculates the total amount payable by multiplying the number of rice units taken by the price per kg. 

Validation Rules 
 Purpose: Ensures data integrity by validating user inputs.
  Is Blank Formula: Verifies if a field is blank and displays an error message if the rule returns a value of "True".

 Permission Sets 
 Organization Wide Defaults (OWD): Defines the baseline level of access for the most restricted user.
  Roles and Access:
 o Owner: Can view records of employers and workers.
 o Employer: Can view records of workers
