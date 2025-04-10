# Internship Summary

## Day-26 (09/04/25)

### <ins> Key learnings of the day:</ins>

Today I designed a page for my note app for creating notes with title and description. I did not add any functions for it but I created an empty array and made all the routing to insert the details that I type in the note app inside the array that I created. First I got all the values from the form using form group and stored it in a variable. Then I inserted the values inside the array using push() method.

After that I tried to make the inputs that I have given display in another component, but I was unable to do it. I tried googling for finding a solution but I could not understand how it works. So I created another array in the other component and then gave values inside it . Then by using the ngFor method I was able to display the content inside the array in a div.

Then we had a session where we discussed about errors and exceptions. Errors are the problems that are caused by the developer, it might be a syntax error or semantic error. An error can be fixed but an exception should be handled. Compile time happens before the program runs where it checks for the syntax errors and semantics. The runtime error happens when the program is running. For example if we try to divide a number by 0 it will not throw any error during compilation. But it throws error during run time. There are many types of exceptions like zeroDivisionError, valueError, typeError and many more.

The zeroDivisionError is caused when we try to divide a number by zero. The valueError is caused when we declare a variable of integer type with a string value. The typeError is caused when we try to add a value of integer type with a value of string type.
