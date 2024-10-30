<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عيادة د. نشوان الخولاني للأسنان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            direction: rtl;
            text-align: right;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2rem 0;
        }
        .services, .about, .contact {
            background: #fff;
            padding: 2rem;
            margin: 1rem 0;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>عيادة د. نشوان الخولاني للأسنان</h1>
        <nav>
            <a href="#about">من نحن</a>
            <a href="#services">خدماتنا</a>
            <a href="#contact">اتصل بنا</a>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="about">
            <h2>من نحن</h2>
            <p>مرحبًا بكم في عيادة د. نشوان الخولاني للأسنان، حيث نهتم بصحتكم الفموية وراحتكم. 
               نسعى لتقديم خدمات طب الأسنان بجودة عالية في بيئة مريحة ومهنية، 
               ونوفر مجموعة واسعة من الخدمات لتلبية احتياجاتكم.</p>
        </section>

        <section id="services" class="services">
            <h2>خدماتنا</h2>
            <ul>
                <li>طب الأسنان العام</li>
                <li>طب الأسنان التجميلي</li>
                <li>جراحة الفم والفكين</li>
                <li>زراعة الأسنان</li>
                <li>تبييض الأسنان</li>
                <li>تقويم الأسنان</li>
            </ul>
        </section>

        <section class="services">
            <h2>مشروع مميز</h2>
            <p>اطلع على بعض أعمالنا الأخيرة:</p>
            <iframe src="https://www.behance.net/embed/project/210034937?ilo0=1" height="316" width="404" 
                    allowfullscreen lazyload frameborder="0" 
                    allow="clipboard-write" refererPolicy="strict-origin-when-cross-origin">
            </iframe>
        </section>

        <section id="contact" class="contact">
            <h2>اتصل بنا</h2>
            <p>الهاتف: +123456789</p>
            <p>البريد الإلكتروني: info@alkhawlaniclinic.com</p>
            <p>العنوان: شارع الأسنان 123، مدينة الابتسامة</p>
            <form>
                <label for="name">الاسم:</label><br>
                <input type="text" id="name" name="name"><br><br>
                <label for="message">الرسالة:</label><br>
                <textarea id="message" name="message"></textarea><br><br>
                <input type="submit" value="إرسال">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 عيادة د. نشوان الخولاني للأسنان. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
