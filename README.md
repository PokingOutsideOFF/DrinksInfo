## DrinksInfo Project
The DrinksInfo Project is a C# application that uses the Cocktail API to fetch information about various drinks and allows users to store their favorite drinks in a database.

## Project Workflow
1. Models
The Models folder contains the following classes:
- Category: Stores the list of categories received from the API.
- Drink: Stores the list of drinks for a chosen category from the API.
- DrinkDetail: Stores detailed information about a chosen drink from the API.
  
2. UserInput
The UserInput class is responsible for:
Getting input from the user for the category and drink ID.

3. Validation
The Validation class is responsible for:
Validating the input string and ID from the user to ensure they are correct and safe to use.

4. DrinkService
The DrinkService class is responsible for:
- Making requests to the Cocktail API.
- Fetching the list of categories, drinks, and detailed information about a drink.
- Storing the fetched data in their respective model classes.

5. TableVisualisationEngine
The TableVisualisationEngine class is responsible for:
- Displaying the Category Menu.
- Displaying the Drinks Menu.
- Displaying the Drink Details.
- Displaying the Favorite Drink table.
- Displaying the Most Searched Drink table.

6. DrinkRepo
The DrinkRepo class is responsible for:
Performing CRUD (Create, Read, Update, Delete) operations on the drinksInfo database.


