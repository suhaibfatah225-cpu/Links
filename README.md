<!DOCTYPE html>
<html lang="ar" dir="rtl">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>شركة ملهومن للمونتاج</title>
    <style>
      * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
      }

      body {
        font-family: Arial, sans-serif;
        margin: 0;
        color: #222;
        background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
          url("hero-bg.jpg") no-repeat center/cover;
        background-color: #f5f7fa;
      }

      p {
        font-size: 18px;
      }

      h2 {
        font-size: 27px;
      }
      /* ====== Navigation ====== */

      header {
        background: linear-gradient(90deg, #5dade2, #2e86c1);
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
      }

      nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 12px 40px;
      }

      nav img {
        width: 100px;
      }

      nav ul {
        display: flex;
        list-style: none;
        margin: 0;
        padding: 0;
        gap: 20px;
        font-size: 20px;
      }

      nav ul li a {
        text-decoration: none;
        color: #fff;
        font-weight: 600;
        padding: 8px 14px;
        border-radius: 6px;
        transition: 0.3s;
      }

      nav ul li a:hover {
        background: #fff;
        color: #2e86c1;
      }
      /* ====== Hero Section ====== */

      .hero {
        background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
          url("hero-bg.jpg") no-repeat center/cover;
        color: #fff;
        text-align: center;
        padding: 120px 20px;
      }

      .hero h1 {
        font-size: 48px;
        margin: 0 0 15px;
      }

      .hero p {
        font-size: 20px;
        margin: 0 0 25px;
      }

      .hero button {
        background: #2e86c1;
        color: #fff;
        border: none;
        padding: 12px 24px;
        border-radius: 6px;
        cursor: pointer;
        font-size: 18px;
        transition: 0.3s;
      }

      .hero button:hover {
        background: #1b4f72;
        color: #fff;
      }

      main {
        max-width: 1100px;
        margin: auto;
        padding: 40px 20px;
      }

      section {
        background: #96bef1;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        padding: 30px;
        margin-bottom: 30px;
        border-radius: 12px;
        color: black;
      }

      section h2 {
        margin-top: 0;
        color: #2e86c1;
        border-right: 5px solid #2e86c1;
        padding-right: 10px;
      }
      /* ====== Services ====== */

      .services {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 20px;
      }

      .service {
        text-align: center;
        padding: 20px;
        background: #f4f8ff;
        border-radius: 10px;
        transition: transform 0.3s;
      }

      .service:hover {
        transform: translateY(-5px);
      }
      /* ====== Team ====== */

      .team-members {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
      }

      .member {
        text-align: center;
        width: 200px;
      }

      .member img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        border: 3px solid #0066ff;
        object-fit: cover;
      }
      /* ====== Clients ====== */

      .clients {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 30px;
      }

      .clients img {
        width: 100px;
        filter: grayscale(100%);
        transition: 0.3s;
        margin-left: 3%;
      }

      .clients img:hover {
        filter: grayscale(0);
        transform: scale(1.1);
      }
      /* ====== Important Info ====== */

      #important ul {
        list-style-type: disc;
        padding-right: 20px;
      }

      #important li {
        margin: 8px 0;
        font-size: 18px;
      }
      /* ====== Contact ====== */

      .contact form {
        display: flex;
        flex-direction: column;
        gap: 10px;
      }

      .contact input,
      .contact textarea {
        padding: 10px;
        border: 1px solid #bbb;
        border-radius: 6px;
        font-family: inherit;
      }

      .contact button {
        background: #2e86c1;
        color: #fff;
        border: none;
        padding: 12px;
        border-radius: 6px;
        font-size: 16px;
        cursor: pointer;
      }

      .contact button:hover {
        background: #1b4f72;
      }
      /* ====== Footer ====== */

      footer {
        background: #1b2631;
        color: #fff;
        text-align: center;
        padding: 20px;
      }

      footer a {
        color: #85c1e9;
        margin: 0 10px;
        text-decoration: none;
      }

      .facbook {
        padding-top: 1%;
        margin: 0.8% 0% 1% -3%;
      }

      .instgram {
        padding-top: 1%;
        margin: 0.8% 2% 1% -3.2%;
      }

      .whatsapp {
        padding-top: 1%;
        margin: 0.8% 2% 1% -3.3%;
      }
    </style>
  </head>

  <body>
    <!-- Header -->
    <header>
      <nav>
        <ul>
          <li><a href="#about">عن الشركة</a></li>
          <li><a href="#services">الخدمات</a></li>
          <li><a href="#team">فريق العمل</a></li>
          <li><a href="#clients">عملاؤنا</a></li>
          <li><a href="#contact">تواصل معنا</a></li>
        </ul>
        <img src="Logo.png" alt="Logo" />
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <h1>شركة ملهومن للمونتاج</h1>
      <p>إبداع لا حدود له في صناعة المحتوى المرئي</p>
      <button
        onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})"
      >
        تواصل معنا
      </button>
    </section>

    <!-- Main Content -->
    <main>
      <section id="about">
        <h2>عن الشركة</h2>
        <p>
          نرحب بكم في شركة <strong>ملهومن</strong>، الرائدة في مجال المونتاج
          وصناعة المحتوى المرئي. نمتلك خبرة واسعة وفريق مبدع يضمن جودة عالية في
          كافة أعمالنا من فيديوهات إعلانية، ومحتوى تسويقي متكامل.
        </p>
      </section>

      <section id="services">
        <h2>خدماتنا</h2>
        <div class="services">
          <div class="service">
            <img
              src="Motar.png"
              alt="خدمات المونتاج"
              style="width: 190px; margin-bottom: 17px"
            />
            <h3>مونتاج الفيديو</h3>
            <p>تحرير احترافي لجميع أنواع الفيديوهات بجودة عالية.</p>
          </div>
          <div class="service">
            <img
              src="Disgin.png"
              alt="خدمات المونتاج"
              style="width: 190px; margin-bottom: 17px"
            />
            <h3>تصميم موشن جرافيك</h3>
            <p>رسوم متحركة عصرية لجذب العملاء وزيادة التفاعل.</p>
          </div>
          <div class="service">
            <img
              src="Voice.png"
              alt="خدمات المونتاج"
              style="width: 190px; margin-bottom: 17px"
            />
            <h3>معالجة الصوت</h3>
            <p>تحسين جودة الصوت وإضافة مؤثرات مميزة.</p>
          </div>
          <div class="service">
            <img
              src="OIP.png"
              alt="خدمات المونتاج"
              style="width: 147px; margin-bottom: 8px"
            />
            <h3>إعلانات تسويقية</h3>
            <p>إنتاج إعلانات مبتكرة تزيد من وصول علامتك التجارية.</p>
          </div>
        </div>
      </section>

      <section id="team">
        <h2>فريق العمل</h2>
        <div class="team-members">
          <div class="member">
            <img src="Yosry.png" alt="Yosry" />
            <h3>عبدالرحمن مصطفي</h3>
            <p>مدير الشركة</p>
          </div>
          <div class="member">
            <img src="Saffy.png" alt="Saffy" />
            <h3>عبدالرحمن علي</h3>
            <p>مدير الاستديو</p>
          </div>
          <div class="member">
            <img src="Abas.jpg" alt="Abbas" />
            <h3>محمد عباس</h3>
            <p>مدير المونتاج</p>
          </div>
        </div>
      </section>

      <section id="clients">
        <h2>عملاؤنا المميزون</h2>
        <div class="clients">
          <img src="Client1.png" alt="عميل 1" />
          <img src="Client2.png" alt="عميل 2" />
          <img src="Client3.png" alt="عميل 3" />
          <img src="Client4.png" alt="عميل 4" />
        </div>
      </section>

      <section id="important">
        <h2>معلومات مهمة</h2>
        <ul>
          <li>
            العنوان: شارع الإعلام، مدينة التجمع الاول، بجوار مسجد شباب اهل الجنة
          </li>
          <li>ساعات العمل: الأحد – الخميس، 10 صباحًا – 6 مساءً</li>
          <li>رؤية الشركة: تقديم محتوى مرئي إبداعي ومتميز</li>
          <li>قيمنا: الجودة، الإبداع، الاحترافية</li>
        </ul>
      </section>

      <section id="contact" class="contact">
        <h2>تواصل معنا</h2>
        <p>
          للتواصل مع خدمة العملاء:
          <strong
            ><a href="tel:01234567891" target="_blank">إتصل الان</a>
            201234567890+</strong
          >
        </p>
        <form>
          <input type="text" placeholder="اسمك" required />
          <input type="email" placeholder="بريدك الإلكتروني" required />
          <textarea placeholder="رسالتك" required></textarea>
          <button type="submit">إرسال</button>
        </form>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <p>
        تابعنا على:
        <br />
        <img src="Facebook.png" style="width: 40px" class="facbook" />
        <a
          href="https://www.facebook.com/molhemoncreativeagency"
          target="_blank"
          >فيسبوك</a
        >
        <img src="Instgram (2).png" style="width: 40px" class="instgram" />
        <a href="https://instagram.com" target="_blank">انستجرام</a>
        <img src="Wahtsapp.png" style="width: 40px" class="whatsapp" />
        <a href="tel:01234567890">واتس اب</a>
      </p>
      <p>&copy; 2025 شركة ملهومن للمونتاج - جميع الحقوق محفوظة.</p>
    </footer>
  </body>
</html>
