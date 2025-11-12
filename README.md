cd /path/to/your/project-folder
git init
git remote add origin https://github.com/mrmarketingbose/mmb-consult.git
git add index.html mr.marketingbose.png
git commit -m "Add landing page"
git branch -M main
git push -u origin main
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>mr.marketingbose | Simplify Your Marketing Strategy</title>
  <meta name="description" content="Understand your marketing challenges and find practical solutions with mr.marketingbose's one-on-one business consultation." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --muted: #d4d4aa;
      --text: #fef08a;
      --card: rgba(0, 0, 0, 0.35);
      --max: 1100px;
      --button: #000000;
      --accent-dark: #0b3f20;
      --accent-black: #041012;
    }
    * { box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: linear-gradient(180deg, var(--accent-dark), var(--accent-black));
      color: var(--text);
      letter-spacing: 0.3px;
    }
    .wrap { max-width: var(--max); margin: 24px auto; padding: 20px; }

    header { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; }
    .logo img { width: 110px; height: 110px; border-radius: 50%; object-fit: cover; border: 2px solid rgba(255,255,255,0.2); }
    .logo-text { text-align: center; margin-top: 6px; font-size: 16px; color: var(--text); font-weight: 600; letter-spacing: 0.5px; }
    .header-text { flex: 1; text-align: left; }
    h1 { margin: 0 0 10px; font-size: 36px; font-weight: 700; color: var(--text); }
    .intro { max-width: 700px; font-size: 17px; line-height: 1.7; color: var(--muted); }

    .card {
      background: var(--card);
      backdrop-filter: blur(8px);
      border-radius: 14px;
      padding: 22px;
      border: 1px solid rgba(255,255,255,0.05);
      color: var(--text);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
      margin: 30px 0;
    }

    .btn {
      background: var(--button);
      color: var(--text);
      padding: 14px 26px;
      border-radius: 12px;
      text-decoration: none;
      font-weight: 600;
      display: inline-block;
      margin-top: 22px;
      transition: all 0.3s ease;
      font-size: 15px;
    }
    .btn:hover { opacity: 0.95; transform: translateY(-2px); }

    .section-title { font-size: 26px; font-weight: 600; margin-bottom: 12px; color: var(--text); }
    .tiny { font-size: 15px; color: var(--muted); line-height: 1.7; }

    footer { text-align: center; color: var(--muted); margin-top: 45px; font-size: 14px; }
    .no-refund { font-size: 13px; color: var(--muted); margin-top: 10px; font-style: italic; }
    form input, form select, form textarea {
      width: 100%;
      padding: 12px;
      border-radius: 10px;
      border: 1px solid rgba(255,255,255,0.1);
      background: transparent;
      color: var(--text);
      margin-bottom: 12px;
      font-family: 'Poppins', sans-serif;
      font-size: 15px;
    }
    form label { display: block; margin-bottom: 6px; color: var(--text); font-weight: 500; font-size: 15px; }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="header-text">
        <h1>Feeling stuck with your business growth?</h1>
        <p class="intro">You are not alone. Many small business owners create endless content and invest in ads that fail to convert. The real challenge lies in not having a clear system that turns visibility into consistent sales. My goal is to help you find clarity and create a marketing roadmap that actually works for you.</p>
      </div>
      <div class="logo">
        <img src="mr.marketingbose.png" alt="Profile photo of mr.marketingbose" />
        <div class="logo-text">mr.marketingbose</div>
      </div>
    </header>

    <section class="card">
      <div class="section-title">Here’s How I Can Help</div>
      <p class="tiny">During a 45-minute consultation, we will look closely at your business and identify where your marketing efforts can be improved. This conversation is focused on understanding your pain points and providing realistic solutions that fit your goals.</p>
      <ul class="tiny">
        <li>We will discuss your current marketing strategy and identify gaps.</li>
        <li>We will outline how to convert your audience into paying clients.</li>
        <li>We will map out a simple funnel using Instagram, WhatsApp, and Google tools.</li>
        <li>You will receive a 30-day customized action plan.</li>
      </ul>
      <p class="tiny">You will leave the session with direction and confidence, knowing what to prioritize and how to achieve consistent growth without overcomplicating things.</p>
    </section>

    <section class="card">
      <div class="section-title">Client Experiences</div>
      <p class="tiny">These businesses started with the same challenges but achieved results after implementing structured systems:</p>
      <ul class="tiny">
        <li><a href="https://instagram.com/cafebrewandchew" target="_blank" rel="noopener noreferrer">@cafebrewandchew</a></li>
        <li><a href="https://instagram.com/eklabyainstitute_" target="_blank" rel="noopener noreferrer">@eklabyainstitute_</a></li>
        <li><a href="https://instagram.com/beautybarfamilysalon" target="_blank" rel="noopener noreferrer">@beautybarfamilysalon</a></li>
        <li><a href="https://instagram.com/house_of_kaari_" target="_blank" rel="noopener noreferrer">@house_of_kaari_</a></li>
        <li><a href="https://instagram.com/asian_grub" target="_blank" rel="noopener noreferrer">@asian_grub</a></li>
      </ul>
    </section>

    <section id="book" class="card">
      <div class="section-title">Book Your Personalized Consultation</div>
      <p class="tiny">This is not just another marketing call. It is a practical session designed to help you find solutions that match your goals. Once booked, you will receive a Google Meet link immediately. Please note that the booking is non-refundable as each session slot is personalized and reserved for you.</p>

      <form id="bookingForm">
        <label for="fullname">Full Name</label>
        <input type="text" id="fullname" name="fullname" placeholder="Enter your name" required>

        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>

        <label for="phone">WhatsApp Number</label>
        <input type="tel" id="phone" name="phone" placeholder="Enter your WhatsApp number" required>

        <label for="slot">Preferred Date and Time</label>
        <select id="slot" name="slot" required>
          <option value="">Select a slot</option>
          <option>Monday 7:00 PM</option>
          <option>Monday 8:00 PM</option>
          <option>Tuesday 7:00 PM</option>
          <option>Tuesday 8:00 PM</option>
          <option>Saturday 11:00 AM</option>
          <option>Saturday 12:00 PM</option>
          <option>Sunday 11:00 AM</option>
          <option>Sunday 12:00 PM</option>
        </select>

        <button type="submit" class="btn">Reserve Your Slot for ₹499</button>
      </form>
      <p class="no-refund">No refunds after booking. Your slot will be confirmed instantly.</p>
    </section>

    <footer>
      © <span id="year"></span> mr.marketingbose | Marketing Consultation Page
    </footer>
  </div>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
