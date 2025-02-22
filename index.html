
  <!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>هدية مميزة</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    .background-image {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }

    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(255, 255, 255, 0.3);
      z-index: 0;
    }

    .center-point {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: 1;
    }

    .emoji {
      position: absolute;
      font-size: 2rem;
      transform-origin: center;
      pointer-events: none;
      z-index: 2;
    }

    @keyframes explode {
      0% {
        transform: translate(-50%, -50%) scale(0.1) rotate(0deg);
        opacity: 0;
      }
      20% {
        opacity: 1;
      }
      100% {
        transform: translate(var(--tx), var(--ty)) scale(1) rotate(var(--rot));
        opacity: 0;
      }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translate(-50%, -50%) scale(0.8);
      }
      to {
        opacity: 1;
        transform: translate(-50%, -50%) scale(1);
      }
    }

    #message {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 2rem;
      color: #ff1493;
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(255, 20, 147, 0.3);
      display: none;
      font-family: 'Arial', sans-serif;
      z-index: 3;
      opacity: 0;
      animation: fadeIn 2s ease-in-out forwards;
    }

    #audioPlayer {
      display: none;
    }
  </style>
</head>
<body>
  <img class="background-image" src="https://d41chssnpqdne.cloudfront.net/user_upload_by_module/chat_bot/files/26334481/06rRtLthpCv2BnWD.jpeg?Expires=1741454972&Signature=k1iA8O012esopD79Pg6IcPzSLCR363p5NBn4GZeRGycC~LDRH3sb7WwYuf3DIYkAUw5cCsemVZmuf0lZjX0UIt7wrKJIrqEzEpHJGBr1U7XTX7UIqttXGsmpoj-DcxdY5Z44P7Sd8MvW6hETpHt0KG49iZNCsqspf7eoWXxR7fOgdRsIw88sahYscgHemMe8aC4dYdfWOshIeqyffyeScG9dWc6gtuzLHqarPTUip9xMqQHbW0GSL4NijSSkKljq~0d8LK9V6iir8jI6TD86Qn2nJtYHz484YWpcCZYPAD2UFTT9fKFs58xpOEp67TgaEjR8QYGUL2bPb1YpTPT3HA__&Key-Pair-Id=K3USGZIKWMDCSX" alt="تفاصيل الطلب">
  <div class="overlay"></div>
  <div class="center-point"></div>
  <div id="message">هدية زواجنا من زوجك أبو محمد ❤️</div>
  
  <!-- مشغل الصوت -->
  <audio id="audioPlayer">
    <source src="https://i.top4top.io/m_3340pzh8q0.mp3" type="audio/mp3">
  </audio>

  <script>
    const audio = document.getElementById('audioPlayer');
    let animationRunning = true;

    // تشغيل الصوت عند تحميل الصفحة
    window.onload = function() {
      // محاولة تشغيل الصوت تلقائياً
      audio.play().catch(function(error) {
        console.log("لم نتمكن من تشغيل الصوت تلقائياً. يرجى النقر على الصفحة للتشغيل.");
      });

      // تشغيل الصوت عند النقر على الصفحة (في حال منع التشغيل التلقائي)
      document.body.addEventListener('click', function() {
        audio.play();
      }, { once: true });
    };

    // إعادة تشغيل الصوت عند انتهائه
    audio.addEventListener('ended', function() {
      if (document.getElementById('message').style.display === 'block') {
        audio.currentTime = 0;
        audio.play();
      }
    });

    const emojis = ['🎉', '🎁', '💥', '💌', '🎉', '🎁'];
    const centerPoint = document.querySelector('.center-point');

    function createEmoji() {
      if (!animationRunning) return;

      const emoji = document.createElement('div');
      emoji.className = 'emoji';
      emoji.textContent = emojis[Math.floor(Math.random() * emojis.length)];

      const angle = Math.random() * Math.PI * 2;
      const distance = Math.random() * 300 + 100;
      const tx = Math.cos(angle) * distance;
      const ty = Math.sin(angle) * distance;
      const rotation = Math.random() * 720 - 360;

      emoji.style.setProperty('--tx', `${tx}px`);
      emoji.style.setProperty('--ty', `${ty}px`);
      emoji.style.setProperty('--rot', `${rotation}deg`);

      emoji.style.animation = `explode 2s ease-out forwards`;

      centerPoint.appendChild(emoji);

      setTimeout(() => {
        emoji.remove();
      }, 2000);
    }

    const intervalId = setInterval(createEmoji, 200);

    setTimeout(() => {
      animationRunning = false;
      clearInterval(intervalId);
      
      const emojis = document.querySelectorAll('.emoji');
      emojis.forEach(emoji => emoji.remove());
      
      setTimeout(() => {
        const message = document.getElementById('message');
        message.style.display = 'block';
        
        // إعادة تشغيل الصوت عند ظهور الرسالة
        audio.currentTime = 0;
        audio.play();
      }, 1000);
    }, 10000);
  </script>
</body>
</html>
