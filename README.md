
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Wrench & Shine</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; }
    header { background: #222; color: white; padding: 40px 20px; text-align: center; }
    header h1 { margin: 0; font-size: 2.5em; }
    .content { padding: 20px; max-width: 800px; margin: auto; }
    .services h2 { margin-top: 40px; }
    .service-list { list-style: none; padding: 0; }
    .service-list li { margin: 10px 0; }
    form { margin-top: 30px; display: flex; flex-direction: column; }
    form input, form select, form textarea, form button {
      margin: 5px 0; padding: 10px; font-size: 1em;
    }
    footer { text-align: center; padding: 20px; background: #f2f2f2; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>Wrench & Shine</h1>
    <p>Mobile Detailing & Maintenance — Fast Fixes! Fresh Rides!</p>
  </header>

  <div class="content">
    <section class="services">
      <h2>Our Services</h2>
      <ul class="service-list">
        <li>Brakes</li>
        <li>Oil Change</li>
        <li>Diagnostics</li>
        <li>Small Engine Maintenance And Repairs(lawnmowers, golf carts, etc.)</li>
        <li>Interior & Exterior Detailing(wash, wax, tires, vacuum, shampoo upholstry)</li>
        <li>Garage Located In Ozark Just Off HWY 231 Across From Wal-Mart</li>
        <li>Mobile Service Availabe – At Your Home or Work</li>
         </ul>
    </section>

    <section class="booking">
      <h2>Book an Appointment</h2>
      <form action="mailto:youremail@example.com" method="POST" enctype="text/plain">
        <input type="text" name="Name" placeholder="Levi Evans" required />
        <input type="email" name="Email" placeholder="wrench.shine@gmail.com" required />
        <input type="tel" name="Phone" placeholder="850-732-6668" required />
        <select name="Service" required>
          <option value="">Select Service</option>
          <option>Brake Job</option>
          <option>Oil Change</option>
          <option>Small Engine Repair</option>
          <option>Detailing</option>
        </select>
        <textarea name="Notes" rows="4" placeholder="Preferred date/time or notes"></textarea>
        <button type="submit">Request Appointment</button>
      </form>
    </section>
  </div>

  <footer>
    <p>📞 Call/Text: [850-732-6668] | 📍 Serving [Ozark, Daleville, Enterprise, Dothan]</p>
    <p>DM us on Facebook/Instagram <br> &copy; 2025 Wrench & Shine</p>
  </footer>
</body>
</html>
