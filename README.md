# clintonkisia1996-lab-index.html-README.md<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Registration Form</title>
</head>
<body>
  <header>
    <h1>Course Registration Form</h1>
    <p>Please complete all required fields before submitting.</p>
  </header>

  <main>
    <!-- Semantic form element -->
    <form action="/submit" method="post">
      <!-- Personal Information Section -->
      <fieldset>
        <legend>Personal Information</legend>

        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname" required><br><br>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone"><br><br>
      </fieldset>

      <!-- Account Information Section -->
      <fieldset>
        <legend>Account Details</legend>

        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>

        <label for="confirm-password">Confirm Password:</label>
        <input type="password" id="confirm-password" name="confirm-password" required><br><br>
      </fieldset>

      <!-- Preferences Section -->
      <fieldset>
        <legend>Preferences</legend>

        <label for="course">Choose a Course:</label>
        <select id="course" name="course" required>
          <option value="">-- Select an option --</option>
          <option value="html">HTML Basics</option>
          <option value="css">CSS Fundamentals</option>
          <option value="js">JavaScript Essentials</option>
        </select><br><br>

        <label>Mode of Learning:</label><br>
        <input type="radio" id="online" name="mode" value="online" required>
        <label for="online">Online</label><br>
        <input type="radio" id="onsite" name="mode" value="onsite">
        <label for="onsite">Onsite</label><br><br>

        <label for="newsletter">
          <input type="checkbox" id="newsletter" name="newsletter">
          Subscribe to newsletter
        </label>
      </fieldset>

      <!-- Submission -->
      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 Registration Portal</p>
  </footer>
</body>
</html>
