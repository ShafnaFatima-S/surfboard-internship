# Internship Summary

## Day-17 (27/03/25)

### <ins> Key learnings of the day:</ins>

Today I wrote another service for checking the login details. For that I wrote the service in get method. First I gave the json web tokens in the header section. For that I used the @Header decorator. In nestjs the header decorator is used to access the headers of an incoming request. I have sent the json web tokens inside the header which I retrieved using the checkLogIn function.

I took the entire data and stored it in a variable. Then I took the specific data called authorization and stored it separately in another variable. Now the stored value will have a bearer so we need to remove that so that we can check whether the json web token is still the same or not. To remove the bearer I used the replace() method so that I can replace the bearer with whitespaces.

Now that the bearer token is removed we still have whitespace to remove. So for that I am using the trim() method to remove any whitespaces. Then I used the jwt verify() method. The json web token's verify() method is used to check whether the jwt token is valid or not by checking the signature and the expiration time.

First I used the jwt decode() method. The decode() method simply decodes the jwt into three parts, header, payload and signature. The decode method does not verify the validity of the token. The decode() method takes the jwt token and splits them into header, payload and signature. You can extract the data from the payload but it does not check or validate the tokens.

So using the decode() method will not help me to verify the jwt token. So I used the verify method. The verify() method is used similar to decode() method. The verify() method decodes the jwt token into three parts, header, payload and signature but also checks for validation. It checks the signature and returns an error message if the signature does not match. The signature has the secret key. So the verify() method decodes the jwt token and then checks the secret key.

I also tried using the environment variable inside my nestjs project. The environment variables are the variables that are set outside the program inside an .env file. The environment variables helps us to keep the confidential data away from the program so that we can access them without actually accessing their values. The environment variables are stored in key value pair. So we can access them by using the key and not by actually calling their values.
