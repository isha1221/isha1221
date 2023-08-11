<div style="position: relative;">
  <div style="width: 80px; height: 80px; position: relative;">
    <div style="width: 50%; height: 45%; background: linear-gradient(45deg, gray, rgb(239, 240, 228)); border-radius: 70% 70% 65% 65%; top: 10%; left: 25%; z-index: 1;">
      <div style="width: 60%; height: 70%; background-color: white; border-radius: 70% 70% 60% 60%; top: 15%; left: 5%;"></div>
      <div style="width: 60%; height: 70%; background-color: white; border-radius: 70% 70% 60% 60%; top: 15%; right: 5%;"></div>
      <div style="width: 90%; height: 70%; background-color: white; top: 25%; left: 5%; border-radius: 70% 70% 100% 100%;"></div>
      <div style="width: 15%; height: 17%; background-color: black; top: 45%; left: 25%; border-radius: 50%;"></div>
      <div style="width: 15%; height: 17%; background-color: black; top: 45%; right: 25%; border-radius: 50%;"></div>
      <div style="width: 15%; height: 10%; background-color: pink; top: 65%; left: 15%; border-radius: 50%;"></div>
      <div style="width: 15%; height: 10%; background-color: pink; top: 65%; right: 15%; border-radius: 50%;"></div>
      <div style="height: 10%; background-color: orange; border-radius: 50%; width: 20%; top: 60%; left: 40%;"></div>
      <div style="height: 10%; background-color: orange; border-radius: 50%; width: 16%; top: 65%; left: 42%;"></div>
    </div>
    <div style="width: 53%; height: 45%; background: linear-gradient(45deg, rgb(134, 133, 133) 0%, rgb(234, 231, 231) 25%, white 67%); border-radius: 80% 80% 100% 100%; top: 40%; left: 23.5%;"></div>
    <div style="content: ''; position: absolute; width: 50%; height: 45%; background-color: gray; top: 10%; left: 25%; border-radius: 0% 0% 100% 100%; opacity: 70%;"></div>
    <div style="width: 30%; height: 60%; background: linear-gradient(90deg, gray, rgb(209, 210, 199)); border-radius: 30% 30% 30% 120%; z-index: -1; top: 35%; left: 5%; transform-origin: top left; transform: rotate(130deg) scaleX(-1); animation: 3s linear infinite wave;"></div>
    <div style="width: 15%; height: 30%; background-color: orange; border-radius: 50%; z-index: -1; top: 85%; left: 25%; transform: rotate(80deg);"></div>
    <div style="width: 15%; height: 30%; background-color: orange; border-radius: 50%; z-index: -1; top: 85%; right: 25%; transform: rotate(-80deg);"></div>
  </div>
</div>

<!-- <div class="penguin">
        <div class="penguin-head">
          <div class="face left"></div>
          <div class="face right"></div>
          <div class="chin"></div>
          <div class="eye left">
            <div class="eye-lid"></div>
          </div>
          <div class="eye right">
            <div class="eye-lid"></div>
          </div>
          <div class="blush left"></div>
          <div class="blush right"></div>
          <div class="beak top"></div>
          <div class="beak bottom"></div>
        </div>
        <div class="penguin-body">
          <div class="arm left"></div>
          <div class="arm right"></div>
          <div class="foot left"></div>
          <div class="foot right"></div>
        </div>
      </div>
      <style>
        @media (max-width: 600px) {
    #navbar {
      justify-content: center;
    }}
    .penguin {
        width: 80px;
        height: 80px;
        z-index: 4;
        position: relative;
        transition: transform 1s ease-in-out 0ms;
      }
      .penguin * {
        position: absolute;
      }
      .penguin:active {
        transform: scale(1.5);
        cursor: not-allowed;
      }
      .penguin-head {
        width: 50%;
        height: 45%;
        background: linear-gradient(
          45deg,
          gray,
          rgb(239, 240, 228)
        );
        border-radius: 70% 70% 65% 65%;
        top: 10%;
        left: 25%;
        z-index: 1;
      }
      .face {
        width: 60%;
        height: 70%;
        background-color: white;
        border-radius: 70% 70% 60% 60%;
        top: 15%;
      }
      .face.left {
        left: 5%;
      }
      .face.right {
        right: 5%;
      }
      .chin {
        width: 90%;
        height: 70%;
        background-color: white;
        top: 25%;
        left: 5%;
        border-radius: 70% 70% 100% 100%;
      }
      .eye {
        width: 15%;
        height: 17%;
        background-color: black;
        top: 45%;
        border-radius: 50%;
      }
      .eye.left {
        left: 25%;
      }
      .eye.right {
        right: 25%;
      }
      .eye-lid {
        width: 150%;
        height: 100%;
        background-color: white;
        top: 25%;
        left: -23%;
        border-radius: 50%;
      }
      .blush {
        width: 15%;
        height: 10%;
        background-color: pink;
        top: 65%;
        border-radius: 50%;
      }
      .blush.left {
        left: 15%;
      }
      .blush.right {
        right: 15%;
      }
      .beak {
        height: 10%;
        background-color: orange;
        border-radius: 50%;
      }
      .beak.top {
        width: 20%;
        top: 60%;
        left: 40%;
      }
      .beak.bottom {
        width: 16%;
        top: 65%;
        left: 42%;
      }
      .penguin-body {
        width: 53%;
        height: 45%;
        background: linear-gradient(
          45deg,
          rgb(134, 133, 133) 0%,
          rgb(234, 231, 231) 25%,
          white 67%
        );
        border-radius: 80% 80% 100% 100%;
        top: 40%;
        left: 23.5%;
      }
      .penguin-body::before {
        content: "";
        position: absolute;
        width: 50%;
        height: 45%;
        background-color: gray;
        top: 10%;
        left: 25%;
        border-radius: 0% 0% 100% 100%;
        opacity: 70%;
      }
      .arm {
        width: 30%;
        height: 60%;
        background: linear-gradient(
          90deg,
          gray,
          rgb(209, 210, 199)
        );
        border-radius: 30% 30% 30% 120%;
        z-index: -1;
      }
      .arm.left {
        top: 35%;
        left: 5%;
        transform-origin: top left; 
        transform: rotate(130deg) scaleX(-1);
        animation: 3s linear infinite wave;
      }
      .arm.right {
        top: 0%;
        right: -5%;
        transform: rotate(-45deg);
      }
      @keyframes wave {
        10% {
          transform: rotate(110deg) scaleX(-1);
        }
        20% {
          transform: rotate(130deg) scaleX(-1);
        }
        30% {
          transform: rotate(110deg) scaleX(-1);
        }
        40% {
          transform: rotate(130deg) scaleX(-1);
        }
      }
      .foot {
        width:  15%;
        height: 30%;
        background-color: orange;
        top: 85%;
        border-radius: 50%;
        z-index: -1;
      }
      .foot.left {
        left: 25%;
        transform: rotate(80deg);
      }
      .foot.right {
        right: 25%;
        transform: rotate(-80deg);
      }      
      </style> -->

### Hi there 👋


**isha1221/isha1221** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

