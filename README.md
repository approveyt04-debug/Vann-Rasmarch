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
        <h1>សួស្តី! ខ្ញុំឈ្មោះ Approve Yt</h1>
    </header>

    <main>
        <section id="info">
            <h2>ព័ត៌មានផ្ទាល់ខ្លួន</h2>
            <p>ខ្ញុំជាអ្នកអភិវឌ្ឍន៍វេបសាយ និងចូលចិត្តបង្កើតរចនាបទថ្មីៗ។</p>
        </section>

        <section id="action">
            <h2>ចុចប៊ូតុងនេះ</h2>
            <button id="greetBtn">សួស្តីខ្ញុំ!</button>
            <p id="greetMessage"></p>
        </section>
    </main>

    <footer>
        <p>© 2025 Approve Yt</p>
    </footer>

    <script src="script.js"></script>
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
