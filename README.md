# yasmine-12.CODSOFT.io
loading page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Landing Page</h1>
    </header>
    <section class="intro">
        <h2>About Us</h2>
        <p>This is a brief introduction about our website.</p>
    </section>
    <section class="features">
        <h2>Features</h2>
        <div class="feature">
            <h3>Feature 1</h3>
            <p>Details about feature 1.</p>
        </div>
        <div class="feature">
            <h3>Feature 2</h3>
            <p>Details about feature 2.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

.intro, .features {
    padding: 2rem;
    text-align: center;
}

.features {
    display: flex;
    justify-content: space-around;
}

.feature {
    background-color: #fff;
    padding: 1rem;
    margin: 1rem;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}
