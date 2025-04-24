<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Информация для школьников о кибермошенничестве. Узнайте, как защитить себя от фишинга, взлома аккаунтов и других угроз в интернете.">
    <meta name="keywords" content="кибермошенничество, школа, фишинг, безопасность, интернет, соцсети, взлом, информационная безопасность, защита детей">
    <title>Кибермошенничество в школе</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #1a1a2e;
            color: #f1f1f1;
            scroll-behavior: smooth;
        }
        header {
            background: #16213e;
            color: #e94560;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #e94560;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background 0.3s, color 0.3s;
        }
        nav a:hover {
            background: rgba(233, 69, 96, 0.3);
            color: #fff;
        }
        section {
            background: #0f3460;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
            margin-bottom: 20px;
        }
        h2 {
            color: #e94560;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #e94560;
            color: white;
            padding: 10px;
            border-radius: 50%;
            text-align: center;
            font-size: 18px;
            cursor: pointer;
            display: none;
        }
        .back-to-top:hover {
            background-color: #ff3366;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            color: #bbb;
        }
        @media screen and (max-width: 600px) {
            body {
                padding: 10px;
            }
            header {
                padding: 15px;
            }
            nav a {
                display: block;
                margin: 10px 0;
            }
            section {
                padding: 15px;
            }
        }
        .quiz-button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            background: #e94560;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
            width: 80%;
            font-size: 16px;
        }
        .quiz-button:hover {
            background: #f06a85;
        }
        #result {
            font-size: 18px;
            color: #e94560;
            display: none;
        }
        #review-container {
            display: none;
            margin-top: 20px;
        }
        .review-item {
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            background: #1a1a2e;
        }
        .correct {
            color: #4CAF50; /* Зеленый */
        }
        .incorrect {
            color: #ff4c4c; /* Красный */
        }
        .explanation {
            display: none;
            margin-top: 5px;
            font-size: 14px;
            color: #ccc;
        }
        .show {
            display: block;
        }
    </style>
</head>
<body>

<header>
    <h1>Кибермошенничество в школе</h1>
</header>

<nav>
    <strong>Содержание:</strong>
    <a href="#section1">Что такое кибермошенничество?</a>
    <a href="#section2">Фишинговые сайты</a>
    <a href="#section3">Обман в соцсетях</a>
    <a href="#section4">Взлом аккаунтов</a>
    <a href="#section5">Просьба денег</a>
    <a href="#section6">Спам-рассылки</a>
    <a href="#section7">Основные правила информационной безопасности</a>
</nav>

<section id="section1">
    <h2>Что такое кибермошенничество?</h2>
    <p>Кибермошенничество — это обман в интернете, целью которого является получение денег или личной информации от жертвы. Мошенники используют различные методы и техники, чтобы манипулировать своими жертвами. Важно понимать, что многие мошенники нацелены на детей и подростков, поскольку они могут быть менее осведомлены о рисках в интернете.</p>
    <p>Основные методы кибермошенников включают:</p>
    <ul>
        <li><strong>Фишинг:</strong> Создание поддельных веб-сайтов или сообщений, которые выглядят как официальные, чтобы получить личные данные.</li>
        <li><strong>Социальная инженерия:</strong> Манипуляция жертвами, чтобы заставить их выдать личные данные.</li>
        <li><strong>Мошенничество через сообщения:</strong> Отправка ложных сообщений, в которых мошенники просят деньги или личную информацию.</li>
    </ul>
</section>

<section id="section2">
    <h2>Фишинговые сайты</h2>
    <p>Фишинговые сайты представляют собой поддельные веб-страницы, которые копируют интерфейс настоящих сайтов, таких как интернет-банки или социальные сети. Их цель — заставить пользователей ввести свои учетные данные, такие как логин и пароль.</p>
    <p><strong>Как распознать фишинговый сайт?</strong></p>
    <ul>
        <li>Проверьте адрес URL. Убедитесь, что он соответствует официальному сайту.</li>
        <li>Обратите внимание на наличие HTTPS в адресе. Если он отсутствует, это может быть признаком фишинга.</li>
        <li>Ищите грамматические ошибки и неаккуратности в тексте. Поддельные сайты часто содержат ошибки.</li>
    </ul>
    <p>Если вы столкнулись с фишинговым сайтом, никогда не вводите свои данные и сообщите об этом взрослым.</p>
