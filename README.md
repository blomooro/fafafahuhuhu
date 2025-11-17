<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Timeless Video</title>
<style>
    body {
        margin: 0;
        background: #333;
        font-family: Arial, sans-serif;
        color: white;
        text-align: center;
    }

    /* Header */
    .navbar {
        background: #2b2b2b;
        padding: 15px;
        display: flex;
        justify-content: center;
        gap: 30px;
        font-size: 18px;
    }

    .navbar a {
        text-decoration: none;
        color: white;
        transition: 0.2s;
    }

    .navbar a:hover {
        color: #00eaff;
    }

    /* Center Content */
    .content {
        max-width: 900px;
        margin: 40px auto;
    }

    video {
        width: 100%;
        border-radius: 10px;
    }

</style>
</head>
<body>

<!-- NAVBAR -->
<div class="navbar">
    <a href="#">🏠 Home</a>
    <a href="#">🖼 Gallery</a>
    <a href="#">🔥 Viral</a>
</div>

<!-- CONTENT -->
<div class="content">
    <h2>Timeless</h2>
    <video controls autoplay muted>
        <source src="yourvideo.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<!-- TEMPAT PASANG SCRIPT IKLAN -->
<!-- Example Adsterra script -->
<!-- <script type="text/javascript" src="AD_CODE_HERE"></script> -->

</body>
</html>
