# Day 7 of Code 102!!

## Scripts
  1. Access content
    - You can access text from the HTML document i.e. `<h1>`
  1. Modify Content
    - You can add text after headings/lines in an HTML Doc
  1. React to Events
    -You can make JS react to a button being pressed or after a certain point of loading a page.
  1. Just like learning a recipe, there is a lot of terminology to learn about. When I first started cooking I had no idea what a julienne was. It is the same concept. Whether it is an easy script or complex, it is the same as a simple or complex dish.

## Script Design
  1. List out the tasks that need to take place on a FlowChart
  1. List the steps required to do job

## Key things to keep in mind

  1. Vocabulary of JS- the words that computers understand
  1. Syntax- How you put those words together to create instructions computers can follow.
  1. I need to learn to think like a computer, it thinks and solves things differently than we do.

## Expressions & Operators

### Two Types of Expressions
  1. Expressions that just assign a value to a variable
    - `var color = 'beige';`
  1. Expressions that use two or more values to return a single value
    - `var area = 3 * 2;`
### Expressions rely on Operators
  1. assignment operators
    -`color = 'beige';`
    -`area= 3 * 2;`
    -`greeting = 'hi ' + 'Molly';`
    -`buy = 3 > 5;`
    -`but = (5>3 && (2 < 4);`
Function Demo

Any time you make a new function, create a new file.

`<script src="functionDemo.js"></script/>`
Functions have three parts:
1. Inputs
2. Work
3. Outputs (return value)

.. And then we have to tell them to run.

1. Inputs/parameters: meat, cheese, bread
2. Work: Assemble our sandwich form these supplied ingredients (Parameters)
3. Output (return value): sandwich

Pseudocode: Fake code
1. Parameters: Meat - "turkey", cheese - "pepperjack", bread - "wheat"
2. Work: "Here is your beautiful sandwich. It has " + meat +" and " + cheese + " on " + bread + "."
3. Return value: "Here is your beautiful sandwich. It has turkey and cheese on wheat. Enjoy!

JavaScript Code:

`Function makeSandwich (meat, cheese, bread) {`
//  work goes in here
`Var newSandwich =  "Here is your beautiful sandwich. It has " + meat +"` `and " + cheese + " on " + bread + ".";`
// tell JavaScript to return
`Return newSandwich;}`

// "call" (or run) the function with these specific input values (aka "arguments")
`Var korySandwich = makeSandwich("turkey", "pepperjack", "wheat");`
`Console.log(korySandwich);`


constructRecipeHTML.js
// input: name, description
//work: construct an html string that we can hand off to document.write
//output: an html article with placeholder pic, name, and description

// pseudocode
// input: name - 'fluffy', description - 'softest cat ever'

// output:
`<article> + ` 
     `<img src=pasta.jpeg>`
     `<h3> +`
	 
 
     `<p>`
                Cook Time: 45 min
	`<p>`
`</article>`

Wrapper Code:

// prompt user if they want to add a recipe
`Var wantstoAddRecipe = prompt(Do you want to add cat?")`
// if so, ask for name and description
`If (wantstoaddcat === 'yes') {`
`Var catName = prompt("what is the cat's name?")`
`Var catDescription = prompt("What is the cat's description");`

// give name and description to the constructRecipeHTML function to let it do its thing

`Var newCatHTML = constructCatHTML(catName, catDescription);`


`// hand the resulting HTML off to document.write`
`Document.write(newCatHTML);`
`}'







[Home](README.md)