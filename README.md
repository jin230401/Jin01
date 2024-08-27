<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表白网页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
        }

        h1 {
            color: #333;
            animation: fadeInUp 1s ease-in-out;
        }

        p {
            font-size: 18px;
            color: #666;
            opacity: 0;
            animation: fadeInUp 1s ease-in-out forwards;
            animation-delay: 0.5s;
        }

       .heart {
            color: red;
            animation: pulse 1s infinite;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>

<body>
    <h1>亲爱的：</h1>
    <p>从见到你的第一眼起，你就住进了我的心里。</p>
    <p>你的笑容如阳光般温暖，照亮了我的世界。</p>
    <p>你的眼睛犹如璀璨星辰，让我沉醉其中。</p>
    <p>我想告诉你，我喜欢你，愿与你携手走过每一个美好的日子。</p>
    <p>爱你的[你的名字] <span class="heart">&hearts;</span></p>
</body>

</html>
