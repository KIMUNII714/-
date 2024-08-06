# -git clone https://github.com/KIMUNII714/my-website.git
cd my-website
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>期末テスト情報</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>期末テスト情報</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#schedule">日程</a></li>
            <li><a href="#content">テスト範囲</a></li>
            <li><a href="#assignments">提出物</a></li>
        </ul>
    </nav>
    <main>
        <section id="schedule">
            <h2>日程</h2>
            <p>ここにテストの日程を記載します。</p>
        </section>
        <section id="content">
            <h2>テスト範囲</h2>
            <p>ここにテストの範囲を記載します。</p>
        </section>
        <section id="assignments">
            <h2>提出物</h2>
            <p>ここに提出物の情報を記載します。</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 学校名</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header, nav, main, footer {
    padding: 20px;
    margin: 10px;
}

header {
    background: #333;
    color: white;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    border: 1px solid #ccc;
    padding: 10px;
    margin-top: 10px;
}

footer {
    text-align: center;
    margin-top: 20px;
    padding: 10px;
    background: #333;
    color: white;
}
git add index.html styles.css
git commit -m "Add initial website files"
git push origin main
