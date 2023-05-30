# ODS-System
Order Delivery System, a DCOMS(Distributed Computer Systems) Module assignment.

### Technologies involved in the project:
Front end: Java Swing <br>
Backend: Java DB <br>
Others: Passowrd Hashing, Remote Method Interface(RMI), Serialization. 

# Project Background
  The KGF Group Malaysia, a multinational company which focuses mainly on e-commerce. The e-commerce company is best known for its top selling categories like Baby products, Accessories, Home Appliances and Mobile phones through e-commerce platform. At present, the company is using a ODS (Order Delivery System) to handle product delivery, but they feel that the system did not seem to be an easy-to-use platform and it’s not able to handle product delivery as the demand for products are getting increased day by day. So, they would like to have a **ODS (Order Delivery System)** that eliminates the current shortfalls and take control of delivery operations, increase revenue, and delight customers with a single, easy to use platform. 

As a group of 4 members, my team and I have designed and developed an Order Delivery System. Below are my tasks in the project: 
### Task #1: Creation of Server Class in RMIConnections package
In our proposed ODS System, the Client class looks up the Interface object from the RMI registry, and the Register class binds the Server object to the RMI registry. My teammate and I are responsible for creating the barebones Server class and also connecting the Client and Server connections.

### Task #2: Basic Customer CRUD functions 
I am responsible for creating Customer functions that allows them to perform basic CRUD operations (Create, Read, Update, Delete) on items. The CRUD operations allow users to add items into their, view cart, view items from the list of available item, update cart items, and delete items. The following are the developed customer functionalites:
- Customer Main Menu 
- Customer View Item Availabiliy Page
- Add Item To Cart 
- Update Cart
- Delete Cart Item(s)
- View Cart Item(s)
- Search Cart Item
- Purchase Cart Item
 
### Task #3: Relevant connections to the Database
To store the items that the customer has chosen or purchased a database is needed hence a data model is first created that accurately represents the items and their attributes. Afterwards, a connection is established between the database and the customer UI logic where the Cart table will be initialized and static Cart Objects will be stored, ensuring that the data is properly normalized to minimize redundancy and improve data integrity. 
These functionalities include, but are not limited to:
- Cart Object
- Initialize Cart table with some static values

----------------------------------------------
