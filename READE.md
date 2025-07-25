# folder
Contact-Us/
├── index.html
├── style.css
├── script.js (optional, empty)
├── README.md
└── assets/
    └── images/ (if you add any)
# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Us - Cybergenix Security</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <section class="contact-section">
    <h2>Contact Us</h2>
    <div class="contact-container">
      <!-- Contact Form -->
      <form class="contact-form">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <input type="text" placeholder="Subject" />
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
     <!-- Contact Info + Map -->
      <div class="contact-info">
        <h3>Get in Touch</h3>
        <p><strong>Email:</strong> contact@cybergenixsecurity.com</p>
        <p><strong>Phone:</strong> +91-9876543210</p>
        <p><strong>Address:</strong> 123, Cyber Street, New Delhi, India</p>
        <div class="map-container">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14014.511597719077!2d77.20902165!3d28.6139396!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390ce2d83eecbaf7%3A0x68912dc4d6d7ae0c!2sIndia%20Gate!5e0!3m2!1sen!2sin!4v1620000000000!5m2!1sen!2sin"
            width="100%" height="250" style="border:0;" allowfullscreen="" loading="lazy"
          ></iframe>
        </div>
      </div>
    </div>
  </section>

  <script src="script.js"></script>
</body>
</html>

# style.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  color: #333;
}

.contact-section {
  padding: 40px 20px;
  background: #fff;
  max-width: 1200px;
  margin: auto;
}

.contact-section h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 32px;
  color: #222;
}

.contact-container {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
}

.contact-form {
  flex: 1 1 350px;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 6px;
}

.contact-form button {
  padding: 12px;
  background: #0078d4;
  color: #fff;
  border: none;
  font-size: 16px;
  border-radius: 6px;
  cursor: pointer;
  transition: background 0.3s ease;
}

.contact-form button:hover {
  background: #005fa3;
}

.contact-info {
  flex: 1 1 350px;
}

.contact-info h3 {
  margin-bottom: 10px;
  font-size: 20px;
  color: #0078d4;
}

.contact-info p {
  margin: 8px 0;
}

.map-container {
  margin-top: 20px;
  border-radius: 10px;
  overflow: hidden;
}

/* Responsive */
@media (max-width: 768px) {
  .contact-container {
    flex-direction: column;
  }
}
# README.md
# cybergenix Security-contact Us section

**Author**: Neerav Pal  
**Date**: 24 July 2025  

"This is a Responsive Contact Us Section created using HTML, CSS, and optional JavaScript".
It contains:
- Contact form (Name, Email, Subject, Message)
- Embedded Google Map (placeholder)
- Static contact info

## How to View:
1. Open `index.html` in any browser.
2. Make sure `style.css` is in the same folder.
3. All responsive features work on desktop and mobile.

This is part of a static homepage project for Cybergenix Security Pvt. Ltd.
