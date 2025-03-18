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
    <title>Task Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- Optional: Link an external stylesheet -->
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Task Page</h1>
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

