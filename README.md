<!DOCTYPE html>
<html>
  <head>
    <title>Salong Claes</title>
  </head>
  <body>
    <h1>Welcome to Salong Claes</h1>
    <p>We offer a range of beauty services, including haircuts, styling, coloring, and nail services.</p>
    <h2>Our Services</h2>
    <ul>
      <li>Haircuts and styling</li>
      <li>Hair coloring</li>
      <li>Nail services</li>
        <ul>
          <li>Manicures</li>
          <li>Pedicures</li>
        </ul>
      </li>
    </ul>
    <h2>Contact Us</h2>
    <p>Phone: 555-1234</p>
    <p>Email: info@salongclaes.com</p>
    <p>Address: 123 Main St, Anytown, USA</p>

    <button id="book-appointment" onclick="bookNailService()">Book a Nail Service Appointment</button>
    <p id="booking-message"></p>

    <script>
      function bookNailService() {
        var message = "Thank you for booking a nail service appointment! We will contact you shortly to confirm the details.";
        document.getElementById("booking-message").innerHTML = message;
      }
    </script>
  </body>
</html>
