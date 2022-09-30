# Data storage in solid data vaults.

### Vidyashree Tarikere, Ruben Taelman

For a couple of years now, companies with centralized user data are in charge of both the data and the development of software applications. 

In order to stimulate innovative and creative software applications, data and applications need to be decoupled.

The problem here is to manage data when they are decentralized. That is, where to store this huge amount of data and how to do operations on them. 

One of the solutions is Sir Tim Berner-Lee’s **Solid Project**. In this project, every person will have one or more data vaults, called solid pods, where people are in control of their data, and where and how it is stored. 

<!--- I have developed a software application, To-Do Solid application, where data and application are independent of each other. --->

<!--- In this application, I have inspected different ways one can store data in their data vaults. ---> 

For example, Alice may want to store her todo's in her data vault in various ways. 

To help Alice store her todo's, I have developed a Todo application which stores todo's in different files and folders, following the choices made by Alice, in the data vault. 

My goal is to investigate how to enable users to define how their data must be stored, and how applications can take this into account when writing data.

<!--- This method allows user to organise data in their data vaults in a structured way. --->

<!---  If person A wants to store each todo item in separate files or if she/he wants to store all the todo items in one single file or she/he wants to store todo items in multiple files, it is done by **sparql-update queries**. 

For case 1, whenever a new todo is created, first, a new turtle file is generated and inside which the created todo is inserted. For case 2, all the todos created by the user just go to a fixed place inside the pod. 

For case 3, the user is asked if he wants to put newly created todos inside an existing file or if she/he wants to create a new file to store the todos. Thus, this satisfies all the possible needs a user might have when he wants to manage the data on solid pods. -->

As a researcher, it is always useful to determine in what ways data can be stored, especially in a decentralized environment, such that it will provide positive results when reading and searching these data. 

Future work will investigate the other possible ways in which a user can store data in their data vaults. 


