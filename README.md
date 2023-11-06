# age-calculator

https://shikhasharma06.github.io/age-calculator/

Element Selection and Traversal:
getElementById(id): Retrieves an element by its unique id attribute.
getElementsByClassName(className): Returns a collection of elements with a specific class name.
getElementsByTagName(tagName): Returns a collection of elements with a specific tag name.
querySelector(selector): Returns the first element that matches the CSS selector.
querySelectorAll(selector): Returns a list of all elements that match the CSS selector.
The code starts by getting references to three HTML elements using their IDs and stores them in the variables outputYears, outputMonths, and outputDays. These elements are expected to be used to display the output of the date difference calculations.

It then creates a Date object named currentDate to represent the current date and time.

It retrieves the current year, month, and day from the currentDate object and stores them in the variables year, month, and day, respectively.

The code also gets a reference to an HTML input element with the ID 'input-date' and a button with the ID 'calculate' using getElementById. These will be used to collect the user's input date and trigger the calculation.

An event listener is added to the 'calculate' button, which listens for a click event. When the button is clicked, the code within the event listener function is executed.
