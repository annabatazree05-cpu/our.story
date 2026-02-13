# our.story
this our story
<!DOCTYPE html>
<html>
<head>
<title>Our Story</title>

<style>
body{
font-family:Georgia;
text-align:center;
background:#f8f6f4;
padding:40px;
}

.container{
background:white;
padding:35px;
border-radius:16px;
max-width:650px;
margin:auto;
}

img{
width:100%;
border-radius:12px;
margin-top:15px;
}

button{
margin-top:20px;
padding:12px 20px;
font-size:16px;
border:none;
border-radius:8px;
background:#e8e3df;
cursor:pointer;
}

.section{
display:none;
animation:fade 1.5s;
}

@keyframes fade{
from{opacity:0;}
to{opacity:1;}
}
</style>

<script>
function show(id){
document.querySelectorAll('.section').forEach(s=>s.style.display='none');
document.getElementById(id).style.display='block';
}
</script>

</head>

<body>

<div class="container">

<audio autoplay loop controls>
<source src="song.mp3" type="audio/mpeg">
</audio>

<div id="start">
<h2>Our Story</h2>
<p>Click slowly… this is everything I wanted to say 🤍</p>
<button onclick="show('s1')">Start</button>
</div>

<div id="s1" class="section">
<h3>First Impression</h3>
<p>You were good looking… and extremely talkative 😌</p>
<img src="pic1.jpeg">
<button onclick="show('s2')">Next</button>
</div>

<div id="s2" class="section">
<h3>Why I Fell In Love</h3>
<p>You made time for me even when life was busy.</p>
<img src="pic2.jpeg">
<button onclick="show('s3')">Next</button>
</div>

<div id="s3" class="section">
<h3>The Cutest Thing</h3>
<p>You stayed when things were messy… and took care of me.</p>
<img src="pic3.jpeg">
<button onclick="show('s4')">Next</button>
</div>

<div id="s4" class="section">
<h3>Our Memories</h3>
<p>Cooking. Surprises. Ordinary days that became special.</p>
<img src="pic4.jpeg">
<button onclick="show('s5')">Next</button>
</div>

<div id="s5" class="section">
<h3>The Guitar</h3>
<p>I couldn’t get it… but I remembered everything you liked.</p>
<img src="pic5.jpeg">
<button onclick="show('s6')">Next</button>
</div>

<div id="s6" class="section">
<h3>A Letter</h3>
<p>I loved you honestly. I showed up with my whole heart.</p>
<img src="pic6.jpeg">
<button onclick="show('s7')">Final Page</button>
</div>

<div id="s7" class="section">
<h3>Final Goodbye</h3>
<p>
I loved you in the best way I knew how.<br>
But somewhere along the way… my heart broke.<br><br>
So as my final act of love… I’m removing myself quietly.<br>
Our first Valentine’s Day will remain unfinished.<br>
I only ever wanted to love you.
</p>
<img src="pic7.jpeg">
</div>

</div>
</body>
</html>
