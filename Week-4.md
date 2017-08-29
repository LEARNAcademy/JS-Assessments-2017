### Javascript Course Assessment
 
## Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. SQL stands for Structured Query Language. In your own words (no need to write a googled answer), what role does SQL play in a full-stack web application? How does this relate to MVC organization? 


 
#### 2. Here is a basic SQL query. What are the various parts of this statement doing? (Comment the code to explain each piece)
 
     SELECT
      name,
      breed,
      vaccinations,
      age * 15 AS equivalent_human_age,
    FROM
      mydogs
    WHERE
      equivalent_human_age > 20
    ORDER BY
      equivalent_human_age DESC
      
 
 
#### 3. What is a foreign key? 

// Your Answer


// Googled Answer


#### 4. What is this Sequelize code doing? Comment the code to explain each peice.

    ComicBook
      .all({limit: 2})
      .then(function(comics){
      let mapped = comics.map(function(cb){
         return cb.get()
      })
      console.log(mapped)
    })
 
 
 //Your Answer
 
 
 //Googled Answer
 
 
#### 5. Try to explain the role of an ORM in a full-stack application. Include at least two benefits of implementing an ORM.

//Your Answer
 
 
 //Googled Answer

#### 6. Write a command to alter the TABLE water_monsters in the monster DATABASE to name it "sea_monsters" instead.(assume we are using a postgres databse)
 
 //Your Answer
 
 
 //Googled Answer
 
 
 #### 7. What does CRUD stand for? And what do we use CRUD actions for?
 
 //Your Answer
 
 
 //Googled Answer
 
 
 #### 8. When working with Sequelize, how do we make changes on a table or database level? Give a code example along with your answer.
 
 
 #### 9. During the review we came across the idea of primitives types in Javascript but didn't really get to go into detail about them, other than the fact that they sometimes behave differently than objects and arrays. Do 5 min of research about primitives and record your findings here:

 //Googled Answer
 
   
#### 10. Friday's lesson was difficult because Sequelize updated its syntax. What did you think about this problem, and how might you deal with breaking updates like this in the future?
 
 
 //Your Answer
 
 
 //Googled Answer
