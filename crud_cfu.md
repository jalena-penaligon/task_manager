Define CRUD.
Create, Read, Update, Delete. We must be able to write programs that have a controlled that can create databases, read their contents, update their contents and delete data when necessary.


Why do we use set method_override: true?
It allows us to access _method from within the HTML form

Explain the difference between value and name in this line: <input type='text' name='task[title]' value="<%= @task.title %>"/>.
Name is referencing the task_params hash, and value is referencing the instance variable title of a task object.

What are params? Where do they come from?
Params is a hash with title and description as keys. They come from the user input on new.erb.

Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
The first route simply renders the view, while the second route creates/updates it within the SQLite3 database.
