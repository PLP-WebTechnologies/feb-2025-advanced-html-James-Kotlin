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

**Answers**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Roman Numeral List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>

    <!-- External Image -->
    <h2>External Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/123456/example.jpg" alt="Beautiful Landscape" width="500">

    <!-- Table of Contacts -->
    <h2>Contacts</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>long last john</td>
            <td>123 Main Street</td>
            <td>+123456789</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane head</td>
            <td>456 Elm Street</td>
            <td>+987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Paul kenya</td>
            <td>789 Oak Avenue</td>
            <td>+192837465</td>
            <td>paul@example.com</td>
        </tr>
        <tr>
            <td>Lisa</td>
            <td>321 </td>
            <td>+102938475</td>
            <td>lirsa@example.com</td>
        </tr>
        <tr>
            <td>Michael wetu</td>
            <td>654 Mare Lane</td>
            <td>+564738291</td>
            <td>michael@example.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h2>Registration Form</h2>

    <!-- Form starts here -->
    <form>
        <!-- Name field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

        <!-- Email field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required><br><br>

        <!-- Date field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown field -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">--Select your country--</option>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
            <option value="others">Others</option>
        </select><br><br>

        <!-- Radio buttons -->
        <fieldset>
            <legend>Gender:</legend>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
        </fieldset><br>

        <!-- Checkboxes -->
        <fieldset>
            <legend>Hobbies (Choose at least one):</legend>
            <input type="checkbox" id="reading" name="hobbies" value="reading" required>
            <label for="reading">Reading</label><br>
            <input type="checkbox" id="traveling" name="hobbies" value="traveling">
            <label for="traveling">Traveling</label><br>
            <input type="checkbox" id="sports" name="hobbies" value="sports">
            <label for="sports">Sports</label>
        </fieldset><br>

        <!-- Submit button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>
</body>
</html>


Happy Coding! 💻✨
