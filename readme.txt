Main Portfolio page
	- Inlined CSS to remove render blocking
	- Async'd the JavaScript as they weren't required to render and it removed the render blocking
	- Shrunk the profile pic and the pizza pic using PhotoShop to bring them down in size to an acceptable level
	
Pizza page
	- Pulled out the class from the pizzaSize function for loop and the document prototype from the updatePositions function for loop and placed them in separate variables as they did not need to be run on every iteration through the loop
	- Moved the items variable out of the updatePositions for loop into the function scope as it did not need to be calculated on every iteration
	- Lowered the number of pizzas that are painted in the function from 200 to 75, as 200 seemed to be more than was needed