# Alfaro_G-P1

# P1
# Robotic Shopping Assistant 2.0

# Tech Stack
- UiPath Studio
- HTML
- CSS
- Javascript
- PostGreSQL

# Features
- Automation will add client to database to be stored and later read to process transaction.
- Automation will shop at the correct store and scrape the price, item and quantity.
- Automation will then calculate the total price of the shopping trip and insert it into SQL database.
To-Do List:
- Implement pdf and email automation for each clients order.
- Clean up code for quicker runtime.

# Getting Started
- Copy the path of the github repository.
- Use git clone "github path" in git bash.
- Open project in UiPath.
- Run project in Main xaml file.

# MVP Functionalities
- [x] Robot should be able to take client shopping lists and place orders on the appropriate vendors.
- [x] Robot should record the total expense of each shopping trip for each client.
- [ ] Robot should be able to record any items that were out of stock or not found.
- [x] Robot should be able to add clients to the existing client list and take in their shopping order.
- [x] Robot should shop from at least 2 vendors
- [x] One of the vendors should be Pega
- [x] The other vendor should be a self made shop using HTML, CSS, and JS

# Constraints
- [x] Client information should be stored in a DB
- [x] Vendor information should be stored in a webpage
- [x] Expense Reports should be stored in a DB
- [x] Automations should have exception handling enabled
- [ ] DB tables should be 3NF

