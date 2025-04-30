<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>النجم الحديث - قطع غيار السيارات</title>
  <style>
    body { font-family: 'Tahoma', sans-serif; margin: 0; background-color: #f5f5f5; color: #222; }
    header { background-color: #0f172a; color: white; padding: 1rem 2rem; text-align: center; }
    nav { background-color: #1e293b; display: flex; justify-content: center; gap: 2rem; padding: 1rem; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    .hero { background-color: #e2e8f0; padding: 2rem; text-align: center; }
    .hero h2 { font-size: 2rem; margin-bottom: 1rem; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; padding: 2rem; }
    .product { background-color: white; padding: 1rem; border-radius: 0.5rem; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .contact, .order { background-color: white; margin: 2rem; padding: 2rem; border-radius: 0.5rem; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    .contact h2, .order h2 { text-align: center; margin-bottom: 1rem; }
    form { display: flex; flex-direction: column; gap: 1rem; }
    input, textarea, select { padding: 0.75rem; border: 1px solid #ccc; border-radius: 0.5rem; }
    button { background-color: #0f172a; color: white; padding: 0.75rem; border: none; border-radius: 0.5rem; cursor: pointer; }
    footer { background-color: #0f172a; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>

  <header>
    <h1>النجم الحديث</h1>
    <p>متخصصون في بيع قطع غيار السيارات الأصلية</p>
  </header>

  <nav>
    <a href="#">الرئيسية</a>
    <a href="#">المنتجات</a>
    <a href="#order">طلب شراء</a>
    <a href="#contact">اتصل بنا</a>
  </nav>

  <section class="hero">
    <h2>أفضل قطع الغيار لسيارتك</h2>
    <p>توصيل سريع - جودة مضمونة - دفع عبر بنك الكريمي</p>
  </section>

  <section class="products">
    <div class="product">
      <h3>فلتر زيت</h3>
      <p>فلتر زيت أصلي لجميع أنواع السيارات.</p>
      <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
    </div>
    <div class="product">
      <h3>بطارية</h3>
      <p>بطاريات عالية الجودة تدوم طويلاً.</p>
      <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
    </div>
<section class="products">
  <div class="product">
    <h3>بلاكات</h3>
    <p>بلاكات عالية الجودة لأداء احتراق مثالي.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>فلتر هواء</h3>
    <p>فلتر هواء أصلي يحافظ على كفاءة المحرك.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>فلتر مكيف</h3>
    <p>فلتر مكيف لتنقية الهواء داخل السيارة.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>مرتزيات</h3>
    <p>مرتزيات أصلية لثبات السيارة وراحة القيادة.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>بوشات مقصات</h3>
    <p>بوشات مقاومة للتآكل لعمر افتراضي أطول.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>باكن راس</h3>
    <p>باكن راس بجودة عالية لمنع التسربات.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>باكن غطاء والات</h3>
    <p>باكن غطاء والات لتحكم محكم وتسريب أقل.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>ربلات والات</h3>
    <p>ربلات مقاومة للحرارة والعوامل الجوية.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>بستونات مكينة</h3>
    <p>بستونات عالية الأداء لمحركات البنزين والديزل.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>يد بستون مكينه</h3>
    <p>يد بستون قوية لتحمل الضغط العالي داخل المحرك.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>براصات الكرين</h3>
    <p>براصات دقيقة لحركة سلسة للكرين.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>براصات اليدات</h3>
    <p>براصات يدات لضمان حركة دقيقة وعمر أطول.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>هلالات الكرين</h3>
    <p>هلالات أصلية تناسب أنظمة الرفع الدقيقة.</p>
    <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
  </div>
  <div class="product">
    <h3>والات الهواء</h3>
    <p>والات مخصصة لضغط الهواء بثبات وكفاءة.</p>
    <button onclick
    <div class="product">
      <h3>رديتر</h3>
      <p>رديترات مصممة لتحمّل درجات الحرارة العالية.</p>
      <button onclick="document.getElementById('order').scrollIntoView({ behavior: 'smooth' });">اطلب الآن</button>
    </div>
  </section>

  <section class="order" id="order">
    <h2>طلب شراء</h2>
    <form>
      <input type="text" name="fullname" placeholder="الاسم الكامل" required>
      <input type="tel" name="phone" placeholder="رقم الهاتف" required>
      <input type="text" name="part" placeholder="اسم القطعة المطلوبة" required>
      <select name="payment" required>
        <option value="">اختر طريقة الدفع</option>
        <option value="الكريمي">بنك الكريمي</option>
        <option value="عند الاستلام">عند الاستلام</option>
      </select>
      <textarea name="notes" rows="4" placeholder="ملاحظات إضافية (اختياري)"></textarea>
      <button type="submit">إرسال الطلب</button>
    </form>
  </section>

  <section class="contact" id="contact">
    <h2>اتصل بنا</h2>
    <form action="https://formspree.io/f/xwpovznk" method="POST">
      <input type="text" name="name" placeholder="الاسم الكامل" required>
      <input type="email" name="email" placeholder="البريد الإلكتروني" required>
      <textarea name="message" placeholder="رسالتك..." required></textarea>
      <button type="submit">إرسال</button>
    </form>
  </section>

  <footer>
    <p>جميع الحقوق محفوظة &copy; النجم الحديث 2025</p>
    <p>للتواصل: 776798168</p>
  </footer>

</body>
</html># alnajmalhadeth-for-autoparts
