<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Get Started - ToonTales</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #333;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            padding-top: 25px;
            height: 0;
        }
        .video-container iframe, .video-container video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<div class="content">
    <h1>Get Started with ToonTales</h1>
    <p>Watch the video below to see how you can create your own ToonTales.</p>
    <div class="video-container">
        <!-- Fixed: Wrap source tag within video tag -->
        <video controls>
            <source src="video/project_video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>


<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
