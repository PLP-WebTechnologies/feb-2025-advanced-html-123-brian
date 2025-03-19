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
    <title>Advanced HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>
    
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>
    
    <section>
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/example.jpg" alt="Example Image from Pexels" width="500">
    </section>
    
    <section>
        <h2>Contacts Table</h2>
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
                    <td>John Doe</td>
                    <td>123 Street, City</td>
                    <td>+1234567890</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Avenue, City</td>
                    <td>+9876543210</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Mike Brown</td>
                    <td>789 Boulevard, City</td>
                    <td>+1122334455</td>
                    <td>mikebrown@example.com</td>
                </tr>
                <tr>
                    <td>Alice Green</td>
                    <td>1011 Lane, City</td>
                    <td>+5566778899</td>
                    <td>alicegreen@example.com</td>
                </tr>
                <tr>
                    <td>Bob White</td>
                    <td>1213 Drive, City</td>
                    <td>+6677889900</td>
                    <td>bobwhite@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            
            <fieldset>
                <legend>Subscription Preferences</legend>
                <input type="radio" id="basic" name="subscription" value="basic" required>
                <label for="basic">Basic</label>
                <input type="radio" id="premium" name="subscription" value="premium">
                <label for="premium">Premium</label>
            </fieldset>
            
            <label>
                <input type="checkbox" name="terms" required>
                I agree to the terms and conditions
            </label>
            
            <button type="submit">Register</button>
        </form>
    </section>
    
    <section>
        <h2>Multimedia Elements</h2>
        <h3>Audio</h3>
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <h3>Video</h3>
        <video controls width="500">
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>
</body>
</html>
