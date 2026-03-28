<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haroon Khan | Official Hub</title>
    <style>
        /* Live Animated Background */
        body { 
            margin: 0; padding: 20px; font-family: 'Segoe UI', sans-serif; 
            background: linear-gradient(-45deg, #000428, #004e92, #000000, #1a1a1a);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: #fff; text-align: center;
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .profile-container { position: relative; display: inline-block; margin-top: 30px; }
        .avatar { 
            width: 140px; height: 140px; border-radius: 50%; 
            border: 3px solid #00f2ea; overflow: hidden; 
            background: #222; box-shadow: 0 0 25px rgba(0, 242, 234, 0.5); 
        }
        .avatar img { width: 100%; height: 100%; object-fit: cover; }
        
        .yt-badge { 
            position: absolute; top: -5px; right: -5px; 
            background: #fff; color: #ff0000; 
            width: 40px; height: 40px; border-radius: 50%; 
            display: flex; align-items: center; justify-content: center;
            font-size: 20px; border: 3px solid #000;
            box-shadow: 0 4px 10px rgba(255, 0, 0, 0.4);
        }

        .section-title { margin-top: 30px; font-size: 13px; text-transform: uppercase; letter-spacing: 2px; color: #00f2ea; font-weight: bold; }

        .links-container { margin-top: 12px; display: flex; flex-direction: column; gap: 12px; align-items: center; }
        
        .btn { 
            width: 90%; max-width: 400px; padding: 16px; 
            background: rgba(255, 255, 255, 0.07); backdrop-filter: blur(10px); 
            border-radius: 15px; text-decoration: none; color: white; 
            display: flex; justify-content: space-between; align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.1); transition: 0.3s ease; 
        }
        .btn:hover { background: rgba(255, 255, 255, 0.12); transform: translateY(-3px); border-color: #00f2ea; }
        
        .tag { padding: 4px 10px; border-radius: 6px; font-size: 11px; font-weight: bold; text-transform: uppercase; }
        .yt-tag { background: #ff0000; }
    </style>
</head>
<body>

    <div class="profile-container">
        <div class="yt-badge">▶</div>
        <div class="avatar">
            <img src="https://i.ibb.co/99Gfdcgs/1000069964.jpg" alt="Haroon Khan">
        </div>
    </div>

    <h1>Haroon Khan</h1>
    <p style="opacity: 0.8; font-size: 14px;">Digital Content Creator</p>

    <div class="section-title">YouTube Hub</div>
    <div class="links-container">
        <a href="https://youtube.com/@quiztime-d6n" class="btn">
            <span>Main Channel</span>
            <span class="tag yt-tag">25K+ Subs</span>
        </a>
        <a href="https://youtube.com/@shor_video-d2e" class="btn">
            <span>2 Official Channel</span>
            <span class="tag yt-tag">9.4K Subs</span>
        </a>
        <a href="https://youtube.com/@shabirkhan11shabirkhan11-g5i" class="btn">
            <span>Channel 3</span>
        </a>
        <a href="https://youtube.com/@karemkhan-wr3zj" class="btn">
            <span>Channel 4</span>
        </a>
    </div>

    <div class="section-title">Follow Me Socially</div>
    <div class="links-container">
        <a href="https://www.facebook.com/share/1biN4MABti/" class="btn" style="border-left: 5px solid #1877F2;">
            <span>Facebook</span>
        </a>
        <a href="https://www.instagram.com/haroon_khan6764" class="btn" style="border-left: 5px solid #e1306c;">
            <span>Instagram</span>
        </a>
        <a href="https://www.tiktok.com/@sycoboy7906" class="btn" style="border-left: 5px solid #ffffff;">
            <span>TikTok</span>
        </a>
        <a href="https://www.snapchat.com/add/user780492346" class="btn" style="border-left: 5px solid #FFFC00;">
            <span>Snapchat</span>
        </a>
    </div>

    <p style="margin-top: 50px; opacity: 0.4; font-size: 10px;">Powered by Haroon Khan</p>

</body>
</html>
