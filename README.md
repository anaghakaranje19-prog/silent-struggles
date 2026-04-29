<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Silent Struggles</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f5f7fa;
    color: #333;
}

header {
    background: #4a90e2;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    display: flex;
    justify-content: center;
    background: #2c3e50;
}

nav a {
    color: white;
    padding: 14px 20px;
    text-decoration: none;
}

nav a:hover {
    background: #1abc9c;
}

section {
    padding: 40px;
    max-width: 900px;
    margin: auto;
}

.hero {
    text-align: center;
}

.card {
    background: white;
    padding: 20px;
    margin: 20px 0;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

button {
    padding: 10px 20px;
    background: #1abc9c;
    border: none;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #16a085;
}

footer {
    text-align: center;
    padding: 20px;
    background: #2c3e50;
    color: white;
}

textarea {
    width: 100%;
    height: 100px;
    padding: 10px;
    margin-top: 10px;
}

</style>
</head>

<body>

<header>
    <h1>Silent Struggles</h1>
    <p>Because asking for help shouldn’t feel scary</p>
</header>

<nav>
    <a href="#problem">Problem</a>
    <a href="#solution">Solution</a>
    <a href="#prototype">Prototype</a>
    <a href="#feedback">Feedback</a>
</nav>

<section class="hero">
    <h2>Students struggle in silence</h2>
    <p>Fear of judgment, language barriers, and anxiety prevent students from asking questions.</p>
</section>

<section id="problem">
    <div class="card">
        <h2>🔍 Problem</h2>
        <p>Many students hesitate to ask doubts due to:</p>
        <ul>
            <li>Fear of embarrassment</li>
            <li>Peer judgment</li>
            <li>Lack of confidence</li>
            <li>Language barriers</li>
        </ul>
    </div>
</section>

<section id="solution">
    <div class="card">
        <h2>💡 Our Solution</h2>
        <p>An anonymous platform where students can:</p>
        <ul>
            <li>Ask doubts without revealing identity</li>
            <li>Get peer + mentor answers</li>
            <li>Use AI-based hint system</li>
        </ul>
    </div>
</section>

<section id="prototype">
    <div class="card">
        <h2>🧪 Prototype</h2>
        <p>Try submitting an anonymous doubt:</p>

        <textarea placeholder="Type your doubt here..."></textarea>
        <br><br>
        <button onclick="submitDoubt()">Submit Anonymously</button>

        <p id="response" style="margin-top:15px;"></p>
    </div>
</section>

<section id="feedback">
    <div class="card">
        <h2>📊 Feedback</h2>
        <p>“I finally asked questions without feeling judged.”</p>
        <p>“This would help shy students a lot.”</p>
    </div>
</section>

<footer>
    <p>Design Thinking Project | Silent Struggles</p>
</footer>

<script>
function submitDoubt() {
    document.getElementById("response").innerText =
        "Your doubt has been submitted anonymously!";
}
</script>

</body>
</html># silent-struggles
