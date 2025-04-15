# Internship Summary
## Day-29 (14/04/25)
### <ins> Key learnings of the day:</ins>
Today we did not have any other sessions. I was developing my note app using the angular framework. I displayed all the notes and then I created a note and then displayed it again in all notes. Here I had an issue in displaying all the notes. When I tried to display all the notes every notes stored in the database was displayed and not the particular users notes. To solve this problem I took the users id to get all the notes based on the user id.

Then later on I created another button to display the deleted notes in last 30 days. I have already created a service for getting the last 30 days deleted notes by the user. After that I called that function using axios api call. I gave the token in the header of the api call and requested backend for the specific data. After the response is generated it will be displayed on the ui.

I then created another component for getting password for locking the notes. I designed the ui for the locking page. I have given a div in that page. Inside the div I have created a form with a label password and input box. I have also given a button name create to perform click operation. 

For my all notes component I temporarily stored the token inside an array in the all note component. Later I wanted to use the token in other component but I could not export it so I declared that array inside the app component and then imported that array inside the all note component and many other components that needed the token.
