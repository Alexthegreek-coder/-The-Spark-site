# -The-Spark-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advertising Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to AdSpace</h1>
        <p>Your #1 platform for digital advertising</p>
    </header>
    <section id="ads">
        <h2>Featured Advertisements</h2>
        <div class="ad-container">
            <div class="ad">Ad Slot 1</div>
            <div class="ad">Ad Slot 2</div>
            <div class="ad">Ad Slot 3</div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <script src="script.js"></script>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f4f4f4;
}
header {
    background-color: #333;
    color: white;
    padding: 20px;
}
.ad-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 20px;
}
.ad {
    background-color: white;
    padding: 20px;
    border: 1px solid #ddd;
    width: 150px;
    text-align: center;
}
form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: auto;
}
input, textarea {
    margin: 10px 0;
    padding: 10px;
    border: 1px solid #ddd;
}
button {
    background-color: #333;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}

/* script.js */
document.querySelector("form").addEventListener("submit", function(event) {
    event.preventDefault();
    alert("Thank you for contacting us! We will get back to you soon.");
});
