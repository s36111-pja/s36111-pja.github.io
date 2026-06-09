# s36111-pja.github.io

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MyWiki</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f6f6f6;
}

header {
    background: white;
    border-bottom: 1px solid #ccc;
    padding: 15px 30px;
}

header h1 {
    margin: 0;
}

.container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
}

.box {
    background: white;
    border: 1px solid #a7d7f9;
    margin-bottom: 20px;
}

.box-header {
    background: #eaf3ff;
    padding: 10px;
    font-weight: bold;
    border-bottom: 1px solid #a7d7f9;
}

.box-content {
    padding: 15px;
}

.article-link {
    color: #0645ad;
    text-decoration: none;
}

.article-link:hover {
    text-decoration: underline;
}

.page-footer {
    position: fixed;
    bottom: 10px;
    right: 15px;
    font-size: 12px;
    color: #666;
    background: rgba(255,255,255,0.9);
    padding: 4px 8px;
    border: 1px solid #ccc;
    border-radius: 3px;
}
</style>
</head>

<body>

<header>
    <h1>MyWiki</h1>
    <p>The free encyclopedia</p>
</header>

<div class="container">

    <div class="box">
        <div class="box-header">Welcome to MyWiki</div>
        <div class="box-content">
            <p>
                MyWiki contains articles on a variety of topics.
                Browse featured content below.
            </p>
        </div>
    </div>

    <div class="box">
        <div class="box-header">Featured Article</div>
        <div class="box-content">
            <h3>
                <a href="apple.html" class="article-link">Apple</a>
            </h3>
            <p>
                The apple is the edible fruit of the apple tree
                (<em>Malus domestica</em>) and is one of the most widely
                cultivated fruits in the world.
            </p>
            <p>
                <a href="apple.html" class="article-link">
                    Read more...
                </a>
            </p>
        </div>
    </div>

    <div class="box">
        <div class="box-header">Did You Know?</div>
        <div class="box-content">
            <ul>
                <li>There are over 7,500 known varieties of apples.</li>
                <li>Apple trees can live for more than 100 years.</li>
                <li>The science of growing fruit is called pomology.</li>
            </ul>
        </div>
    </div>

</div>

<footer class="page-footer">
    s36111
</footer>

</body>
</html>