</section>

<section id="section3">
    <h2>Обман в соцсетях</h2>
    <p>Социальные сети стали популярным местом для мошенников, которые используют различные способы обмана. Часто они создают поддельные профили, чтобы завести доверительные отношения с жертвами и получить от них личную информацию.</p>
    <p><strong>Как защититься от обмана в соцсетях:</strong></p>
    <ul>
        <li>Будьте осторожны с добавлением незнакомцев в друзья.</li>
        <li>Не делитесь личной информацией, такой как адрес, номер телефона или финансовые данные, с незнакомыми людьми.</li>
        <li>Проверяйте профили людей, которые хотят с вами дружить. Часто мошенники используют фальшивые фотографии и информацию.</li>
    </ul>
    <p>Если кто-то просит вас о деньгах или личной информации, лучше сообщить об этом взрослым и заблокировать такого человека.</p>
</section>

<section id="section4">
    <h2>Взлом аккаунтов</h2>
    <p>Взлом аккаунтов — это еще один распространенный вид мошенничества. Мошенники могут использовать различные методы, чтобы получить доступ к вашим аккаунтам в социальных сетях или онлайн-сервисах.</p>
    <p><strong>Как защититься от взлома:</strong></p>
    <ul>
        <li>Используйте сложные пароли, которые содержат буквы, цифры и специальные символы.</li>
        <li>Не используйте один и тот же пароль для разных аккаунтов.</li>
        <li>Включите двухфакторную аутентификацию, если это возможно. Это добавляет дополнительный уровень безопасности.</li>
    </ul>
    <p>Если вы подозреваете, что ваш аккаунт был взломан, немедленно измените пароль и сообщите об этом в службу поддержки.</p>
</section>

<section id="section5">
    <h2>Просьба денег</h2>
    <p>Мошенники часто пытаются выманить деньги у своих жертв через различные методы, включая сообщения, электронные письма или звонки. Они могут притворяться знакомыми, друзьями или даже членами семьи.</p>
    <p><strong>Как защититься от просьбы о деньгах:</strong></p>
    <ul>
        <li>Никогда не отправляйте деньги незнакомым людям, даже если они говорят, что находятся в трудной ситуации.</li>
        <li>Если кто-то просит вас о деньгах, всегда обсуждайте это с родителями или другими взрослыми.</li>
        <li>Не передавайте личные данные, такие как номер карты или банковскую информацию.</li>
    </ul>
    <p>Помните, что настоящие друзья никогда не будут просить вас о деньгах через интернет.</p>
</section>

<section id="section6">
    <h2>Спам-рассылки</h2>
    <p>Спам-рассылки — это нежелательные сообщения, которые могут содержать рекламу или попытки обмана. Часто такие сообщения приходят на электронную почту или в мессенджеры.</p>
    <p><strong>Как защититься от спама:</strong></p>
    <ul>
        <li>Не открывайте сообщения от незнакомых отправителей.</li>
        <li>Не переходите по ссылкам в спам-сообщениях.</li>
        <li>Используйте фильтры спама в почтовых сервисах для автоматической блокировки нежелательных сообщений.</li>
    </ul>
    <p>Если вы получаете много спама, рассмотрите возможность изменения адреса электронной почты.</p>
</section>

<section id="section7">
    <h2>Основные правила информационной безопасности для школьников</h2>
    <p>Чтобы защитить себя в интернете, следуйте этим простым правилам:</p>
    <ul>
        <li>Используйте надежные пароли и меняйте их регулярно.</li>
        <li>Не делитесь личной информацией с незнакомыми людьми.</li>
        <li>Обсуждайте с родителями любые подозрительные сообщения или ситуации.</li>
        <li>Не открывайте подозрительные ссылки и вложения.</li>
        <li>Регулярно обновляйте свои устройства и программы для защиты от вредоносных программ.</li>
        <li>Помните, что безопасность в интернете — это ваша ответственность!</li>
    </ul>
</section>
<section id="quiz-container">
    <h2>Интерактивный тест</h2>
    <p id="question"></p>
    <div id="options"></div>
    <p id="result"></p>
    <button id="review-button" class="quiz-button" style="display:none;">Посмотреть ответы</button>
</section>

<section id="review-container">
    <h2>Ваши ответы</h2>
    <div id="review"></div>
</section>

