<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Be My Valentine 💘</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* { box-sizing:border-box; font-family:Arial,sans-serif; }

body{
margin:0;
background:linear-gradient(135deg,#ff6f91,#ff9a9e);
color:white;
overflow:hidden;
}

/* pages */
.page{
display:none;
min-height:100vh;
padding:40px 20px 160px;
text-align:center;
}
.page.active{display:block}

/* indicator */
.indicator{
position:fixed;
bottom:20px;
left:50%;
transform:translateX(-50%);
width:90%;
max-width:420px;
background:rgba(255,255,255,0.2);
backdrop-filter:blur(12px);
border-radius:20px;
padding:18px;
box-shadow:0 15px 30px rgba(0,0,0,0.3);
}
.indicator h2{
margin:0 0 10px;
font-size:1.5rem;
}
.progress{
height:16px;
background:rgba(255,255,255,0.4);
border-radius:10px;
overflow:hidden;
}
.progress-bar{
height:100%;
width:0%;
background:linear-gradient(90deg,#ff4d6d,#ff85a2);
transition:width .5s;
}

/* buttons */
button{
padding:14px 30px;
border:none;
border-radius:40px;
font-size:1.1rem;
cursor:pointer;
transition:.2s;
}
button:active{
transform:scale(1.25,.8) rotate(-3deg);
}

.heart{background:#ff4d6d;color:white}
.broken{background:white;color:#ff4d6d}

/* floating */
.floating{
position:fixed;
bottom:-40px;
font-size:28px;
animation:floatUp 4s forwards ease-out;
pointer-events:none;
}
@keyframes floatUp{
to{transform:translateY(-110vh);opacity:0}
}

/* quiz */
input{
padding:12px;
border:none;
border-radius:12px;
font-size:1rem;
width:80%;
}

/* chaos page */
.yes-grid{
position:relative;
width:100%;
height:70vh;
}
.yes-grid button{
position:absolute;
}

.love-wall{
position:fixed;
inset:0;
opacity:.15;
font-size:1.2rem;
pointer-events:none;
}
</style>
</head>

<body>

<div class="indicator">
<h2>💘 Valentine’s Readiness Indicator 💘</h2>
<div class="progress">
<div class="progress-bar" id="progress"></div>
</div>
</div>

<!-- PAGE 1 -->
<div class="page active" id="page1">
<h1>Dear Maddelyn,<br>Will you be my Valentine? 💘</h1>

<div style="margin-top:60px;height:240px;position:relative;">
<button id="yesBtn" class="heart">Yes ❤️</button>
<button id="noBtn" class="broken" style="position:absolute;">No 💔</button>
</div>
</div>

<!-- PAGE 2 QUIZ -->
<div class="page" id="page2">
<h1>Let’s see if you are REALLY good enough to be my Valentine 🤔</h1>

<p id="question"></p>

<input id="answer">

<p id="feedback"></p>

</div>

<!-- PAGE 3 EVENING -->
<div class="page" id="page3">

<h1>What would I choose for a perfect evening?</h1>

<button onclick="eveningPick()">Fancy restaurant</button><br><br>
<button onclick="eveningPick()">Home cooking and movie</button><br><br>
<button onclick="eveningPick()">Picnic outside</button><br><br>
<button onclick="eveningPick()">Spending the night cuddling and fucking (rough!! ;) with you like there’s no tomorrow</button>

</div>

<!-- PAGE 4 PLEDGE -->
<div class="page" id="page4">

<h1>Now say it:</h1>

<p>I, Maddelyn, faithfully swear that I would like to be Lukas Valentine</p>

<input id="pledge">

<br><br>

<button onclick="checkPledge()">Submit</button>

</div>

<!-- PAGE 5 CHAOS -->
<div class="page" id="page5">

<div class="love-wall" id="loveWall"></div>

<h1>So… will you be my Valentine?? 💘</h1>

<div class="yes-grid" id="yesGrid"></div>

</div>

<!-- PAGE 6 FINAL -->
<div class="page" id="page6">

<h1>YAAAAAY 💖💘</h1>

<p>
The prettiest girl on the planet is my Valentine ❤️💘<br><br>
See you tomorrow, my love &lt;3
</p>

</div>

<script>

/* progress */
let progress=0
function updateProgress(){
progress+=20
document.getElementById("progress").style.width=progress+"%"
}

/* navigation */
function nextPage(n){
document.querySelector(".page.active").classList.remove("active")
document.getElementById("page"+n).classList.add("active")
updateProgress()
}

/* floating kisses */
function floatKisses(){
for(let i=0;i<20;i++){
let e=document.createElement("div")
e.className="floating"
e.textContent=Math.random()>0.5?"💋 bisous":"💋 үнсэлт"
e.style.left=Math.random()*100+"vw"
document.body.appendChild(e)
setTimeout(()=>e.remove(),5000)
}
}

/* praise bubble */
function floatPraise(){
for(let i=0;i<6;i++){
let e=document.createElement("div")
e.className="floating"
e.textContent="good girl 😏💦"
e.style.left=Math.random()*100+"vw"
document.body.appendChild(e)
setTimeout(()=>e.remove(),5000)
}
}

/* PAGE 1 */
const yesBtn=document.getElementById("yesBtn")
yesBtn.onmouseover=()=>yesBtn.textContent="Maybe 🤔"
yesBtn.onmouseout=()=>yesBtn.textContent="Yes ❤️"
yesBtn.onclick=()=>{
floatKisses()
setTimeout(()=>nextPage(2),1000)
}

const noBtn=document.getElementById("noBtn")
noBtn.onmouseover=()=>{
noBtn.style.left=Math.random()*90+"vw"
noBtn.style.top=Math.random()*80+"vh"
}

/* QUIZ */
const questions=[
{q:"What is my favorite cuisine?",a:["indian"]},
{q:"What is my favorite video game?",a:["league of legends"]},
{q:"What is my favourite movie?",a:["forest gump","inception","shawshank redemption","the shawshank redemption","12 angry men","the lord of the rings","gladiator","the prestige","the intouchables"]},
{q:"What is my favourite sport?",a:["tennis","padel"]},
{q:"Where was our very first date?",a:["isshin","restaurant isshin"]}
]

let qi=0,fails=0

function loadQuestion(){
document.getElementById("question").textContent=questions[qi].q
document.getElementById("answer").value=""
}

loadQuestion()

document.getElementById("answer").addEventListener("change",()=>{
let val=document.getElementById("answer").value.trim().toLowerCase()

if(questions[qi].a.includes(val)){
floatPraise()
fails=0
qi++

if(qi>=questions.length){
setTimeout(()=>nextPage(3),1000)
}
else loadQuestion()
}
else{
fails++
if(fails>=3){
document.getElementById("feedback").textContent="Answer: "+questions[qi].a[0]
fails=0
qi++
qi>=questions.length?nextPage(3):loadQuestion()
}
}
})

/* page 3 */
function eveningPick(){
floatPraise()
setTimeout(()=>nextPage(4),1000)
}

/* page 4 */
function checkPledge(){
let val=document.getElementById("pledge").value.toLowerCase()
if(val.includes("maddelyn")){
nextPage(5)
}
}

/* chaos buttons */
let grid=document.getElementById("yesGrid")

for(let i=0;i<80;i++){

let b=document.createElement("button")

b.textContent=Math.random()>0.75?"Creampie and make me your girl 💕":"Yes ❤️"

b.style.left=Math.random()*90+"%"
b.style.top=Math.random()*90+"%"

grid.appendChild(b)

setInterval(()=>{
b.style.left=Math.random()*90+"%"
b.style.top=Math.random()*90+"%"
},800)

b.onclick=()=>nextPage(6)

}

/* love wall */
document.getElementById("loveWall").innerHTML="love ".repeat(600)

</script>

</body>
</html>
