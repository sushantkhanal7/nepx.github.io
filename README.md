<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEP X - Tournament Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <img src="nepx-logo.png" alt="NEP X Logo" class="logo">
    </header>

    <main>
        <div class="images">
            <img src="mobile1.png" alt="NEP X Mobile Preview">
            <img src="mobile2.png" alt="NEP X Mobile Preview">
        </div>

        <div class="download-section">
            <img src="nepx-logo.png" alt="NEP X Logo" class="small-logo">
            <a href="nepx.apk" class="download-button">⬆ Download Apk</a>
        </div>
    </main>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.logo {
    width: 120px;
    margin-top: 20px;
}

.images {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-top: 20px;
}

.images img {
    width: 40%;
    max-width: 300px;
    border-radius: 15px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.download-section {
    background: white;
    padding: 20px;
    margin: 30px auto;
    width: 90%;
    max-width: 400px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.small-logo {
    width: 80px;
    margin-bottom: 10px;
}

.download-button {
    display: inline-block;
    text-decoration: none;
    background: blue;
    color: white;
    padding: 10px 20px;
    font-size: 1.2em;
    border-radius: 5px;
    margin-top: 10px;
}
