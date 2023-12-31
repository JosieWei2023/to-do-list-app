# To-Do List App ⭐

The To-Do List App is a **Node.js, Express, MongoDB, and the EJS templating engine** based application designed to help users manage their tasks efficiently.

![todo_app_preview](https://github.com/JosieWei2023/ToDoList/blob/main/preview.png)

## Prerequisites
Before running this project, make sure you have the following installed:

* Node.js: [Download and Install Node.js](https://nodejs.org/en/download "Node.js Download")

* MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community "MongoDB Download")

## Installation 

Follow these steps to set up the application:

1. Open Powershell/Terminal and Clone the repository to your local machine:

   ```bash
   git clone https://github.com/AmanKumarSinhaGitHub/To-Do-List-App.git
   ```

2. Navigate to the project directory:

   ```bash
   cd To-Do-List-App
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Install additional packages:

   ```bash
   npm install mongoose lodash
   ```

## Get Started

To run the To-Do List App, perform the following actions:

1. Open a new PowerShell window.

2. Start the MongoDB:

   ```bash
   mongod
   ```

3. Open another PowerShell window.

4. Launch the MongoDB shell:

   ```bash
   mongo
   ```

5. Open another PowerShell window and Navigate to the project directory:

   ```bash
   cd ToDoList
   ```

6. Start the application using nodemon:

   ```bash
   nodemon .\index.js
   ```

7. Open a web browser and navigate to [localhost:3000](http://localhost:3000) to access the application. Use [localhost:3000/work](http://localhost:3000/work) and whatever you want to create new todo list.

## Usage
* __Home Page (http://localhost:3000):__ This is the default page that shows the "Today" list. 
You can add new items to the list by typing in the input field and clicking the "+" button.

* __Custom Lists:__ You can create custom lists by adding a name in the URL (e.g., http://localhost:3000/work). You can then add items to the custom list and access it using the specified name.

* __Deleting Items:__ To delete an item, click on the checkbox next to the item. It will be marked as completed and automatically removed from the list.


## Project Structure
The project structure is as follows:

* `index.js:` The main entry point of the application. It configures the server, sets up the routes, and connects to the database.
   
   **Models:** "_index.js_" contains the Mongoose models for the database schema.

   * `Item:` The model for individual to-do list items.
   * `List:` The model for the custom lists.

* `public:` This directory contains static files such as CSS stylesheets.
   * `main.css:` This file contains the CSS stylesheets for the application.

* `views:` This directory contains the EJS templates used to render the HTML pages.
   * `index.ejs:` The template for the to-do list page.
---

## Contributing
Contributions are welcome! 

If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

---
## Acknowledgements
This project was created using Node.js, Express, MongoDB, and the EJS templating engine. 

Special thanks to the authors and contributors of these technologies for their valuable work. 

Additionally, I would like to express my gratitude to my instructor [Angela Yu](https://twitter.com/yu_angela "Twitter") for her guidance and support throughout the development of this project.

---

## 🚀 About Me

* I'm a first year postgraduate in Northeastern University.


### Contact Details
* Email: tinaweizq@outlook.com

* LinkedIn Profile: [@JosieWei](https://www.linkedin.com/in/josie-wei-279462245/)

---
