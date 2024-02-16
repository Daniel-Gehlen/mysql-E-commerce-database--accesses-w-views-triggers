### Report: Customizing Database Accesses and Triggers

#### Introduction
In this report, we will discuss the implementation of access customizations and triggers in a relational database, using SQL language. The main objectives are to create views for various scenarios and to develop triggers for specific scenarios in a simulated e-commerce environment.

![photo](/ecommercedb-accesses-w-views-triggers.png)

#### Methods
1. **Customizing Accesses with Views:**
   - We created several views to meet different scenarios, such as the number of employees per department and location, a list of departments and their managers, projects with the highest number of employees, a list of projects with departments and managers, and which employees have dependents.
   - We used SQL queries to join tables, perform counts, and filter data as necessary for each view.
   - Access permissions were defined for each view according to the user account type, allowing access only to relevant information for each user profile.

2. **Creating Triggers for E-commerce Scenario:**
   - We developed triggers to handle specific actions, such as deletion and updating of data, in a simulated e-commerce environment.
   - We created `before delete` triggers to prevent the loss of important information when deleting records, such as deleting user accounts.
   - `Before update` triggers were implemented to apply constraints or adjust data before an update, such as preventing the reduction of employee salaries.

#### Results
- All objectives were successfully achieved. The views were created, and access permissions were configured according to the needs of different types of users.
- The triggers were implemented and tested, ensuring that deletion and data update actions occur according to the defined policies.

#### Conclusion
Customizing accesses and using triggers are important strategies to ensure the security and integrity of data in a database management system. By restricting access to sensitive information and applying automatic actions on certain events, we can better control and protect the stored data.

#### Case Study:
Imagine an e-commerce company that needs to manage data for its employees, departments, projects, and customers. By implementing the access customizations discussed in this report, the company can ensure that only relevant information is accessed by different teams, such as department managers and regular employees. Additionally, triggers can be used to automate important tasks, such as keeping a record of salary changes or preventing accidental deletion of customer accounts. This contributes to operational efficiency and data security for the company.

This report highlights the importance of advanced database management strategies for modern businesses, demonstrating how access customizations and triggers can be effectively applied in practical scenarios.



![photo](/ecommercedb-routines.png)

