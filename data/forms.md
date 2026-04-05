# Forms Handling in PHP

## What is Forms Handling?
Forms handling in PHP is used to collect user input from HTML forms and process it on the server.

## Key Points
- PHP can collect form data using GET or POST methods
- $_GET and $_POST are superglobals used to access form data
- Input validation is important for security

## Example
```php
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = $_POST["name"];
    echo "Hello, " . $name;
}
?>

<form method="post">
    Name: <input type="text" name="name">
    <input type="submit">
</form>
##Practice

Create a PHP form that takes a user's age and displays it after submission.
