<!DOCTYPE html>
<html lang="en">
<head>
    <title>Sunnydale School</title>
    <style>
        /* Styles for the page title */
        h1 {
            font-size: 24px;
            font-weight: bold;
            color: #1E90FF;
        }

        /* General body font */
        body {
            font-family: 'Arial', sans-serif;
        }

        /* Section heading colors */
        h2:nth-of-type(1) {
            color: #32CD32; /* Mission Statement */
        }

        h2:nth-of-type(2) {
            color: #FFA07A; /* Upcoming Events */
        }

        h2:nth-of-type(3) {
            color: #20B2AA; /* Contact Us */
        }

        /* Style for the dates in Upcoming Events */
        .upcoming-events span {
            font-weight: bold;
            color: red;
        }

        /* Style for the Upcoming Events section */
        #upcoming-events {
            background-color: #FFFFE0;
        }

        /* Style for outdoor events */
        .outdoor {
            background-color: #AFEEEE;
            padding: 5px;
            border: 1px solid #B0E0E6;
        }

        /* Style for the Contact Us section */
        .contact-us {
            background-color: #f8f3f3;
            padding: 10px;
        }
    </style>
</head>
<body>

    <h1>Welcome to Sunnydale School</h1>

    <h2>Mission Statement</h2>
    <p>Our mission is to provide a nurturing and stimulating environment where students can achieve their full potential.</p>

    <h2 id="upcoming-events">Upcoming Events</h2>
    <ul class="upcoming-events">
        <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - <span >June 10</span></li>
        <li data-event-type="outdoor" title="Event Type: Outdoor" class="outdoor">Art Exhibition - <span >June 15</span></li>
        <li data-event-type="outdoor" title="Event Type: Outdoor" class="outdoor">Sports Day - <span>June 20</span></li>
        <li data-event-type="indoor" title="Event Type: Indoor">Debate Competition - <span>June 25</span></li>
    </ul>

    <h2 >Contact Us</h2>
    <div class="contact-us">
        <p>Email: <a href="mailto:info@sunnydale.edu" title="Click to copy email">info@sunnydale.edu</a></p>
        <p>Phone: <a href="tel:+15551234567" title="Click to copy phone number">+1 (555) 123-4567</a></p>
        <!-- Imagine clicking here shows a message: 'Thanks for reaching out!' -->
    </div>

</body>
</html>
Write
