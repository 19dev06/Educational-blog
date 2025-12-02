<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>PowerFit Gym</title>
<style>
  body{font-family:"Times New Roman",serif;margin:16px;color:#111}
  .wrap{max-width:900px;margin:0 auto}
  header{text-align:center}
  h1{font-size:24px;margin:0}
  p.lead{margin:6px 0 10px;color:#444;font-size:13px}
  nav{font-size:13px;text-align:center;margin-bottom:8px}
  nav a{margin:0 6px;text-decoration:underline}
  hr{border:0;height:1px;background:#ddd;margin:12px 0}
  h2{font-size:18px;margin:14px 0 6px}
  table{border-collapse:collapse;width:100%;font-size:14px}
  th,td{border:1px solid #333;padding:6px;text-align:left}
  .small{font-size:13px;color:#333}
  label{display:block;margin-top:8px}
  input,textarea{width:260px;max-width:100%;padding:6px;border:1px solid #bbb;box-sizing:border-box}
  textarea{height:80px;display:block}
  button{margin-top:8px;padding:6px 10px}
  footer{text-align:center;margin-top:18px;font-size:12px;color:#666}
  @media(max-width:520px){input,textarea{width:100%}}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>PowerFit Gym</h1>
    <p class="lead">"Train Hard, Stay Strong, Live Healthy"</p>
    <nav>
      <a href="#">Home</a> |
      <a href="#">Class Schedule</a> |
      <a href="#">Our Trainers</a> |
      <a href="#">Membership Plans</a> |
      <a href="#">Fitness Blog</a> |
      <a href="#">Contact</a>
    </nav>
  </header>

  <hr>

  <section>
    <h2>Welcome to PowerFit Gym</h2>
    <p class="small">Welcome to <strong>PowerFit Gym</strong>, your neighborhood fitness club where health meets passion. We offer personalized training, group workouts, and expert guidance to help you stay fit and confident.</p>
  </section>

  <section>
    <h2>Class Schedule</h2>
    <table>
      <tr><th>Day</th><th>Class</th><th>Time</th><th>Instructor</th></tr>
      <tr><td>Monday</td><td>Yoga</td><td>6:00 AM - 7:00 AM</td><td>Vikas</td></tr>
      <tr><td>Tuesday</td><td>Cardio Blast</td><td>7:00 AM - 8:00 AM</td><td>Raj</td></tr>
      <tr><td>Wednesday</td><td>Strength Training</td><td>6:00 PM - 7:00 PM</td><td>Tarun</td></tr>
      <tr><td>Thursday</td><td>Zumba</td><td>5:00 PM - 6:00 PM</td><td>Srijan</td></tr>
      <tr><td>Friday</td><td>CrossFit</td><td>6:00 PM - 7:30 PM</td><td>Aman</td></tr>
    </table>
  </section>

  <section>
    <h2>Our Trainers</h2>
    <p><strong>1. Rahul Sharma</strong><br><span class="small">Certified Personal Trainer with 5 years of experience in weight loss and muscle building.</span></p>
    <p><strong>2. Neha Verma</strong><br><span class="small">Zumba and Yoga specialist who makes fitness fun and energetic.</span></p>
    <p><strong>3. Arjun Singh</strong><br><span class="small">CrossFit expert and nutrition advisor, helps you push limits safely.</span></p>
  </section>

  <section>
    <h2>Membership Plans</h2>
    <table>
      <tr><th>Plan</th><th>Duration</th><th>Price</th><th>Benefits</th></tr>
      <tr><td>Basic</td><td>1 Month</td><td>₹1,999</td><td>Gym Access, Free Diet Tips</td></tr>
      <tr><td>Standard</td><td>3 Months</td><td>₹4,499</td><td>Gym + 1 Personal Training Session/Week</td></tr>
      <tr><td>Premium</td><td>6 Months</td><td>₹8,499</td><td>All Classes + Diet Chart + Free Merchandise</td></tr>
    </table>
  </section>

  <section>
    <h2>Fitness Blog</h2>
    <p class="small"><strong>Top 5 Exercises for Beginners:</strong> Push-ups, Squats, Lunges, Planks, Jumping Jacks — great to start your fitness journey.</p>
    <p class="small"><strong>Healthy Eating Tips:</strong> Eat more protein, drink water, avoid junk food, get enough sleep.</p>
    <p class="small"><strong>How to Stay Motivated:</strong> Set small goals, track progress, and celebrate improvements no matter how small.</p>
  </section>

  <section>
    <h2>Contact Us</h2>
    <form onsubmit="alert('Message sent (demo)'); return false;">
      <label>Name:<input type="text" name="name"></label>
      <label>Email:<input type="text" name="email" value="dev069975@gmail.com"></label>
      <label>Message:<textarea name="msg"></textarea></label>
      <button type="submit">Send Message</button>
    </form>

    <p style="margin-top:12px" class="small">
      <strong>Address:</strong> Ghaziabad, India<br>
      <strong>Email:</strong> <a href="mailto:dev069975@gmail.com">dev069975@gmail.com</a><br>
      <strong>Phone:</strong> 7982737536
    </p>
  </section>

  <footer>
    © 2025 PowerFit Gym | Made by Dev Sharma
  </footer>
</div>
</body>
</html>
