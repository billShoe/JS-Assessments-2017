### Javascript Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. How do you link a css file to your html page?

 //Your Answer

 <link type="stylesheet" href=" cssfile goes here ">

 #### 2. What is a css class? How do you use declare one in html? How do you use it in css?

 //Your Answer
css classes are identifiers for your HTML to assign styes to a div. add class="classname" in your div declaration. in your css file, use .class to assign styles to your class


#### 3. The class "heading-box" exists in our html file - write the css code that would:
1) align this box to the center of its container:
2) give it a black border that is 5px wide,
3) make its text appear in the center of the box
  {
    margin: auto;
    width: 80%
    border: 5px;
    border-color: black;
    text-align: center;
  }



#### 4. What is Bootstrap? Explain a few reasons that you might choose to use it in a project?


 //Your Answer
 Bootstrap is a library of styles and scripts that is preconstructed for you, so by merely changing the classes of your containers you can easily change the layout and appearance of your site


#### 5. Name 4 semantic html tags.
header, footer, body, nav


#### 6. What is block scope that became available in ES6? Include how it differs from local and global scope, and what variables are block scoped.
Block scope allows certain variables to be restricted into where they are declared, such as in the parameters of for loops, and not just functions. Unlike local or global scopes, the block scope prevents javascript from using a variable

 #### 7. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

 //Your Answer
 Front end development helps create the interface that users see, as well as handling any information that the user may need to see displayed. The frontend receives data from the back end and makes it available to the user.

 #### 8. Choose one of the new ES6 concepts we learned about this week (namely: block scope, classes, and string interpolation) and write example code that demonstrates the concept, with comments to explain what is going on.

//This snippet demonstrates string interpolation and block scope
// number is scoped inside the loop declaration and will not be defined outside of it
for (let iter = 0 ; iter > 0 ; iter++) {
    console.log('iter');                    // "0"
}
console.log(iter)                           // undefined


 #### 9. What is the difference between a div and a span?
 //Your Answer
 A div is an individual container, while a span is inline, meaning it can be used for text without breaking the text layout


#### 10. How would you explain the idea of "inheritance" in object oriented programming?
inheritance allows a child object to access values created by the parent object. This allows the programmer to create several different objects with similar values without having to rewrite the same values over and over.
