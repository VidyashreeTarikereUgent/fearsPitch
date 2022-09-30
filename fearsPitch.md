# Data storage in solid data vaults.

### Vidyashree Tarikere, Ruben Taelman

For a long time now, companies with centralized user data are in charge of both the data and the development of software applications. 
RT: "a long time now" Hasn't been for that long though :-)

Only if the data is separated from the software applications, meaning making data independent of application, will open ways for innovative and creative software applications. 
RT: Start with the problem, and then say what the solution is. For example: "In order to stimulate innovative and creative, software applications, data and application need to be decoupled..."

The problem here is to manage data when they are decentralized. That is, where to store this huge amount of data that is generated every millisecond and how to manage this data synchronously. 
RT: "every millisecond" maybe this is not an aspect we want to focus on, since this comes in the area of stream processing.
RT: What do you mean by "manage this data synchronously"?

The answer to these questions is Sir Tim Berner-Lee’s **Solid Project**. In this project, every person will have one or more data vaults, where they can store and manage their own data. 
RT: "The answer" -> "One answer" (in research, we're never certain)
RT: "where they can store and manage their own data", but more importantly, people are in full control of their data, and where/how it is stored!

I have developed a software application, To-Do Solid application, where data and application are independent of each other. 
RT: Maybe start first by saying why you have done this.

In this application, I have inspected different ways one can store data in their data vaults. 

For example, Alice may want to store her todo's in her vault in various ways.

The method I considered implementing is to put these data in different files and folders chosen by the user. 
RT: Put this more in a research context, for example: "My goal is to investigate how to enable users to define how their data must be stored, and how applications can take this into account when writing data"

This method allows user to organise data in their data vaults in a structured way. 
RT: This sentence can probably go.

<!---  If person A wants to store each todo item in separate files or if she/he wants to store all the todo items in one single file or she/he wants to store todo items in multiple files, it is done by **sparql-update queries**. 

For case 1, whenever a new todo is created, first, a new turtle file is generated and inside which the created todo is inserted. For case 2, all the todos created by the user just go to a fixed place inside the pod. 

For case 3, the user is asked if he wants to put newly created todos inside an existing file or if she/he wants to create a new file to store the todos. Thus, this satisfies all the possible needs a user might have when he wants to manage the data on solid pods. -->

As a researcher, it is always useful to determine what is the optimal way of storing data,
RT: Note that "optimal" may not exist. Different use cases may have a different "optimal" solution.

especially in a decentralized environment, such that it will provide maximum results when reading and searching these data. 
RT: "maximum results", do you mean "complete" results?

Future work will investigate the ways in which a user can store data following certain timestamp, logical relevance, geographic location and priority-wise. 
RT: Unclear what this means. But perhaps this is going into too much detail for the audience of FEARS?


