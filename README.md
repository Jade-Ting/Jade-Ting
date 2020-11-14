<head>
    <title>Hi there 👋</title>
    <link href='http://cdn.repository.webfont.com/webfonts/nomal/141932/37509/5faf7910f629d83b80c59d62.css' rel='stylesheet' type='text/css' />
    <style type="text/css">
        div {
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            width: 100%;
            height: 100px;
        }
        label {
            position: absolute;
            width: 16px;
            height: 16px;
            background: hsl(354 81% 62% / 1);
            cursor: grabbing;
            transform: rotate(-45deg);
            animation: scale-out 1s infinite;
        }
        label::before,
        label::after {
            position: absolute;
            content: "";
            width: 100%;
            height: 100%;
            background: inherit;
            border-radius: 50%;
        }
        label::before {
            top: -50%;
        }
        label::after {
            right: -50%;
        }
        p {
            text-align: center;
            font-family:'Malapropism';
        }
        @keyframes scale-out {
            0% {
                transform: scale(1) rotate(-45deg);
            }
            100% {
                transform: scale(1.2) rotate(-45deg);
            }
        }
    </style>
</head>
<body>
    <div>
        <label for="like-toggle" class="heart"> </label>
    </div>
    <p>Hi there 👋</p>
    <p>Nice to meet you.<p/>
</body>  

<!--
**Jade-Ting/Jade-Ting** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
