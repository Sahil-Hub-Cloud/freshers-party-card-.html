<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fresher's Party Invitation</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8f9fa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            padding-bottom: 20px;
        }

        .card {
            perspective: 1000px;
            display: flex;
            justify-content: center;
            align-items: center;
            max-width: 90%;
            margin-bottom: 20px;
        }

        .invitation-card {
            width: 600px;
            height: 450px;
            transform-style: preserve-3d;
            transition: transform 1s ease-in-out;
            transform-origin: center;
            position: relative;
        }

        .invitation-card:hover {
            transform: rotateY(180deg);
        }

        .card-front, .card-back {
            background-color: #ffffff;
            border: 2px solid #2e4053;
            border-radius: 15px;
            padding: 30px;
            width: 100%;
            height: 100%;
            position: absolute;
            backface-visibility: hidden;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .card-front {
            font-size: 30px;
            font-weight: bold;
            color: #2e4053;
            background-image: url('https://w0.peakpx.com/wallpaper/262/444/HD-wallpaper-artificial-intelligence-cyber-intelligence.jpg');
            background-size: cover;
            background-position: center;
            transition: transform 0.5s ease;
        }

        .card-front:hover {
            transform: scale(1.05);
        }

        .card-back {
            transform: rotateY(180deg);
            background: linear-gradient(135deg, #dfe6e9, #b2bec3);
        }

        .header {
            text-align: center;
            margin-bottom: 15px;
        }

        .logo {
            width: 100px;
            height: 100px;
            margin-bottom: 10px;
        }

        .header h1 {
            color: #2e4053;
            margin: 0;
            font-size: 26px;
            font-weight: 600;
        }

        .content {
            text-align: center;
            width: 100%;
        }

        .content h2 {
            color: #d35400;
            margin-bottom: 8px;
            font-size: 24px;
        }

        .content h3 {
            color: #2980b9;
            margin-bottom: 15px;
            font-size: 22px;
        }

        .details p {
            margin: 5px 0;
            color: #34495e;
            font-size: 18px;
        }

        .from {
            margin-top: 15px;
            font-style: italic;
            color: #7f8c8d;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="invitation-card">
            <div class="card-front">
                <h2 style="color: rgba(214, 148, 26, 0.922)" >Freshers Party @  2K25</h2>
            </div>
            <div class="card-back">
                <div class="header">
                    <img src="https://litam.in/wp-content/uploads/2023/05/processed-38ec4f37-6aaa-4337-bb5e-dcb51e50613f_FEUqdgnj-300x300.jpeg" alt="College Logo" class="logo">
                    <h1>LOYOLA COLLEGE OF ENGINEERING</h1>
                </div>
                <div class="content">
                    <h2>Welcome Freshers!</h2>
                    <p>We are excited to invite you to the</p>
                    <h3>Fresher's Party 2025</h3>
                    <p>Join us for an evening of fun, music, and celebration as we welcome the new batch of students.</p>
                    <div class="details">
                        <p><strong>Date:</strong> 01ST OF MARCH 2025</p>
                        <p><strong>Time:</strong> 6:00 PM onwards</p>
                        <p><strong>Venue:</strong> College</p>
                    </div>
                    <p>Don't miss out on the fun! See you there!</p>
                    <p class="from">- All seniors of 2nd year</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
