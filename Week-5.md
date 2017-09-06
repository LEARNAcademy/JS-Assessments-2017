### Javascript Course Assessment

## Week 5 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Comment this code from an express server to explain what each part is doing.

app.get('/', function (request, response) {
 response.send('Hello World!');
});

app.listen(3000, function () {
 console.log('Example app listening on port 3000!');
});



#### 2. We have now used both EJS and React to render views with dynamic javascript content (If you want a refresher, take a look at the "Full Stack Express" day). Compare and contrast the two approaches, include a pro and con of each. Which one did you prefer?

// Your answer


// Googled answer


#### 3. Sequelize and Express are the Model and Controller portions of our MVC structure. How the two relate and pass information between each other is important to understand but can be hard to follow. Below are some generic events that happen when a browser requests a web page, but they are not in order. Put them in order and also specify whether the task is done by Sequelize or Express. The first step has been given to you as an example:

1. Server is set to "listen" for requests coming in on a port, or range of ports (Express)

----- organize from here down:

3. SQL responses are translated into a javascript object

4. If incoming requests recquire information from the database, the request is parsed into a SQL query

2. The content required for a view is sent back to the browser, along with any additional information required

5. Incoming requests are handled by the router

** Understanding this process will be important to building full stack apps, if you have any questions about this process, write them here and I will answer them with you in the future:


#### 4. We implement back end tests with Jest and Supertest, look back at the "Testing Express" day and do a few minutes of outside research to understand what this code is doing, and what it is testing. Add comments explaining your findings.

** Also comment any piece you don't understand with questions, and I will get back to you.


const request = require('supertest')
const app = require('./App.js')

describe('Test the root path', ()=>{
  it('Should respond to GET', () => {
    return request(app).get('/').then((response)=>{
      expect(response.statusCode).toBe(418)
    })
  })

  it('Should respond with a message of "Relax, and have a cup of tea", ()=>{
    return request(app).get('/').then((response)=>{
      expect(response.body.greeting).toBe('Relax, and have a cup of tea')
    })
  })
})


#### 5. What are cookies and sessions? Try to explain what they are, and any differences between them that you remember.

//Your Answer


 //Googled Answer

#### 6. Try to explain the process of how information from a user can be persisted to a database using a form, the "post" method, sequelize, and express.  Look back at the "Full Stack Express" day for a refresher.

 //Your Answer


 //Googled Answer


 #### 7. What is sequelize "seed" data for? Why can it be helpful as you develope a project?

 //Your Answer


 //Googled Answer


 #### 8. Red, Green, Refactor is the process for TDD - what does this mean to you right now, and what do you think it might look like to do this in a work environment?


 #### 9. This is an example express application on github: https://github.com/shapeshed/express_example. Take a few minutes to go to the address and look around in the files. List a few things here about the project - what do you notice that is different about their setup? What looks familiar from class? What sticks out to you or gives you questions?



#### 10.  Try to explain what an express router does in your own words. 

 //Your Answer


