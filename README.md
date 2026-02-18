<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GS Iridium | Golden Sensitivity</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --gold: #d4af37;
            --dark-bg: #000000;
            --whatsapp: #25d366;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Cairo', sans-serif; background-color: var(--dark-bg); color: white; overflow-x: hidden; scroll-behavior: smooth; }

        /* Header & Logo */
        header { position: absolute; top: 0; width: 100%; z-index: 1000; padding: 20px; text-align: center; background: linear-gradient(to bottom, rgba(0,0,0,0.8), transparent); }
        .logo { max-width: 250px; width: 100%; filter: drop-shadow(0 0 10px rgba(212, 175, 55, 0.5)); }

        /* Video Hero Section */
        .hero { position: relative; height: 100vh; display: flex; align-items: center; justify-content: center; overflow: hidden; }
        #bg-video { position: absolute; top: 50%; left: 50%; min-width: 100%; min-height: 100%; width: auto; height: auto; z-index: -1; transform: translate(-50%, -50%); object-fit: cover; opacity: 0.6; }
        .hero-overlay { position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: radial-gradient(circle, transparent 20%, #000 100%); z-index: 0; }
        .hero-content { position: relative; z-index: 10; text-align: center; padding: 20px; }
        .hero-content h1 { font-size: clamp(2.5rem, 8vw, 5rem); color: var(--gold); font-weight: 900; margin-bottom: 10px; text-shadow: 2px 2px 15px rgba(0,0,0,0.8); }
        .hero-content p { font-size: 1.5rem; color: #f4f4f4; margin-bottom: 30px; }

        /* Floating WhatsApp */
        .whatsapp-btn { position: fixed; bottom: 30px; right: 30px; background: var(--whatsapp); color: white; width: 65px; height: 65px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 35px; text-decoration: none; box-shadow: 0 10px 25px rgba(0,0,0,0.5); z-index: 9999; transition: 0.3s; }
        .whatsapp-btn:hover { transform: scale(1.1); }

        /* Features Section */
        .section { padding: 100px 5%; max-width: 1300px; margin: 0 auto; }
        .title-gold { color: var(--gold); font-size: 2.5rem; text-align: center; margin-bottom: 50px; font-weight: 900; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .card { background: rgba(255,255,255,0.03); border: 1px solid rgba(212,175,55,0.2); padding: 40px; border-radius: 20px; transition: 0.4s; }
        .card:hover { border-color: var(--gold); background: rgba(212,175,55,0.05); transform: translateY(-10px); }
        .card h3 { color: var(--gold); margin-bottom: 15px; font-size: 1.8rem; }

        /* App & Specs */
        .flex-box { display: flex; flex-wrap: wrap; align-items: center; gap: 50px; margin-top: 50px; }
        .flex-text { flex: 1; min-width: 320px; }
        .flex-img { flex: 1; min-width: 320px; border-radius: 25px; border: 2px solid #222; }
        .specs-list { list-style: none; margin-top: 20px; }
        .specs-list li { padding: 10px 0; border-bottom: 1px solid #222; }
        .specs-list li::before { content: "✦ "; color: var(--gold); margin-left: 10px; }

        .cta-btn { background: linear-gradient(135deg, var(--gold), #b38f2a); color: black; padding: 18px 45px; border-radius: 50px; text-decoration: none; font-weight: 900; font-size: 1.3rem; display: inline-block; transition: 0.3s; }
        .cta-btn:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(212,175,55,0.4); }

        footer { text-align: center; padding: 60px; border-top: 1px solid #111; margin-top: 50px; }
    </style>
</head>
<body>

<a href="https://wa.me/962782993023" class="whatsapp-btn" target="_blank"><i class="fab fa-whatsapp"></i></a>

<header>
    <img src="photo_2025-11-23_12-53-31.jpg" alt="Golden Sensitivity Logo" class="logo">
</header>

<section class="hero">
    <video autoplay muted loop playsinline id="bg-video">
        <source src="اكتشاف الذهب مع جهاز جي एस إيريديوم-1770758826835.mp4" type="video/mp4">
    </video>
    <div class="hero-overlay"></div>
    <div class="hero-content">
        <h1>GS IRIDIUM</h1>
        <p>اكتشف ما هو مخفي بأحدث تقنيات التصوير الأرضي</p>
        <a href="#order" class="cta-btn">ابدأ رحلة الاستكشاف</a>
    </div>
</section>

<section class="section">
    <h2 class="title-gold">أنظمة كشف ثلاثية الأبعاد </h2>
    <div class="grid">
        <div class="card">
            <h3>المسح الذكي</h3>
            <p>مدعوم بالذكاء الاصطناعي لتحديد الكنوز والهياكل بدقة متناهية.</p>
        </div>
        <div class="card">
            <h3>أقصى عمق</h3>
            <p>يصل إلى 12 متراً تحت الأرض لكشف السراديب والغرف الدفينة.</p>
        </div>
        <div class="card">
            <h3>مسح مباشر</h3>
            <p>رؤية فورية لما تحت الأرض عبر الجهاز أو التابلت بوضوح تام.</p>
        </div>
    </div>
</section>

<section class="section" style="background: #050505;">
    <div class="flex-box">
        <div class="flex-text">
            <h2 class="title-gold" style="text-align: right;">تحليل GS MAGNOVA</h2>
            <p>تطبيق متطور يعمل بنظام أندرويد يتيح لك حفظ الصور وتحليلها بدقة احترافية[cite: 3].</p>
            <ul class="specs-list">
                <li>دمج متعدد للترددات لتحديد نوع المعدن.</li>
                <li>تصوير عمودي وأفقي لتغطية شاملة للموقع.</li>
                <li>يحتوي على حساس الميلان والتوازن وبوصلة رقمية[cite: 3].</li>
                <li>صناعة عالية الجودة مع ضمان لمدة 3 سنوات[cite: 3].</li>
            </ul>
        </div>
        <img src="6dca5bf2-0c22-4f4d-9776-fad45c3e4be9.jpg" class="flex-img" alt="App Interface">
    </div>
</section>

<section class="section" style="text-align: center;" id="order">
    <h2 class="title-gold">محتويات الحقيبة الاحترافية</h2>
    <img src="AS.jpg" style="width: 100%; border-radius: 30px; margin-bottom: 40px;" alt="Package Contents">
    <br>
    <a href="https://wa.me/962782993023" class="cta-btn">اطلب الجهاز الآن عبر واتساب</a>
</section>

<footer>
    <img src="photo_2025-11-23_12-53-31.jpg" style="max-width: 180px; margin-bottom: 20px;" alt="Logo">
    <p>Golden Sensitivity - التكنولوجيا الألمانية برؤية متطورة</p>
    <p style="color: #444; margin-top: 10px;">جميع الحقوق محفوظة © 2026</p>
</footer>

</body>
</html>
