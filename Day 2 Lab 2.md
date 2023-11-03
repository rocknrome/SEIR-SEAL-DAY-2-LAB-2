



## Loop It!

Now, let's get started with some reps

1. Create a loop that will print "hi" 15 times.

   `for (i=1; i<=15; i++) {`

   `console.log("hi");`

   `}`

2. Create a loop that will print "YEP!" 30 times.

   `for (i=1; i<=30; i++) {`

   `console.log(i + " YEP!");`

   `}`

## Booleans & Loops - Part 1

1. Create a variable called `some_num` and assign a random number.

2. Create a loop that will run ten times (`while` or `for` loop, your choice!)

3. Inside the loop, print "that's a small number" if `some_num` is less than 10.

4. Create another loop that will print "that's a big number" if the value of `sum_num` is greater than 20.

5. Take these two loops and adjust them so that they can be used together. Write some code to deal with what happens if `some_num` is a value in between between 10 - 20.

   `const some_num = 7;` 

   `if (some_num < 10) {`
       `console.log("That's a small number");`
   `} else if (some_num > 20) {`
       `console.log("That's a big number");`
   `} else {`
       `console.log("That's a number between 10 and 20");`
   `}`

   **BONUS**

   - Inside the loop after your if if/else statements, update your `some_num` variable to a new random number

   - How can you generate a random number in JS? Google it!

     `let some_num = Math.floor(Math.random() * 30); // Generating a random number between 0 and 29`

     `if (some_num < 10) {`
       `console.log("That's a small number");`
     `} else if (some_num > 20) {`
       `console.log("That's a big number");`
     `} else {`
       `console.log("That's a number between 10 and 20");`
     `}`

     `console.log(Random number: ${some_num});`

## Intro to Pseudocoding

You'll be learning more about [pseudo-coding](https://en.wikipedia.org/wiki/Pseudocode) next week, but as a quick introduction: Pseudo-coding is writing out what you think the question is asking or structuring your answer in **human language** rather than *computer language*. Before you create a variable or write out a loop, write down what you're thinking (like you're explaining it to another person) before you solve the problem.

Let's take some time to practice a bit of pseudo-coding! Read the problems below and try to write out some // commented out pseudo-code for them without writing any actual code. Try to see past any convoluted language, redundancy, or complexity to get to the core of the problem. Remember, we're not trying to solve the problem, but write out how to solve the problem.

<details style="box-sizing: border-box; display: block; margin-top: 0px; margin-bottom: 16px; color: rgb(201, 209, 217); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; background-color: rgb(13, 17, 23); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><summary style="box-sizing: border-box; display: list-item; cursor: pointer;"><g-emoji class="g-emoji" alias="earth_americas" fallback-src="https://assets.git.generalassemb.ly/images/icons/emoji/unicode/1f30e.png" style="box-sizing: border-box; font-family: &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 1em; font-weight: 400; line-height: 1; vertical-align: -0.075em; font-style: normal !important;">🌎</g-emoji><span>&nbsp;</span>EQUATOR DRIVE</summary></details>

<details style="box-sizing: border-box; display: block; margin-top: 0px; margin-bottom: 16px; color: rgb(201, 209, 217); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; background-color: rgb(13, 17, 23); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><summary style="box-sizing: border-box; display: list-item; cursor: pointer;"><g-emoji class="g-emoji" alias="bread" fallback-src="https://assets.git.generalassemb.ly/images/icons/emoji/unicode/1f35e.png" style="box-sizing: border-box; font-family: &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 1em; font-weight: 400; line-height: 1; vertical-align: -0.075em; font-style: normal !important;">🍞</g-emoji><span>&nbsp;</span>Hungry for More? SANDWICH</summary></details>

<details style="box-sizing: border-box; display: block; margin-top: 0px; margin-bottom: 16px; color: rgb(201, 209, 217); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; background-color: rgb(13, 17, 23); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><summary style="box-sizing: border-box; display: list-item; cursor: pointer;"><g-emoji class="g-emoji" alias="sunny" fallback-src="https://assets.git.generalassemb.ly/images/icons/emoji/unicode/2600.png" style="box-sizing: border-box; font-family: &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 1em; font-weight: 400; line-height: 1; vertical-align: -0.075em; font-style: normal !important;">☀️</g-emoji><span>&nbsp;</span>Hungry for even More? SARCOPHAGUS</summary></details>



**EQUATOR DRIVE:**

1. We need to declare a const variable for the Earth's circumference.
2. Declare a variable for the car's fuel efficiency. This will help to calculate the number of gallons of gas needed to complete the trip. 
3. Declare variable for the cost of gas. 
4. Calculate the number of gallons of gas needed to complete the trip (circumference / car's fuel efficiency).
5. Multiply that number of gallons to the cost per gallon. 
6. Print the result. 



**SANDWICH:**   Peanut butter and jelly

1. Take a piece of bread / declare the "bread" variable.
2. Declare the PB&J variable.
3. Add "bread" and PB&J variables.
4. Print the result.



**SARCOPHAGUS:**

1. Declare const variable of sun distance.
2. Convert it to miles.
3. Calculate the speed needed to cover that distance in one second.
4. Print the result. 

Now try to pseudo-code the next Booleans & Loops section **before** you write any computer code.

## Booleans & Loops - Part 2

1. Create a variable called `fave_day` and assign it to your favorite day of the week.

2. Create a loop that uses the variable `fave_day` that you created. Make a loop that will print `I like the weekend` if `fave_day` equals Saturday or Sunday. The loop should print `Give me a good 'ol weekday` if `fave_day` is equal to Monday, Tuesday, Wednesday, Thursday, or Friday.

3. Think about outliers: What if I had entered "September" in `fave_day`? What would happen? Add something to your code to handle that situation.

   `const fave_day = 'Saturday' //reserved the variable for future usage`
   `//for the tasks like this, I would use SWITCH/CASE approach`
   `switch (fave_day) {`
     `case "Saturday":`
     `case "Sunday":`
       `console.log("I like the weekend")`
       `break`

     `case "Monday":`
     `case "Tuesday":`
     `case "Wednesday":`
     `case "Thursday":`
     `case "Friday":`
       `console.log("Give me a good 'ol weekday")`
       `break`

     `default:`
       `console.log("I can't seem to understand your choice.. Please try again")`

