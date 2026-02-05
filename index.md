<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bdedia – Under Construction</title>
    <meta name="description" content="Bdedia is under construction. Visit our official website DebateSylhetBD for updates.">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* ==========================
           General Reset & Fonts
        ========================== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background: #f5f7fa;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        /* ==========================
           Container
        ========================== */
        .container {
            text-align: center;
            background: #fff;
            padding: 50px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
        }

        /* ==========================
           Animated Construction Gear
        ========================== */
        .gear {
            font-size: 80px;
            color: #ffb100;
            animation: rotate 3s linear infinite;
        }
        @keyframes rotate {
            from { transform: rotate(0deg);}
            to { transform: rotate(360deg);}
        }

        /* ==========================
           Headings
        ========================== */
        h1 {
            margin-top: 20px;
            font-size: 36px;
            font-weight: 700;
            color: #222;
        }
        p {
            margin-top: 15px;
            font-size: 18px;
            color: #555;
        }

        /* ==========================
           Button
        ========================== */
        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 30px;
            background: #007bff;
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            border-radius: 10px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .btn:hover {
            background: #0056b3;
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }

        /* ==========================
           Background Animated Shapes
        ========================== */
        .shape {
            position: absolute;
            border-radius: 50%;
            opacity: 0.2;
            animation: float 10s infinite linear;
        }
        .shape1 { width: 200px; height: 200px; background: #ffb100; top: -50px; left: -50px;}
        .shape2 { width: 150px; height: 150px; background: #007bff; bottom: -50px; right: -50px;}
        @keyframes float {
            0% { transform: translateY(0);}
            50% { transform: translateY(20px);}
            100% { transform: translateY(0);}
        }
    </style>
</head>
<body>
    <!-- Background shapes for decoration -->
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>

    <div class="container">
        <!-- Animated construction gear -->
        <div class="gear">⚙️</div>

        <!-- Main heading -->
        <h1>Bdedia is Under Construction</h1>

        <!-- Subheading / description -->
        <p>Our official website is live. Click below to visit DebateSylhetBD for updates!</p>

        <!-- Button linking to your official website -->
        <a href="https://debatesylhetbd.onrender.com/" target="_blank" class="btn">Go to DebateSylhetBD</a>
    </div>
</body>
</html>
