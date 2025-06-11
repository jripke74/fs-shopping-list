# fs-shopping-list

In this workshop, you will practice how to work with arrays by building a shopping list.

You will review how to add and remove elements from an array using methods like push, pop, shift, and unshift.

Step 1
In this workshop, you will continue to learn about arrays by building a grocery shopping list.

Start by adding a console.log that logs the string "Grocery shopping list" to the console.

Step 2
For this shopping list, you will use an array to represent the items you need to buy.

In the previous lecture videos, you learned how to create arrays like this:

Example Code
const fruits = ['apple', 'banana', 'orange'];
In this step, create a variable called shoppingList and assign it an empty array.

Step 3
For this next portion of the workshop, you will practice adding food items to the grocery list.

Start by using console.log to log the message "It will be nice to have some fruit to eat.".

Step 4
In the previous lecture videos, you learned how to add items to the end of an array using the push method like this:

Example Code
fruits.push('pear');
Using the push method, add the string "Apples" to the shoppingList array.

Step 5
To see the updated shopping list, you will need to log the current shopping list and a short message to the console.

Since this message will be used repeatedly throughout the workshop, it is best to create a reusable function.

Create a function called getShoppingListMsg that takes an array as a parameter and returns the string "Current Shopping List: " followed by the contents of the provided array.

You can use template literals or string concatenation with the + operator to combine the string and the shoppingList array.

Step 6
Now it is time to see the message logged to the console.

Add a console.log and call the getShoppingListMsg function inside of the console.log to see the message logged to the console.

Step 7
Now it is time to add another fruit to the list.

Using the same array method as earlier, add the string "Grapes" to the end of the shoppingList array.

Then, add a console.log and call the getShoppingListMsg function inside of the console.log to see the updated list logged to the console.

Step 8
Now it is time to start adding items to the top of the grocery list.

Start by adding a console.log that logs the message "It looks like we need to get some cooking oil." to the console.

Step 9
In the lecture videos, you learned how to add elements to the beginning of an array using the unshift() method.

Here is a reminder of how to use the unshift() method:

Example Code
array.unshift(item1, item2, ..., itemX);
Use the unshift() method to add the string "Vegetable Oil" to the beginning of the shoppingList array.