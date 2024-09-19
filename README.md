# PROJET-1<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>محرك بحث بسيط</title>
</head>
<body>
    <div class="container">
        <h1>محرك البحث</h1>
        <input type="text" id="search-input" placeholder="ابحث هنا...">
        <button id="search-button">ابحث</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

.container {
    text-align: center;
}

h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

input {
    padding: 10px;
    width: 300px;
    font-size: 1rem;
}

button {
    padding: 10px 20px;
    font-size: 1rem;
    cursor: pointer;
}
document.getElementById('search-button').addEventListener('click', function() {
    const query = document.getElementById('search-input').value;
    if (query) {
        alert('ستتم عملية البحث عن: ' + query);
        // هنا يمكنك إضافة منطق البحث
    } else {
        alert('يرجى إدخال نص للبحث.');
    }
});
git init
git add .
git commit -m "النسخة الأولى من محرك البحث"
git branch -M main
git remote add origin https://github.com/اسم_المستخدم/اسم_المستودع.git
git push -u origin main
