<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <title>سایت امیرعلی مردانی</title>

    <style>
        body {
            margin: 0;
            font-family: Tahoma, Arial;
            background: linear-gradient(135deg, #1d2671, #c33764);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            direction: rtl;
        }

        .card {
            background: white;
            width: 90%;
            max-width: 400px;
            padding: 30px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }

        h1 {
            color: #1d2671;
            margin-bottom: 10px;
        }

        p {
            color: #555;
            font-size: 16px;
        }

        button {
            margin-top: 20px;
            background: #c33764;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #1d2671;
        }

        #msg {
            margin-top: 15px;
            color: #1d2671;
            font-weight: bold;
        }
    </style>
</head>
<meta name="google-site-verification" content="pFUktzcQv85MJjNOze9NupTtiqeNSrn_QjMSBHxM_2w" />
<body>

    <div class="card">
        <h1>امیرعلی مردانی</h1>

        <p>به سایت شخصی من خوش آمدید 🌟</p>

        <p>شماره تماس: ۰۹۱۸ ۷۰۳۱ ۷۴۷</p>

        <button onclick="showMessage()">
            کلیک کن
        </button>

        <div id="msg"></div>
    </div>

    <script>
        function showMessage() {
            document.getElementById("msg").innerHTML =
                "ممنون که وارد سایت من شدی 😄🔥";
        }
    </script>

</body>
</html>
