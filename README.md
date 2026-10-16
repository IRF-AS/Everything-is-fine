# Everything-is-fine

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Letter for Jennie ♡</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&family=Patrick+Hand&display=swap');

* { box-sizing: border-box; }

body {
  margin: 0;
  min-height: 100vh;
  padding: 28px 14px;
  background: linear-gradient(145deg,#ffe8f0,#fff5f8,#f9e5ff);
  color: #69475b;
  font-family: 'Quicksand', sans-serif;
  overflow-x: hidden;
}

.heart {
  position: fixed;
  bottom: -30px;
  color: #e8a0be;
  opacity: .7;
  pointer-events: none;
  animation: floatUp 8s linear infinite;
  z-index: 0;
}

@keyframes floatUp {
  from { transform: translateY(0) rotate(0); opacity: 0; }
  15% { opacity: .7; }
  to { transform: translateY(-110vh) rotate(35deg); opacity: 0; }
}

.container {
  position: relative;
  z-index: 1;
  max-width: 680px;
  margin: 0 auto;
  text-align: center;
}

.top {
  padding: 20px 10px 28px;
}

.kicker {
  color: #bd7799;
  letter-spacing: 3px;
  font-size: 11px;
  font-weight: 700;
}

h1 {
  font: 42px 'Patrick Hand', cursive;
  color: #c56891;
  margin: 14px 0 6px;
}

.subtitle {
  font-size: 13px;
  color: #a47b92;
}

.envelope-area {
  margin: 12px auto 26px;
  padding: 26px 16px;
  background: #fff9fc;
  border: 1px solid #f4d1e1;
  border-radius: 25px;
  box-shadow: 0 12px 35px #b96b8b18;
}

.envelope {
  font-size: 83px;
  line-height: 1.4;
  animation: bob 2.5s ease-in-out infinite;
}

@keyframes bob {
  50% { transform: translateY(-7px) rotate(2deg); }
}

.envelope-area p {
  font-size: 14px;
  line-height: 1.7;
}

button {
  border: none;
  border-radius: 30px;
  padding: 13px 23px;
  background: #eaa6c3;
  color: #713e57;
  font: 700 14px 'Quicksand', sans-serif;
  box-shadow: 0 5px 13px #c8799925;
  cursor: pointer;
  transition: transform .2s;
}

button:active { transform: scale(.96); }

#letter {
  display: none;
  text-align: left;
  background: #fffdfb;
  border: 1px solid #f2d5df;
  border-radius: 20px;
  padding: clamp(20px,5vw,38px);
  box-shadow: 0 12px 35px #b96b8b1a;
  line-height: 1.9;
  font-size: 14px;
  animation: appear .7s ease;
}

#letter.show { display: block; }

@keyframes appear {
  from { opacity: 0; transform: translateY(15px); }
  to { opacity: 1; transform: translateY(0); }
}

.letter-title {
  font: 30px 'Patrick Hand', cursive;
  text-align: center;
  color: #c56891;
  margin: 0 0 6px;
}

.date-note {
  text-align: center;
  font-size: 11px;
  color: #bd91a5;
  margin-bottom: 28px;
}

p { margin: 0 0 19px; }

.highlight {
  color: #bb628b;
  font-weight: 700;
}

.signature {
  font: 27px 'Patrick Hand', cursive;
  color: #c56891;
  text-align: center;
  margin-top: 28px;
}

.end {
  text-align: center;
  color: #bd7799;
  font-size: 12px;
  margin: 25px 0 8px;
}

footer {
  padding: 28px 8px 10px;
  text-align: center;
  color: #b1849a;
  font-size: 11px;
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation: none !important;
    transition: none !important;
  }
}
</style>
</head>

<body>

<div class="container">

  <header class="top">
    <div class="kicker">A LITTLE SOMETHING FOR YOU ♡</div>
    <h1>Hey, Jennie! 🌷</h1>
    <div class="subtitle">A tiny letter with a few things to say...</div>
  </header>

  <section class="envelope-area">
    <div class="envelope">💌</div>
    <p>
      Someone has left a little letter for you!<br>
      It contains apologies, silly jokes and a little love. ♡
    </p>
    <button id="openBtn" onclick="openLetter()">
      Open your letter ♡
    </button>
  </section>

  <main id="letter">
    <h2 class="letter-title">Dear Jennie, ♡</h2>
    <div class="date-note">Please read this with a little smile 🌸</div>

    <p>
      Let me tell you something—everything is fine now.
      I spoke to my bro, and somehow, he agreed. Before
      talking to him, I had even prayed to God because
      I was genuinely scared of what might happen if he
      exposed everything.
    </p>

    <p>
      Do you know why? Because if my mother ever found
      out that I was in a relationship or even talking
      to a girl like you, she would be completely shocked.
      I don't know how to explain it, but she trusts me
      so much. According to her, boys and girls can't
      really be friends, and things like love and
      relationships are something she doesn't believe in.
      If she ever found out about you or any of my other
      female friends, I honestly think she would be
      heartbroken. 🥲
      So, thankfully, things are back to normal now.
    </p>

    <p>
      But there's something I genuinely want to ask you:
      <span class="highlight">Why did you even cry for me?</span>
      😭 We've known each other for less than six months,
      and you were already missing me that much? 😏😏😏
      You've never cried for Narcisa, not even Ayu—
      ahem, ahem! (Just kidding, just kidding! 😂)
    </p>

    <p>
      But seriously, I promise I'm not going to make
      any more reckless decisions. And please, don't
      call me out to meet you without warning me first.
      I have a feeling you're going to slap me, and
      honestly, I don't want our first in-person
      interaction to begin like that. 🥲
      So, if you ever ask me to meet you, at least give
      me a heads-up. I might just show up wearing my
      bike helmet for protection! 😭😂
    </p>

    <p>
      On a serious note, I'm genuinely sorry, Jennie,
      that I made you cry. At that moment, I was
      completely overwhelmed and didn't know what to
      think or how to respond. I never wanted to put
      you through that, and I'm truly sorry for making
      you feel that way. ❤️
    </p>

    <p>
      Anyway, please take good care of yourself, get
      some proper rest, and don't overthink things.
      I hope you have a peaceful night. 🌙
    </p>

    <p>
      Good night, Jennie. Stay safe, take care, and
      peace out! ✌🏻❤️
    </p>

    <div class="signature">Tataaa!! ♡</div>
    <div class="end">Sending you a tiny virtual hug 🧸🌷</div>
  </main>

  <footer>
    Made with care, a little chaos & lots of pink ♡
  </footer>

</div>

<script>
function openLetter() {
  const letter = document.getElementById('letter');
  const button = document.getElementById('openBtn');

  letter.classList.add('show');
  button.textContent = 'Your letter is open ♡';
  button.disabled = true;

  setTimeout(() => {
    letter.scrollIntoView({
      behavior: 'smooth',
      block: 'start'
    });
  }, 150);
}

// Gentle floating hearts
for (let i = 0; i < 12; i++) {
  const heart = document.createElement('div');
  heart.className = 'heart';
  heart.textContent = ['♡', '♥', '✧', '💕'][i % 4];
  heart.style.left = (Math.random() * 100) + '%';
  heart.style.animationDelay = (Math.random() * 8) + 's';
  heart.style.animationDuration = (7 + Math.random() * 5) + 's';
  heart.style.fontSize = (14 + Math.random() * 14) + 'px';
  document.body.appendChild(heart);
}
</script>

</body>
</html>
