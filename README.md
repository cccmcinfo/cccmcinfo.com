# Call and Collect Collection Management Corporation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
            text-align: center;
        }

        header {
            background-color: #0078D7;
            color: white;
            padding: 20px;
        }

        main {
            padding: 40px;
        }

        button {
            background-color: #0078D7;
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #005fa3;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <p>A simple website made with HTML, CSS, and JavaScript</p>
    </header>

    <main>
        <h2>Hello!</h2>
        <p>This is a basic webpage.</p>

        <button onclick="showMessage()">Click Me</button>
    </main>

    <footer>
        &copy; 2026 My Website
    </footer>

    <script>
        function showMessage() {
            alert("Thanks for visiting my website!");
        }
    </script>

</body>
</html>
