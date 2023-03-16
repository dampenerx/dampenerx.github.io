<!DOCTYPE html>
<html>
  <head>
    <title>Salong Claes - Beauty Services</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#services">Our Services</a></li>
          <li><a href="#book-appointment">Book an Appointment</a></li>
          <li><a href="#contact">Contact Us</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="hero">
        <div class="hero-text">
          <h1>Welcome to Salong Claes</h1>
          <p>We offer a range of beauty services, including haircuts, styling, coloring, and nail services.</p>
        </div>
      </section>
      <section id="services">
        <h2>Our Services</h2>
        <ul>
          <li>Haircuts and styling</li>
          <li>Hair coloring</li>
          <li>Nail services
            <ul>
              <li>Manicures</li>
              <li>Pedicures</li>
            </ul>
          </li>
        </ul>
      </section>
      <section id="book-appointment">
        <h2>Book an Appointment</h2>
        <p>Click the button below to book a nail service appointment.</p>
        <button onclick="bookNailService()">Book a Nail Service Appointment</button>
        <p id="booking-message"></p>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <ul>
          <li>Phone: 555-1234</li>
          <li>Email: info@salongclaes.com</li>
          <li>Address: 123 Main St, Anytown, USA</li>
        </ul>
      </section>
    </main>
    <footer>
      <p>&copy; 2023 Salong Claes. All rights reserved.</p>
    </footer>
    <script>
      function bookNailService() {
        var message = "Thank you for booking a nail service appointment! We will contact you shortly to confirm the details.";
        document.getElementById("booking-message").innerHTML = message;
      }
    </script>
  </body>
</html>
