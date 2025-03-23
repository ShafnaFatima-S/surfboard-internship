# Internship Summary

## Day-13 (20/03/25)

### <ins> Key learnings of the day:</ins>

Today we had a session where we learned about address. First we recalled what functions and classes are. A function has a name and list of parameters, it has a body where the code to be executed is written. A class is a collection of properties and methods. properties are the variables and methods are the functions. Addresses are used to referencing.

When you try to assign a value stored in a variable to another variable you are just assigning the same address to the other variable. When you assign a value to a variable a as 10 and then you are assigning a value to a variable b as a then both the variables a and b have the same value because they share the same address. Now if you try changing the value of variable a as 20 and now you try to access both the variables a and b, the value of a will be 20 and the value of b will be 10. This is because the variable a has changed to a new address and the variable b is still on the old address.

When you assign a variable a with a value 10 and then assign the variable b as a , the value of both a and b will be 10 as they both share the same address. Now if you change the value of a as 20 and then assign the value of b as a , now both value of a and b will be 20 as they both changed the address and share another address together. When you assign a value as an array of [1,2,3] to a variable a and then you assign the value of variable a to another variable b.Now both the variable a and b have the same value. Now if I change the value of a as [1,2,3,4] and assign the variable a to variable b, both the variables have the same value [1,2,3,4].

The spread operator allows you to spread or expand the elements of an array or object. The spread operator can be used for copying or combining data.When using a function we can give values while calling the function. When you give a value in the parameter while calling a function it is known as pass by value. When you give a variable in the parameter while calling a function it is known as pass by reference.

I made crud operations on the note app. After creating it and storing the data in the database I am trying to do other operations as well. I got the data of all the notes saved in the database. Then using id as param I got the notes of a particular id. I updated a value using the id as the param and displayed the updated notes. I also did delete function where the data is not actually deleted but the user will not know that the deleted data still exists. Then I wrote another function for retrieving the deleted data in the last 30 days. I had to use the between keyword in the where clause to get that range of data.

I created another project for the authentication purpose and I am going to work on it soon. JWT stand for JSON Web Tokens. The jwt is used for securely transmitting the information between two parties as a json object. It is commonly used for web applications authentication purpose. JWT consists of three parts each separated by dot. The parts are the header, payload and signature.
