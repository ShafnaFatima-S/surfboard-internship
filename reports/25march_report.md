# Internship Summary

## Day-16 (25/03/25)

### <ins> Key learnings of the day:</ins>

Today I wrote a service for checking whether the password entered by the user and the stored password is same or different. When creating the password I hashed it and then stored it in the database. Now to check whether the password entered by the user and the stored password is same I need to compare them. To compare the password and the hashed password I used compare() method.

First using the findOne() method I found all the details of the user by using the username. From that I took the hashed password and then stored it separately. Now from the user I got the password. To compare these two passwords I used the brcypt compare() method. The compare() method returns true or false value. If the passwords match it returns true value. If the passwords does not match it return false value.

Then I created another service to fetch all the user details. I used the find method to get all the user details by using a condition where the delete column value must be false. By doing this the all the user details will be displayed but the deleted user details will not be displayed. Later I created another service for updating the user details.

For updating the user details I wrote a validation. If the user tries to change the username and if the username is something else other than a string then it will throw an error message that the username should only be a string. If the password that the user tries to change and the password is of some other type than string then it will throw an error that the password should be of the type string.

Then using the findOne() method I found all the user details by using the particular id from the database. Later I took the details entered by the user and selected the new password entered. I kept 10 salt rounds and hashed the new password by using the bcrypt hash() method. The bcrypt hash() method takes two arguments, one for the new password and another for salt rounds. Later I used the spread operator to merge all the details together and stored it in a variable. Then by using the update() method I updated the password in the database.

I am currently writing another service for generating jwt tokens. The user will start the authentication by giving the username and the password. After completing the authentication a jwt token will be generated. JWT stands for JSON Web Tokens. The JSON web tokens provide a way to securely authenticate, validate and ensures the safe communication between the user and the server. The json web tokens prevents any unauthorized user to access the details.

First the user sends the login details to the server. If the details entered by the user and the details in the database matches the server will create a json web token which contains the user details along with a secret key. The json web token consists of three parts separated by dot. The three parts are the header, payload and signature. The header contains the details like what algorithm is used and what type is used. The payload contains the details of the user, the data to be transferred. The signature is generated using the header, payload and a secret code.

I took the user details from the database using the findOne() method by using the username. Then I compared the password entered by the user and the password that I took from the database using the bcrypt compare method. If the values match the jwt token should generate. If the values does not match then an error message will be displayed.
