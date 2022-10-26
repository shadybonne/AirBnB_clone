![65f4a1dd9c51265f49d0](https://user-images.githubusercontent.com/70880808/197966297-769f3015-81dd-42ef-a849-b8dd29712655.png)
AirBnB clone - The console

Description

The AirbnB clone is a web application project that consists of four(4) different parts:

A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
A website (the front-end) that shows the final product to everybody: static and dynamic
A database or files that store data (data = objects)
An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)

The Console

This part of the project is to create a console (a command interpreter) that uses file storage system to manipulate data The goal of the console part fo the project is to:

create a data model
manage (create, update, destroy, etc) objects via a console / command interpreter
store and persist objects to a file (JSON file)
The first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”. This means: from your console code (the command interpreter itself) and from the front-end and RestAPI you will build later, you won’t have to pay attention (take care) of how your objects are stored.

This abstraction will also allow you to change the type of storage easily without updating all of your codebase.

The console will be a tool to validate this storage engine.
![815046647d23428a14ca](https://user-images.githubusercontent.com/70880808/197966097-da7e89e2-6f45-41fa-8f05-d24d0d518481.png)
