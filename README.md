<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>عزّنا بطبعنا – اليوم الوطني السعودي 95 (2025)</title>

  <!-- خط ويب آمن: IBM Plex Sans Arabic (بديل ويب معتمد في الدليل) -->
  <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Arabic:wght@300;400;600;700&display=swap" rel="stylesheet">
  <!-- اختياري: عند توفّر خط Saudi الرسمي من حزمة الدليل، فعّل @font-face أدناه وغيّر font-family إلى 'SaudiND' -->
  <!--
  <style>
  @font-face{
    font-family: 'SaudiND';
    src: url('assets/fonts/SaudiND.woff2') format('woff2');
    font-display: swap;
  }
  </style>
  -->

  <style>
    :root{
      /* ألوان الهوية (قابلة للاستبدال بقيم الحزمة الرسمية COLORS.zip) */
      --nd-green: #027A3D;       /* أخضر رئيسي – استبدله بالأخضر الرسمي عند تنزيل الحزمة */
      --nd-dark:  #0B1F17;       /* أخضر داكن/أسود مخضر */
      --nd-mint:  #59B78C;       /* أخضر فاتح داعم */
      --nd-gold:  #C89A2B;       /* ذهبي داعم */
      --nd-sky:   #58A7C8;       /* أزرق سماوي داعم */
      --nd-cream: #F4F2EA;       /* كريمي للخلفيات */
      --nd-white: #FFFFFF;

      --container: 1200px;
      --radius: 16px;
      --shadow: 0 10px 30px rgba(0,0,0,.08);
    }

    html, body{
      margin:0;
      padding:0;
      background: var(--nd-cream);
      color: var(--nd-dark);
      font-family: "IBM Plex Sans Arabic", system-ui, -apple-system, "Segoe UI", Tahoma, Arial, sans-serif;
      line-height: 1.7;
    }

    .container{
      width: min(100% - 32px, var(--container));
      margin-inline: auto;
    }

    /* رأس الصفحة (Hero) */
    .hero{
      position: relative;
      isolation: isolate;
      overflow: hidden;
      background:
        radial-gradient(1200px 600px at 100% 0, rgba(2,122,61,.20), transparent 60%),
        radial-gradient(800px 400px at 0 100%, rgba(88,167,200,.18), transparent 60%),
        var(--nd-white);
      border-bottom: 8px solid var(--nd-green);
    }
    .hero-inner{
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 24px;
      align-items: center;
      padding: 72px 0 56px;
    }
    .badge{
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 6px 12px;
      border-radius: 999px;
      background: rgba(2,122,61,.10);
      color: var(--nd-green);
      font-weight: 600;
      font-size: 14px;
      margin-bottom: 12px;
    }
    .title{
      margin: 0 0 8px;
      font-size: clamp(28px, 4vw, 48px);
      line-height: 1.2;
      font-weight: 800;
      letter-spacing: .2px;
      color: var(--nd-dark);
    }
    .subtitle{
      margin: 0 0 20px;
      font-size: clamp(16px, 2.2vw, 20px);
      color: #224438;
    }
    .kpis{
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .kpi{
      background: var(--nd-cream);
      border: 1px solid #e7e3d7;
      border-radius: 12px;
      padding: 12px 16px;
      min-width: 140px;
      box-shadow: var(--shadow);
    }
    .kpi b{ display:block; font-size: 22px; color: var(--nd-green); }

    .hero-logo{
      justify-self: center;
      width: min(420px, 100%);
      aspect-ratio: 1/1;
      border-radius: var(--radius);
      background: radial-gradient(600px 400px at 50% 50%, rgba(200,154,43,.10), transparent 60%), var(--nd-white);
      display: grid;
      place-items: center;
      box-shadow: var(--shadow);
      border: 1px solid #eee5cf;
      padding: 20px;
    }
    .hero-logo img{
      width: 88%;
      height: auto;
      object-fit: contain;
    }

    /* شبكة القيم/العناصر */
    .section{
      padding: 56px 0;
    }
    .section h2{
      font-size: clamp(22px, 3vw, 30px);
      margin: 0 0 18px;
      color: var(--nd-dark);
    }
    .grid{
      display: grid;
      grid-template-columns: repeat(12, 1fr);
      gap: 16px;
    }
    .card{
      grid-column: span 6;
      background: var(--nd-white);
      border-radius: var(--radius);
      padding: 20px;
      box-shadow: var(--shadow);
      border: 1px solid #EEEAE0;
    }
    @media (max-width: 860px){
      .hero-inner{ grid-template-columns: 1fr; }
      .card{ grid-column: span 12; }
    }

    .pill{
      display:inline-flex; align-items:center; gap:8px;
      background: rgba(2,122,61,.08);
      border:1px solid rgba(2,122,61,.22);
      color: var(--nd-green); padding:6px 12px; border-radius:999px; font-weight:600; font-size:14px;
      margin-bottom: 10px;
    }

    /* وسوم وشعارات */
    .tags{
      display:flex; gap:12px; flex-wrap:wrap; margin-top:10px;
    }
    .tag{
      background:#f0f6f3; border:1px dashed #bcd7c9; color:#1d6a49;
      padding:6px 10px; border-radius:999px; font-weight:600; font-size:14px;
    }

    /* قوالب وصور */
    .templates{
      display:grid; grid-template-columns: repeat(3,1fr); gap:16px;
    }
    .tpl{
      background: var(--nd-white);
      border:1px solid #EEEAE0;
      border-radius: var(--radius);
      overflow: hidden;
      box-shadow: var(--shadow);
    }
    .tpl img{ width:100%; height:220px; object-fit:cover; background:#f3f0e6; }
    .tpl h3{ margin:12px 12px 4px; font-size:18px; }
    .tpl p{ margin:0 12px 14px; color:#3a4f46; font-size:14px; }

    /* تذييل */
    footer{
      margin-top: 40px;
      border-top: 1px solid #E7E3D7;
      background: #FAF8F2;
      padding: 24px 0 40px;
      color: #2a3b33;
      font-size: 14px;
    }
    .sources ul{ margin: 8px 0 0; padding: 0 18px; }
    .notice{
      background: #fff7e6;
      border: 1px solid #ffe2a6;
      color: #7a5a00;
      padding: 10px 14px;
      border-radius: 10px;
    }

    /* زر عام */
    .btn{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 14px; border-radius:10px; border:1px solid #dfe8e1;
      background: var(--nd-white); color:#124233; text-decoration:none; font-weight:700;
      box-shadow: var(--shadow);
    }
    .btn:focus{ outline: 3px solid rgba(2,122,61,.25); outline-offset: 2px; }
  </style>
</head>
<body>

  <!-- رأس الصفحة -->
  <header class="hero">
    <div class="container hero-inner">
      <div>
        <div class="badge" aria-label="هوية اليوم الوطني 95">#اليوم_الوطني_السعودي95</div>
        <h1 class="title">عزّنا بطبعنا</h1>
        <p class="subtitle">
          موقع تعريفي لهوية <strong>اليوم الوطني السعودي 95 (2025)</strong>، يعكس أصالة الشعب السعودي وقيمه المتجذّرة:
          الكرم، الأصالة، الطموح، الفزعة، الرؤية، والجود اللامتناهي.
        </p>
        <div class="kpis" role="list">
          <div class="kpi" role="listitem"><b>٢٣ سبتمبر ٢٠٢٥</b><span>تاريخ اليوم الوطني</span></div>
          <div class="kpi" role="listitem"><b>٩٥</b><span>رقم النسخة لهذا العام</span></div>
          <div class="kpi" role="listitem"><b>٦</b><span>عناصر هوية رئيسية</span></div>
        </div>
      </div>

      <!-- مساحة الشعار وفق الدليل: في الزاوية للشاشات الرقمية -->
      <div class="hero-logo" aria-label="شعار اليوم الوطني">
        <!-- TODO: استبدل src بشعار PNG من LOGO.zip -->
        <img src="assets/logo-nd95.png" alt="شعار اليوم الوطني السعودي 95 – عزّنا بطبعنا">
      </div>
    </div>
  </header>

  <main>

    <!-- القيم/العناصر الرئيسية للهوية -->
    <section class="section">
      <div class="container">
        <h2>عناصر الهوية البصرية</h2>
        <div class="grid" aria-label="شبكة عناصر الهوية">
          <article class="card">
            <span class="pill">الرؤية</span>
            <p>رمز إشعاعي مستلهم من شعار رؤية 2030، يعبّر عن الوضوح والتقدّم والتحوّل نحو المستقبل.</p>
          </article>
          <article class="card">
            <span class="pill">الطموح</span>
            <p>جبل طويق كأيقونة صمود وعلو، يُجسّد العزيمة والإصرار وقدرة التحدّي.</p>
          </article>
          <article class="card">
            <span class="pill">الأصالة</span>
            <p>شجرة متجذّرة ترمز لشجرة العائلة وعمق الانتماء والاتصال بين الماضي والحاضر.</p>
          </article>
          <article class="card">
            <span class="pill">الفزعة</span>
            <p>إيماءة اليدين المتقاطعتين رمز الاستعداد والتكاتف والدعم في اللحظات الحرجة.</p>
          </article>
          <article class="card">
            <span class="pill">الكرم</span>
            <p>الدلّة والفناجين أيقونة الضيافة السعودية وروح المشاركة والعطاء.</p>
          </article>
          <article class="card">
            <span class="pill">الجود اللامتناهي</span>
            <p>عطاء يتجاوز المال إلى الوقت والجهد والموقف؛ قيمة متوارثة ومتجذّرة في الثقافة السعودية.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- العبارات الداعمة والوسوم -->
    <section class="section" style="background: var(--nd-white); border-block:1px solid #EEEAE0;">
      <div class="container">
        <h2>العبارات الداعمة والوسوم</h2>
        <p>الشعار اللفظي لهذا العام يجمع الخط الهندسي مع زخارف مُستلهمة من فنون النسيج التقليدي، ليعكس الجرأة والوحدة والإرث ضمن أسلوب عصري.</p>
        <div class="tags" aria-label="وسوم رسمية">
          <span class="tag">#اليوم_الوطني_السعودي95</span>
          <span class="tag">#SaudiNationalDay95</span>
          <span class="tag">#عزنا_بطبعنا</span>
        </div>
      </div>
    </section>

    <!-- قوالب الاستخدام (معاينات صور توضيحية) -->
    <section class="section">
      <div class="container">
        <h2>قوالب وتطبيقات الهوية</h2>
        <div class="templates" aria-label="قوالب رسمية">
          <div class="tpl">
            <!-- TODO: استبدل بالصورة من DESIGN_TEMPLATES.zip (القالب العام) -->
            <img src="assets/template-general.jpg" alt="القالب العام – استخدام صفة واحدة أو أكثر">
            <h3>القالب العام</h3>
            <p>يستوعب صفة واحدة أو أكثر حسب قياس الملصق أو التصميم.</p>
          </div>
          <div class="tpl">
            <!-- TODO: استبدل بالصورة من DESIGN_TEMPLATES.zip (قالب الإطار) -->
            <img src="assets/template-frame.jpg" alt="قالب الإطار – إطار بزخرفة ثانوية للصورة">
            <h3>قوالب الصور</h3>
            <p>توظيف الزخارف الثانوية كإطار أو خلفية لعبارات مرافقة.</p>
          </div>
          <div class="tpl">
            <!-- TODO: استبدل بالصورة من DESIGN_TEMPLATES.zip (قوالب الرسوم) -->
            <img src="assets/template-illustration.jpg" alt="قوالب الرسوم – توظيف الزخارف كأساس للتصميم">
            <h3>قوالب الرسوم</h3>
            <p>الزخرفة الخاصة بكل صفة تشكّل الأساس البصري للتكوين.</p>
          </div>
        </div>

        <div style="margin-top:18px; display:flex; gap:12px; flex-wrap:wrap;">
          <a class="btn" href="https://nd.gea.gov.sa/id/NationalDayGuidelines/LOGO.zip">تنزيل الشعار (LOGO.zip)</a>
          <a class="btn" href="https://nd.gea.gov.sa/id/NationalDayGuidelines/COLORS.zip">لوحة الألوان (COLORS.zip)</a>
          <a class="btn" href="https://nd.gea.gov.sa/id/NationalDayGuidelines/FONTS.zip">حزمة الخطوط (FONTS.zip)</a>
          <a class="btn" href="https://nd.gea.gov.sa/id/NationalDayGuidelines/DESIGN_TEMPLATES.zip">قوالب التصميم</a>
          <a class="btn" href="https://nd.gea.gov.sa/id/NationalDayGuidelines/IDENTITY_TEMPLATES.zip">عناصر الهوية</a>
        </div>
      </div>
    </section>

    <!-- إرشادات سريعة (تماشياً مع الدليل) -->
    <section class="section" style="background: var(--nd-white); border-block:1px solid #EEEAE0;">
      <div class="container">
        <h2>إرشادات استخدام الشعار</h2>
        <ul>
          <li>للمنصّات الرقمية: يُفضّل وضع الشعار في إحدى الزوايا العلوية (يمين/يسار). للطباعة: في وسط مساحة التصميم.</li>
          <li>المساحة الهامشية حول الشعار = ارتفاع مربعين من نمط الهوية على جميع الجوانب (2X).</li>
          <li>يُستخدم إصدار الأبيض/الأسود فقط في حال الطباعة بالأبيض والأسود.</li>
          <li>يُمنع تغيير الشعار أو إعادة رسمه أو التلاعب بألوانه أو نسبه.</li>
          <li>عند المشاركة مع شعارات أخرى: يجب أن يكون شعار اليوم الوطني أكبر أفقيًا بمقدار الضعف وأن يتموضع أعلى اليمين أو في المنتصف أعلى.</li>
        </ul>
        <p class="notice" role="note">لنتائج دقيقة: استبدِل متغيّرات الألوان في :root بقيم الحزمة الرسمية (COLORS.zip)، واستخدم الخط الرسمي من حزمة الخطوط.</p>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <p><strong>حقوق الاستخدام:</strong> تُستخدم هذه الهوية وفق الدليل الإرشادي الرسمي لليوم الوطني 95 – 2025.</p>
      <div class="sources">
        <p><strong>المصادر الموثوقة:</strong></p>
        <ul>
          <li>الدليل الإرشادي الرسمي لهوية اليوم الوطني 95 (PDF) – الهيئة العامة للترفيه GEA.  [oai_citation:0‡Saudi_National_Day_95_Guidelines.pdf](file-service://file-WDRHZhzVsH4rgC6giDjLXX)</li>
          <li><a href="https://nd.gea.gov.sa/id/NationalDayGuidelines/LOGO.zip">حزمة الشعار (LOGO.zip)</a></li>
          <li><a href="https://nd.gea.gov.sa/id/NationalDayGuidelines/COLORS.zip">لوحة الألوان (COLORS.zip)</a></li>
          <li><a href="https://nd.gea.gov.sa/id/NationalDayGuidelines/FONTS.zip">حزمة الخطوط (FONTS.zip)</a></li>
          <li><a href="https://nd.gea.gov.sa/id/NationalDayGuidelines/DESIGN_TEMPLATES.zip">قوالب التصميم (DESIGN_TEMPLATES.zip)</a></li>
          <li><a href="https://nd.gea.gov.sa/id/NationalDayGuidelines/IDENTITY_TEMPLATES.zip">عناصر الهوية (IDENTITY_TEMPLATES.zip)</a></li>
          <li><a href="https://nd.gea.gov.sa/id/OutdoorAdvertisingApplications.zip">تطبيقات الإعلانات الخارجية/الداخلية</a></li>
          <li><a href="https://nd.gea.gov.sa/id/OfficeApplications.zip">حزمة المكتب</a></li>
          <li><a href="https://nd.gea.gov.sa/id/ProductApplications.zip">تطبيقات المنتجات</a></li>
        </ul>
      </div>
    </div>
  </footer>
</body>
</html>
