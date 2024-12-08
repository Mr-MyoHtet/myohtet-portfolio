<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7fc;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .form-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
        }
        .form-container h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .form-container p {
            font-size: 14px;
            color: #888;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            font-size: 14px;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group textarea {
            height: 80px;
            resize: none;
        }
        .form-container button {
            background: black;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h1>Contact Us</h1>
        <p>Please fill this form in a decent manner</p>
         <form action="https://formsubmit.co/21272515c8f406285699a793fb39cae0" method="POST">
            <div class="form-group">
                <label for="first-name">Full Name</label>
                <input type="text" id="first-name" placeholder="First Name" required>
                <input type="text" id="last-name" placeholder="Last Name" required>
            </div>
            <div class="form-group">
                <label for="email">E-mail</label>
                <input type="email" id="email" placeholder="example@example.com" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" placeholder="Your message here..." required></textarea>
            </div>
            <button type="submit">SUBMIT</button>
        </form>
    </div>
</body>
</html>
