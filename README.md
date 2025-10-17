# Vann-Rasmarch
Information by ..........
<!DOCTYPE html>
<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ទំព័រព័ត៌មានខ្ញុំ</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>សួស្តី! ខ្ញុំឈ្មោះ Vann RaSmarch</h1>
    </header> 
</body>
</html>
body {
    font-family: "Khmer OS", Arial, sans-serif;
    background-color: #1e1e1e;
    color: #00ff00;
    text-align: center;
    padding: 20px;
}

header h1 {
    font-size: 2em;
}

button {
    padding: 10px 20px;
    font-size: 1em;
    background-color: #333;
    color: #00ff00;
    border: 2px solid #00ff00;
    cursor: pointer;
    margin-top: 10px;
}

button:hover {
    background-color: #00ff00;
    color: #000;
}
document.getElementById('greetBtn').addEventListener('click', function() {
    document.getElementById('greetMessage').innerText = 'សូមស្វាគមន៍មកកាន់ទំព័រព័ត៌មានរបស់ខ្ញុំ!';
});
