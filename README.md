# NOPROBLEM.ithub.io
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NO PROBLEM - Качественные отделочные работы</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Шапка */
        header {
            background: #333;
            color: white;
            padding: 1rem;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
        }

        /* Герой-секция */
        .hero {
            background: url('https://via.placeholder.com/1920x600') center/cover;
            height: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }

        .hero-content {
            background: rgba(0, 0, 0, 0.6);
            padding: 2rem;
        }

        /* Секции */
        .section {
            padding: 4rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            border: 1px solid #ddd;
            padding: 1.5rem;
            text-align: center;
        }

        /* Галерея */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }

        .portfolio-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        /* Футер */
        footer {
            background: #333;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }

        /* Адаптивность */
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero {
                height: 400px;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ПрофиРемонт</div>
            <div class="nav-links">
                <a href="#services">Услуги</a>
                <a href="#portfolio">Портфолио</a>
                <a href="#reviews">Отзывы</a>
                <a href="#contact">Контакты</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Профессиональные отделочные работы</h1>
            <p>Качественный ремонт под ключ с гарантией</p>
            <button style="margin-top: 1rem; padding: 0.8rem 2rem; background: #ff4d4d; border: none; color: white;">
                Заказать звонок
            </button>
        </div>
    </section>

    <section id="services" class="section">
        <h2>Наши услуги</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Косметический ремонт</h3>
                <p>Обновление интерьера с заменой покрытий</p>
            </div>
            <div class="service-card">
                <h3>Капитальный ремонт</h3>
                <p>Полная перепланировка с заменой коммуникаций</p>
            </div>
            <div class="service-card">
                <h3>Дизайн интерьера</h3>
                <p>Разработка индивидуального дизайн-проекта</p>
            </div>
        </div>
    </section>
<section id="portfolio" class="section">
        <h2>Наши работы</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300x200" alt="Пример работы">
            </div>
            <!--![IMAGE 2025-02-03 01:05:33](https://github.com/user-attachments/assets/34f44d1e-a364-4be3-8ddd-1c14f779b09a)
зображений -->
        </div>
    </section>

    <footer id="contact">
        <h3>Контакты</h3>
        <p>Телефон: +7 (999) 123-45-67</p>
        <p>Email: info@profiremont.ru</p>
        <p>Адрес: г. Москва, ул. Строителей, 15</p>
    </footer>
</body>
</html>
