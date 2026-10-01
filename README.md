<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<title>برنامه هفتگی</title>
<style>
  @page { size: A4 landscape; margin: 8mm; }
  * { box-sizing: border-box; }
  body {
    font-family: 'Tahoma', 'Vazirmatn', sans-serif;
    margin: 0;
    padding: 10px;
    background: #fff;
  }
  .header {
    text-align: center;
    margin-bottom: 12px;
    padding-bottom: 8px;
    border-bottom: 3px solid #333;
  }
  .header h1 {
    font-size: 22px;
    font-weight: 900;
    margin: 0 0 4px 0;
    color: #222;
    letter-spacing: 1.5px;
  }
  .header h2 {
    font-size: 26px;
    font-weight: 700;
    margin: 0;
    color: #111;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
  }
  th {
    background: #2c3e50;
    color: #fff;
    padding: 7px 3px;
    font-size: 13px;
    border: 1px solid #34495e;
  }
  td {
    background: #fff;
    border: 1px solid #ccc;
    padding: 4px 4px;
    vertical-align: top;
    height: 110px;
    font-size: 10px;
  }
  .task {
    display: flex;
    align-items: center;
    gap: 3px;
    margin-bottom: 3px;
    padding: 3px 4px;
    border-radius: 4px;
    font-weight: 600;
    border-right: 4px solid;
    line-height: 1.3;
  }
  .task .box {
    flex-shrink: 0;
    width: 11px;
    height: 11px;
    border: 1.5px solid #555;
    border-radius: 2px;
    background: #fff;
    display: inline-block;
  }
  .task .icon { flex-shrink: 0; }
  .task .txt { flex: 1; }
  .time {
    font-size: 8.5px;
    opacity: 0.75;
    display: block;
    font-weight: normal;
  }
  /* رنگ کارها */
  .t-break  { background:#FBE9E7; color:#5D4037; border-color:#8D6E63; }
  .t-study  { background:#FFF8E1; color:#5D4037; border-color:#FFA000; }
  .t-free   { background:#F1F8E9; color:#33691E; border-color:#7CB342; }
  .t-prog   { background:#E3F2FD; color:#0D47A1; border-color:#1976D2; }
  .t-cinet  { background:#E8F5E9; color:#1B5E20; border-color:#388E3C; }
  .t-matlab { background:#FFF3E0; color:#E65100; border-color:#F57C00; }
  .t-python { background:#FFFDE7; color:#F57F17; border-color:#FBC02D; }
  .t-thermo { background:#FFEBEE; color:#B71C1C; border-color:#D32F2F; }
  .t-work   { background:#E0F7FA; color:#006064; border-color:#00ACC1; }
  .t-sport  { background:#F1F8E9; color:#33691E; border-color:#689F38; }
  .t-nahj   { background:#F3E5F5; color:#4A148C; border-color:#7B1FA2; }
  .t-excel  { background:#E8F5E9; color:#1B5E20; border-color:#43A047; }
  .t-lab    { background:#FCE4EC; color:#880E4F; border-color:#C2185B; }
  .t-fluid  { background:#E1F5FE; color:#01579B; border-color:#0288D1; }
  .t-fluid2 { background:#B3E5FC; color:#01579B; border-color:#0277BD; }
  .t-nuc    { background:#EDE7F6; color:#311B92; border-color:#512DA8; }
  .t-digital{ background:#ECEFF1; color:#263238; border-color:#546E7A; }
</style>
</head>
<body>

<div class="header">
  <h1>NO PAIN NO GAIN</h1>
  <h2>برنامه هفتگی</h2>
</div>

<table>
  <thead>
    <tr>
      <th>شنبه</th>
      <th>یکشنبه</th>
      <th>دوشنبه</th>
      <th>سه‌شنبه</th>
      <th>چهارشنبه</th>
      <th>پنجشنبه</th>
      <th>جمعه</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <!-- شنبه -->
      <td>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۶:۰۰–۷:۰۰</span></span></span>
        <span class="task t-prog"><span class="box"></span><span class="icon">💻</span><span class="txt">برنامه‌سازی کامپیوتر<span class="time">۸:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۱۰:۰۰–۱۲:۰۰</span></span></span>
        <span class="task t-cinet"><span class="box"></span><span class="icon">⚗️</span><span class="txt">سینتیک و طراحی راکتور<span class="time">۱۲:۰۰</span></span></span>
		<span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۱۶:۰۰–۱۸:۰۰</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۱۸:۳۰–۲۰:۰۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>

      <!-- یکشنبه -->
      <td>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۶:۰۰–۷:۰۰</span></span></span>
        <span class="task t-thermo"><span class="box"></span><span class="icon">🔥</span><span class="txt">ترمودینامیک ۲<span class="time">۸:۰۰</span></span></span>
        <span class="task t-work"><span class="box"></span><span class="icon">🛠️</span><span class="txt">کارگاه نرم‌افزار مهندسی<span class="time">۱۰:۰۰</span></span></span>
        <span class="task t-sport"><span class="box"></span><span class="icon">🏃</span><span class="txt">تربیت بدنی<span class="time">۱۲:۰۰</span></span></span>
        <span class="task t-nahj"><span class="box"></span><span class="icon">📖</span><span class="txt">تفسیر نهج‌البلاغه<span class="time">۱۴:۰۰</span></span></span>
        <span class="task t-matlab"><span class="box"></span><span class="icon"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:14px;vertical-align:middle;"></span><span class="txt">متلب<span class="time">۱۸:۰۰–۲۰:۰۰</span></span></span>
        <span class="task t-excel"><span class="box"></span><span class="icon">📊</span><span class="txt">اکسل<span class="time">۲۰:۳۰–۲۱:۳۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>

      <!-- دوشنبه -->
      <td>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۶:۰۰–۷:۰۰</span></span></span>
        <span class="task t-prog"><span class="box"></span><span class="icon">💻</span><span class="txt">برنامه‌سازی کامپیوتر<span class="time">۸:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۱۰:۰۰–۱۲:۰۰</span></span></span>
        <span class="task t-cinet"><span class="box"></span><span class="icon">⚗️</span><span class="txt">سینتیک و طراحی راکتور<span class="time">۱۲:۰۰</span></span></span>
        <span class="task t-fluid"><span class="box"></span><span class="icon">💧</span><span class="txt">مکانیک سیالات ۱<span class="time">۱۶:۰۰</span></span></span>
        <span class="task t-excel"><span class="box"></span><span class="icon">📊</span><span class="txt">اکسل<span class="time">۱۹:۳۰–۲۰:۳۰</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۲۰:۴۵–۲۱:۳۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>

      <!-- سه‌شنبه -->
      <td>
        <span class="task t-matlab"><span class="box"></span><span class="icon"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:14px;vertical-align:middle;"></span><span class="txt">متلب<span class="time">۶:۰۰–۸:۰۰</span></span></span>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۸:۰۰–۹:۰۰</span></span></span>
		<span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۹:۲۰–۱۱:۰۰</span></span></span>
        <span class="task t-excel"><span class="box"></span><span class="icon">📊</span><span class="txt">اکسل<span class="time">۱۱:۲۰–۱۲:۴۵</span></span></span>
        <span class="task t-lab"><span class="box"></span><span class="icon">🧪</span><span class="txt">آزمایشگاه شیمی آلی<span class="time">۱۴:۰۰</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۱۷:۳۰–۱۸:۳۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۱۹:۰۰–۲۰:۳۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۲۰:۴۵–۲۱:۳۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>

      <!-- چهارشنبه -->
      <td>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۶:۰۰–۸:۰۰</span></span></span>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۸:۰۰–۹:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۹:۲۰–۱۱:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۱۱:۲۰–۱۲:۴۵</span></span></span>
        <span class="task t-thermo"><span class="box"></span><span class="icon">🔥</span><span class="txt">ترمودینامیک ۲<span class="time">۱۴:۰۰</span></span></span>
        <span class="task t-fluid"><span class="box"></span><span class="icon">💧</span><span class="txt">مکانیک سیالات ۱<span class="time">۱۶:۰۰</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۱۹:۱۵–۲۰:۴۵</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>

      <!-- پنجشنبه -->
      <td>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۶:۰۰–۷:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۷:۰۰–۸:۴۵</span></span></span>
        <span class="task t-fluid2"><span class="box"></span><span class="icon">📝</span><span class="txt">حل تمرین مکانیک سیالات ۱<span class="time">۱۰:۰۰–۱۲:۰۰</span></span></span>
        <span class="task t-matlab"><span class="box"></span><span class="icon"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:14px;vertical-align:middle;"></span><span class="txt">متلب<span class="time">۱۶:۰۰–۱۸:۰۰</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۱۸:۳۰–۲۰:۰۰</span></span></span>
        <span class="task t-nuc"><span class="box"></span><span class="icon">⚛️</span><span class="txt">فیزیک هسته‌ای<span class="time">۲۰:۲۰–۲۱:۳۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>
	  <!-- جمعه -->
      <td>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۶:۰۰–۸:۰۰</span></span></span>
        <span class="task t-break"><span class="box"></span><span class="icon">☕</span><span class="txt">صرف صبحانه<span class="time">۸:۰۰–۹:۰۰</span></span></span>
        <span class="task t-study"><span class="box"></span><span class="icon">📚</span><span class="txt">مطالعه دروس<span class="time">۹:۱۵–۱۱:۴۵</span></span></span>
        <span class="task t-python"><span class="box"></span><span class="icon">🐍</span><span class="txt">پایتون<span class="time">۱۲:۰۰–۱۳:۳۰</span></span></span>
        <span class="task t-nuc"><span class="box"></span><span class="icon">⚛️</span><span class="txt">فیزیک هسته‌ای<span class="time">۱۶:۰۰–۱۸:۰۰</span></span></span>
        <span class="task t-digital"><span class="box"></span><span class="icon">📱</span><span class="txt">ارز دیجیتال / مطالعه دروس<span class="time">۱۸:۳۰–۲۰:۳۰</span></span></span>
        <span class="task t-free"><span class="box"></span><span class="icon">📖</span><span class="txt">مطالعه آزاد<span class="time">۲۲:۳۰–۲۳:۰۰</span></span></span>
      </td>
    </tr>
  </tbody>
</table>

</body>
</html>
