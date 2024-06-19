# things-of-bob

Guidelines:
 
The following exercise is designed to let you show some of your coding skills, but to also show us how you think and solve problems. The expectation is that you should have to spend 30-60 minutes of your own time working on this exercise. We are not going to hold a stopwatch to you, and you can use any resource you want. You may use any combination of AWS Services you want to accomplish the task. You should be prepared to discuss your solution, including alternatives considered and discarded as you selected your components.
 
While we like functioning code to look at, it is acceptable to have detailed pseudocode.

Our goal here is not to criticize or condemn your work, but to get a sense of how you think and create 
 
** Scenario **
 
 
You will be creating an integration between our systems and a major retailer, codenamed BOB. 
BOB has been selling name brand products for years, and has millions of skus. In recent years, some of those products have not sold as well and are clogging up their warehouses. They want us to sell these items on secondary discount sites for as much as we can. We are not the only player in this endeavor, so BOB will assign inventory to us.
 
BOB's IT department is overloaded, and has little time to help us. They have provided us with an API which allows us to pull the inventory that has been assigned to us. The API is a simple REST API which returns paged inventory data including:
SKU, Description, SerialNumber, Vendor ID Number, QTY, Location (Warehouse BOB Warehouse BILL),

You should create this API data source anyway you see fit - RDS DB with an API endpoint is fine, mongo is fine too, we just want to see you grab data, manipulate it and store it. It gives us a good understading of how you work through the different needs a customer has. Feel free to use any AWS technology you see fit, but please limit it to AWS.
 
We need to extract this data and persist it into a database.
 
We need to refresh this data a minimum of once every hour.
