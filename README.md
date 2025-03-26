<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Week Two Assigment</title>
</head>
<body>

    <h2>Roman Numeral List</h2>
    <ol type="I">
        <li>Cool</li>
        <li>Hot</li>
        <li>Cold</li>
        <li>Freezing</li>
        <li>Wild </li>
    </ol>

    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="Beautiful Landscape" width="500">

    <h2>Contact List</h2>
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
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>123-456-7890</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave</td>
                <td>987-654-3210</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>David Lee</td>
                <td>789 Pine Ln</td>
                <td>555-123-4567</td>
                <td>david.lee@example.com</td>
            </tr>
            <tr>
              <td>Alice Johnson</td>
              <td>101 Elm Rd</td>
              <td>111-222-3333</td>
              <td>alice.johnson@example.com</td>
            </tr>
            <tr>
              <td>Robert Brown</td>
              <td>202 Maple Dr</td>
              <td>444-555-6666</td>
              <td>robert.brown@example.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <fieldset>
            <legend>User Registration</legend>

            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="8"><br><br>

            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="country">Country:</label><br>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select><br><br>

            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <p>Interests:</p>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br><br>

            <input type="submit" value="Submit">
        </fieldset>
    </form>
    
    <h2>Multimedia</h2>

    <audio controls>
      <source src="https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_700KB.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <br><br>

    <video width="320" height="240" controls>
      <source src="https://file-examples-com.github.io/uploads/2017/04/file_example_480_1_5MG.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>

</body>
</html>
