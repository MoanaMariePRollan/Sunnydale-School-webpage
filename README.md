<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sunnydale School</title>
  <style>
    /* 1. Enhance the Page Title */
    h1 {
      font-size: 24px;
      font-weight: bold;
      color: #1E90FF;
    }

    /* 2. Customize Fonts and Section Colors */
    body {
      font-family: 'Arial', sans-serif;
    }

    h2.mission {
      color: #32CD32;
    }

    h2.events {
      color: #FFA07A;
    }

    h2.contact {
      color: #20B2AA;
    }

    /* 5. Style Specific Sections with IDs and Classes */
    #upcoming-events {
      background-color: #FFFFE0;
    }

    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
    }

    /* 7. Add a Box for Contact Info and Make It Look Nice */
    .section {
      background-color: #f8f3f3;
      padding: 10px;
    }
  </style>
</head>
<body>
  <h1>Sunnydale School</h1>

  <!-- Mission Statement -->
  <h2 class="mission">Mission Statement</h2>
  <p>Our mission is to foster academic excellence and community spirit.</p>

  <!-- Upcoming Events -->
  <h2 id="upcoming-events" class="events">Upcoming Events</h2>
  <ul>
    <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - 
      <span style="font-weight: bold; color: red;">June 10</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">Sports Day - 
      <span style="font-weight: bold; color: red;">June 20</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">Art Exhibition - 
      <span style="font-weight: bold; color: red;">July 5</span>
    </li>
  </ul>

  <!-- Contact Us -->
  <h2 class="contact">Contact Us</h2>
  <div class="section">
    <p>Email: <a href="mailto:info@sunnydaleschool.com" title="Click to copy email">info@sunnydaleschool.com</a></p>
    <p>Phone: <a href="tel:+1234567890" title="Click to copy email">+123 456 7890</a></p>
    <!-- Imagine clicking here shows a message: 'Thanks for reaching out!' -->
  </div>
</body>
</html>
