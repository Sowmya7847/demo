<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .contact-form {
      background: white;
      padding: 20px 30px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
      max-width: 400px;
      width: 100%;
    }
    .contact-form h2 {
      margin-bottom: 15px;
      color: #333;
    }
    .contact-form label {
      display: block;
      margin: 10px 0 5px;
      font-weight: bold;
    }
    .contact-form input, 
    .contact-form textarea {
      width: 100%;
      padding: 8px;
      border: 1px solid #ddd;
      border-radius: 4px;
      resize: vertical;
      font-size: 14px;
    }
    .contact-form button {
      margin-top: 15px;
      background-color: #007BFF;
      border: none;
      color: white;
      padding: 10px;
      width: 100%;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }
    .contact-form button:hover {
      background-color: #0056b3;
    }
    .success-message {
      color: green;
      margin-top: 15px;
      display: none;
    }
  </style>
</head>
<body>
  <form class="contact-form" id="contactForm">
    <h2>Contact Us</h2>
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="Your full name" required />
    
    <label for="email">Email</label>
    <input type="email" id="email" name="email" placeholder="Your email address" required />
    
    <label for="subject">Subject</label>
    <input type="text" id="subject" name="subject" placeholder="Subject" required />
    
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" placeholder="Write your message here..." required></textarea>
    
    <button type="submit">Send</button>
    <p class="success-message" id="successMessage">Thank you! Your message has been sent.</p>
  </form>

  <script>
    const form = document.getElementById('contactForm');
    const successMessage = document.getElementById('successMessage');

    form.addEventListener('submit', function(e) {
      e.preventDefault();

      // Simple client-side validation or processing here
      // For demo, just show success message
      successMessage.style.display = 'block';

      // Clear the form fields
      form.reset();
    });
  </script>
</body>
</html>
