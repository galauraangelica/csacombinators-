<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Combinators Challenge</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            margin: 0;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        aside {
            background-color: #f4f4f4;
            width: 25%;
            padding: 20px;
        }

        main {
            flex: 1;
            padding: 20px;
            display: flex;
            flex-direction: column;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <aside>
        <h2>Sidebar</h2>
        <p>This is the sidebar content.</p>
    </aside>
    <main>
        <h2>Main Content</h2>
        <p>This is the main content area.</p>
    </main>
    <footer>
        <p>&copy; 2024 My Webpage. All rights reserved.</p>
    </footer>
</body>
</html>
