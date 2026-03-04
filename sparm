<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sparm club</title>
    <!-- استدعاء خط عربي جميل من Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* --- إعدادات عامة --- */
        :root {
            --primary-color: #1c344b; /* لون أساسي داكن */
            --accent-color: #a30a0a;  /* لون مميز أخضر */
            --bg-color: #f9f9f9;
            --text-color: #0c0c0c;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        /* --- القائمة العلوية --- */
        header {
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent-color);
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: bold;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent-color);
        }

        /* --- القسم الرئيسي (Hero) --- */
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('https://source.unsplash.com/1600x900/?school,students');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .btn {
            background-color: var(--accent-color);
            color: white;
            padding: 10px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: #219150;
        }

        /* --- قسم الأخبار --- */
        .news-section {
            padding: 50px 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 30px;
            color: var(--primary-color);
        }

        .news-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .news-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .news-card:hover {
            transform: translateY(-5px);
        }

        .news-img {
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #666;
        }

        .news-content {
            padding: 20px;
        }

        .news-date {
            color: #888;
            font-size: 0.9rem;
        }

        /* --- قسم من نحن --- */
        .about-section {
            background-color: white;
            padding: 50px 5%;
            text-align: center;
        }

        /* --- الفوتر --- */
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }

        /* --- التجاوب مع الجوال --- */
        @media (max-width: 768px) {
            .nav-links {
                display: none; /* يمكن إضافة قائمة منسدلة هنا لاحقاً */
            }
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <!-- القائمة العلوية -->
    <header>
        <nav>
            <div class="logo">SPARM CLUB</div>
            <ul class="nav-links">
                <li><a href="#home">accueil</a></li>
                <li><a href="#news">news</a></li>
                <li><a href="#about">about</a></li>
                <li><a href="#contact">contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- القسم الرئيسي -->
    <section id="home" class="hero">
        <div>
            <h1>bienvenue au club Sparm</h1>
            <p>Le club SPARM est un club scientifique de l’École Supérieure de l’Éducation et de la Formation.</p>
            <a href="#news" class="btn">Nouvelles</a>
        </div>
    </section>

    <!-- قسم الأخبار -->
    <section id="news" class="news-section">
        <h2 class="section-title">dernières nouvelles</h2>
        <div class="news-grid">
            <!-- خبر 1 -->
            <div class="news-card">
                <div class="news-img">صورة الخبر</div>
                <div class="news-content">
                    <span class="news-date">20 أكتوبر 2023</span>
                    <h3>Création de SPARM </h3>
                    <p>تعلن إدارة المدرسة عن انطلاق مسابقة العلوم لهذا العام...</p>
                </div>
            </div>
            <!-- خبر 2 -->
            <div class="news-card">
                <div class="news-img">صورة الخبر</div>
                <div class="news-content">
                    <span class="news-date">15 أكتوبر 2023</span>
                    <h3>فعاليات النادي الثقافي</h3>
                    <p>ندعو جميع الطلاب لحضور ورشة العمل الخاصة بالقراءة...</p>
                </div>
            </div>
            <!-- خبر 3 -->
            <div class="news-card">
                <div class="news-img">صورة الخبر</div>
                <div class="news-content">
                    <span class="news-date">10 أكتوبر 2023</span>
                    <h3>جدول الامتحانات النهائية</h3>
                    <p>تم نشر الجدول الرسمي لامتحانات الفصل الدراسي الأول...</p>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم من نحن -->
    <section id="about" class="about-section">
        <h2 class="section-title">about Sparm</h2>
        <p style="max-width: 800px; margin: 0 auto;">
    Le club SPARM est un club scientifique de l’École Supérieure de l’Éducation et de la Formation. Son nom représente ses principaux domaines d’intérêt :

    S pour Sciences ,
    P pour Physique ,
    A pour Analyse  ,
    R pour Réactions,
    M pour Mathématiques.
    
    Notre club a pour objectif de renforcer l’esprit scientifique chez les étudiants, de développer la coopération entre eux et d’encourager l’excellence académique. Nous organisons des activités pédagogiques, des ateliers scientifiques et des rencontres éducatives dans un cadre dynamique et motivant.

SPARM joue également un rôle important dans l’orientation et la sensibilisation des étudiants, en les accompagnant dans leur parcours universitaire et professionnel. Nous croyons que l’université n’est pas seulement un lieu d’étude, mais un espace de développement personnel et scientifique.

SPARM, c’est un espace d’apprentissage, d’innovation et de partage au service de la science et de l’éducation.
        </p>
    </section>

    <!-- قسم Lego الجديد -->
<section id="lego" class="about-section">
    <h2 class="section-title">قسم Lego في النادي</h2>
    <div class="news-grid">
        <div class="news-card">
            <img src="lego1.jpg" alt="Lego" style="width:100%; height:200px; object-fit:cover;">
            <div class="news-content">
                <h3>بناء النماذج</h3>
                <p>نعمل على بناء نماذج إبداعية باستخدام قطع Lego...</p>
            </div>
        </div>
        <div class="news-card">
            <img src="lego2.jpg" alt="Lego" style="width:100%; height:200px; object-fit:cover;">
            <div class="news-content">
                <h3>المسابقات</h3>
                <p>نقيم مسابقات أسبوعية لأفضل تصميم Lego...</p>
            </div>
        </div>
    </div>
</section>

    <!-- الفوتر -->
    <footer id="contact">
        <p>جميع الحقوق محفوظة © 2023 - نادي Sparm المدرسي</p>
        <p>تواصل معنا عبر البريد الإلكتروني: club@sparm-school.edu</p>
    </footer>

    <script>
        // كود بسيط لتأثير التمرير السلس عند الضغط على الروابط
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
