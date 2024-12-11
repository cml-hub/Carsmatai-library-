<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CARSMATAI LIBRARY (CML)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 2rem;
            background: white;
        }
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 1rem 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>CARSMATAI LIBRARY (CML)</h1>
        <p>Promoting Reading and Investment</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#lenders">Lenders</a>
        <a href="#borrowers">Borrowers</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>CARSMATAI LIBRARY (CML) is a community-driven library where individuals can lend books as investments while borrowers access books affordably. Join us in promoting literacy and creating value!</p>
        </section>
        <section id="lenders">
            <h2>For Lenders</h2>
            <ul>
                <li>Lend books as investments and earn interest.</li>
                <li>Track your book's borrowing activity and earnings.</li>
            </ul>
        </section>
        <section id="borrowers">
            <h2>For Borrowers</h2>
            <ul>
                <li>Browse and borrow from our vast collection.</li>
                <li>Affordable membership and borrowing fees.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4"></textarea><br><br>
                <button type="submit">Send</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 CARSMATAI LIBRARY. All Rights Reserved.</p>
    </footer>
</body>
</html>
