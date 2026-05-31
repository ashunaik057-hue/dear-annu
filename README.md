# dear-annu
For Annu, with love and a sincere apology ❤️
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Annu ❤️</title>

<style>
body{
    margin:0;
    padding:20px;
    font-family:Georgia, serif;
    background:linear-gradient(135deg,#ffd1dc,#fff5f7);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

.card{
    background:white;
    max-width:800px;
    padding:40px;
    border-radius:20px;
    box-shadow:0 15px 40px rgba(0,0,0,0.1);
    text-align:center;
}

h1{
    color:#ff4f7b;
}

p{
    font-size:18px;
    line-height:1.8;
    color:#444;
}

button{
    margin-top:20px;
    padding:14px 30px;
    border:none;
    border-radius:30px;
    background:#ff4f7b;
    color:white;
    font-size:16px;
    cursor:pointer;
}

.hidden{
    display:none;
    margin-top:25px;
    color:#ff4f7b;
    font-size:20px;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="card">
    <h1>To My Annu ❤️</h1>

    <p>
        I'm sorry for every moment I hurt you,
        every misunderstanding,
        every disappointment,
        and every mistake I've made.

        <br><br>

        You mean more to me than words can explain.

        <br><br>

        Thank you for your love, patience, care, and for staying beside me even when I'm imperfect.

        <br><br>

        I know I don't always get everything right, but one thing I never get wrong is loving you.

        <br><br>

        If I could erase every moment that made you sad, I would.

        <br><br>

        I love you, Annu. Today, tomorrow, and every day after that. ❤️
    </p>

    <button onclick="showLove()">One More Thing ❤️</button>

    <div id="love" class="hidden">
        Annu, if I had a thousand chances, I'd still choose you every single time. ❤️
    </div>
</div>

<script>
function showLove(){
    document.getElementById("love").style.display = "block";
}
</script>

</body>
</html>
