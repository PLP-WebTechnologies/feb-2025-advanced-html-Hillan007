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




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Page</title>
      <!-- Inline CSS -->
      <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        /* Header Styles */
        header {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-bottom: 1rem;
        }

        /* Section Styles */
        section {
            margin: 20px auto;
            padding: 15px;
            max-width: 800px;
            background: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #007bff;
            border-bottom: 2px solid #ddd;
            padding-bottom: 5px;
        }

        /* Ordered List */
        ol {
            padding-left: 20px;
        }

        ol li {
            margin: 5px 0;
        }

        /* Image */
        img {
            display: block;
            margin: 0 auto;
            border-radius: 8px;
            border: 1px solid #ddd;
        }

        /* Table Styles */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        table th, table td {
            border: 1px solid #ddd;
            text-align: left;
            padding: 8px;
        }

        table th {
            background-color: #007bff;
            color: white;
        }

        /* Form Styles */
        form {
            margin-top: 15px;
        }

        label {
            display: inline-block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input, select, button {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        input:focus, select:focus, button:focus {
            border-color: #007bff;
            outline: none;
            box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
        }

        button {
            background-color: #007bff;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #007bff;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Website Page Today</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I"> <!-- Roman numeral list -->
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
        </ol>
    </section>

    <!-- External Image -->
    <section>
        <h2> Image</h2>
        <img src="https://www.pexels.com/photo/haus-auf-den-faroern-13008672/" alt="Sample Image from Pexels" width="400">
        <!-- Replace the src URL with the actual link to the image on Pexels -->
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
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
                    <td>John Ndungu'u</td>
                    <td>123 Elm St</td>
                    <td>+254757123456</td>
                    <td>johnndung'u@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Sanare</td>
                    <td>456 Oak St</td>
                    <td>+254789894567</td>
                    <td>janesanare@gmail.com</td>
                </tr>
                <tr>
                    <td>Emily Borire</td>
                    <td>789 Pine St</td>
                    <td>+25476767508923</td>
                    <td>emilyborire@gmail.com</td>
                </tr>
                <tr>
                    <td>Michael kamau</td>
                    <td>101 Maple St</td>
                    <td>+254789101111</td>
                    <td>michaelkamau@gmail.com</td>
                </tr>
                <tr>
                    <td>Sarah Wilson</td>
                    <td>202 Birch St</td>
                    <td>+1556677889</td>
                    <td>sarah.wilson@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post"> <!-- Replace action="#" with the desired backend endpoint -->
            <!-- Name Field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a strong password" required>
            <br><br>

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">--Select your country--</option>
                <option value="usa">USA</option>
                <option value="kenya">Kenya</option>
                <option value="japan">Japan</option>
            </select>
            <br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
            <br><br>

            <!-- Checkboxes -->
            <label>Hobbies:</label>
            <input type="checkbox" id="reading" name="hobbies" value="reading">
            <label for="reading">Reading</label>
            <input type="checkbox" id="traveling" name="hobbies" value="traveling">
            <label for="traveling">Traveling</label>
            <input type="checkbox" id="sports" name="hobbies" value="sports">
            <label for="sports">Sports</label>
            <br><br>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Champ Industries. All rights reserved.</p>
    </footer>
</body>
</html>

