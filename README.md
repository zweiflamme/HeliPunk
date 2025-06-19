<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heli Punk</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: #d3d3d3; /* Hellgrau */
            font-family: 'Montserrat', sans-serif;
            color: #000; /* Schwarze Schrift */
        }

        h1 {
            font-size: 3.5rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1.5s ease-in-out;
        }

        img {
            width: 350px;
            height: 350px;
            object-fit: cover;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        img:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2.5rem;
                letter-spacing: 2px;
            }

            img {
                width: 250px;
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <h1>Heli Punk</h1>
    <img src="https://assets.grok.com/users/8a626341-4382-4058-bff3-93010588b7b7/generated/0b75a7bb-8e1c-49ac-84c8-d55a19a54a9e/image.jpg" alt="Heli Punk Bild">
</body>
</html>
