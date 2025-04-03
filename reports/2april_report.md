# Internship Summary

## Day-21 (02/04/25)

### <ins> Key learnings of the day:</ins>

Today we discussed about the async and await keywords in javascript. If we want our program functions to be executed in a different order we can make use of the callback functions. The callback function is a function that can be passed as an argument inside another function so that it can be executed after one function is executed. This can be used when we have a limited number of functions. But when we have many functions to work the same way we cannot use this.

To solve that problem we have .then() method. This also works the same way as the callback function. If we give a a function inside the .then() method it will be executed after a program gets executed. So here also the work is done after another work gets completed. But even with this it will be hard to manage many functions and the structure of the program will also be difficult to understand. To solve this we have async and await in javascript. The workflow of the async and await functions are similar to the previous ones but the complication of understanding the program will be reduced.

When using a function if we assign that function as an async function we can make it work one after the other. The async keyword returns a promise and the await keyword waits for the promise and resolve them. Comparing to the callback function and the .then() method the async function will make it more understandable for a programmer and also the we can use the async and await keywords for many number of functions.

I had to do some changes in my note app so I was doing them today. The login details should be used for all the services for verification. To do so I have added the user Id as a parameter for all the services. So that when a service is taken it first checks the login details. If the user is valid the function will be performed. If the user is not valid an error message will be thrown saying that the user id is invalid.

I also had a correction in listing all the notes. The locked notes should not be listed when the user tries to access all the notes. For that I had to give a condition in the service to list all notes so that the locked notes will not be displayed. I also did many other changes as well.

For locking the note I created another table so that I can store the passwords in a separate table. When the user tries to access the locked notes first it will check whether the user is a valid user or not. If the user is valid then it will check whether the given password and the password stored in the table are the same. If the passwords match the locked notes will be displayed. If the passwords does not match it will throw an error stating that the password is incorrect. If the user login is not valid it will throw an error stating that the user id is not valid.
