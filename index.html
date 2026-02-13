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
  padding:40px 20px 190px;
  text-align:center;
}
.page.active{display:block}

/* ---------- DYNAMIC TEXT / EMOJI ANIMATIONS ---------- */
.breathe {
  animation: breathe 2.8s ease-in-out infinite;
}
@keyframes breathe {
  0%, 100% { transform: scale(1); filter: drop-shadow(0 0 0 rgba(255,255,255,0)); }
  50% { transform: scale(1.03); filter: drop-shadow(0 6px 10px rgba(0,0,0,0.15)); }
}

.pulse {
  animation: pulse 1.1s ease-in-out infinite;
}
@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.12); }
}

.wiggle {
  display: inline-block;
  animation: wiggle 1.8s ease-in-out infinite;
}
@keyframes wiggle {
  0%, 100% { transform: rotate(-2deg) translateY(0); }
  50% { transform: rotate(2deg) translateY(-3px); }
}

.glow {
  text-shadow:
    0 0 10px rgba(255,255,255,0.25),
    0 0 24px rgba(255, 77, 109, 0.25);
}

.floaty-hearts {
  margin-top: 10px;
  font-size: 1.6rem;
  opacity: 0.95;
}
.floaty-hearts span {
  display:inline-block;
  margin: 0 4px;
  animation: floatHeart 2.6s ease-in-out infinite;
}
.floaty-hearts span:nth-child(2){ animation-delay: .2s; }
.floaty-hearts span:nth-child(3){ animation-delay: .4s; }
.floaty-hearts span:nth-child(4){ animation-delay: .6s; }
.floaty-hearts span:nth-child(5){ animation-delay: .8s; }

@keyframes floatHeart {
  0%, 100% { transform: translateY(0) scale(1); opacity: .9; }
  50% { transform: translateY(-10px) scale(1.15); opacity: 1; }
}
/* ---------------------------------------------------- */

