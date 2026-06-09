<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MyWiki - Main Page</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f5f1e8;
    background-image:
        radial-gradient(circle at 20% 20%, rgba(0,0,0,0.04) 0%, transparent 20%),
        radial-gradient(circle at 80% 30%, rgba(0,0,0,0.03) 0%, transparent 25%),
        radial-gradient(circle at 40% 70%, rgba(0,0,0,0.04) 0%, transparent 20%),
        radial-gradient(circle at 70% 80%, rgba(0,0,0,0.03) 0%, transparent 25%);
    background-size: 300px 300px;
}

header {
    background: rgba(255,255,255,0.95);
    border-bottom: 1px solid #ccc;
    padding: 20px 30px;
}

header h1 {
    margin: 0;
    font-size: 2.2rem;
}

header p {
    margin: 5px 0 0;
    color: #555;
}

.container {
    max-width: 1200px;
    margin: 25px auto;
    padding: 0 20px;
}

.box {
    background: rgba(255,255,255,0.92);
    border: 1px solid #a7d7f9;
    margin-bottom: 20px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

.box-header {
    background: #eaf3ff;
    border-bottom: 1px solid #a7d7f9;
    padding: 10px 15px;
    font-weight: bold;
}

.box-content {
    padding: 15px;
}

.article-link {
    color: #0645ad;
    text-decoration: none;
    font-weight: bold;
}

.article-link:hover {
    text-decoration: underline;
}

.featured-image {
    width: 100%;
    max-width: 450px;
    display: block;
    margin: 0 auto;
    border: 1px solid #ccc;
}

.center {
    text-align: center;
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
    <h1>Creature Logs</h1>
    <p>Please enjoy your stay!</p>
</header>

<div class="container">

    <div class="box">
        <div class="box-header">Welcome to Creature Logs</div>
        <div class="box-content">
            <p>
                Creature Logs, a wiki where all the information about different fauna is found.
            </p>
        </div>
    </div>

    <div class="box">
        <div class="box-header">Featured Article</div>

        <div class="box-content center">

            <a href="Sparker.html">
                <img
                    class="featured-image"
                    src="https://upload.wikimedia.org/wikipedia/commons/1/15/Red_Apple.jpg"
                    alt="Sparker"
                >
            </a>

            <p>
                <a href="Sparker.html" class="article-link">
                    Apple
                </a>
            </p>

        </div>
    </div>

    <div class="box">
        <div class="box-header">Did You Know?</div>

        <div class="box-content">
            <ul>
                <li>There are more than 7,500 known varieties of apples.</li>
                <li>Apple trees belong to the rose family.</li>
                <li>The science of fruit cultivation is called pomology.</li>
            </ul>
        </div>
    </div>

    <div class="box">
        <div class="box-header">Featured Facts</div>

        <div class="box-content">
            <ul>
                <li>Wikipedia launched in 2001.</li>
                <li>The oldest known trees can live for thousands of years.</li>
                <li>Honey never spoils when stored properly.</li>
            </ul>
        </div>
    </div>

</div>

<footer class="page-footer">
    s36111
</footer>

</body>
</html>