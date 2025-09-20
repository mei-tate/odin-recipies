# Odin Recipes Project Instructions

## Iteration 1: Initial Structure

1. Within the `odin-recipes` directory, create a file named `index.html`.
2. Add the usual boilerplate HTML to the file.
3. Inside the `<body>`, add an `<h1>` heading with the text:

   ```html
   <h1>Odin Recipes</h1>
   ```

---

## Iteration 2: Recipe Page

1. Inside the `odin-recipes` directory, create a new folder called `recipes`.

2. Inside the `recipes` directory, create a new HTML file named after the recipe it will contain.
   Example: `lasagna.html`

3. Add the usual HTML boilerplate to the new recipe file.
   Include an `<h1>` heading with the recipe’s name.
   Example:

   ```html
   <h1>Lasagna</h1>
   ```

4. Go back to `index.html` and add a link to the recipe page beneath the `<h1>` heading.
   Example:

   ```html
   <a href="recipes/lasagna.html">Lasagna</a>
   ```

5. On the recipe page (e.g., `lasagna.html`), add a link back to the index page to allow easier navigation.
   This link can go at the top or bottom of the page:

   ```html
   <a href="../index.html">Home</a>
   ```

---

## Iteration 3: Recipe Page Content

Each recipe page should include the following:

1. An image of the finished dish placed under the `<h1>` heading.

2. A **"Description"** section:

   * Use an appropriately sized heading.
   * Include a paragraph or two describing the recipe.

3. An **"Ingredients"** section:

   * Use a heading.
   * Follow it with an unordered list (`<ul>`) of the ingredients.

4. A **"Steps"** section:

   * Use a heading.
   * Follow it with an ordered list (`<ol>`) of the steps to make the dish.

---

## Iteration 4: Add More Recipes

1. Create **two more** recipe pages, following the same structure as your first.

2. Add links to the new recipes on the `index.html` page.

3. Consider using an unordered list to organize your links:
   Example:

   ```html
   <ul>
     <li><a href="recipes/lasagna.html">Lasagna</a></li>
     <li><a href="recipes/pizza.html">Pizza</a></li>
     <li><a href="recipes/salad.html">Salad</a></li>
   </ul>
   ```

> ⚠️ Your links don’t need to be fancy at this point—just focus on building a solid structure.


