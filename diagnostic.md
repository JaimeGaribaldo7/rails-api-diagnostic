# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
A backend is used to communicate with a database to send and retrieve information
for the front end.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller takes information from the SERVER to manipulate the Model.
```

Which layer in the MVC pattern communicates with the model?

```bash
The CONTROLLER is the one that communicates with the model, it relays the
information it recieved from the server.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
It is not as important for us to use the views of the MVC pattern because we are
focusing on learning how the backend communicates/works with a database.
```

What does C.R.U.D stand for?

```bash
C.R.U.D stands for
Create
Read
Update
Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The CONTROLLER tells the MODEL what action it needs to happen.
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Five standard actions are:
1. Index
2. Show
3. Create
4. Update
5. Destroy
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
The Client will tell the server that it wants to make a GET request For a person
with an id of 1, Then the server will talk to the controller and tell it that it
needs person with id of 1 to be shown. At this point the controller will check
If it has a Command For showing person with id 1 and Then that action is fired.
Then the model communicates with the database and sends that person with id of 1
back through the controller to the server where it sents it back to the client
where the user can see person with id 1.
```

What is the command to generate a new rails-api app?

```bash
The command is rails new.
```

What is the command to start an instance of a rails server?

```bash
Then command for creating an instance of a rails server is
NameOfNewServer.new
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
To drop, you use rails generate migration
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
