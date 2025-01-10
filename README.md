<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infinite Video Reels</title>
    <style>
        body {
            margin: 0;
            overflow: hidden; /* Prevent scrolling */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #000;
        }
        video {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%); /* Center the video */
            width: 100vw;
            height: 100vh;
            object-fit: cover; /* Ensure video fills the screen */
        }
    </style>
</head>
<body>
    <video src="https://sikhobhai.shop/wp-content/uploads/2025/01/video6055252899166950525.mp4" 
           autoplay 
           loop 
           muted 
           playsinline>
        Your browser does not support the video tag.
    </video>
</body>
</html>
