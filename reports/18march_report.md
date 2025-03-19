# Internship Summary
## Day-11 (18/03/25)
### <ins> Key learnings of the day:</ins>
Today I started working in nest.js, and tried to create a note app. There are key concepts in nest js like module, controller, service. Modules are a way to organize and structure the application. The @Module() decorator is used to define a module. Modularity allows us to organize our code, We can reuse the code easily. Whenever we are in the need to use that particular code , we can easily export it and then import it to the particular file and use it efficiently.

The controllers in nest js are responsible for handling incoming HTTP requests and provide response for that HTTP requests. Controllers use decorators to specify the route path, http method with create, get, put, delete. Services are used by the controllers to perform various operations like processing a data, querying a database. The crud operations are performed in the services. There are many other concepts in nest js , I am still in the process of learning it one by one.

I tried to create a note app in nest js using crud operations. I have listed out all the fields that I need in my note app and then using post method I called that function and made it work. I have also done validations on it. My note app has features like title, description, id, categories, image, pin, lock, archive. I created unique id for each notes using the jetit/Id.

The validations that I gave was like, if the data in title is not in the string format then throw error that the title should be in string. If the data in the description is not in the string format then throw error that the description should be in string. If the categories is not work or personal then throw error that the categories should be either work or personal and you can't enter something else.

I installed typeorm in my folder. To install typeorm I used " npm i @nestjs/typeorm ". Then I declared entities for typeorm. Entity is a collection of fields and associated database operations. It is used to map database tables and its fields with the entities and attributes. I created a new file and then imported Entity, PrimaryColumn, Column from typeorm. The PrimaryColumn is used to mention what fieldname is my primary key , as primary keys are unique. In my note app I have generated unique id for each notes so the id is my primary key. 

We can use PrimaryGeneratedColumn if you want the orm to generate its own unique id. In that case we don't have to generate id separately. The Column is used to mention all the other field names. I then imported this class inside the service. The crud operations in nest js seems very different from node js so I find it a bit difficult to catch on to it. But i'll definitely keep trying until I become good at it.

I am currently trying to get the notes by using a specific id . I am using get method for that. Then I am planning to get all the notes that are stored using the get method. Then by using the put method I am gonna update any specific note by using the unique id of that particular note. Then I am gonna try delete any specific note using the delete method by taking the unique id of that specific note.
