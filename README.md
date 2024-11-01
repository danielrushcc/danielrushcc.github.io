<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Background</title>
    <style>
        /* Reset margins and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Full-screen video background */
        body, html {
            width: 100%;
            height: 100%;
            overflow: hidden;
        }

        .video-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
    </style>
</head>
<body>
    <!-- Video Background -->
    <video autoplay loop muted playsinline class="video-bg">
        <source src="vid_small.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>
