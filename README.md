<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<title>برنامه هفتگی</title>
<style>
  @page { size: A4 landscape; margin: 10mm; }
  * { box-sizing: border-box; }
  body {
    font-family: 'Tahoma', 'Vazirmatn', sans-serif;
    margin: 0;
    padding: 15px;
    background: #fff;
  }
  .header {
    text-align: center;
    margin-bottom: 15px;
    padding-bottom: 10px;
    border-bottom: 3px solid #333;
  }
  .header h1 {
    font-size: 20px;
    font-weight: 900;
    margin: 0 0 5px 0;
    color: #222;
    letter-spacing: 1px;
  }
  .header h2 {
    font-size: 24px;
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
    padding: 8px 4px;
    font-size: 14px;
    border: 1px solid #34495e;
  }
  td {
    background: #fff;
    border: 1px solid #ccc;
    padding: 6px 5px;
    vertical-align: top;
    height: 100px;
    font-size: 11px;
  }
  .task {
    display: block;
    margin-bottom: 4px;
    padding: 3px 5px;
    border-radius: 4px;
    font-weight: 600;
    border-right: 4px solid;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .time {
    font-size: 9px;
    opacity: 0.75;
    display: block;
    font-weight: normal;
  }
  /* رنگ کارها */
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
        <span class="task t-prog">💻 برنامه‌سازی کامپیوتر<span class="time">۸:۰۰</span></span>
        <span class="task t-cinet">⚗️ سینتیک و طراحی راکتور<span class="time">۱۲:۰۰</span></span>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۱۶:۰۰–۱۸:۰۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۱۸:۳۰–۲۰:۰۰</span></span>
      </td>

      <!-- یکشنبه -->
      <td>
        <span class="task t-thermo">🔥 ترمودینامیک ۲<span class="time">۸:۰۰</span></span>
        <span class="task t-work">🛠️ کارگاه نرم‌افزار مهندسی<span class="time">۱۰:۰۰</span></span>
        <span class="task t-sport">🏃 تربیت بدنی<span class="time">۱۲:۰۰</span></span>
        <span class="task t-nahj">📖 تفسیر نهج‌البلاغه<span class="time">۱۴:۰۰</span></span>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۱۸:۰۰–۲۰:۰۰</span></span>
        <span class="task t-excel">📊 اکسل<span class="time">۲۰:۳۰–۲۱:۳۰</span></span>
      </td>
	<!-- دوشنبه -->
      <td>
        <span class="task t-prog">💻 برنامه‌سازی کامپیوتر<span class="time">۸:۰۰</span></span>
        <span class="task t-cinet">⚗️ سینتیک و طراحی راکتور<span class="time">۱۲:۰۰</span></span>
        <span class="task t-fluid">💧 مکانیک سیالات ۱<span class="time">۱۶:۰۰</span></span>
        <span class="task t-excel">📊 اکسل<span class="time">۱۹:۳۰–۲۰:۳۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۲۰:۴۵–۲۱:۳۰</span></span>
      </td>

      <!-- سه‌شنبه -->
      <td>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۶:۰۰–۸:۰۰</span></span>
        <span class="task t-excel">📊 اکسل<span class="time">۱۰:۰۰–۱۱:۳۰</span></span>
        <span class="task t-lab">🧪 آزمایشگاه شیمی عالی<span class="time">۱۴:۰۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۱۷:۳۰–۱۹:۰۰</span></span>
      </td>

      <!-- چهارشنبه -->
      <td>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۶:۰۰–۸:۰۰</span></span>
        <span class="task t-excel">📊 اکسل<span class="time">۱۰:۰۰–۱۱:۳۰</span></span>
        <span class="task t-thermo">🔥 ترمودینامیک ۲<span class="time">۱۴:۰۰</span></span>
        <span class="task t-fluid">💧 مکانیک سیالات ۱<span class="time">۱۶:۰۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۱۹:۱۵–۲۰:۴۵</span></span>
      </td>

      <!-- پنجشنبه -->
      <td>
        <span class="task t-fluid2">📝 حل تمرین مکانیک سیالات ۱<span class="time">۱۰:۰۰–۱۲:۰۰</span></span>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۱۶:۰۰–۱۸:۰۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۱۸:۳۰–۲۰:۰۰</span></span>
        <span class="task t-nuc">⚛️ فیزیک هسته‌ای<span class="time">۲۰:۲۰–۲۱:۳۰</span></span>
      </td>

      <!-- جمعه -->
      <td>
        <span class="task t-matlab"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="width:16px;vertical-align:middle;"> متلب<span class="time">۶:۰۰–۸:۰۰</span></span>
        <span class="task t-excel">📊 اکسل<span class="time">۱۰:۳۰–۱۱:۳۰</span></span>
        <span class="task t-python">🐍 پایتون<span class="time">۱۱:۴۵–۱۳:۳۰</span></span>
        <span class="task t-nuc">⚛️ فیزیک هسته‌ای<span class="time">۱۶:۰۰–۱۸:۰۰</span></span>
        <span class="task t-digital">📱 عرضه دیجیتال<span class="time">۱۸:۳۰–۲۰:۳۰</span></span>
      </td>
    </tr>
  </tbody>
</table>

</body>
</html>  


















