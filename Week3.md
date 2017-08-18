### Javascript Course Assessment
 
## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React was created to be simple, so that even people with minimal code experience could use it and create Single Page Applications (SPAs)
- React is a modern, efficient answer to complex UI applications
- React is a full stack framework for modern web applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer
 
 
 //Googled Answer
 
 
#### 3. Write a simple component that simply prints "I am a dumb component" to the screen. Be sure to include all necessary imports, expots, etc...


#### 4. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?
 
 
 //Your Answer
 
 
 //Googled Answer
 
 
#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    import React, { Component } from 'react';

    class Recipes {
      constructor(props){
        super(props)
        this.state = {
          recipes: 
            {name: 'Meatballs'},
            {name: 'Mac & Cheese'}
      
        }
      }

      render() {
    
        return (
    
          let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{recipe.name}</li>
            )
          })
    
          <ul>
            {recipes}
          </ul>
        );
      }
    }

    export default Recipes;

#### 6. Name three input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 
 
 //Googled Answer
 
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 //Your Answer
 
 
 //Googled Answer
 
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 
 
 #### 9. Name three benefits of testing and TDD:
 
 
 //Your Answer
 
 
 //Googled Answer
 
   
#### 10. List two helpful testing matchers and two helpful enzyme simulators that we can use when writing our tests:
 
 
 //Your Answer
 
 
 //Googled Answer
