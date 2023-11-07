# 30 Days of HTML - Day 8: Forms

## Introduction

Welcome to Day 8 of "30 Days of HTML." Today, we'll explore forms, an essential part of web development that allows users to input data, submit information, and interact with web applications.

## Creating a Basic Form

In HTML, you create forms using the `<form>` element. Here's a simple example of a form that includes input fields for a name and email address:

```html
<form class="form">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <input type="submit" value="Submit">
</form>
```

## Working with form data

```html
<script>
    document.querySelector('.form').addEventListener('submit', function(e) {
        e.preventDefault();
        var name = document.getElementById('name').value;
        var email = document.getElementById('email').value;
        alert('Name: ' + name + '\nEmail: ' + email);
    });
</script>
```

This JavaScript code sends and alert when the form is submited