/* indicator */
.indicator{
  position:fixed;
  bottom:20px;
  left:50%;
  transform:translateX(-50%);
  width:90%;
  max-width:460px;
  background:rgba(255,255,255,0.22);
  backdrop-filter:blur(12px);
  border-radius:22px;
  padding:18px 18px 16px;
  box-shadow:0 18px 36px rgba(0,0,0,0.30);
  border: 1px solid rgba(255,255,255,0.18);
}
.indicator h2{
  margin:0 0 10px;
  font-size:1.6rem;     /* bigger */
}
.progress{
  height:16px;
  background:rgba(255,255,255,0.45);
  border-radius:10px;
  overflow:hidden;
}
.progress-bar{
  height:100%;
  width:0%;
  background:linear-gradient(90deg,#ff4d6d,#ff85a2);
  transition:width .5s ease;
}

/* buttons */
button{
  padding:14px 30px;
  border:none;
  border-radius:40px;
  font-size:1.1rem;
  cursor:pointer;
  transition:transform .2s ease, filter .2s ease;
}
button:hover { filter: brightness(1.05); }
button:active{
  transform:scale(1.25,.82) rotate(-3deg);
}

.heart{background:#ff4d6d;color:white}
.broken{background:white;color:#ff4d6d}

/* floating bubbles */
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
  opacity:.16;
  font-size:1.25rem;
  pointer-events:none;
  line-height: 1.65;
  transform: rotate(-2deg);
}

/* keep content above love-wall */
#page5 h1, #page5 .yes-grid { position: relative; z-index: 2; }
</style>
</head>

<body>

<div class="indicator breathe">
  <h2 class="glow">💘 Valentine’s Readiness Indicator 💘</h2>
  <div class="progress"><div class="progress-bar" id="progress"></div></div>
</div>

<!-- PAGE 1 -->
<div class="page active" id="page1">
  <h1 class="breathe glow">Dear Maddelyn,<br>Will you be my Valentine? 💘</h1>

  <div class="floaty-hearts">
    <span>💗</span><span>💞</span><span>💖</span><span>💘</span><span>❤️</span>
  </div>

  <div style="margin-top:55px;height:260px;position:relative;">
    <button id="yesBtn" class="heart">Yes ❤️</button>
    <button id="noBtn" class="broken" style="position:absolute;">No 💔</button>
  </div>
</div>

<!-- PAGE 2 QUIZ -->
<div class="page" id="page2">
  <h1 class="breathe glow">Let’s see if you are REALLY good enough to be my Valentine 🤔</h1>

  <div class="floaty-hearts">
    <span class="pulse">💘</span><span>💖</span><span class="pulse">💞</span><span>❤️</span>
  </div>

  <p id="question" class="breathe"></p>
  <input id="answer">
  <p id="feedback"></p>
</div>

<!-- PAGE 3 EVENING -->
<div class="page" id="page3">
  <h1 class="breathe glow">What would I choose for a perfect evening?</h1>

  <div class="floaty-hearts">
    <span>💗</span><span class="pulse">💞</span><span>💖</span><span class="pulse">💘</span>
  </div>

  <div style="margin-top:30px;">
    <button onclick="eveningPick()">Fancy restaurant</button><br><br>
    <button onclick="eveningPick()">Home cooking and movie</button><br><br>
    <button onclick="eveningPick()">Picnic outside</button><br><br>
    <button onclick="eveningPick()">Spending the night cuddling and fucking (rough !! ;)) like there’s no tomorrow</button>
  </div>
</div>

<!-- PAGE 4 PLEDGE -->
<div class="page" id="page4">
  <h1 class="breathe glow">Now say it:</h1>

  <div class="floaty-hearts">
    <span>💖</span><span class="pulse">💘</span><span>💞</span><span class="pulse">❤️</span>
  </div>

  <p class="breathe">I, Maddelyn, faithfully swear that I would like to be Lukas Valentine</p>
  <input id="pledge">
  <br><br>
  <button onclick="checkPledge()">Submit</button>
</div>

<!-- PAGE 5 CHAOS -->
<div class="page" id="page5">
  <div class="love-wall" id="loveWall"></div>

  <h1 class="breathe glow">So… will you be my Valentine?? 💘</h1>

  <div class="floaty-hearts" style="position:relative; z-index:2;">
    <span class="pulse">💘</span><span>💖</span><span class="pulse">💞</span><span>❤️</span><span class="pulse">💗</span>
  </div>

  <div class="yes-grid" id="yesGrid"></div>
</div>

<!-- PAGE 6 FINAL -->
<div class="page" id="page6">
  <h1 class="pulse glow" style="font-size:3.2rem;">YAAAAAY 💖💘</h1>

  <div class="floaty-hearts" style="font-size:2rem;">
    <span class="pulse">❤️</span><span class="pulse">💖</span><span class="pulse">💘</span><span class="pulse">💞</span><span class="pulse">💗</span>
  </div>

  <p class="breathe" style="margin-top:25px;font-size:1.2rem;">
    The prettiest girl on the planet is my Valentine ❤️💘<br><br>
    See you tomorrow, my love &lt;3
  </p>
</div>

<script>
/* progress */
let progress=0;
function updateProgress(){
  progress+=20;
  document.getElementById("progress").style.width=progress+"%";
}

/* navigation */
function nextPage(n){
  document.querySelector(".page.active").classList.remove("active");
  document.getElementById("page"+n).classList.add("active");
  updateProgress();
}

/* floating kisses */
function floatKisses(){
  for(let i=0;i<20;i++){
    const e=document.createElement("div");
    e.className="floating";
    e.textContent=Math.random()>0.5?"💋 bisous":"💋 үнсэлт";
    e.style.left=Math.random()*100+"vw";
    e.style.animationDuration=(3+Math.random()*2)+"s";
    document.body.appendChild(e);
    setTimeout(()=>e.remove(),5000);
  }
}

/* praise bubble (kept from earlier version) */
function floatPraise(){
  for(let i=0;i<6;i++){
    const e=document.createElement("div");
    e.className="floating";
    e.textContent="good girl 😏💦";
    e.style.left=Math.random()*100+"vw";
    e.style.animationDuration=(3+Math.random()*2)+"s";
    document.body.appendChild(e);
    setTimeout(()=>e.remove(),5000);
  }
}

/* PAGE 1 */
const yesBtn=document.getElementById("yesBtn");
yesBtn.onmouseover=()=>yesBtn.textContent="Maybe 🤔";
yesBtn.onmouseout=()=>yesBtn.textContent="Yes ❤️";
yesBtn.onclick=()=>{
  floatKisses();
  setTimeout(()=>nextPage(2),1000);
};

const noBtn=document.getElementById("noBtn");
/* more drastic movement across whole page */
noBtn.onmouseover=()=>{
  noBtn.style.left=Math.random()*95+"vw";
  noBtn.style.top=Math.random()*85+"vh";
};
noBtn.onmousemove=()=>{
  noBtn.style.left=Math.random()*95+"vw";
  noBtn.style.top=Math.random()*85+"vh";
};

/* QUIZ */
const questions=[
  {q:"What is my favorite cuisine?",a:["indian"]},
  {q:"What is my favorite video game?",a:["league of legends"]},
  {q:"What is my favourite movie?",a:["forest gump","inception","shawshank redemption","the shawshank redemption","12 angry men","the lord of the rings","gladiator","the prestige","the intouchables"]},
  {q:"What is my favourite sport?",a:["tennis","padel"]},
  {q:"Where was our very first date?",a:["isshin","restaurant isshin"]}
];

let qi=0,fails=0;

function loadQuestion(){
  document.getElementById("question").textContent=questions[qi].q;
  document.getElementById("answer").value="";
  document.getElementById("feedback").textContent="";
}
loadQuestion();

document.getElementById("answer").addEventListener("change",()=>{
  const val=document.getElementById("answer").value.trim().toLowerCase();

  if(questions[qi].a.includes(val)){
    floatPraise();
    fails=0;
    qi++;

    if(qi>=questions.length){
      floatKisses(); /* celebration after quiz */
      setTimeout(()=>nextPage(3),1100);
    } else {
      loadQuestion();
    }
  } else {
    fails++;
    if(fails>=3){
      document.getElementById("feedback").textContent="Answer: "+questions[qi].a[0];
      fails=0;
      qi++;
      if(qi>=questions.length){
        setTimeout(()=>nextPage(3),900);
      } else {
        loadQuestion();
      }
    } else {
      document.getElementById("feedback").textContent="Try again 😈";
    }
  }
});

/* page 3 */
function eveningPick(){
  floatPraise();
  setTimeout(()=>nextPage(4),900);
}

/* page 4 */
function checkPledge(){
  const val=document.getElementById("pledge").value.toLowerCase();
  if(val.includes("maddelyn")){
    floatPraise();
    setTimeout(()=>nextPage(5),700);
  }
}

/* chaos buttons */
const grid=document.getElementById("yesGrid");
for(let i=0;i<80;i++){
  const b=document.createElement("button");
  b.textContent=Math.random()>0.75?"Creampie and make me yours 💕":"Yes ❤️";
  b.style.left=Math.random()*90+"%";
  b.style.top=Math.random()*90+"%";
  grid.appendChild(b);

  setInterval(()=>{
    b.style.left=Math.random()*90+"%";
    b.style.top=Math.random()*90+"%";
  },800);

  b.onclick=()=>{
    floatKisses();
    setTimeout(()=>nextPage(6),700);
  };
}

/* love wall */
document.getElementById("loveWall").innerHTML="love ".repeat(700);
</script>

</body>
</html>
