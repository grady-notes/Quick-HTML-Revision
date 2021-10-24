# Form Tags

Form tags are also very useful as they make it possible for the website to collect information from the user in the form of input.
For example adding comments on a post, registering a new account on a website, loggin into an existing account on a website, adding a feedback, or posting a query & many other numerous examples.

The `<form>` tag is the entry point of the form & wraps all the input fields & controls them in a way that it enables the website to retrieve information from the user & send it to te server.

The `<input>` tag is used to instruct the browser to accept user input as text.
The `<select>` tag is used to instruct the browser to ask the user to select an option from a given list. The `<option>` tag is used to define multiple options inside the `<select>` tag.

An example of a form

```
<body>
  <form method="GET">
    <fieldset>
      <h3>Registration Form</h3>
      First Name - <input type="text" /><br />
      Last Name - <input type="text" /><br />
      Please choose a username - <input type="text" /><br />
      Please create a password - <input type="password" /><br />
      Please select your gender -
      <input type="radio" name="gender" value="male" />Male
      <input type="radio" name="gender" value="female" />Female <br />
      Please select your region -
      <select>
        <option>select one</option>
        <option>more options can be provided</option></select
      ><br />
      <input type="submit" value="Register" />
    </fieldset>
  </form>
</body>

```
