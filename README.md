<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Капибара Учитель - Обучающий сайт</title>
    <style>
        :root {
            --primary-color: #8B5A2B;
            --secondary-color: #A67C52;
            --light-color: #F5E7D8;
            --accent-color: #6B8E23;
        }
        
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light-color);
            color: #333;
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .capybara-header {
            font-size: 2.5em;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .capybara-icon {
            font-size: 1.5em;
            margin: 0 15px;
        }
        
        nav {
            background-color: var(--secondary-color);
            padding: 10px;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 20px;
            transition: background-color 0.3s;
        }
        
        nav a:hover {
            background-color: var(--primary-color);
        }
        
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        .hero {
            background-image: url('https://example.com/capybara-bg.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            position: relative;
            margin-bottom: 30px;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.4);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            padding: 20px;
        }
        
        .courses {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .course-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .course-card:hover {
            transform: translateY(-5px);
        }
        
        .course-image {
            height: 180px;
            background-color: var(--secondary-color);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 3em;
        }
        
        .course-content {
            padding: 20px;
        }
        
        .course-title {
            margin-top: 0;
            color: var(--primary-color);
        }
        
        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            text-decoration: none;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #556B2F;
        }
        
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
        
        .fun-fact {
            background-color: white;
            border-left: 5px solid var(--accent-color);
            padding: 15px;
            margin: 20px 0;
            border-radius: 0 5px 5px 0;
        }
        
        @media (max-width: 768px) {
            .courses {
                grid-template-columns: 1fr;
            }
            
            .capybara-header {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1 class="capybara-header">
            <span class="capybara-icon">🦫</span>
            Капибара Учитель
            <span class="capybara-icon">🦫</span>
        </h1>
        <p>Обучаем с расслаблением, как капибара в горячем источнике</p>
    </header>
    
    <nav>
        <a href="#">Главная</a>
        <a href="#">Курсы</a>
        <a href="#">О капибарах</a>
        <a href="#">Блог</a>
        <a href="#">Контакты</a>
    </nav>
    
    <div class="container">
        <div class="hero">
            <div class="hero-content">
                <h2>Учитесь легко и с удовольствием</h2>
                <p>Как капибары, которые наслаждаются каждым моментом жизни</p>
                <a href="#" class="btn">Начать обучение</a>
            </div>
        </div>
        
        <div class="fun-fact">
            <h3>Знаете ли вы?</h3>
            <p>Капибары - самые крупные грызуны в мире! Они отличные пловцы и очень социальные животные. Мы взяли их расслабленный подход к жизни за основу нашего стиля обучения.</p>
        </div>
        
        <h2>Наши курсы</h2>
        <div class="courses">
            <div class="course-card">
                <div class="course-image">📚</div>
                <div class="course-content">
                    <h3 class="course-title">Основы программирования</h3>
                    <p>Изучите основы программирования в расслабленной атмосфере, как капибара в теплой воде.</p>
                    <a href="#" class="btn">Узнать больше</a>
                </div>
            </div>
            
            <div class="course-card">
                <div class="course-image">🌿</div>
                <div class="course-content">
                    <h3 class="course-title">Природа и экология</h3>
                    <p>Узнайте о природе и экосистемах, в которых живут капибары и другие удивительные животные.</p>
                    <a href="#" class="btn">Узнать больше</a>
                </div>
            </div>
            
            <div class="course-card">
                <div class="course-image">🧘</div>
                <div class="course-content">
                    <h3 class="course-title">Релаксация и медитация</h3>
                    <p>Научитесь расслабляться как капибара - мастер релаксации и наслаждения моментом.</p>
                    <a href="#" class="btn">Узнать больше</a>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>© 2023 Капибара Учитель. Все права защищены.</p>
        <p>Сайт создан с любовью к капибарам и обучению</p>
        <p>🦫 🦫 🦫</p>
    </footer>
</body>
</html>
