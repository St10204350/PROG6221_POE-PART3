# PROG6221_POE-PART3
Readme file

Part3 is a WPF (Windows Presentation Foundation) application that allows users to create, view, and filter recipes. Each recipe contains a list of ingredients and a set of preparation steps. Users can also filter recipes by ingredient, food group, or maximum calories.

Features

- Add ingredients to a recipe.
- Add preparation steps to a recipe.
- View the list of recipes.
- Filter recipes by ingredient, food group, or maximum calories.

Requirements

- .NET Framework
- Visual Studio

Getting Started

1. Clone the repository or download the source code.
2. Open the solution in Visual Studio.
3. Build the solution to restore the necessary packages.
4. Run the application.

Usage

Adding Ingredients

1. Click on the "Add Ingredients" button.
2. Enter the number of ingredients.
3. For each ingredient, enter the name, quantity, and unit of measurement.
4. The ingredient will be added to the list.

Adding Steps

1. Click on the "Add Step" button.
2. Enter the step description.
3. The step will be added to the list.

Adding a Recipe

1. Enter the recipe name in the "Recipe Name" textbox.
2. Add ingredients and steps as described above.
3. Click on the "Add Recipe" button to save the recipe.

Viewing Recipes

1. Click on the "View Recipe List" button.
2. A list of recipes will be displayed.
3. Enter the name of the recipe to view its details.

Filtering Recipes

1. Click on the "Filter Recipes" button.
2. Select a filter option: by ingredient, food group, or maximum calories.
3. Enter the filter criteria.
4. The list of recipes will be updated based on the filter.

Classes

MainWindow

The main class for the application. Handles UI interactions and manages the list of recipes.

Recipe

Represents a recipe with a name, list of ingredients, and list of preparation steps.

Ingredient

Represents an ingredient with a name, calories, food group, quantity, and unit of measurement.

