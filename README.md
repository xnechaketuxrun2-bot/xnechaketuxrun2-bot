<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แนะนำตัว - อเนชา (ต้า)</title>
    <!-- โหลดฟอนต์ Kanit จาก Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;600&display=swap" rel="stylesheet">
    
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Kanit', sans-serif;
            background-color: #f7f9fa;
            color: #2c3e50;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .card {
            background-color: #ffffff;
            width: 100%;
            max-width: 420px;
            padding: 40px 30px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            background-color: #eef2f5;
            color: #4a5568;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 36px;
            font-weight: 600;
            margin: 0 auto 20px auto;
        }

        h1 {
            font-size: 1.6rem;
            font-weight: 600;
            margin-bottom: 6px;
        }

        .subtitle {
            font-size: 0.95rem;
            color: #718096;
            margin-bottom: 24px;
            font-weight: 300;
        }

        .bio {
            font-size: 0.95rem;
            line-height: 1.6;
            color: #4a5568;
            margin-bottom: 24px;
        }

        .tag-container {
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .tag {
            background-color: #f1f5f9;
            color: #334155;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 400;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="profile-img">ต</div>
        <h1>อเนชา (ต้า)</h1>
        <p class="subtitle">Welcome to my profile site</p>
        
        <p class="bio">
            สวัสดีครับ! ผมต้า ยินดีที่ได้รู้จักครับ <br>
            หลงใหลการสร้างสรรค์สิ่งใหม่ๆ ผ่านหน้าจอ
        </p>

        <div class="tag-container">
            <span class="tag">🎮 เล่นเกม</span>
            <span class="tag">💻 เขียนโค้ด</span>
        </div>
    </div>

</body>
</html>