<script>
    document.addEventListener("DOMContentLoaded", function () {
        const questions = [
            {
                question: "Как распознать фишинговое письмо?",
                options: ["Если письмо пришло от знакомого", "Если письмо содержит подозрительные ссылки и ошибки", "Если письмо обещает выигрыш"],
                answer: 1,
                explanation: "Фишинговые письма часто содержат ошибки, подозрительные ссылки и просьбы ввести данные."
            },
            {
                question: "Что делать, если вас взломали?",
                options: ["Игнорировать", "Сменить пароль и сообщить в поддержку", "Удалить аккаунт"],
                answer: 1,
                explanation: "Немедленно смените пароль, включите 2FA и сообщите в поддержку."
            },
            {
                question: "Что нельзя делать в соцсетях?",
                options: ["Добавлять незнакомцев", "Писать друзьям", "Ставить лайки"],
                answer: 0,
                explanation: "Добавление незнакомцев может привести к утечке данных и мошенничеству."
            },
            {
                question: "Как создать надежный пароль?",
                options: ["Только цифры", "Буквы, цифры и символы", "Имя питомца"],
                answer: 1,
                explanation: "Надежный пароль должен содержать заглавные и строчные буквы, цифры и символы."
            },
            {
                question: "Как защитить аккаунт?",
                options: ["Использовать 2FA", "Не менять пароль", "Публиковать личные данные"],
                answer: 0,
                explanation: "Двухфакторная аутентификация значительно снижает риск взлома."
            },
            {
                question: "Как избежать вирусов?",
                options: ["Скачивать файлы с подозрительных сайтов", "Не обновлять антивирус", "Не открывать неизвестные файлы"],
                answer: 2,
                explanation: "Не скачивайте подозрительные файлы и используйте антивирус."
            },
            {
                question: "Какой признак мошенничества?",
                options: ["Письмо с просьбой срочно перевести деньги", "Сообщение от друга", "Уведомление от банка"],
                answer: 0,
                explanation: "Мошенники часто требуют срочного перевода денег."
            },
            {
                question: "Что делать, если вам угрожают в сети?",
                options: ["Игнорировать", "Сообщить в полицию", "Удалить аккаунт"],
                answer: 1,
                explanation: "Угрозы в интернете — серьезное преступление, сообщите в полицию."
            },
            {
                question: "Как не попасть на фальшивый сайт?",
                options: ["Перейти по незнакомой ссылке", "Проверить URL", "Ввести логин и пароль"],
                answer: 1,
                explanation: "Проверяйте URL и не вводите данные на подозрительных сайтах."
            },
            {
                question: "Что делать при подозрительном звонке от банка?",
                options: ["Сказать все данные", "Положить трубку и перезвонить в банк", "Перевести деньги"],
                answer: 1,
                explanation: "Никогда не сообщайте данные по телефону, перезвоните в банк."
            }
        ];

        let currentQuestion = 0;
        let correctAnswers = 0;
        let userAnswers = [];
        const questionEl = document.getElementById("question");
        const optionsEl = document.getElementById("options");
        const resultEl = document.getElementById("result");
        const reviewButton = document.getElementById("review-button");
        const reviewContainer = document.getElementById("review-container");
        const reviewEl = document.getElementById("review");

        function loadQuestion() {
            if (currentQuestion >= questions.length) {
                questionEl.style.display = "none";
                optionsEl.style.display = "none";
                resultEl.style.display = "block";
                resultEl.innerText = `Вы ответили правильно на ${correctAnswers} из ${questions.length} вопросов!`;
                reviewButton.style.display = "block";
                return;
            }

            questionEl.innerText = questions[currentQuestion].question;
            optionsEl.innerHTML = "";

            questions[currentQuestion].options.forEach((option, index) => {
                const button = document.createElement("button");
                button.innerText = option;
                button.classList.add("quiz-button");
                button.dataset.index = index;
                button.addEventListener("click", () => checkAnswer(index));
                optionsEl.appendChild(button);
            });
        }

        function checkAnswer(selectedIndex) {
            userAnswers.push(selectedIndex);
            if (selectedIndex === questions[currentQuestion].answer) {
                correctAnswers++;
            }
            currentQuestion++;
            loadQuestion();
        }

        reviewButton.addEventListener("click", function () {
            reviewContainer.style.display = "block";
            reviewEl.innerHTML = "";
            questions.forEach((q, i) => {
                reviewEl.innerHTML += `
                    <div class="review-item">
                        <p><strong>${q.question}</strong></p>
                        <p>Ваш ответ: <span class="${userAnswers[i] === q.answer ? "correct" : "incorrect"}">${q.options[userAnswers[i]]}</span></p>
                        <p>Правильный ответ: <span class="correct">${q.options[q.answer]}</span></p>
                        <p class="explanation show">${q.explanation}</p>
                    </div>`;
            });
        });

        loadQuestion();
    });
