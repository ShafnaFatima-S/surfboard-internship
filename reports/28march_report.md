# Internship Summary

## Day-18 (28/03/25)

### <ins> Key learnings of the day:</ins>

Today I tried solving the issues when I used the environment variables. I installed the dotenv by using the command " npm i dotenv ". Then I imported the dotenv inside the file. I gave all the needed details to the file. To access the environment variables we should use process.env. I have given al the details like the host, type, username, password, database, entities, synchronize, secret passkey and other details as well. To load the environment variable I tried using the source. env command but it threw error. I tried loading it in all way possible and then restarted to the system to load the environment variables.

I wrote another service to check the login details. First I took the generated jwt token given in the header. To verify whether the jwt token is the same as the original token we use the verify() method. The verify() method takes two arguments. The first argument is the jwt token and the second argument is the secret key. The secret key helps to check whether the jwt was changed along the way or not. If the secret key matches then the token was not changed. If the secret key does not match then it means the jwt token was changed while transferring.

To find the issued date and the expiry date I used the new Date() method to convert it into date. I generated date will be in milliseconds to convert that into seconds I multiplied that by 1000. I converted the date for both the jwt token issued date and the jwt token expiry date. Then I used the " npm install date-fns --save " command to apply certain functions on the date. I used the format() method to format the date and time of the jwt token issued date and jwt token expiry date.

The format() method takes two arguments, the first argument is the date and the second argument is the format in which we want to display the date and time. I have given the date and time in the format " yyyy-MM-dd HH-mm-ss ". I have taken this for both the issued date and time as well as for the expiry date and time. Additionally I have also taken it for the current date and time with the same format.

To check whether the token has passed the expiry date and time I wrote a condition to check using the if statement. If the expiry date and time is less than the current date and time it means the token has expired. So it will throw error that the jwt token has been expired. If the expiry date and time is greater than the current date and time it means the jwt token is still valid. So it gives a message that the jwt token is still valid. I am also trying to complete my note app design using figma, which I am still in the process of learning.
