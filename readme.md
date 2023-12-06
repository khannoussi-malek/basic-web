# HTML Elements Documentation
## Useful links
- [HTML Input types](https://www.w3schools.com/html/html_form_input_types.asp)
- [HTML Input examples](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
## `<div>`

The `<div>` element is a generic container that is used to group other HTML elements together. It does not carry any specific meaning or purpose on its own and is primarily used for styling and layout purposes.

**Syntax:**
```html
<div>
  <!-- Content goes here -->
</div>    
```
##### Example:
```html
<div>
  <h1>Welcome to our website!</h1>
  <p>Here is some content...</p>
</div>
```
<div style="background-color:#abc; border-radius:1rem; padding:1rem;">
  <h1>Welcome to our website!</h1>
  <p>Here is some content...</p>
</div>



## `<form>`

The `<form>` element represents a section of an HTML document that contains interactive controls for submitting data to a server. It is used to create web forms, such as login forms, registration forms, and contact forms.

**Syntax:**
```html
<form action="/submit" method="post">
  <!-- Form controls go here -->
</form> 
```
##### Example:
```html
<form action="/login" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <button type="submit">Login</button>
</form>
```


## `<input>`

The `<input>` element is used to create various types of input controls within a form. It allows users to enter and submit data.

**Syntax:**
```html
<input type="text" name="input_name" id="input_id" value="default_value">
```
##### Example:
<ul>
<li>
<h5>text:</h5>

```html
<label for="username">Username</label>
<input type="text" name="username" id="username" placeholder="Enter your username" required>
```

</li>
<li>
<h5>password:</h5>

```html
<label for="password">Password</label>
<input type="password" name="password" id="password" placeholder="Enter your password" required>
```


</li>
<li>
<h5>Checkbox:</h5>

```html
  <p>Subscribe to :</p>
    <input type="checkbox" id="subscribe">
    <label for="subscribe">Newsletter</label>
    <br/>
    <input type="checkbox" id="youtube">
    <label for="youtube">Youtube</label>
    <br/>
    <input type="checkbox" id="somthing">
    <label for="somthing">Somthing</label>
    <br/>
```
</li>
<li>
<h5>Checkbox:</h5>

```html
  <p>Subscribe to :</p>
    <input type="checkbox" id="subscribe"/>
    <label for="subscribe">Newsletter</label>
    <br/>
    <input type="checkbox" id="youtube"/>
    <label for="youtube">Youtube</label>
    <br/>
    <input type="checkbox" id="somthing"/>
    <label for="somthing">Somthing</label>
    <br/>

```

</li>

<li>
    <h5>Radio:</h5>

  ```html
    <label>Gender:</label>
    <input type="radio" id="male" name="gender">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender">
    <label for="female">Female</label>
    <br/>
  ```

</li>
<li>
    <h5>Date</h5>


```html
    <label for="birthday">Birthday:</label>
    <input type="date" id="birthday" name="birthday">
```

</li>

<li>
    <h5>File</h5>

```html
    <label for="myfile">Select a file:</label>
    <input type="file" id="myfile" name="myfile">
```

</li>
</ul>