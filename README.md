# personal_site

#### Questions

1. Define CRUD.
  * CRUD stands for Create, Read, Update, Destroy and they are the four basic functions of persistant storage.

2. Why do we use set method_override: true?
  * It allows us to use _method in the HTML form.

3. Explain the difference between value and name in this line: <input type='text' name='task[title]' value="<%= @task.title %>"/>.
  * 

4. What are params? Where do they come from?
  * Params are values that we get from our HTML form. They come from our HTML form when it is submitted.

5. Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
  * We need two routes because the /edit and the /new make different requests to the SQL database. In terms of CRUD functionality, the /new route is "Creating" and the /edit route is "Updating".
