Running The Page
	-Open index.html in a new browser tab or window

Main Portfolio page
	- Inlined CSS to remove render blocking
	- Async'd the JavaScript as they weren't required to render and it removed the render blocking
	- Shrunk the profile pic and the pizza pic using PhotoShop to bring them down in size to an acceptable level
	- Removed the font link, as it was not changing the rendered page
	
Pizza page
	- Pulled out the class from the pizzaSize function for loop and the document prototype from the updatePositions function for loop and placed them in separate variables as they did not need to be run on every iteration through the loop
	- Moved the items variable out of the updatePositions for loop into the function scope as it did not need to be calculated on every iteration
	- Lowered the number of pizzas that are painted in the function from 200 to 75, as 200 seemed to be more than was needed
	-Pulled the items variable out of the updateposition function as it did not need to be created each time the function was called
	-Assigned the value of items.length to a seperate variable outside the function, as it did not need to be run each time the function was called
	-Changed the style.left to style.transform and used the translateX value to move the pizzas along the x-axis
	-Used the style.left in DOMcontentloaded function to establish the initial position of the pizzas so they would move correctly
	
References 
	- The google developers website https://developers.google.com/web/fundamentals/
	- The Piazza discussions at 
		- https://piazza.com/class/i0sf6tsmg0r7do?cid=1198
		- https://piazza.com/class/i0sf6tsmg0r7do?cid=1218
		- https://piazza.com/class/i0sf6tsmg0r7do?cid=1071
		- https://piazza.com/class/i0sf6tsmg0r7do?cid=1204
	- The compression tools at http://www.textfixer.com/html/compress-html-compression.php and http://jscompress.com/ which I did see listed in Nathan Bateman's github
	- The slideshow at https://docs.google.com/presentation/d/1CH8ifryioHDLT1Oryyy8amusUmq2FytpCPCpk0G3E4o/edit#slide=id.g1762bf0ec_02
	- The links included in the ReadMe file with the original repository
	- Previously having read the books Thinking in JavaScript and JavaScript, A Beginner's Guide
	- Several of the office hours discussing this project

I hereby confirm that this submission is my work. I have cited above the origins of any parts of the submission that were taken from Websites, books, forums, blog posts, github repositories, etc. By including this in my email, I understand that I will be expected to explain my work in a video call with a Udacity coach before I can receive my verified certificate.

Jeffrey Barnes