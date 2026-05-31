# dear-annu
For Annu, with love and a sincere apology ❤️
<img src="Snapchat-194158009.jpg"
     style="width:180px;
     height:180px;
     border-radius:50%;
     object-fit:cover;
     border:5px solid #ff4d88;
     margin-bottom:20px;
     box-shadow:0 0 25px rgba(255,77,136,0.5);">
<script>
function createHeart() {
    const heart = document.createElement("div");

    heart.innerHTML = "❤️";
    heart.style.position = "fixed";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.bottom = "-20px";
    heart.style.fontSize = (Math.random() * 20 + 20) + "px";
    heart.style.pointerEvents = "none";
    heart.style.zIndex = "9999";

    document.body.appendChild(heart);

    let position = -20;

    const animation = setInterval(() => {
        position += 3;
        heart.style.bottom = position + "px";
        heart.style.transform =
            `translateX(${Math.sin(position/30)*20}px) rotate(${position}deg)`;

        if (position > window.innerHeight + 100) {
            clearInterval(animation);
            heart.remove();
        }
    }, 20);
}

setInterval(createHeart, 400);
</script>