</script>



<style>
    #quiz-container {
        margin: 20px 0;
        padding: 15px;
        background: #16213e;
        border-radius: 8px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        text-align: center;
    }
    .quiz-button {
        display: block;
        margin: 10px auto;
        padding: 10px;
        background: #e94560;
        color: white;
        border: none;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.3s;
        width: 80%;
    }
    .quiz-button:hover {
        background: #f06a85;
    }
    #result {
        text-align: center;
        font-size: 18px;
        color: #e94560;
    }
</style>
<section id="section9">
    <h2>Инфографика</h2>
    <p>Информативные плакаты и схемы, объясняющие правила безопасного поведения в интернете.</p>

    <div class="infographic">
        <h3>5 правил для защиты от мошенников</h3>
        <img src="https://xoronxojskoe-r81.gosweb.gosuslugi.ru/netcat_files/37/49/pamyatka_po_profilaktike_ITT_prestupleniy.jpg" alt="5 правил для защиты от мошенников">
    </div>

    <div class="infographic">
        <h3>Как создать надежный пароль?</h3>
        <img src="https://sun9-31.userapi.com/impg/fC-3IF2NVG4IKmhXSzVIUbsm3sUcaOZO7wT8Wg/WlR3GbUf7yw.jpg?size=604x437&quality=95&sign=d47a6508a840ebaa11a25a5fcd698f4d&type=album" alt="Как создать надежный пароль">
    </div>
</section>

<section id="section10">
    <h2>Часто задаваемые вопросы (FAQ)</h2>
    <p>Ответы на популярные вопросы о кибермошенничестве:</p>

    <div class="faq">
        <h3>Что такое фишинг?</h3>
        <p>Фишинг — это метод кибермошенничества, при котором злоумышленники создают поддельные сайты или отправляют мошеннические письма с целью кражи личных данных.</p>
    </div>

    <div class="faq">
        <h3>Как защитить свой аккаунт в социальных сетях?</h3>
        <p>Используйте сложные пароли, включите двухфакторную аутентификацию и не передавайте данные посторонним.</p>
    </div>

    <div class="faq">
        <h3>Куда обращаться, если меня обманули?</h3>
        <p>Сообщите об инциденте родителям, учителям или в полицию. Также можно обратиться в службу поддержки соответствующего онлайн-сервиса.</p>
    </div>
</section>

<script>
    function checkAnswer(button, isCorrect) {
        if (isCorrect) {
            button.style.backgroundColor = "green";
            alert("Правильно!");
        } else {
            button.style.backgroundColor = "red";
            alert("Неправильно, попробуйте снова.");
        }
    }
</script>

<style>
    .quiz {
        margin: 20px 0;
        padding: 15px;
        background: #16213e;
        border-radius: 8px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    }
    .quiz button {
        display: block;
        margin: 5px 0;
        padding: 10px;
        background: #e94560;
        color: white;
        border: none;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.3s;
    }
    .quiz button:hover {
        background: #f06a85;
    }
    .infographic, .faq {
        margin: 20px 0;
        padding: 15px;
        background: #16213e;
        border-radius: 8px;
        text-align: center;
        box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    }
    .infographic img {
        width: 100%;
        max-width: 600px;
        border-radius: 5px;
    }
    .faq h3 {
        color: #e94560;
    }
</style>

<footer>
    <p>&copy; 2025 Обучение безопасности в интернете</p>
</footer>

<!-- Кнопка "Наверх" -->
<div class="back-to-top" onclick="scrollToTop()">&#9650;</div>

<script>
    // Показать кнопку "Наверх" при прокрутке
    window.onscroll = function() {
        var backToTop = document.querySelector('.back-to-top');
        if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
            backToTop.style.display = 'block';
        } else {
            backToTop.style.display = 'none';
        }
    };

    // Прокрутка наверх
    function scrollToTop() {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }
</script>

</body>
</html>
