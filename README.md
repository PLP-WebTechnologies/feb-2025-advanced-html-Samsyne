# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



answer


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgentX </title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #aaa;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        form {
            margin-top: 30px;
        }
        form input, form label {
            display: block;
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <h1>Welcome to AgentX</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <h2>An online Agent vendor where you find your desire homes</h2>

    <p>we cover all locations </p>

  


    <h2> We are located at this locations</h2>
    <ol type="I">
        <li>Lagos</li>
        <li>Abeokuta</li>
        <li>Kano</li>
        <li>Abuja</li>
        
    </ol>

    <h2> Tenants find house easier here</h2>
    <img src=" https://images.pexels.com/photos/280221/pexels-photo-280221.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="Pexels Sample" width="600">

    <h2>Contact your desired location assistance care</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Yemisi Bello</td>
                <td>123 Maple St, NY</td>
                <td>+1 555-1234</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>John Smith</td>
                <td>456 Oak St, CA</td>
                <td>+1 555-5678</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Alice Johnson</td>
                <td>789 Pine St, TX</td>
                <td>+1 555-9012</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Bob Brown</td>
                <td>321 Cedar St, FL</td>
                <td>+1 555-3456</td>
                <td>bob@example.com</td>
            </tr>
            <tr>
                <td>Mary White</td>
                <td>654 Birch St, WA</td>
                <td>+1 555-7890</td>
                <td>mary@example.com</td>
            </tr>
        </tbody>
    </table>


    <p> New here? register below for our newsletters </p>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="mobile">Mobile:</label>
        <input type="tel" id="mobile" name="mobile" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>

        <input type="submit" value="Register">
    </form>

    <p> Already a user  <a href="login">login</a></p>

</body>
</html>
