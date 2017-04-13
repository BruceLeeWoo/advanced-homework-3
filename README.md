#### Setup
Fork, clone, run yarn install, yarn start, pull request

#### Do
 * Create a component for the category menu
 * Use catgories array from state to populate the menu
 * Create a function in index.js changeCategory(cat)
 * This function will set the value in state for currentCategory and then re render App
 * pass this function down to category menu
 * Put an onClick for each menu item
 * on click call the changeCategory function sending in the category that was clicked
 * change App to filter out the products based on the currentCategory
 * 