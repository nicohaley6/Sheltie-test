# Sheltie-test
Cursor Test
git init
git add .
git commit -m "First commit"
git push origin main

git remote add origin https://github.com/nicohaley6/Sheltie-test
git branch -M main
git push -u origin main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shelty Blog</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background-color: #87CEEB;
            background-image: url('Clouds.webp');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
        }
        img {
            max-width: 500px;
            animation: glitter 1.5s infinite;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        @keyframes glitter {
            0% { filter: brightness(100%); }
            50% { filter: brightness(120%); }
            100% { filter: brightness(100%); }
        }
    </style>
</head>
<body>
    <h1>Sheltie Blog</h1>
    <p>Welcome to the Shelty Blog</p>
    <img src="IMG_8182.PNG" alt="Sheltie">
</body>
</html>
