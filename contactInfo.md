<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact</title>
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@600&family=Barlow:wght@400;500&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background-color: #0f1923;
      color: #fff;
      font-family: 'Barlow', sans-serif;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      padding: 60px 20px;
    }

    .container {
      width: 100%;
      max-width: 640px;
    }

    h1 {
      font-family: 'Barlow', sans-serif;
      font-weight: 400;
      font-size: 2rem;
      letter-spacing: 0.08em;
      text-align: center;
      margin-bottom: 60px;
      color: #e8e8e8;
    }

    .field {
      margin-bottom: 28px;
    }

    label {
      display: block;
      font-family: 'Oswald', sans-serif;
      font-size: 0.7rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: #ffffff;
      margin-bottom: 8px;
    }

    label .required {
      color: #fff;
      margin-left: 2px;
    }

    input, textarea {
      width: 100%;
      background-color: #2e2e2e;
      border: none;
      border-radius: 4px;
      padding: 14px 16px;
      color: #aaa;
      font-family: 'Oswald', sans-serif;
      font-size: 0.7rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      outline: none;
      transition: background 0.2s;
    }

    input::placeholder, textarea::placeholder {
      color: #888;
    }

    input:focus, textarea:focus {
      background-color: #383838;
    }

    textarea {
      height: 140px;
      resize: vertical;
    }

    .submit-btn {
      margin-top: 16px;
      background-color: #fff;
      color: #111;
      border: none;
      border-radius: 50px;
      padding: 14px 36px;
      font-family: 'Oswald', sans-serif;
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      cursor: pointer;
      transition: background 0.2s, color 0.2s;
    }

    .submit-btn:hover {
      background-color: #ddd;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>contact</h1>

    <div class="field">
      <label>Full Name <span class="required">*</span></label>
      <input type="text" placeholder="YOUR NAME..." />
    </div>

    <div class="field">
      <label>Email Address <span class="required">*</span></label>
      <input type="email" placeholder="YOUR EMAIL ADDRESS..." />
    </div>

    <div class="field">
      <label>Message <span class="required">*</span></label>
      <textarea placeholder="YOUR MESSAGE..."></textarea>
    </div>

    <div class="field">
      <label>Phone Number</label>
      <input type="tel" placeholder="" />
    </div>

    <button class="submit-btn">Submit</button>
  </div>
</body>
</html>
