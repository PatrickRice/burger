# burger
- This app follows the MVC (Model, View, Controller) structure and utilizes ORM (Object-Relational Mapping) to dynamically update and display the content of the MySQL database in response to user input.
- With a theme that pays tribute to the movie <i>Pulp Fiction</i>, the app displays the burgers ready to be devoured on the left side of the screen with buttons that allow the user to either devour or delete each uneaten burger listed in this column.  If the user chooses to delete the burger, it is removed from the uneaten burger column and deleted from the database.  If the user chooses to devour the burger, it is moved to the column on the right side of the page and the delete button disappears.
- The user can also add their own burger to the uneaten burger column by entering the name of the burger in the text field (up to 250 characters) and clicking on the "Add Burger" button.  This adds the new burger to the database and displays it in the uneaten burger column with buttons to either devour or delete it.
- Handlebars templates are utilized for the dynamic HTML content and all required NPM dependencies for this app are specified in the package.json file.
- API routes for this app are contained in the controllers/burgers_controllers.js file and the AJAX calls are contained in public/assets/js/burgers.js file.  The MySQL update functions and thier associated logic are defined in the config/orm.js file.
