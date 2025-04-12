# Internship Summary

## Day-28 (11/04/25)

### <ins> Key learnings of the day:</ins>

Today I tried many ways to solve the cors error. After clearing the cors error I was able to send the login details to the backend authentication app through api call. Now I had to get the response from the backend and if the response is true a jwt token will be generated. Now I have to get that jwt token and call the notes function using api with the header. The header will contain the jwt token. If the response is false then an error message will be displayed and it will not allow the user to log in.

If the true response is returned all the notes created by the user will be displayed in the front end of the note app. The jwt token will be stored in an array temporarily because I have to use dexie database for storing the details. For now I am using the array for helping me get the values easily.

After sending the api request while logging in, I returned a status message from backend. If the request is true it will send success message if not it will send error message. I took the status message and gave it inside the if condition. If the status is error it will not let the user log into the page . If the status message is success then the user should be able to navigate to the all notes page.Now I am trying to store it in a array so that I can send the notes created by the specific user can be sent to the front end of the note app.
