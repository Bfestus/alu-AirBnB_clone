# alu-AirBnB_clone
![Alt Text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.dezeen.com%2F2014%2F07%2F16%2Fairbnb-rebrand-designstudio-logo-belo%2F&psig=AOvVaw1-Ad2G2Ddb9z6nX9h-dDnR&ust=1704885116782000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKjiwZKW0IMDFQAAAAAdAAAAABAX)

This repository is about Airbnb clone project at ALU

# Airbnb Clone Project Readme

This project is offered by ALU, from holberton school of software engineering, we will be working to the in whole term. the project is not supposed to be made at on sit, rather is step by step process untill the final project is found. the aim is to clone the real application called "AirBnB". the popular rental property website.
 

# Project Description 

Here, We'll be cloning the console part of the AirBnB clone Project.

We'll be writing a command interpreter to manage our AirBnb objects.

We'll need to 
- put in place a parent class (called BaseModel) to take care of the 
initialization, serialization and deserialization of your future instances 
- create a simple flow of serialization/deserialization: Instance < - >
Dictionary < - > json string < - > file
- create all clases used for AirBnB(User,  State, City, Place...) that
inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittest to validate all our classes and storage engine.

Our command interpreter would be able to:


    - Create a new object(ex: a new User or a new Place)


    - Retrieve an object from a file, a database etc...


    - Do operations on objects(count, compute stats, etc...)


    - Update attributes of an object


    - Destroy an object 


Writer: Festus Bigirimana
