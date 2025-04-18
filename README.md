# saudi-heritage
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ذاكرة وطن</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #f7f2e8;
      margin: 0;
      padding: 0;
      color: #3b2f2f;
    }
    header {
      background-color: #6b3e26;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2em;
    }
    nav {
      display: flex;
      justify-content: space-around;
      background-color: #a7744b;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 20px;
    }
    .section h2 {
      color: #6b3e26;
    }
    .cards {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }
    .card {
      background-color: white;
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 8px;
      width: calc(33% - 10px);
    }
    footer {
      background-color: #6b3e26;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    @media(max-width: 768px) {
      .card { width: 100%; }
    }
  </style>
</head>
<body>

  <header>
    <h1>ذاكرة وطن</h1>
    <p>حكاياتنا، أزياؤنا، أكلاتنا... هنا تتنفس الأصالة</p>
  </header>

  <nav>
    <a href="#">الرئيسية</a>
    <a href="#">الفيديوهات</a>
    <a href="#">المقالات</a>
    <a href="#">الصور</a>
    <a href="#">أضف محتوى</a>
  </nav>

  <div class="section">
    <h2>مقالات تراثية</h2>
    <div class="cards">
      <div class="card">
        <h3>الزي النجدي التقليدي</h3>
        <p>تعرف على تفاصيل الزي التقليدي في منطقة نجد وألوانه المميزة.</p>
      </div>
      <div class="card">
        <h3>فن السدو</h3>
        <p>حرفة يدوية نسائية قديمة تمثل جزء من التراث البدوي.</p>
      </div>
      <div class="card">
        <h3>القرية التراثية في أبها</h3>
        <p>أبرز المعالم التي تجسد التاريخ والتراث في الجنوب.</p>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 ذاكرة وطن - جميع الحقوق محفوظة
  </footer>

</body>
</html>
