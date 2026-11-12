



<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>English Master</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}

body{font-family:Arial,sans-serif;min-height:100vh;color:#f7f8ff;background-color:#080b1c;background-image:radial-gradient(ellipse at 8% 12%,rgba(139,92,246,.30),transparent 38%),radial-gradient(ellipse at 92% 18%,rgba(14,165,233,.24),transparent 35%),radial-gradient(ellipse at 75% 90%,rgba(236,72,153,.16),transparent 38%),radial-gradient(ellipse at 35% 65%,rgba(45,212,191,.10),transparent 42%),linear-gradient(135deg,#070b1b 0%,#11152d 48%,#090d20 100%);background-attachment:fixed;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background-image:linear-gradient(rgba(148,163,184,.055) 1px,transparent 1px),linear-gradient(90deg,rgba(148,163,184,.055) 1px,transparent 1px);background-size:46px 46px;mask-image:linear-gradient(to bottom,rgba(0,0,0,.9),transparent 95%)}
body::after{content:"";position:fixed;width:42vw;height:42vw;min-width:280px;min-height:280px;top:18%;left:-12%;border-radius:50%;pointer-events:none;z-index:-1;background:radial-gradient(circle,rgba(99,102,241,.13),transparent 68%);filter:blur(12px);animation:ambientFloat 16s ease-in-out infinite alternate}
@keyframes ambientFloat{from{transform:translate3d(0,0,0) scale(.9)}to{transform:translate3d(16vw,12vh,0) scale(1.2)}}


header{
background:linear-gradient(120deg,#5636ff,#008dff);
padding:35px 15px;
text-align:center;
}

header h1{font-size:36px;margin-bottom:12px}

nav{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:10px;
background:#151c32;
padding:15px;
}

button{
border:none;
padding:12px 18px;
border-radius:10px;
cursor:pointer;
background:#593aff;
color:white;
font-size:15px;
}

button:hover{opacity:.8}

.container{
max-width:1000px;
margin:30px auto;
padding:15px;
}

.page{display:none}
.page.active{display:block}

h2{margin-bottom:20px;color:#64c9ff}

input{
width:100%;
padding:15px;
border-radius:10px;
background:#171f38;
border:1px solid #424e73;
color:white;
font-size:17px;
margin-bottom:20px;
}

.card{
background:#171f38;
padding:22px;
border-radius:15px;
margin-bottom:15px;
border:1px solid #303c60;
}

.word{
font-size:29px;
color:#62caff;
direction:ltr;
text-align:left;
margin-bottom:12px;
}

.translation{font-size:20px;margin:12px 0}

.level{
display:inline-block;
padding:6px 12px;
border-radius:7px;
background:#4935bd;
margin-bottom:12px;
}

.levels{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(130px,1fr));
gap:12px;
margin-bottom:25px;
}

.level-card{
padding:25px 10px;
background:#171f38;
border:1px solid #3c4770;
border-radius:15px;
text-align:center;
cursor:pointer;
}

.level-card:hover{background:#29345b}

.level-card h3{font-size:25px;margin-bottom:8px}

.stats{
display:flex;
gap:10px;
flex-wrap:wrap;
margin:20px 0;
}

.stat{
flex:1;
min-width:120px;
background:#171f38;
padding:20px;
border-radius:12px;
text-align:center;
}

.stat strong{
display:block;
font-size:25px;
color:#64caff;
margin-top:10px;
}

.option{
display:block;
width:100%;
text-align:right;
margin:10px 0;
background:#293450;
}

.option.correct{background:#13834b}
.option.wrong{background:#b52d42}

#quizResult{
font-size:23px;
text-align:center;
padding:20px;
}

footer{
text-align:center;
padding:30px;
color:#929bb8;
}

#exam .card button{margin:8px 5px}
#examFeedback{font-size:17px}
.grammar-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin:18px 0}
.grammar-card{background:#171f38;border:1px solid #3c4770;border-radius:14px;padding:18px}
.grammar-card h3{color:#64caff;margin-bottom:10px}
.grammar-card p,.grammar-card li{line-height:1.9}
.grammar-card ul{padding-right:20px;margin:10px 0}
.grammar-question{margin:15px 0;padding:15px;background:#202b49;border-radius:12px}

header{position:relative;overflow:hidden;background:linear-gradient(115deg,rgba(79,70,229,.96),rgba(14,165,233,.92) 55%,rgba(168,85,247,.92));border-bottom:1px solid rgba(255,255,255,.18);box-shadow:0 16px 50px rgba(14,165,233,.16)}
header:before,header:after{content:"";position:absolute;border:1px solid rgba(255,255,255,.16);border-radius:50%;pointer-events:none}header:before{width:260px;height:260px;top:-175px;right:8%}header:after{width:190px;height:190px;bottom:-145px;left:12%}
header h1{position:relative;text-shadow:0 4px 22px rgba(0,0,0,.24)}header p{position:relative;color:rgba(255,255,255,.9)}
nav{position:sticky;top:0;z-index:20;background:rgba(10,16,37,.82);border-bottom:1px solid rgba(148,163,184,.18);backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);box-shadow:0 8px 30px rgba(0,0,0,.2)}
button{position:relative;overflow:hidden;background:linear-gradient(135deg,#6366f1,#8b5cf6 52%,#0ea5e9);color:#fff;font-weight:700;border:1px solid rgba(255,255,255,.16);box-shadow:0 7px 18px rgba(79,70,229,.22);transition:transform .22s ease,box-shadow .22s ease,filter .22s ease}
button:after{content:"";position:absolute;inset:0;left:-120%;background:linear-gradient(110deg,transparent,rgba(255,255,255,.2),transparent);transition:left .55s ease;pointer-events:none}
button:hover{opacity:1;transform:translateY(-3px);filter:saturate(1.18);box-shadow:0 12px 26px rgba(99,102,241,.32)}button:hover:after{left:120%}button:active{transform:translateY(-1px) scale(.98)}button:focus-visible{outline:3px solid #67e8f9;outline-offset:3px}
.container{position:relative;z-index:1}
.card,.grammar-card,.stat,.level-card{background:linear-gradient(145deg,rgba(25,35,67,.88),rgba(14,22,47,.88));border:1px solid rgba(148,163,184,.22);box-shadow:0 14px 36px rgba(0,0,0,.18),inset 0 1px rgba(255,255,255,.035);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px)}
.card{transition:border-color .25s ease,box-shadow .25s ease}.card:hover{border-color:rgba(129,140,248,.42);box-shadow:0 18px 42px rgba(0,0,0,.24)}
.level-card{transition:transform .22s ease,border-color .22s ease,background .22s ease}.level-card:hover{transform:translateY(-5px);border-color:#818cf8;background:linear-gradient(145deg,rgba(49,46,129,.65),rgba(14,116,144,.35))}
h2{color:#7dd3fc;text-shadow:0 0 22px rgba(56,189,248,.14)}
input{background:rgba(15,23,42,.82);border-color:rgba(129,140,248,.35)}input:focus{outline:none;border-color:#67e8f9;box-shadow:0 0 0 3px rgba(103,232,249,.13)}
.option{background:linear-gradient(120deg,#263653,#29365a);border:1px solid rgba(148,163,184,.14)}.option.correct{background:linear-gradient(120deg,#047857,#16a34a)}.option.wrong{background:linear-gradient(120deg,#be123c,#e11d48)}
#celebrationLayer{position:fixed;inset:0;z-index:9999;pointer-events:none;overflow:hidden}
.celebration-banner{position:fixed;z-index:10000;top:18px;left:50%;transform:translateX(-50%);padding:14px 24px;border-radius:18px;text-align:center;direction:rtl;color:white;font-size:clamp(18px,3vw,26px);font-weight:800;background:linear-gradient(120deg,rgba(79,70,229,.96),rgba(219,39,119,.96),rgba(8,145,178,.96));border:1px solid rgba(255,255,255,.35);box-shadow:0 16px 45px rgba(0,0,0,.35);animation:celebratePop .55s cubic-bezier(.2,1.4,.4,1) both}
@keyframes celebratePop{from{opacity:0;transform:translate(-50%,-25px) scale(.65)}to{opacity:1;transform:translate(-50%,0) scale(1)}}
.confetti-piece{position:absolute;top:-24px;opacity:.95;animation:confettiFall var(--fall-time,3.4s) linear forwards}
@keyframes confettiFall{to{transform:translate3d(var(--drift,0px),110vh,0) rotate(var(--spin-end,900deg));opacity:.1}}
.celebration-spark{position:absolute;width:7px;height:7px;border-radius:50%;background:#fff;box-shadow:0 0 16px 5px rgba(255,255,255,.7);animation:sparkle 1s ease-out forwards}
@keyframes sparkle{from{opacity:1;transform:scale(.2)}to{opacity:0;transform:scale(3)}}
@media(max-width:600px){header{padding:28px 12px}header h1{font-size:29px}nav{gap:7px;padding:10px}nav button{padding:10px 12px;font-size:13px}.card{padding:17px}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{scroll-behavior:auto!important;animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}}

</style>
</head>

<body>

<header>
<h1>🌍 English Master</h1>
<p>تعلم الإنجليزية من الصفر حتى الاحتراف</p>
</header>

<nav>
<button onclick="showPage('home')">🏠 الرئيسية</button>
<button onclick="showPage('dictionary')">📚 القاموس</button>
<button onclick="showPage('levels')">🎓 المستويات</button>
<button onclick="showPage('exam')">📝 الامتحانات</button>
<button onclick="showPage('favorites')">❤️ المفضلة</button>
<button onclick="showPage('grammar')">📖 القواعد</button>
</nav>

<div class="container">

<section id="home" class="page active">

<h2>مرحباً بك في English Master!</h2>

<div class="card">
<h3>تعلم الإنجليزية بطريقة احترافية</h3>
<p style="margin-top:15px;line-height:2">
ابدأ من مستوى A1 وتقدم تدريجياً حتى تصل إلى C2.
تعلم الكلمات، استمع إلى النطق، واختبر معلوماتك.
</p>
</div>

<div class="stats">

<div class="stat">
الكلمات المفضلة
<strong id="favCount">0</strong>
</div>

<div class="stat">
الامتحانات
<strong id="examCount">0</strong>
</div>

<div class="stat">
أفضل علامة
<strong id="bestScore">0%</strong>
</div>

<div class="stat">
إجمالي الكلمات
<strong id="wordCount">0</strong>
</div>

</div>

<h2>اختر مستواك</h2>

<div class="levels" id="homeLevels"></div>

</section>

<section id="dictionary" class="page">

<h2>📚 القاموس الإنجليزي العربي</h2>

<input id="search"
placeholder="ابحث عن كلمة إنجليزية أو عربية..."
oninput="searchWords()">

<div class="levels" id="dictionaryFilters"></div>

<div id="wordList"></div>

</section>

<section id="levels" class="page">

<h2>🎓 مستويات اللغة الإنجليزية</h2>

<div class="levels" id="levelCards"></div>

<div id="levelInfo"></div>

</section>

<section id="exam" class="page">

<h2>📝 امتحان اللغة الإنجليزية</h2>

<div id="examStart">
<div class="card" style="border:2px solid #64caff">
<h3>🎯 اختبار تحديد مستوى اللغة الإنجليزية</h3>
<p style="line-height:2;margin:10px 0">امتحان شامل من A1 إلى C2، يحتوي على 90 سؤال معاني: 15 سؤالاً لكل مستوى. إذا أخطأت في 5 أسئلة متتالية ضمن المستوى نفسه، يتوقف الاختبار ويُحدد مستواك عند هذا المستوى.</p>
<button type="button" onclick="startLevelAssessment()">ابدأ اختبار تحديد المستوى</button>
</div>
<div class="card">
<p>اختر نوع الامتحان:</p><br>
<div class="levels">
<button onclick="chooseExamMode('choice')">1️⃣ تحديد الإجابة الصحيحة</button>
<button onclick="chooseExamMode('dictation')">2️⃣ الاستماع وكتابة الكلمة</button>
<button onclick="chooseExamMode('pronunciation')">3️⃣ قراءة الكلمة بالمايك</button>
<button onclick="chooseExamMode('arabicToEnglish')">4️⃣ المعنى بالعربي واكتب بالإنجليزي</button>
<button onclick="chooseExamMode('wordToPronunciation')">5️⃣ الكلمة بالإنجليزي وانطقها</button>
</div>
<p id="modeHint" style="line-height:2">اختَر طريقة الامتحان، وبعدها اختَر المستوى.</p>
<p>كل امتحان يحتوي على 15 سؤالاً.</p>
</div>
<div class="card"><p>اختر المستوى:</p><br><div class="levels" id="examButtons"></div></div>
</div>

<div id="quiz" style="display:none">
<div id="progress"></div>
<div class="card">
<h3 id="question"></h3>
<div id="options"></div>
<div id="examFeedback" style="margin-top:15px;line-height:2"></div>
</div>
<button id="nextButton" onclick="nextQuestion()">السؤال التالي</button>
</div>

<div id="quizResult"></div>
<div id="levelAssessment" style="display:none"></div>

</section>


<section id="favorites" class="page">

<h2>❤️ الكلمات المفضلة</h2>

<div id="favoriteList"></div>

</section>
<section id="grammar" class="page">
<h2>📖 قواعد اللغة الإنجليزية</h2>
<p style="line-height:2;margin-bottom:15px">اختر القاعدة لقراءة الاستخدام والدلالات وتركيب الجملة، ثم حل امتحاناً من 15 سؤالاً.</p>
<div class="grammar-grid" id="grammarTopics">
<div class="grammar-card" id="verbPatternsGrammarCard">
<h3>Verb Patterns</h3>
<p>أنماط الأفعال: متى نستخدم to + V1 ومتى نستخدم verb-ing، وما الذي يأتي قبل الفعل وبعده.</p>
<br><button type="button" onclick="openGrammar('verbPatterns')">شرح القاعدة والامتحان</button>
</div>
</div><div id="grammarLesson"></div>
</section>

</div>

<footer>
English Master © 2026
<br><br>
تعلم كلمة جديدة كل يوم 🌍
</footer>

<script>
// ===================================
// قاعدة الكلمات
// ===================================

const words = [];

function addLevel(level,data){
 data.split(";").forEach(entry=>{
  const parts=entry.split("|");
  if(parts.length===2){
   const word=parts[0].trim(), translation=parts[1].trim();
   if(!word || !translation) return;
   if(!words.some(x=>x.l===level && x.w.toLowerCase()===word.toLowerCase())){
    words.push({w:word,t:translation,l:level});
   }
  }
 });
}

// ===================================
// A1 - مبتدئ
// ===================================

addLevel("A1",`

Hello|مرحبا;
Beautiful|جميل;
Apple|تفاحة;
School|مدرسة;
Friend|صديق;
Love|حب;
Water|ماء;
House|منزل;
Book|كتاب;
Family|عائلة;
Cat|قطة;
Dog|كلب;
Food|طعام;
Happy|سعيد;
Morning|صباح;

Mother|أم;
Father|أب;
Sister|أخت;
Brother|أخ;
Baby|طفل رضيع;
Child|طفل;
Woman|امرأة;
Man|رجل;
Teacher|معلم;
Student|طالب;
Doctor|طبيب;
Nurse|ممرض;
Driver|سائق;
Farmer|مزارع;
Cook|طباخ;
City|مدينة;
Village|قرية;
Street|شارع;
Room|غرفة;
Kitchen|مطبخ;
Bedroom|غرفة نوم;
Door|باب;
Window|نافذة;
Table|طاولة;
Chair|كرسي;
Bed|سرير;
Car|سيارة;
Bus|حافلة;
Train|قطار;
Bike|دراجة;
Shop|متجر;
Market|سوق;
Money|مال;
Phone|هاتف;
Computer|حاسوب;
Music|موسيقى;
Movie|فيلم;
Game|لعبة;
Ball|كرة;
Run|يركض;
Walk|يمشي;
Eat|يأكل;
Drink|يشرب;
Sleep|ينام;
Read|يقرأ;
Write|يكتب;
Speak|يتحدث;
Listen|يستمع;
Play|يلعب

`);

// ===================================
// A2 - أساسي
// ===================================

addLevel("A2",`

Airport|مطار;
Journey|رحلة;
Weather|طقس;
Shopping|تسوق;
Healthy|صحي;
Dangerous|خطير;
Remember|يتذكر;
Improve|يحسن;
Decision|قرار;
Experience|تجربة;
Possible|ممكن;
Important|مهم;
Different|مختلف;
Usually|عادة;
Careful|حذر;

Arrive|يصل;
Borrow|يستعير;
Cancel|يلغي;
Carry|يحمل;
Choose|يختار;
Collect|يجمع;
Compare|يقارن;
Continue|يستمر;
Create|ينشئ;
Describe|يصف;
Discover|يكتشف;
Invite|يدعو;
Explain|يشرح;
Forget|ينسى;
Happen|يحدث;
Hope|يأمل;
Include|يتضمن;
Leave|يغادر;
Lend|يقرض;
Miss|يفتقد;
Offer|يعرض;
Order|يطلب;
Plan|يخطط;
Prepare|يجهز;
Promise|يعد;
Receive|يستلم;
Return|يعود;
Save|يوفر;
Spend|ينفق;
Suggest|يقترح;
Travel|يسافر;
Visit|يزور;
Wait|ينتظر;
Worry|يقلق;
Advice|نصيحة;
Appointment|موعد;
Building|مبنى;
Customer|زبون;
Exercise|تمرين;
Health|صحة;
Invitation|دعوة;
Language|لغة;
Message|رسالة;
Passenger|راكب;
Recipe|وصفة;
Ticket|تذكرة;
Traffic|حركة المرور;
Holiday|عطلة;
Museum|متحف;
Station|محطة

`);

// ===================================
// B1 - متوسط
// ===================================

addLevel("B1",`

Achievement|إنجاز;
Environment|بيئة;
Opportunity|فرصة;
Relationship|علاقة;
Confidence|ثقة;
Knowledge|معرفة;
Development|تطوير;
Challenge|تحدي;
Advantage|ميزة;
Responsible|مسؤول;
Communicate|يتواصل;
Independent|مستقل;
Influence|تأثير;
Research|بحث;
Successful|ناجح;

Ability|قدرة;
Advice|نصيحة;
Agree|يوافق;
Appear|يظهر;
Arrange|يرتب;
Attention|انتباه;
Behavior|سلوك;
Believe|يؤمن;
Benefit|فائدة;
Career|مهنة;
Cause|سبب;
Certain|متأكد;
Comfortable|مرتاح;
Community|مجتمع;
Complete|يكمل;
Consider|يعتبر;
Culture|ثقافة;
Decrease|ينخفض;
Describe|يصف;
Education|تعليم;
Effect|تأثير;
Effort|جهد;
Encourage|يشجع;
Energy|طاقة;
Especially|خصوصاً;
Event|حدث;
Government|حكومة;
Growth|نمو;
Identify|يحدد;
Imagine|يتخيل;
Increase|يزيد;
Individual|فرد;
Manage|يدير;
Necessary|ضروري;
Opinion|رأي;
Organize|ينظم;
Particular|معين;
Perform|يؤدي;
Prevent|يمنع;
Purpose|هدف;
Quality|جودة;
Reason|سبب;
Reduce|يقلل;
Require|يتطلب;
Solution|حل;
Support|يدعم;
Tradition|تقليد;
Value|قيمة

`);

// ===================================
// B2 - فوق المتوسط
// ===================================

addLevel("B2",`

Consequently|وبناءً على ذلك;
Significant|مهم أو ملحوظ;
Controversial|مثير للجدل;
Sustainable|مستدام;
Inevitable|حتمي;
Comprehensive|شامل;
Furthermore|علاوة على ذلك;
Achievement|إنجاز;
Establish|يؤسس;
Assumption|افتراض;
Appropriate|ملائم;
Negotiate|يتفاوض;
Perspective|وجهة نظر;
Consequence|نتيجة;
Nevertheless|مع ذلك;

Accomplish|ينجز;
Accurate|دقيق;
Acknowledge|يعترف;
Adequate|كاف;
Alternative|بديل;
Analyze|يحلل;
Approach|نهج;
Assess|يقيّم;
Attitude|موقف;
Available|متاح;
Capacity|سعة;
Circumstance|ظرف;
Clarify|يوضح;
Complex|معقد;
Concentrate|يركز;
Conduct|يجري;
Conflict|صراع;
Consistent|متسق;
Construct|يبني;
Consume|يستهلك;
Contrast|تباين;
Contribute|يساهم;
Convince|يقنع;
Cooperate|يتعاون;
Decline|يتراجع;
Demonstrate|يوضح;
Determine|يحدد;
Distribute|يوزع;
Emphasize|يؤكد;
Estimate|يقدر;
Evidence|دليل;
Expand|يوسع;
Factor|عامل;
Flexible|مرن;
Function|وظيفة;
Generate|يولد;
Impact|تأثير;
Implement|ينفذ;
Indicate|يشير;
Interpret|يفسر;
Maintain|يحافظ;
Majority|أغلبية;
Modify|يعدل;
Obtain|يحصل على;
Participate|يشارك;
Policy|سياسة;
Principle|مبدأ;
Significance|أهمية;
Strategy|استراتيجية;
Valid|صالح

`);

// ===================================
// C1 - متقدم
// ===================================

addLevel("C1",`

Ubiquitous|موجود في كل مكان;
Meticulous|دقيق للغاية;
Ambiguous|غامض أو ملتبس;
Exacerbate|يزيد الأمر سوءاً;
Pragmatic|عملي وواقعي;
Paradigm|نموذج فكري;
Substantial|جوهري أو كبير;
Deteriorate|يتدهور;
Intricate|معقد ودقيق;
Resilient|قادر على التعافي;
Scrutinize|يدقق بعناية;
Inevitably|بشكل حتمي;
Articulate|يعبر بوضوح;
Prevalent|شائع الانتشار;
Plausible|معقول أو محتمل;

Abundant|وفير;
Adverse|سلبي;
Advocate|يدافع عن;
Albeit|رغم أن;
Allocate|يخصص;
Apprehensive|قلق ومتوتر;
Arbitrary|اعتباطي;
Assert|يؤكد;
Attain|يحقق;
Authentic|أصيل;
Coherent|مترابط;
Compelling|مقنع;
Conceive|يتصور;
Conventional|تقليدي;
Credible|موثوق;
Cumulative|تراكمي;
Deprive|يحرم;
Detrimental|ضار;
Discrepancy|اختلاف;
Elaborate|مفصل;
Empirical|تجريبي;
Endeavor|مسعى;
Exemplary|مثالي;
Explicit|صريح;
Feasible|قابل للتنفيذ;
Fluctuate|يتذبذب;
Formulate|يصوغ;
Foster|يعزز;
Fundamental|أساسي;
Imminent|وشيك;
Implicit|ضمني;
Inherent|متأصل;
Innovative|مبتكر;
Legitimate|شرعي;
Lucrative|مربح;
Manipulate|يتلاعب;
Mitigate|يخفف;
Notion|مفهوم;
Obsolete|قديم ومتجاوز;
Persistent|مستمر;
Profound|عميق;
Reinforce|يعزز;
Reluctant|متردد;
Scrupulous|شديد الدقة;
Simultaneous|متزامن;
Tentative|مؤقت;
Transparent|شفاف;
Undermine|يقوض;
Versatile|متعدد الاستخدامات;
Viable|قابل للاستمرار

`);

// ===================================
// C2 - إتقان
// ===================================

addLevel("C2",`

Abstruse|غامض وصعب الفهم;
Acquiesce|يذعن;
Acrimony|حدة ومرارة;
Alacrity|حماس وسرعة;
Ameliorate|يحسن;
Anachronism|مفارقة زمنية;
Anathema|شيء مكروه بشدة;
Antithetical|متناقض تماماً;
Apocryphal|مشكوك في صحته;
Assiduous|مجتهد ومثابر;
Austere|صارم وبسيط;
Bellicose|ميال للقتال;
Capricious|متقلب المزاج;
Castigate|يوبخ بشدة;
Circumspect|حذر ومتأن;
Cogent|مقنع ومنطقي;
Conundrum|لغز محير;
Copious|وفير جداً;
Deleterious|ضار;
Demagogue|شخص يستغل مشاعر الجماهير;
Desultory|عشوائي وغير منتظم;
Diatribe|هجوم لفظي طويل;
Didactic|تعليمي ووعظي;
Disparate|مختلف جذرياً;
Ebullient|مفعم بالحيوية;
Eclectic|انتقائي;
Effrontery|وقاحة;
Enervate|يضعف;
Ephemeral|قصير الأمد;
Equivocate|يراوغ في الكلام;
Esoteric|خاص بفئة محدودة;
Exonerate|يبرئ;
Fastidious|شديد التدقيق;
Garrulous|ثرثار;
Grandiloquent|متكلف في الكلام;
Iconoclast|متمرد على المعتقدات;
Idiosyncrasy|صفة مميزة;
Impecunious|فقير;
Inchoate|غير مكتمل;
Intransigent|متعنت;
Laconic|مقتضب;
Magnanimous|كريم النفس;
Mendacious|كاذب;
Munificent|سخي جداً;
Obfuscate|يعقد الأمور;
Obsequious|متملق;
Onerous|مرهق;
Ostentatious|استعراضي;
Pernicious|مدمر وضار;
Perspicacious|نافذ البصيرة;
Quintessential|مثالي ونموذجي;
Recalcitrant|متمرد;
Recondite|عميق وصعب;
Sanguine|متفائل;
Sycophant|متملق;
Trenchant|حاد وقوي;
Truculent|عدواني;
Vacillate|يتردد;
Venerable|موقر;
Veracity|صدق;
Vicissitude|تقلب;
Vindicate|يثبت براءته;
Vitriolic|لاذع وقاس;
Zealous|متحمس بشدة

`);


// 50 كلمة إضافية لكل مستوى: 300 كلمة جديدة

addLevel("A1",`
Afternoon|بعد الظهر;Evening|مساء;Night|ليل;Today|اليوم;Tomorrow|غداً;Yesterday|أمس;Week|أسبوع;Month|شهر;Year|سنة;Time|وقت;Minute|دقيقة;Hour|ساعة;Number|رقم;Name|اسم;Age|عمر;Country|دولة;Language|لغة;English|اللغة الإنجليزية;Arabic|اللغة العربية;Color|لون;Red|أحمر;Blue|أزرق;Green|أخضر;Black|أسود;White|أبيض;Big|كبير;Small|صغير;Long|طويل;Short|قصير;New|جديد;Old|قديم;Good|جيد;Bad|سيئ;Hot|حار;Cold|بارد;Open|يفتح;Close|يغلق;Start|يبدأ;Finish|ينتهي;Buy|يشتري;Sell|يبيع;Give|يعطي;Take|يأخذ;Come|يأتي;Go|يذهب;See|يرى;Look|ينظر;Know|يعرف;Like|يحب;Need|يحتاج
`);

addLevel("A2",`
Accommodation|مكان إقامة;Advertisement|إعلان;Agreement|اتفاق;Application|طلب أو تطبيق;Argument|جدال;Competition|منافسة;Conversation|محادثة;Culture|ثقافة;Customer|عميل;Department|قسم;Direction|اتجاه;Entrance|مدخل;Equipment|معدات;Fare|أجرة;Flight|رحلة جوية;Foreign|أجنبي;Guest|ضيف;Information|معلومات;Location|موقع;Neighbor|جار;Payment|دفعة مالية;Permission|إذن;Pollution|تلوث;Population|سكان;Queue|طابور;Recently|مؤخراً;Reservation|حجز;Service|خدمة;Several|عدة;Situation|موقف;Surprised|متفاجئ;Temperature|درجة الحرارة;Traditional|تقليدي;Transport|نقل;Useful|مفيد;Vacation|إجازة;Waste|نفايات;Wonderful|رائع;Accept|يقبل;Achieve|يحقق;Advise|ينصح;Allow|يسمح;Avoid|يتجنب;Belong|ينتمي;Complain|يشتكي;Depend|يعتمد;Enjoy|يستمتع;Prepare|يحضّر;Protect|يحمي;Recommend|يوصي
`);

addLevel("B1",`
Ambition|طموح;Analysis|تحليل;Attempt|محاولة;Average|متوسط;Background|خلفية;Circumstance|ظرف;Commitment|التزام;Concern|قلق أو اهتمام;Conclusion|استنتاج;Connection|اتصال;Contribution|مساهمة;Creativity|إبداع;Demand|طلب;Disadvantage|عيب;Disaster|كارثة;Employment|توظيف;Encounter|مواجهة;Essential|ضروري;Estimate|تقدير;Failure|فشل;Feature|ميزة;Focus|تركيز;Generation|جيل;Goal|هدف;Identity|هوية;Issue|قضية;Leadership|قيادة;Method|طريقة;Motivation|دافع;Outcome|نتيجة;Percentage|نسبة مئوية;Performance|أداء;Pressure|ضغط;Progress|تقدم;Resource|مورد;Risk|مخاطرة;Strength|قوة;Task|مهمة;Theory|نظرية;Threat|تهديد;Trend|اتجاه سائد;Volunteer|متطوع;Adapt|يتكيف;Appreciate|يقدّر;Establish|يؤسس;Examine|يفحص;Handle|يتعامل مع;Mention|يذكر;Recognize|يتعرف على;Respond|يرد
`);

addLevel("B2",`
Abstract|مجرد;Adaptation|تكيّف;Aggregate|إجمالي;Albeit|رغم ذلك;Apparent|واضح;Bias|تحيز;Briefing|إحاطة;Coherent|مترابط;Commodity|سلعة;Compensate|يعوض;Competent|كفؤ;Component|مكوّن;Constitute|يشكل;Constraint|قيد;Contemporary|معاصر;Contradict|يناقض;Crucial|حاسم;Debate|نقاش;Deduce|يستنتج;Deficiency|نقص;Dimension|بُعد;Distinguish|يميز;Diverse|متنوع;Domestic|محلي;Eliminate|يزيل;Enhance|يعزز;Ethical|أخلاقي;Exceed|يتجاوز;Expenditure|إنفاق;Exposure|تعرض;Framework|إطار;Incentive|حافز;Insight|فهم عميق;Integrate|يدمج;Intervene|يتدخل;Justify|يبرر;Legislation|تشريع;Monitor|يراقب;Objective|موضوعي;Phenomenon|ظاهرة;Prioritize|يرتب حسب الأولوية;Regulate|ينظم;Relevant|ذو صلة;Restrict|يقيد;Substitute|بديل;Underlying|أساسي أو كامن;Valid|صالح;Welfare|رفاه;Whereas|بينما;Virtue|فضيلة
`);

addLevel("C1",`
Adversity|محنة;Aesthetic|جمالي;Anomaly|حالة شاذة;Aptitude|استعداد;Benevolent|محسن;Bolster|يدعم;Bureaucracy|بيروقراطية;Catalyst|عامل محفز;Cohesive|متماسك;Concede|يقرّ;Connotation|دلالة ضمنية;Corroborate|يؤيد بالدليل;Cumbersome|مرهق;Decisive|حاسم;Disseminate|ينشر;Eloquent|فصيح;Exemplify|يضرب مثالاً;Exhaustive|شامل ومستقصٍ;Facilitate|يسهّل;Frivolous|تافه;Impartial|محايد;Inadvertent|غير مقصود;Incompatible|غير متوافق;Indispensable|لا غنى عنه;Inept|غير كفؤ;Inhibit|يعيق;Juxtapose|يضع جنباً إلى جنب;Nuance|فارق دقيق;Paramount|بالغ الأهمية;Perpetuate|يديم;Predominant|سائد;Proponent|مؤيد;Reconcile|يوفّق;Redundant|زائد عن الحاجة;Repercussion|تداعٍ;Rhetoric|بلاغة;Salient|بارز;Scrutiny|تدقيق;Sporadic|متقطع;Substantiate|يدعم بالأدلة;Succinct|موجز;Superficial|سطحي;Tangible|ملموس;Thorough|شامل ودقيق;Transcend|يتجاوز;Unprecedented|غير مسبوق;Vindictive|انتقامي;Warrant|يبرر;Withstand|يتحمل;Yield|يسفر عن
`);

addLevel("C2",`
Abdicate|يتنازل عن العرش;Abeyance|تعليق مؤقت;Abjure|ينبذ;Abrogate|يلغي رسمياً;Admonish|يوبخ;Anodyne|غير مثير للجدل;Antipathy|نفور;Apotheosis|قمة الكمال;Assuage|يخفف;Banal|مبتذل;Bastion|حصن أو معقل;Bifurcate|ينقسم إلى فرعين;Cacophony|نشاز;Cajole|يستميل بالإلحاح;Calumny|افتراء;Chicanery|خداع;Conciliatory|تصالحي;Contumacious|عاصٍ;Corollary|نتيجة منطقية;Cupidity|جشع;Debilitate|يضعف;Defenestration|إلقاء من النافذة;Demur|يعترض;Dissemble|يتظاهر;Efficacy|فعالية;Encomium|مديح;Enigmatic|غامض;Erudite|واسع المعرفة;Exculpate|يبرئ;Exigent|ملحّ;Fecund|خصب;Fervent|متحمس;Germane|وثيق الصلة;Hegemony|هيمنة;Inimical|معادٍ;Inveigh|يهاجم بالكلام;Lugubrious|كئيب;Malleable|قابل للتشكيل;Misanthrope|كاره البشر;Nefarious|شرير;Obdurate|عنيد;Palliate|يخفف;Panacea|حل شامل;Pejorative|انتقاصي;Polemical|جدلي;Proclivity|ميل;Profligate|مسرف;Reprobate|فاسق;Soporific|منوّم;Stultify|يعيق أو يبلّد
`);



// كلمات إضافية لاستكمال قاموس الألف كلمة
addLevel("A1",`
Yesterday's|الذي حدث أمس;
Father-in-law|حمو;
Grandmother|جدة;
Grandfather|جد;
Parents|والدان;
Cousin|ابن أو ابنة العم أو الخال;
Uncle|عم أو خال;
Aunt|عمة أو خالة;
Son|ابن;
Daughter|ابنة;
Husband|زوج;
Wife|زوجة;
People|ناس;
Person|شخص;
Animal|حيوان;
Bird|طائر;
Fish|سمكة;
Horse|حصان;
Cow|بقرة;
Sheep|خروف;
Chicken|دجاجة;
Egg|بيضة;
Bread|خبز;
Milk|حليب;
Cheese|جبنة;
Rice|أرز;
Meat|لحم;
Fruit|فاكهة;
Vegetable|خضار;
Banana|موزة;
Orange|برتقالة;
Grape|عنب;
Potato|بطاطا;
Tomato|بندورة;
Sugar|سكر;
Salt|ملح;
Breakfast|فطور;
Lunch|غداء;
Dinner|عشاء;
Cup|كوب;
Plate|صحن;
Spoon|ملعقة;
Fork|شوكة;
Knife|سكين;
Bag|حقيبة;
Shoes|حذاء;
Shirt|قميص;
Trousers|بنطال;
Dress|فستان;
Hat|قبعة;
Rain|مطر;
Sun|شمس;
Moon|قمر;
Star|نجمة
`);

addLevel("A2",`
Abroad|في الخارج;
Actually|في الحقيقة;
Almost|تقريباً;
Although|على الرغم من;
Among|بين;
Asleep|نائم;
Attractive|جذاب;
Baggage|أمتعة;
Booking|حجز;
Business|عمل تجاري;
Comfort|راحة;
Convenient|مريح;
Cough|سعال;
Accident|حادث;
Activity|نشاط;
Adult|بالغ;
Announcement|إعلان;
Anxious|قلق;
Area|منطقة;
Article|مقال;
Author|مؤلف;
Basic|أساسي;
Bill|فاتورة;
Boil|يغلي;
Calm|هادئ;
Cash|نقد;
Celebrate|يحتفل;
Climate|مناخ;
Crowded|مزدحم;
Damage|ضرر;
Deliver|يوصل;
Departure|مغادرة;
Destination|وجهة;
Develop|يطور;
Device|جهاز;
Diary|مذكرات;
Digital|رقمي;
Disease|مرض;
Drawer|درج;
Dust|غبار;
Emergency|حالة طوارئ;
Employee|موظف;
Employer|صاحب عمل;
Factory|مصنع;
Gift|هدية;
Guide|دليل;
Industry|صناعة;
Local|محلي;
Luck|حظ;
Meeting|اجتماع;
Notice|ملاحظة;
Patient|مريض;
Perhaps|ربما;
Quiet|هادئ;
Repair|يصلح
`);

addLevel("B1",`
Aware|واعٍ;
Brief|موجز;
Cope|يتأقلم;
Abandon|يتخلى عن;
Accuse|يتهم;
Admire|يعجب بـ;
Admit|يعترف;
Advance|يتقدم;
Affect|يؤثر في;
Afford|يستطيع تحمل التكلفة;
Announce|يعلن;
Apologize|يعتذر;
Apply|يتقدم بطلب;
Argue|يجادل;
Arrest|يعتقل;
Attend|يحضر;
Attract|يجذب;
Blame|يلوم;
Compete|يتنافس;
Confuse|يربك;
Consist|يتكون;
Curious|فضولي;
Deny|ينكر;
Deserve|يستحق;
Destroy|يدمر;
Escape|يهرب;
Exhausted|منهك;
Familiar|مألوف;
Former|سابق;
Generous|كريم;
Graduate|يتخرج;
Hesitate|يتردد;
Ignore|يتجاهل;
Impress|يبهر;
Involve|يشمل;
Lack|يفتقر إلى;
Limit|يحد;
Measure|يقيس;
Persuade|يقنع;
Predict|يتنبأ;
Publish|ينشر;
Remind|يذكر;
Replace|يستبدل;
Request|يطلب;
Reveal|يكشف;
Satisfy|يرضي;
Separate|يفصل;
Strengthen|يقوي;
Survive|ينجو;
Treat|يعامل
`);

addLevel("B2",`
Advancement|تقدم;
Arise|ينشأ;
Assertion|تأكيد;
Cease|يكف;
Consecutive|متتالٍ;
Contrary|مخالف;
Depict|يصور;
Disclose|يفصح;
Distort|يشوه;
Endorsement|تأييد;
Abnormal|غير طبيعي;
Abuse|إساءة;
Amend|يعدل;
Analogy|تشبيه;
Anticipate|يتوقع;
Apparatus|جهاز;
Aspect|جانب;
Asset|أصل أو مورد;
Authority|سلطة;
Beneficial|مفيد;
Boundary|حد;
Civilian|مدني;
Collaborate|يتعاون;
Compromise|حل وسط;
Confront|يواجه;
Conform|يمتثل;
Conservative|محافظ;
Controversy|جدل;
Coordinate|ينسق;
Corporate|مؤسسي;
Correspond|يتوافق;
Criteria|معايير;
Currency|عملة;
Dedicate|يكرس;
Definite|محدد;
Dispute|نزاع;
Distinct|متميز;
Dominant|مهيمن;
Draft|مسودة;
Dynamic|ديناميكي;
Enforce|يفرض;
Enterprise|مشروع تجاري;
Equivalent|مكافئ;
Exclude|يستثني;
Exhibit|يعرض;
Exploit|يستغل;
External|خارجي;
Flaw|عيب;
Guarantee|ضمان;
Hierarchy|تسلسل هرمي;
Hypothesis|فرضية;
Infrastructure|بنية تحتية
`);

addLevel("C1",`
Abeyant|معلق;
Abhor|يمقت;
Abstain|يمتنع;
Accolade|تكريم;
Acumen|فطنة;
Adulation|إطراء مبالغ فيه;
Affectation|تصنع;
Affluent|ثري;
Aggravate|يفاقم;
Alleviate|يخفف;
Amalgamate|يدمج;
Ample|وفير;
Animosity|عداء;
Arduous|شاق;
Artifice|حيلة;
Ascertain|يتحقق من;
Astute|فطن;
Avert|يتفادى;
Awe|رهبة;
Candid|صريح;
Clandestine|سري;
Commence|يبدأ;
Concur|يتفق;
Condone|يتغاضى عن;
Conspicuous|ملحوظ;
Contentious|مثير للخلاف;
Credence|مصداقية;
Cursory|سطحي وسريع;
Daunting|مخيف;
Debacle|فشل ذريع;
Deference|احترام;
Diligent|مجتهد;
Disdain|ازدراء;
Egregious|فادح;
Elusive|مراوغ;
Encompass|يشمل;
Endorse|يؤيد;
Entail|يستلزم;
Exorbitant|باهظ;
Extol|يمدح;
Fallacy|مغالطة;
Fortuitous|عرضي سعيد;
Impeccable|لا تشوبه شائبة;
Incessant|متواصل;
Indignant|ساخط;
Insidious|خبيث تدريجي;
Intrepid|جريء;
Lament|يندب;
Metaphorical|مجازي;
Negligible|ضئيل;
Ominous|ينذر بالخطر
`);

addLevel("C2",`
Abnegation|إنكار الذات;
Abstrusity|غموض شديد;
Adumbrate|يلمح إلى;
Anfractuous|ملتوي ومعقد;
Apoplectic|شديد الغضب;
Arrant|تام أو واضح;
Asperity|خشونة;
Atavistic|ارتدادي إلى الأصل;
Avarice|طمع;
Baleful|مشؤوم;
Bibulous|محب للشراب;
Bloviate|يتكلم بإسهاب فارغ;
Bucolic|ريفي;
Byzantine|معقد للغاية;
Callous|قاسٍ;
Canard|خبر كاذب;
Chary|حذر;
Choleric|سريع الغضب;
Clemency|رحمة;
Conflagration|حريق هائل;
Contumely|إهانة;
Crepuscular|شبه مظلم;
Defalcation|اختلاس;
Demotic|شعبي;
Desideratum|أمر مرغوب;
Diaphanous|شفاف رقيق;
Disquisition|بحث مطول;
Doughty|شجاع;
Eleemosynary|خيري;
Enervating|مسبب للوهن;
Epistolary|رسائلي;
Exiguous|ضئيل;
Expiate|يكفر عن;
Fatuous|أحمق;
Feckless|عديم الفاعلية;
Felicity|سعادة أو ملاءمة;
Fustian|لغة متكلفة;
Gainsay|ينكر;
Gambit|مناورة افتتاحية;
Gossamer|رقيق كالنسيج;
Harangue|خطبة توبيخية;
Imbroglio|مأزق معقد;
Ineluctable|لا مفر منه;
Insouciant|غير مكترث;
Lachrymose|كثير البكاء;
Lambaste|ينتقد بشدة;
Mawkish|عاطفي بإفراط;
Nugatory|عديم القيمة;
Pellucid|واضح جداً;
Penurious|شديد الفقر;
Persiflage|مزاح ساخر;
Propinquity|قرب
`);



// 200 كلمة جديدة لمستوى A1 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("A1",`
arm|ذراع;back|ظهر;face|وجه;head|رأس;hair|شعر;eye|عين;ear|أذن;nose|أنف;mouth|فم;tooth|سن;hand|يد;finger|إصبع;leg|ساق;foot|قدم;heart|قلب;body|جسم;coat|معطف;jacket|سترة;sock|جورب;skirt|تنورة;jeans|جينز;belt|حزام;watch|ساعة يد;glasses|نظارات;desk|مكتب;sofa|أريكة;lamp|مصباح;mirror|مرآة;wall|جدار;floor|أرضية;ceiling|سقف;garden|حديقة;tree|شجرة;flower|زهرة;grass|عشب;river|نهر;sea|بحر;lake|بحيرة;mountain|جبل;beach|شاطئ;sky|سماء;cloud|غيمة;wind|ريح;snow|ثلج;fire|نار;road|طريق;bridge|جسر;park|منتزه;farm|مزرعة
Monday|الاثنين;Tuesday|الثلاثاء;Wednesday|الأربعاء;Thursday|الخميس;Friday|الجمعة;Saturday|السبت;Sunday|الأحد;January|يناير;February|فبراير;March|مارس;April|أبريل;May|مايو;June|يونيو;July|يوليو;August|أغسطس;September|سبتمبر;October|أكتوبر;November|نوفمبر;December|ديسمبر;spring|الربيع;summer|الصيف;autumn|الخريف;winter|الشتاء;early|مبكر;late|متأخر;fast|سريع;slow|بطيء;easy|سهل;difficult|صعب;right|صحيح أو يمين;wrong|خطأ;near|قريب;far|بعيد;full|ممتلئ;empty|فارغ;clean|نظيف;dirty|متسخ;kind|لطيف;funny|مضحك;strong|قوي;weak|ضعيف;hungry|جائع;thirsty|عطشان;tired|متعب;busy|مشغول;free|متاح;ready|جاهز;safe|آمن;dark|مظلم
wake|يستيقظ;wash|يغسل;brush|يفرش;wear|يرتدي;cut|يقطع;draw|يرسم;sing|يغني;dance|يرقص;swim|يسبح;drive|يقود;ride|يركب;fly|يطير;teach|يدرّس;learn|يتعلم;study|يدرس;work|يعمل;help|يساعد;ask|يسأل;answer|يجيب;call|يتصل;send|يرسل;show|يعرض;bring|يحضر;put|يضع;keep|يحتفظ;find|يجد;think|يفكر;understand|يفهم;meet|يلتقي;pay|يدفع;wait|ينتظر;turn|يدير;move|يتحرك;stop|يتوقف;happen|يحدث;smile|يبتسم;cry|يبكي;laugh|يضحك;begin|يبدأ;end|ينتهي;win|يفوز;lose|يخسر;forget|ينسى;remember|يتذكر;feel|يشعر;touch|يلمس;carry|يحمل
bread|خبز;butter|زبدة;honey|عسل;jam|مربى;soup|حساء;salad|سلطة;sandwich|شطيرة;cake|كعكة;biscuit|بسكويت;coffee|قهوة;tea|شاي;juice|عصير;lemon|ليمون;strawberry|فراولة;watermelon|بطيخ;onion|بصل;cucumber|خيار;carrot|جزر;corn|ذرة;bean|فاصولياء;toy|لعبة;key|مفتاح;map|خريطة;gift|هدية;box|صندوق;letter|رسالة;paper|ورق;pen|قلم;pencil|قلم رصاص;notebook|دفتر;picture|صورة;photo|صورة فوتوغرافية;clock|ساعة;calendar|تقويم;ticket|تذكرة;wallet|محفظة;coin|عملة معدنية;bank|بنك;hospital|مستشفى;library|مكتبة;restaurant|مطعم;hotel|فندق;cinema|سينما;airport|مطار;classroom|صف;office|مكتب;toilet|مرحاض;shopkeeper|صاحب متجر;ankle|كاحل;thumb|إبهام;chin|ذقن;neck|رقبة;shoulder|كتف;knee|ركبة;toe|إصبع القدم;stomach|معدة;cheek|خد;lip|شفة
`);


// 200 كلمة جديدة لمستوى A2 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("A2",`
across|عبر;along|على طول;around|حول;behind|خلف;below|أسفل;beside|بجانب;between|بين;beyond|ما وراء;inside|داخل;outside|خارج;through|من خلال;toward|باتجاه;without|من دون;within|ضمن;against|ضد;above|فوق;opposite|مقابل;straight|مباشرة;upstairs|في الطابق العلوي;downstairs|في الطابق السفلي;somewhere|في مكان ما;anywhere|في أي مكان;nowhere|لا مكان;everywhere|في كل مكان;probably|على الأرجح;especially|خصوصاً;finally|أخيراً;immediately|فوراً;slowly|ببطء;carefully|بحذر;luckily|لحسن الحظ;unfortunately|لسوء الحظ;nearly|تقريباً;exactly|بالضبط;quite|تماماً;rather|إلى حد ما;instead|بدلاً من ذلك;otherwise|وإلا;already|بالفعل;still|ما زال;yet|حتى الآن;once|مرة واحدة;twice|مرتين;daily|يومياً;weekly|أسبوعياً;monthly|شهرياً;annually|سنوياً
accompany|يرافق;advertise|يعلن;apologise|يعتذر;attend|يحضر;believe|يصدق;check|يتحقق;connect|يربط;correct|يصحح;disagree|يختلف;download|ينزّل;earn|يكسب;enter|يدخل;expect|يتوقع;fail|يفشل;fill|يملأ;follow|يتبع;guess|يخمن;imagine|يتخيل;introduce|يقدم;join|ينضم;lift|يرفع;manage|يدير;pack|يحزم;prefer|يفضل;refuse|يرفض;relax|يسترخي;remove|يزيل;repeat|يكرر;reply|يرد;share|يشارك;shout|يصرخ;upload|يرفع ملفاً;warn|يحذر;wish|يتمنى;wonder|يتساءل
appointment|موعد;audience|جمهور;beard|لحية;billboard|لوحة إعلانية;cashier|أمين صندوق;century|قرن;charity|جمعية خيرية;choice|اختيار;colleague|زميل;concert|حفلة موسيقية;continent|قارة;countryside|ريف;crowd|حشد;cycle|دورة;discount|خصم;document|وثيقة;engine|محرك;event|حدث;exchange|تبادل;festival|مهرجان;goal|هدف;habit|عادة;headline|عنوان رئيسي;holidaymaker|مصطاف;instruction|تعليمات;knowledge|معرفة;machine|آلة;magazine|مجلة;neighbourhood|حي;noise|ضوضاء;owner|مالك;package|طرد;photographer|مصور;platform|رصيف;postcard|بطاقة بريدية;price|سعر;programme|برنامج;purpose|غرض;reception|استقبال;refund|استرداد;ability|قدرة;active|نشيط;advantage|ميزة;adventure|مغامرة;alarm|منبه;album|ألبوم;amazing|مدهش;ancient|قديم;ankle|كاحل;arrival|وصول;artist|فنان;assistant|مساعد;athlete|رياضي;attention|انتباه;available|متاح;bakery|مخبز;basement|قبو;battery|بطارية;beach|شاطئ;beginner|مبتدئ;birth|ولادة;blanket|بطانية;blouse|بلوزة;booth|كشك;borrower|مستعير;bowl|وعاء;brand|علامة تجارية;break|استراحة;bright|ساطع;button|زر;cable|كابل;camp|مخيم;capital|عاصمة;captain|قائد;careless|مهمل;carpet|سجادة;cartoon|رسوم متحركة;castle|قلعة;ceiling|سقف;cellphone|هاتف محمول;channel|قناة;cheerful|مبتهج;chest|صدر;chin|ذقن;church|كنيسة;cloudy|غائم;coach|مدرب;coast|ساحل;collector|جامع;comfortable|مريح;common|شائع;company|شركة;copy|نسخة;corner|زاوية;costume|زي;couple|زوجان;creative|مبدع;cupboard|خزانة;curtain|ستارة;decide|يقرر;dentist|طبيب أسنان;dictionary|قاموس;dining room|غرفة طعام;dirty|متسخ;dish|طبق;distance|مسافة;documentary|فيلم وثائقي;double|مزدوج;dream|حلم;driver|سائق;dry|جاف;each|كل واحد;east|شرق;education|تعليم;electric|كهربائي;email|بريد إلكتروني;empty|فارغ;enough|كافٍ;envelope|ظرف;excited|متحمس
`);


// 200 كلمة جديدة لمستوى B1 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("B1",`
absolutely|بالتأكيد;actually|في الواقع;apparently|على ما يبدو;approximately|تقريباً;basically|بشكل أساسي;certainly|بالتأكيد;clearly|بوضوح;currently|حالياً;definitely|بالتأكيد;eventually|في النهاية;fortunately|لحسن الحظ;generally|عموماً;gradually|تدريجياً;hardly|بالكاد;however|مع ذلك;indeed|حقاً;mainly|بشكل رئيسي;obviously|من الواضح;particularly|خصوصاً;possibly|ربما;previously|سابقاً;rarely|نادراً;recently|مؤخراً;similarly|بالمثل;therefore|لذلك;though|رغم ذلك;ultimately|في نهاية المطاف;unlike|على عكس;wherever|أينما;whether|سواء;meanwhile|في هذه الأثناء;moreover|علاوة على ذلك;nevertheless|ومع ذلك;perhaps|ربما;otherwise|وإلا;regardless|بغض النظر;somehow|بطريقة ما;somewhat|إلى حد ما;thus|وهكذا;unless|ما لم;whenever|كلما;whereas|بينما;instead|بدلاً من;besides|بالإضافة;despite|بالرغم من;thereby|وبذلك;accordingly|وفقاً لذلك;consequently|نتيجة لذلك;likewise|كذلك
accomplish|ينجز;analyze|يحلل;appeal|يناشد;appoint|يعيّن;approach|يقترب;approve|يوافق;assume|يفترض;avoid|يتجنب;behave|يتصرف;cancel|يلغي;claim|يدعي;combine|يدمج;commit|يلتزم;concentrate|يركز;confirm|يؤكد;contribute|يساهم;convince|يقنع;criticise|ينتقد;define|يعرّف;demonstrate|يوضح;develop|يطور;disappoint|يخيب;exist|يوجد;expand|يوسع;experience|يختبر;express|يعبر;insist|يصر;maintain|يحافظ;obtain|يحصل;recommend|يوصي
absence|غياب;access|وصول;accident|حادث;account|حساب;advertising|إعلان;agreement|اتفاق;ancestor|سلف;anxiety|قلق;application|طلب;appointment|موعد;argument|جدال;atmosphere|أجواء;attitude|موقف;authority|سلطة;balance|توازن;campaign|حملة;candidate|مرشح;capacity|قدرة;characteristic|صفة;citizen|مواطن;climate|مناخ;communication|تواصل;competition|منافسة;conflict|صراع;consequence|نتيجة;consumer|مستهلك;context|سياق;convenience|راحة;courage|شجاعة;crime|جريمة;crisis|أزمة;currency|عملة;deadline|موعد نهائي;decision|قرار;definition|تعريف;democracy|ديمقراطية;department|قسم;description|وصف;destination|وجهة;discovery|اكتشاف;discussion|نقاش;disease|مرض;economy|اقتصاد;abandonment|تخلٍّ;abroad|الخارج;absence|غياب;academic|أكاديمي;accommodation|سكن;accountant|محاسب;accurate|دقيق;adaptation|تكيف;additional|إضافي;administration|إدارة;admission|قبول;adolescent|مراهق;affair|شأن;agency|وكالة;agenda|جدول أعمال;aggressive|عدواني;agriculture|زراعة;aid|مساعدة;alarm|إنذار;alternative|بديل;amazed|مندهش;amount|كمية;annual|سنوي;apparent|واضح;appreciation|تقدير;appropriate|مناسب;approval|موافقة;arrangement|ترتيب;artificial|اصطناعي;aspect|جانب;assistance|مساعدة;athlete|رياضي;award|جائزة;awareness|وعي;beneficial|مفيد;biography|سيرة ذاتية;belief|اعتقاد;belonging|انتماء;biological|بيولوجي;boundary|حد;branch|فرع;budget|ميزانية;category|فئة;celebration|احتفال;central|مركزي;ceremony|مراسم;charity|عمل خيري;chemical|كيميائي;classic|كلاسيكي;client|عميل;clue|دليل;colleague|زميل;combination|مزيج;commercial|تجاري;commission|لجنة;comparison|مقارنة;complexity|تعقيد;concentration|تركيز;concept|مفهوم;concerned|قلق;condition|حالة;conference|مؤتمر;confusion|ارتباك;conscious|واعٍ;conservation|حفاظ;construction|بناء;consultant|مستشار;contact|اتصال;content|محتوى;contract|عقد;convenient|ملائم;cooperation|تعاون;council|مجلس;criticism|نقد;curiosity|فضول;data|بيانات;debate|مناظرة;debt|دين;decade|عقد;decline|تراجع
`);


// 200 كلمة جديدة لمستوى B2 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("B2",`
abandon|يتخلى عن;abolish|يلغي;absorb|يمتص;accelerate|يسرّع;accommodate|يستوعب;accumulate|يراكم;advocate|يدافع عن;allocate|يخصص;alter|يغير;attain|يحقق;attribute|ينسب;collapse|ينهار;commence|يبدأ;compel|يجبر;compile|يجمع;comprise|يتألف من;conceal|يخفي;conserve|يحافظ على;constrain|يقيد;consult|يستشير;convert|يحول;demolish|يهدم;derive|يشتق;detect|يكتشف;diminish|يقلل;divert|يحول المسار;dominate|يسيطر;emerge|يظهر;emphasise|يشدد;enable|يمكّن;encounter|يصادف;ensure|يضمن;evaluate|يقيّم;exaggerate|يبالغ;abundance|وفرة;accessibility|سهولة الوصول;accordance|توافق;accountability|مساءلة;accuracy|دقة;acquisition|اكتساب;adequacy|كفاية;administration|إدارة;agenda|جدول أعمال;agriculture|زراعة;alliance|تحالف;ambassador|سفير;amendment|تعديل;analyst|محلل;anecdote|حكاية;anniversary|ذكرى سنوية;anonymous|مجهول;appliance|جهاز منزلي;architecture|هندسة معمارية;arithmetic|حساب;artificial|اصطناعي;assessment|تقييم;assistance|مساعدة;automation|أتمتة;awareness|وعي;bankruptcy|إفلاس;barrier|حاجز;biodiversity|تنوع حيوي;bond|رابطة;budget|ميزانية;bureau|مكتب;capability|قدرة;carbon|كربون;category|فئة;certificate|شهادة;circulation|دوران;civilisation|حضارة;coalition|ائتلاف;code|رمز;collaboration|تعاون;commission|لجنة;commitment|التزام;compensation|تعويض;complexity|تعقيد;compliance|امتثال;composition|تركيب;abstraction|تجريد;accessory|ملحق;accomplishment|إنجاز;accumulation|تراكم;activation|تفعيل;adaptable|قابل للتكيف;adjustment|تعديل;administrative|إداري;adoption|تبنٍّ;adverse|سلبي;agricultural|زراعي;allegation|ادعاء;alteration|تغيير;ambiguous|غامض;analytical|تحليلي;ancestor|سلف;anticipation|ترقب;applicable|قابل للتطبيق;applicant|متقدم;appreciate|يقدر;arbitrary|اعتباطي;assign|يكلف;assurance|ضمان;asylum|لجوء;attachment|مرفق;attainable|قابل للتحقيق;authenticity|أصالة;autonomous|مستقل;availability|توافر;beneficiary|مستفيد;biography|سيرة;capitalism|رأسمالية;casualty|ضحية;ceasefire|وقف إطلاق النار;certification|اعتماد;citizenship|مواطنة;classification|تصنيف;collective|جماعي;colonial|استعماري;committed|ملتزم;compelling|مقنع;competence|كفاءة;competitive|تنافسي;complementary|تكميلي;complication|تعقيد;concession|تنازل;configuration|تكوين;conformity|امتثال;confrontation|مواجهة;consensus|إجماع;conservation|حفاظ;consistency|اتساق;constituent|مكوّن;consultation|استشارة;contamination|تلوث;contradiction|تناقض;contribution|مساهمة;convention|اتفاقية;conversion|تحويل;correlation|ارتباط;credibility|مصداقية;criterion|معيار;declaration|إعلان;deduction|استنتاج;demographic|سكاني;dependency|اعتماد;deployment|نشر;depression|ركود أو اكتئاب;derivative|مشتق;destination|وجهة;deterrent|رادع;diagnosis|تشخيص;disclosure|إفصاح;discretion|تقدير;discrimination|تمييز;displacement|نزوح;disposal|تخلص;disruption|تعطيل;distinction|تمييز;distortion|تشويه;diversification|تنويع;dominance|هيمنة;duration|مدة;economical|اقتصادي;ecosystem|نظام بيئي;efficiency|كفاءة;elaboration|تفصيل;electoral|انتخابي;emission|انبعاث;empirical|تجريبي;empower|يمكّن;enforcement|إنفاذ;engagement|مشاركة;entity|كيان;entrepreneur|رائد أعمال;evaluation|تقييم;exclusion|استبعاد;expertise|خبرة;explicit|صريح;feasibility|جدوى;fluctuation|تقلب;formulation|صياغة;foundation|أساس;funding|تمويل;governance|حوكمة;implementation|تنفيذ;implication|تداعٍ;incidence|حدوث;incorporation|دمج;indicator|مؤشر;innovation|ابتكار;inspection|تفتيش;integration|تكامل;integrity|نزاهة;intellectual|فكري;intensity|شدة;interaction|تفاعل;interference|تدخل;interpretation|تفسير;intervention|تدخل
`);


// 200 كلمة جديدة لمستوى C1 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("C1",`
acquiesce|يذعن;admonish|ينبه بشدة;amplify|يضخم;appraise|يقيّم;assimilate|يستوعب;circumvent|يلتف على;coincide|يتزامن;collaborate|يتعاون;commemorate|يحيي ذكرى;complement|يكمل;contemplate|يتأمل;contrive|يدبر;correlate|يرتبط;curtail|يحد;deem|يعتبر;differentiate|يميز;discriminate|يميز;disrupt|يعطل;elicit|يستخرج;embody|يجسد;envisage|يتصور;evoke|يستحضر;exert|يبذل;exempt|يعفي;exploit|يستغل;fathom|يفهم بعمق;foresee|يتنبأ;hinder|يعرقل;immerse|يغمر;impose|يفرض;incorporate|يدمج;induce|يحث;infer|يستنتج;instigate|يحرض;integrate|يدمج;intensify|يكثف;intervene|يتدخل;invoke|يستدعي;manifest|يظهر;mediate|يتوسط;notwithstanding|على الرغم من
aberration|انحراف;abstraction|تجريد;acclaim|إشادة;accretion|تراكم;affiliation|انتساب;aggregate|مجموع;allegation|ادعاء;ambiguity|غموض;analogy|قياس;antagonism|عداء;apprehension|خشية;arbitration|تحكيم;articulation|صياغة;assertion|تأكيد;asymmetry|عدم تماثل;autonomy|استقلالية;backlash|رد فعل عكسي;benchmark|معيار;bilateral|ثنائي;bureaucrat|موظف بيروقراطي;causality|علاقة سببية;coercion|إكراه;cohesion|تماسك;concession|تنازل;concurrence|موافقة;conformity|امتثال;conjecture|تخمين;consolidation|توحيد;constituency|دائرة انتخابية;contention|خلاف;convergence|تقارب;credibility|مصداقية;criterion|معيار;degradation|تدهور;delegation|وفد;discourse|خطاب;discretion|حرية تقدير;disparity|تفاوت;disposition|نزعة;divergence|تباعد;doctrine|عقيدة;efficacy|فعالية;eloquence|بلاغة;empowerment|تمكين;endeavour|مسعى;enforcement|إنفاذ;aberrant|شاذ;abeyance|تعليق;abject|بائس;abstention|امتناع;adversarial|خصومي;affable|ودود;affinity|تقارب;aggrandize|يعظم;altruism|إيثار;ambivalence|ازدواجية;amelioration|تحسين;anachronistic|خارج سياقه الزمني;anathema|مكروه;antagonistic|عدائي;antiquated|عتيق;apathy|لامبالاة;apocryphal|مشكوك فيه;archetype|نموذج أصلي;assiduous|مثابر;atrophy|ضمور;audacious|جريء;auspicious|مبشر;avaricious|جشع;banal|مبتذل;bellicose|ميال للقتال;brazen|وقح;brevity|إيجاز;burgeoning|متنامٍ;cacophony|نشاز;capricious|متقلب;castigate|يوبخ;caustic|لاذع;coerce|يكره;commensurate|متناسب;complicity|تواطؤ;conflagration|حريق هائل;confluence|التقاء;conjectural|افتراضي;connoisseur|خبير ذواق;conundrum|معضلة;convivial|اجتماعي;copious|وفير;crass|فظ;cryptic|مبهم;dearth|ندرة;debilitating|موهن;decadence|انحطاط;decorum|لياقة;deleterious|ضار;demure|متحفظ;denouement|خاتمة;derivative|تقليدي;despot|طاغية;diaphanous|رقيق شفاف;diffident|خجول;dilatory|مماطل;discernment|تمييز;disingenuous|مخادع;disparate|متباين;dogmatic|متعصب لرأيه;ebullience|حيوية;eclectic|انتقائي;efface|يمحو;effervescent|مفعم بالحيوية;effrontery|وقاحة;elucidate|يوضح;emollient|ملطف;enigmatic|غامض;ephemeral|عابر;equanimity|اتزان;erudition|سعة علم;esoteric|نخبوي;exacerbation|تفاقم;exacting|متطلب;exculpation|تبرئة;exigent|ملح;expedient|ملائم;expiation|تكفير;extant|موجود;fallacious|مضلل;fastidious|دقيق للغاية;fervent|متحمس;flagrant|فاضح;fractious|صعب المراس;frugal|مقتصد;furtive|متخفٍ;garrulous|ثرثار;grandiose|ضخم متكلف;gregarious|اجتماعي;hackneyed|مبتذل;haphazard|عشوائي;iconoclast|ناقد للمعتقدات;idiosyncratic|خاص بطباع فردية;immutable|ثابت;impasse|طريق مسدود;impecunious|معدم;imperious|متسلط;impertinent|وقح;implacable|لا يلين;inane|سخيف;incisive|نافذ;incongruous|غير متناسق;indolent|كسول;ineffable|لا يوصف;inexorable|لا يلين;ingenuous|ساذج;inimical|معادٍ;innate|فطري;inscrutable|غامض;insipid|بلا طعم;intransigent|متعنت;inveterate|راسخ;irascible|سريع الغضب;laconic|مقتضب
`);


// 200 كلمة جديدة لمستوى C2 (الإضافة الجديدة: 1200 كلمة إجمالاً)
addLevel("C2",`
abnegate|يتخلى عن;antedate|يسبق زمنياً;apportion|يقسم;attenuate|يضعف;auspicious|مبشر;avow|يقر علناً;belie|يكذب;bereave|يحرم من;burgeon|ينمو بسرعة;chastise|يعاقب;circumscribe|يحد;coalesce|يتحد;conflate|يخلط;construe|يفسر;decry|يندد;defray|يتكفل بالنفقات;delineate|يحدد بدقة;denigrate|يشوه السمعة;deride|يسخر من;desiccate|يجفف;disabuse|يصحح وهماً;disavow|يتبرأ من;disseminate|ينشر;enjoin|يأمر;entreat|يتوسل;eschew|يتجنب;exacerbate|يفاقم;excoriate|ينتقد بشدة;expatiate|يستفيض;extirpate|يستأصل;foment|يؤجج;impugn|يطعن في;inveigle|يستدرج;ossify|يتصلب;propitiate|يسترضي;recant|يتراجع عن;relegate|يحيل إلى مرتبة أدنى
abeyance|تعليق مؤقت;abjuration|نبذ;absolution|تبرئة;adulation|تملق;affectation|تصنع;approbation|استحسان;arbitrage|مراجحة;assiduity|مواظبة;badinage|مزاح لطيف;bilious|سريع الانفعال;blandishment|استمالة;capitulation|استسلام;castigation|توبيخ;churlishness|فظاظة;complaisance|مجاملة مفرطة;deference|احترام;dereliction|إهمال;desuetude|اندثار;diffidence|خجل;epitome|خلاصة نموذجية;equanimity|رباطة جأش;exigency|ضرورة ملحة;fatuity|حماقة;fecundity|خصوبة;fractiousness|صعوبة المراس;garrulity|ثرثرة;ignominy|عار;impecuniousness|فقر;intransigence|تعنت;jejune|ساذج;lugubriousness|كآبة;munificence|سخاء;obduracy|عناد;abecedarian|مبتدئ;aberrance|انحراف;abeyant|معلق;abscond|يفر;acarpous|عقيم;acerbic|لاذع;acme|ذروة;acrimonious|حاد;adscititious|مضاف;adventitious|طارئ;adytum|قدس الأقداس;afflatus|إلهام;agelast|شخص لا يضحك;agnate|قريب من جهة الأب;alembic|أداة تقطير;animadversion|انتقاد;antediluvian|قديم جداً;antimacassar|غطاء مسند;apodictic|يقيني;apothegm|حكمة موجزة;argute|حاد الذكاء;assuagement|تهدئة;ataraxia|طمأنينة;autochthonous|أصيل محلي;autodidact|عصامي;bathetic|مبتذل;bedizen|يزخرف بإفراط;beldam|امرأة عجوز;benighted|جاهل;besmirch|يشوه;biliousness|حدة الطبع;borborygmus|قرقرة البطن;bruit|يشاع;caliginous|مظلم;callipygian|جميل الأرداف;calumnious|افترائي;canorous|عذب الصوت;cantankerous|مشاكس;cathexis|استثمار نفسي;chthonic|أرضي سفلي;circumlocution|إطناب;cloying|مفرط الحلاوة;concatenation|ترابط متسلسل;concupiscence|شهوة;conviviality|ألفة;coruscate|يلمع;cupreous|نحاسي;deipnosophist|بارع في حديث المآدب;dipsomania|إدمان الكحول;discalced|حافي القدمين;dithyramb|قصيدة حماسية;ebullition|فوران;empyrean|سماوي;ensconce|يستقر;epigone|مقلد;eristic|جدلي;etiolated|شاحب;exiguousness|ضآلة;factotum|متعدد المهام;fastuous|متكبر;ferruginous|صدئي;floccinaucinihilipilification|اعتبار الشيء بلا قيمة;fulminate|يندد;gallimaufry|خليط;gambol|يقفز مرحاً;gibbous|محدب;gimcrack|رديء مزخرف;gloaming|غسق;gorgonize|يبهر أو يرعب;halcyon|هادئ سعيد;hircine|ماعزي;histrionic|مسرحي مبالغ;hobbledehoy|مراهق أخرق;ichor|سائل أسطوري;ignominious|مخزٍ;impecuniosity|فقر;incunabulum|كتاب مطبوع مبكر;ineffable|لا يوصف;inveiglement|استدراج;jocose|مرح;juxtaposition|مجاورة;lachrymation|ذرف الدموع;logorrhea|ثرثرة مفرطة;lucubration|دراسة ليلية;macaronic|مختلط اللغات;maudlin|عاطفي بإفراط;mephitic|كريه الرائحة;meretricious|زائف براق;minatory|تهديدي;misprision|سوء فهم;mnemonic|وسيلة تذكّر;moil|كدح;mondegreen|سماع خاطئ لعبارة;nepenthe|شيء يخفف الحزن;noisome|نتن;obloquy|ذم علني;omphalos|مركز;oneiric|حلمي;onychophagy|قضم الأظافر;opsimath|متعلم متأخر;otiose|عديم الفائدة;palimpsest|مخطوط أعيد استخدامه;panegyric|مديح مطول;paronomasia|جناس;pell-mell|بفوضى;periphrasis|تعبير غير مباشر;perspicuity|وضوح;philippic|خطبة هجومية;pleonasm|حشو لغوي;polymath|موسوعي;psithurism|حفيف الأوراق;pulchritude|جمال;pusillanimous|جبان;quiddity|ماهية;quiescent|ساكن;rebarbative|منفر;refulgent|متألق;rodomontade|تباهٍ فارغ;rubric|عنوان أو معيار;salubrious|صحي;sesquipedalian|مفرط الطول;solipsism|أنانية فلسفية;somnolent|نعسان;stentorian|جهوري;sub rosa|سراً;susurration|همس;tergiversation|مراوغة;thaumaturgy|صناعة المعجزات;threnody|مرثية;ululate|يعوي;umbrage|استياء
`);

// ===================================
// إعداد المستويات
// ===================================

const levelNames = {
A1:"مبتدئ",
A2:"أساسي",
B1:"متوسط",
B2:"فوق المتوسط",
C1:"متقدم",
C2:"إتقان"
};

const levelColors = {
A1:"🟢",
A2:"🔵",
B1:"🟡",
B2:"🟠",
C1:"🔴",
C2:"🟣"
};

const allLevels=["A1","A2","B1","B2","C1","C2"];

// ===================================
// تخزين البيانات
// ===================================

let favorites=JSON.parse(
localStorage.getItem("favorites")||"[]"
);

let examHistory=JSON.parse(
localStorage.getItem("examHistory")||"[]"
);

let selectedLevel="ALL";
let currentExamLevel="";
let questions=[];
let current=0;
let score=0;
let answered=false;
let examMistakes=[];
let currentExamMode="choice";
let speechRecognition=null;

// ===================================
// بناء أزرار المستويات
// ===================================

function buildLevels(){

let home=document.getElementById("homeLevels");
let cards=document.getElementById("levelCards");
let filters=document.getElementById("dictionaryFilters");
let exams=document.getElementById("examButtons");

allLevels.forEach(level=>{

let count=words.filter(x=>x.l===level).length;

home.innerHTML+=`
<div class="level-card" onclick="selectLevel('${level}')">
<h3>${level} ${levelColors[level]}</h3>
${levelNames[level]}
<br><br>
${count} كلمة
</div>`;

cards.innerHTML+=`
<div class="level-card" onclick="selectLevel('${level}')">
<h3>${level}</h3>
${levelNames[level]}
<br><br>
${count} كلمة
</div>`;

filters.innerHTML+=`
<button onclick="filterLevel('${level}')">${level}</button>`;

exams.innerHTML+=`
<button onclick="startExam('${level}')">
امتحان ${level}
</button>`;

});

filters.innerHTML=
`<button onclick="filterLevel('ALL')">كل المستويات</button>`+
filters.innerHTML;

}

// ===================================
// الانتقال بين الصفحات
// ===================================

function showPage(id){

document.querySelectorAll(".page").forEach(p=>{
p.classList.remove("active");
});

document.getElementById(id).classList.add("active");

if(id==="dictionary")renderWords();
if(id==="favorites")renderFavorites();
if(id==="home")updateStats();

}

// ===================================
// النطق
// ===================================

function speak(word){

speechSynthesis.cancel();

let speech=new SpeechSynthesisUtterance(word);
speech.lang="en-US";
speech.rate=0.8;

speechSynthesis.speak(speech);

}

// ===================================
// عرض الكلمات
// ===================================

function renderWords(){

let box=document.getElementById("wordList");
let search=document.getElementById("search").value.toLowerCase();

let filtered=words.filter(x=>
(selectedLevel==="ALL"||x.l===selectedLevel)&&
(
x.w.toLowerCase().includes(search)||
x.t.includes(search)
)
);

box.innerHTML="";

filtered.forEach(item=>{

let div=document.createElement("div");
div.className="card";

let title=document.createElement("div");
title.className="word";
title.textContent=item.w;

let translation=document.createElement("div");
translation.className="translation";
translation.textContent=item.t;

let badge=document.createElement("span");
badge.className="level";
badge.textContent=item.l;

let sound=document.createElement("button");
sound.textContent="🔊 استمع للنطق";
sound.onclick=()=>speak(item.w);

let fav=document.createElement("button");
fav.textContent="❤️ أضف للمفضلة";
fav.style.marginRight="10px";
fav.onclick=()=>addFavorite(item.w);

div.append(
title,
translation,
badge,
document.createElement("br"),
sound,
fav
);

box.appendChild(div);

});

if(filtered.length===0){
box.textContent="لم يتم العثور على الكلمة.";
}

}

function searchWords(){
renderWords();
}

function filterLevel(level){

selectedLevel=level;
showPage("dictionary");
renderWords();

}

// ===================================
// المفضلة
// ===================================

function addFavorite(word){

if(!favorites.includes(word)){

favorites.push(word);

localStorage.setItem(
"favorites",
JSON.stringify(favorites)
);

alert("تمت إضافة الكلمة للمفضلة ❤️");

}else{

alert("الكلمة موجودة بالفعل!");

}

updateStats();

}

function renderFavorites(){

let box=document.getElementById("favoriteList");

box.innerHTML="";

favorites.forEach(word=>{

let item=words.find(x=>x.w===word);

if(!item)return;

let div=document.createElement("div");
div.className="card";

let title=document.createElement("div");
title.className="word";
title.textContent=item.w;

let translation=document.createElement("div");
translation.className="translation";
translation.textContent=item.t;

let sound=document.createElement("button");
sound.textContent="🔊 استمع";
sound.onclick=()=>speak(item.w);

let remove=document.createElement("button");
remove.textContent="حذف";
remove.style.marginRight="10px";

remove.onclick=()=>{

favorites=favorites.filter(x=>x!==word);

localStorage.setItem(
"favorites",
JSON.stringify(favorites)
);

renderFavorites();
updateStats();

};

div.append(title,translation,sound,remove);
box.appendChild(div);

});

if(favorites.length===0){
box.textContent="لم تحفظ أي كلمات بعد.";
}

}

// ===================================
// اختيار المستوى
// ===================================

function selectLevel(level){

selectedLevel=level;

let count=words.filter(x=>x.l===level).length;

document.getElementById("levelInfo").innerHTML=`

<div class="card">

<h2>مستوى ${level} ${levelColors[level]}</h2>

<p>التصنيف: ${levelNames[level]}</p>

<br>

<p>عدد الكلمات المتاحة: ${count}</p>

<br>

<button onclick="startExam('${level}')">
ابدأ امتحان ${level}
</button>

<button onclick="openLevelDictionary('${level}')">
تعلم كلمات المستوى
</button>

</div>

`;

showPage("levels");

}

function openLevelDictionary(level){

selectedLevel=level;
document.getElementById("search").value="";
showPage("dictionary");

}

// ===================================
// الامتحانات
// ===================================

function chooseExamMode(mode){
 currentExamMode=mode;
 const hints={
  choice:"رح تشوف سؤال ومعه أربع إجابات، واختَر الإجابة الصحيحة.",
  dictation:"الموقع رح ينطق الكلمة بالإنجليزي، وإنت اكتب الكلمة اللي سمعتها.",
  pronunciation:"رح تظهرلك كلمة إنجليزية. اضغط زر المايك وانطقها، والموقع يقارن نطقك بالكلمة.",
  arabicToEnglish:"رح يظهرلك معنى الكلمة بالعربي، وإنت اكتب الكلمة الصحيحة بالإنجليزي.",
  wordToPronunciation:"رح تظهرلك كلمة بالإنجليزي، اضغط المايك وانطقها بصوت واضح."
 };
 document.getElementById("modeHint").textContent=hints[mode];
}

function startExam(level){
 currentExamLevel=level;
 let pool=words.filter(x=>x.l===level);
 if(pool.length<15){alert("لا توجد كلمات كافية لهذا الامتحان.");return;}
 if((currentExamMode==="pronunciation"||currentExamMode==="wordToPronunciation") && !(window.SpeechRecognition||window.webkitSpeechRecognition)){
  alert("ميزة التعرف على النطق غير مدعومة في هذا المتصفح. افتح الموقع باستخدام Google Chrome أو Microsoft Edge.");return;
 }
 questions=pool.slice().sort(()=>Math.random()-.5).slice(0,15);
 current=0;score=0;answered=false;examMistakes=[];examReview=[];
 document.getElementById("examStart").style.display="none";
 document.getElementById("quiz").style.display="block";
 document.getElementById("quizResult").innerHTML="";
 showPage("exam");
 document.getElementById("examStart").style.display="none";
 document.getElementById("quiz").style.display="block";
 showQuestion();
}

function showQuestion(){
 answered=false;
 const item=questions[current];
 document.getElementById("progress").textContent="المستوى "+currentExamLevel+" | السؤال "+(current+1)+" من "+questions.length;
 const question=document.getElementById("question");
 const box=document.getElementById("options");
 const feedback=document.getElementById("examFeedback");
 box.innerHTML="";feedback.textContent="";
 if(speechRecognition){try{speechRecognition.abort();}catch(e){}speechRecognition=null;}
 if(currentExamMode==="choice"){
  question.textContent="What is the meaning of: "+item.w+"?";
  let sameLevel=words.filter(x=>x.l===currentExamLevel&&x.w!==item.w);
  let wrong=sameLevel.slice().sort(()=>Math.random()-.5).slice(0,3);
  [item,...wrong].sort(()=>Math.random()-.5).forEach(option=>{
   let btn=document.createElement("button");btn.className="option";btn.textContent=option.t;
   btn.onclick=()=>checkAnswer(btn,option.t,item.t);box.appendChild(btn);
  });
 }else if(currentExamMode==="dictation"){
  question.textContent="استمع للكلمة الإنجليزية، ثم اكتبها كما سمعتها.";
  const play=document.createElement("button");play.textContent="🔊 اسمع الكلمة";play.onclick=()=>speakExamWord(item.w);box.appendChild(play);
  const input=document.createElement("input");input.id="dictationAnswer";input.placeholder="اكتب الكلمة باللغة الإنجليزية...";input.dir="ltr";input.style.marginTop="18px";box.appendChild(input);
  const submit=document.createElement("button");submit.textContent="تحقق من إجابتي";submit.onclick=()=>checkDictation(item);box.appendChild(submit);
  setTimeout(()=>speakExamWord(item.w),350);
 }else if(currentExamMode==="arabicToEnglish"){
  question.textContent="اكتب الكلمة الإنجليزية التي تعني: "+item.t;
  const input=document.createElement("input");input.id="arabicToEnglishAnswer";input.placeholder="اكتب الكلمة باللغة الإنجليزية...";input.dir="ltr";input.style.marginTop="18px";box.appendChild(input);
  const submit=document.createElement("button");submit.textContent="تحقق من إجابتي";submit.onclick=()=>checkArabicToEnglish(item);box.appendChild(submit);
 }else{
  question.textContent="اقرأ الكلمة التالية بصوت واضح باللغة الإنجليزية:";
  const word=document.createElement("div");word.className="word";word.style.fontSize="38px";word.textContent=item.w;box.appendChild(word);
  const mic=document.createElement("button");mic.textContent="🎙️ ابدأ النطق";mic.onclick=()=>startPronunciationCheck(item,mic);box.appendChild(mic);
  const note=document.createElement("p");note.style.marginTop="15px";note.textContent="اسمح للمتصفح باستخدام المايكروفون عند ظهور طلب الإذن.";box.appendChild(note);
 }
 document.getElementById("nextButton").textContent=current===questions.length-1?"إنهاء الامتحان":"السؤال التالي";
}

function speakExamWord(word){
 if(!('speechSynthesis' in window)){alert("تشغيل الصوت غير مدعوم في هذا المتصفح.");return;}
 window.speechSynthesis.cancel();
 const utterance=new SpeechSynthesisUtterance(word);utterance.lang="en-US";utterance.rate=0.85;
 window.speechSynthesis.speak(utterance);
}

function normalizeEnglish(text){return String(text||"").toLowerCase().trim().replace(/[^a-z']/g,"");}

function checkArabicToEnglish(item){
 if(answered)return;
 const input=document.getElementById("arabicToEnglishAnswer");
 if(!input||!input.value.trim()){alert("اكتب الكلمة أولاً.");return;}
 answered=true;
 const correct=normalizeEnglish(input.value)===normalizeEnglish(item.w);
 if(correct)score++;
 saveExamReview(item,input.value,item.w,correct);
 input.disabled=true;
 document.getElementById("examFeedback").innerHTML=(correct?"✅ إجابة صحيحة!":"❌ مش صحيح.")+"<br>إجابتك: <strong dir='ltr'>"+input.value+"</strong><br>الإجابة الصحيحة: <strong dir='ltr' style='color:#75e6a5'>"+item.w+"</strong>";
}

function checkDictation(item){
 if(answered)return;
 const input=document.getElementById("dictationAnswer");
 if(!input||!input.value.trim()){alert("اكتب الكلمة أولاً.");return;}
 answered=true;
 const correct=normalizeEnglish(input.value)===normalizeEnglish(item.w);
 if(correct)score++;
 saveExamReview(item,input.value,item.w,correct);
 input.disabled=true;
 document.getElementById("examFeedback").innerHTML=(correct?"✅ إجابة صحيحة!":"❌ مش صحيح.")+"<br>إجابتك: <strong dir='ltr'>"+input.value+"</strong><br>الإجابة الصحيحة: <strong dir='ltr' style='color:#75e6a5'>"+item.w+"</strong>";
}

function startPronunciationCheck(item,button){
 const SpeechRecognition=window.SpeechRecognition||window.webkitSpeechRecognition;
 if(!SpeechRecognition){alert("متصفحك لا يدعم التعرف على الكلام. جرّب Chrome أو Edge.");return;}
 button.disabled=true;button.textContent="🎙️ أستمع إليك...";
 const recognition=new SpeechRecognition();speechRecognition=recognition;
 recognition.lang="en-US";recognition.interimResults=false;recognition.maxAlternatives=3;
 recognition.onresult=(event)=>{
  const alternatives=Array.from(event.results[0]).map(x=>x.transcript);
  const heard=alternatives.find(x=>normalizeEnglish(x)===normalizeEnglish(item.w))||alternatives[0];
  const correct=alternatives.some(x=>normalizeEnglish(x)===normalizeEnglish(item.w));
  answered=true;if(correct)score++;
  saveExamReview(item,heard,item.w,correct);
  document.getElementById("examFeedback").innerHTML=(correct?"✅ ممتاز! تم التعرف على الكلمة بشكل صحيح.":"❌ ما تعرّف الموقع على الكلمة بشكل صحيح.")+"<br>اللي سمعه الموقع: <strong dir='ltr'>"+heard+"</strong><br>الكلمة المطلوبة: <strong dir='ltr'>"+item.w+"</strong><br><small>ملاحظة: التقييم آلي وقد يتأثر بجودة المايك أو اللهجة.</small>";
  button.textContent="تم تسجيل النطق";
 };
 recognition.onerror=(event)=>{
  button.disabled=false;button.textContent="🎙️ حاول مرة ثانية";
  document.getElementById("examFeedback").textContent=event.error==="not-allowed"?"لازم تسمح للموقع باستخدام المايكروفون.":"ما قدرنا نسمع الكلمة بوضوح. جرّب مرة ثانية.";
 };
 recognition.onend=()=>{if(!answered&&button.disabled){button.disabled=false;button.textContent="🎙️ ابدأ النطق مرة ثانية";}};
 try{recognition.start();}catch(e){button.disabled=false;button.textContent="🎙️ ابدأ النطق";}
}

function saveExamReview(item,userAnswer,correctAnswer,correct){
 examReview[current]={question:currentExamMode==="choice"?"What is the meaning of: "+item.w+"?":currentExamMode==="arabicToEnglish"?"اكتب الكلمة الإنجليزية التي تعني: "+item.t:currentExamMode==="dictation"?"استمع للكلمة الإنجليزية واكتبها":"انطق الكلمة: "+item.w,userAnswer:userAnswer||"—",correctAnswer:correctAnswer,correct:correct};
}
function checkAnswer(button,answer,correct){
 if(answered)return;answered=true;
 const item=questions[current];
 if(answer===correct){score++;button.classList.add("correct");}
 else{button.classList.add("wrong");document.querySelectorAll(".option").forEach(btn=>{if(btn.textContent===correct)btn.classList.add("correct");});}
 saveExamReview(item,answer,correct,answer===correct);
 document.getElementById("examFeedback").innerHTML=(answer===correct?"✅ إجابة صحيحة!":"❌ الإجابة غير صحيحة.")+"<br>إجابتك: <strong>"+answer+"</strong><br>الإجابة الصحيحة: <strong style='color:#75e6a5'>"+correct+"</strong>";
}

function nextQuestion(){
 if(!answered){alert((currentExamMode==="pronunciation"||currentExamMode==="wordToPronunciation")?"انطق الكلمة أولاً باستخدام المايك.":(currentExamMode==="dictation"||currentExamMode==="arabicToEnglish")?"اكتب إجابتك وتحقق منها أولاً.":"اختر إجابة أولاً!");return;}
 current++;if(current<questions.length)showQuestion();else finishExam();
}

// ===================================
// نتيجة الامتحان
// ===================================

function finishExam(){

let percent=Math.round(
score/questions.length*100
);

examHistory.push(percent);

localStorage.setItem(
"examHistory",
JSON.stringify(examHistory)
);

document.getElementById("quiz").style.display="none";

document.getElementById("quizResult").innerHTML=`

<div class="card">

<h2>🎉 انتهى امتحان ${currentExamLevel}!</h2>
<p>نوع الامتحان: ${({choice:"تحديد الإجابة",dictation:"الاستماع والكتابة",pronunciation:"قراءة الكلمة بالمايك",arabicToEnglish:"المعنى بالعربي وكتابة الكلمة",wordToPronunciation:"الكلمة الإنجليزية والنطق"})[currentExamMode]}</p>

<p>علامتك:</p>

<br>

<strong style="font-size:45px;color:#62caff">
${percent}%
</strong>

<br><br>

<p>إجابات صحيحة: ${score} من ${questions.length}</p>
<div class="card" style="margin-top:18px;text-align:right"><h3>📋 مراجعة جميع الأسئلة والإجابات</h3>${examReview.map((m,i)=>`<div class="grammar-question"><strong>${i+1}. ${m.question}</strong><p style="margin-top:8px">إجابتك: <span style="color:${m.correct?'#75e6a5':'#ff9aa8'}">${m.userAnswer}</span></p><p>الإجابة الصحيحة: <strong style="color:#75e6a5">${m.correctAnswer}</strong></p><p>${m.correct?'✅ صحيح':'❌ غير صحيح'}</p></div>`).join("")}</div>

<br>

<p>
${
percent>=90?
"ممتاز! أداء رائع 🔥":
percent>=70?
"جيد جداً! استمر بالتعلم 💪":
percent>=50?
"نتيجة جيدة، تحتاج إلى المزيد من التدريب 📚":
"لا تستسلم! حاول مرة أخرى ❤️"
}
</p>

<br>

<button onclick="resetExam()">امتحان جديد</button>

</div>

`;

document.getElementById("examStart").style.display="block";

updateStats();
if(percent===100)celebratePerfectScore("علامة كاملة في الامتحان!");

}

// ===================================
// إعادة الامتحان
// ===================================

function resetExam(){

document.getElementById("quizResult").innerHTML="";
document.getElementById("quiz").style.display="none";
document.getElementById("examStart").style.display="block";

}

// ===================================
// الإحصائيات
// ===================================

function updateStats(){

document.getElementById("favCount").textContent=
favorites.length;

document.getElementById("examCount").textContent=
examHistory.length;
document.getElementById("wordCount").textContent=words.length;

document.getElementById("bestScore").textContent=
Math.max(0,...examHistory)+"%";

document.getElementById("wordCount").textContent=
words.length;

}


// القواعد: الشرح والدلالات والتركيب والاختبارات
const grammarData=[
{id:"simple",name:"Present Simple",ar:"المضارع البسيط",use:"للعادات والروتين والحقائق والأشياء المتكررة.",signals:"always, usually, often, sometimes, never, every day",forms:["الإثبات: Subject + V1 (نضيف s/es مع he/she/it). She plays tennis.","النفي: Subject + do/does + not + V1. He does not play.","السؤال: Do/Does + subject + V1? Does she play?"],tip:"مع he/she/it نضيف s أو es في الإثبات فقط. بعد does أو doesn't يرجع الفعل للمصدر.",quiz:[
["She ___ to school every day.",["go","goes","going","gone"],1],["They ___ football on Fridays.",["plays","play","playing","played"],1],["He doesn't ___ coffee.",["likes","like","liking","liked"],1],["___ your brother work here?",["Do","Does","Is","Has"],1],["Water ___ at 100°C.",["boil","boils","boiling","boiled"],1],["I ___ get up early.",["usually","am usually","usually am","does usually"],0],["My parents ___ in Amman.",["lives","living","live","is live"],2],["Sara ___ TV in the evening.",["watch","watchs","watches","watching"],2],["We ___ not eat meat.",["does","do","are","has"],1],["Which sentence is correct?",["He study English.","He studies English.","He studying English.","He does studies English."],1],["My sister ___ English very well.",["speak","speaks","speaking","is speak"],1],["The sun ___ in the east.",["rise","rises","rising","is rise"],1],["___ they live near school?",["Do","Does","Are","Have"],0],["Tom and Ali ___ their room every week.",["cleans","clean","cleaning","is clean"],1],["She ___ like cold weather.",["don't","doesn't","isn't","hasn't"],1]]},
{id:"continuous",name:"Present Continuous",ar:"المضارع المستمر",use:"لحدث يحدث الآن، أو وضع مؤقت، أو ترتيب مستقبلي قريب.",signals:"now, right now, at the moment, currently, today, Look!, Listen!",forms:["الإثبات: Subject + am/is/are + verb-ing. I am studying.","النفي: Subject + am/is/are + not + verb-ing. She isn't sleeping.","السؤال: Am/Is/Are + subject + verb-ing? Are they playing?"],tip:"I مع am، وhe/she/it مع is، وyou/we/they مع are. نضيف ing للفعل.",quiz:[
["I ___ studying now.",["am","is","are","be"],0],["She ___ dinner now.",["cook","cooks","is cooking","cooking"],2],["They ___ playing outside.",["is","am","are","be"],2],["He isn't ___ TV now.",["watch","watches","watching","watched"],2],["___ you listening to me?",["Do","Does","Are","Is"],2],["Look! The baby ___.",["cries","cry","is crying","crying"],2],["We ___ staying with our aunt.",["am","is","are","do"],2],["Choose the correct spelling.",["makeing","making","makking","makesing"],1],["What ___ she doing?",["are","am","is","does"],2],["Which sentence describes now?",["I walk daily.","I am walking now.","I walked yesterday.","I have walked before."],1],["The children ___ studying at the moment.",["is","am","are","be"],2],["I am ___ a book right now.",["read","reads","reading","readed"],2],["He ___ not sleeping now.",["are","am","is","do"],2],["Listen! Someone ___ at the door.",["knocks","is knocking","knock","knocked"],1],["Are they ___ dinner now?",["have","has","having","had"],2]]},
{id:"perfect",name:"Present Perfect Simple",ar:"المضارع التام البسيط",use:"لتجربة في وقت غير محدد، أو حدث ماضٍ له نتيجة الآن، أو حالة بدأت في الماضي وما زالت مستمرة.",signals:"already, just, yet, ever, never, since, for, recently",forms:["الإثبات: Subject + have/has + V3. She has finished.","النفي: Subject + have/has + not + V3. I haven't seen it.","السؤال: Have/Has + subject + V3? Have you eaten?"],tip:"has مع he/she/it، وhave مع I/you/we/they. نستخدم التصريف الثالث V3.",quiz:[
["I ___ finished my homework.",["has","have","am","did"],1],["She has ___ to London twice.",["be","been","being","was"],1],["They haven't ___ the film yet.",["see","saw","seen","seeing"],2],["___ he ever eaten sushi?",["Have","Has","Does","Is"],1],["We have lived here ___ 2020.",["for","since","ago","during"],1],["I have known her ___ five years.",["since","from","for","at"],2],["Choose the correct sentence.",["He have finished.","He has finished.","He is finish.","He has finish."],1],["Have you ___ your keys?",["find","found","finding","finds"],1],["She has just ___ home.",["arrive","arrived","arriving","arrives"],1],["Present Perfect is commonly used with:",["yesterday","last year","already","in 2010"],2],["She ___ never visited Petra.",["have","has","is","was"],1],["We have already ___ lunch.",["eat","ate","eaten","eating"],2],["Have you finished your work ___?",["yet","yesterday","ago","last"],0],["He has ___ left the house.",["yet","just","tomorrow","ever"],1],["I ___ this movie before.",["have seen","has saw","am see","seeing"],0]]},
{id:"perfectcontinuous",name:"Present Perfect Continuous",ar:"المضارع التام المستمر",use:"لحدث بدأ في الماضي واستمر مدة وما زال مستمراً أو انتهى للتو، مع التركيز على مدة النشاط أو استمراره.",signals:"for, since, all day, lately, recently, how long",forms:["الإثبات: Subject + have/has + been + verb-ing. I have been studying.","النفي: Subject + have/has + not + been + verb-ing. He hasn't been sleeping.","السؤال: Have/Has + subject + been + verb-ing? Have you been waiting?"],tip:"بعد have/has نضع been ثم الفعل مع ing. for للمدة وsince لنقطة بداية الزمن.",quiz:[
["She has been ___ for an hour.",["study","studied","studying","studies"],2],["I ___ been waiting since 8.",["has","have","am","was"],1],["He has been working ___ three hours.",["since","for","at","from"],1],["They have ___ playing all morning.",["be","being","been","was"],2],["___ you been learning English?",["Has","Have","Are","Do"],1],["She ___ been feeling well lately.",["haven't","hasn't","isn't","doesn't"],1],["We have been ___ for the bus.",["wait","waited","waiting","waits"],2],["Use ___ with a starting point in time.",["for","since","during","ago"],1],["Which is correct?",["He has been read.","He have been reading.","He has been reading.","He is been reading."],2],["This tense often emphasizes:",["finished past time","duration of an activity","daily habit only","future prediction"],1],["They have been ___ since morning.",["work","worked","working","works"],2],["How long ___ she been studying?",["have","has","is","does"],1],["It has been raining ___ two hours.",["since","for","from","at"],1],["He has been living here ___ 2022.",["for","since","during","by"],1],["I am tired because I ___ been running.",["has","have","was","am"],1]]},
{id:"futureContinuous",name:"Future Continuous",ar:"المستقبل المستمر",use:"نستخدمه للتعبير عن حدث سيكون مستمراً في وقت محدد في المستقبل، أو حدث متوقع أن يكون جارياً في تلك اللحظة.",signals:"at this time tomorrow, this time next week, at 8 o’clock tomorrow, at this time next year, all day tomorrow",forms:["الإثبات: Subject + will be + verb-ing. مثال: I will be studying at 8 tomorrow.","النفي: Subject + will not (won't) be + verb-ing. مثال: She won't be sleeping.","السؤال: Will + subject + be + verb-ing? مثال: Will they be travelling tomorrow?"],examples:["This time tomorrow, I will be flying to London. — في مثل هذا الوقت غداً، سأكون مسافراً بالطائرة إلى لندن.","At 9 tonight, she will be studying. — في الساعة التاسعة الليلة، ستكون تدرس.","They won't be working on Friday. — لن يكونوا يعملون يوم الجمعة.","Will you be using the computer later? — هل ستكون تستخدم الحاسوب لاحقاً؟"],tip:"احفظ التركيب: will be + V-ing. لا نضيف s للفعل ولا نستخدم am/is/are؛ الفعل المساعد will ثابت مع جميع الفواعل.",quiz:[
["At 8 tomorrow, I ___ studying.",["will","will be","am","will have"],1],["This time next week, she ___ travelling.",["will be","is","has been","will"],0],["They ___ be playing at noon.",["won't","don't","aren't","haven't"],0],["___ you be waiting for me?",["Do","Are","Will","Have"],2],["He will be ___ dinner at 7.",["cook","cooks","cooking","cooked"],2],["At this time tomorrow, we ___ flying.",["will be","will","are","have"],0],["Choose the correct sentence.",["She will studying.","She will be studying.","She will is studying.","She be studying."],1],["At 10 tonight, I ___ sleeping.",["will be","will have","am","was"],0],["Which phrase often signals Future Continuous?",["yesterday","at this time tomorrow","last week","two days ago"],1],["___ they be staying at the hotel?",["Are","Do","Will","Have"],2],["We won't be ___ at midnight.",["work","worked","working","works"],2],["The children ___ be taking an exam at 9.",["will","will be","are","have"],1],["Future Continuous describes an action that ___ in the future.",["finished long ago","will be in progress","happens every day","started yesterday"],1],["Tomorrow afternoon, Dad ___ be driving home.",["will","is","will be","has"],2],["Which is the correct negative form?",["will not studying","will not be studying","doesn't be studying","not will studying"],1]]},
{id:"futurePerfect",name:"Future Perfect",ar:"المستقبل التام",use:"نستخدمه للتعبير عن حدث سيكون قد اكتمل قبل وقت محدد أو قبل حدث آخر في المستقبل.",signals:"by, by the time, by tomorrow, by next week, before, by 2030",forms:["الإثبات: Subject + will have + V3. مثال: She will have finished.","النفي: Subject + will not (won't) have + V3. مثال: They won't have arrived.","السؤال: Will + subject + have + V3? مثال: Will you have completed the task?"],examples:["By 8 o’clock, I will have finished my homework. — بحلول الساعة الثامنة، سأكون قد أنهيت واجبي.","She will have left before we arrive. — ستكون قد غادرت قبل أن نصل.","They won't have completed the project by Friday. — لن يكونوا قد أكملوا المشروع بحلول الجمعة.","Will you have read the book by tomorrow? — هل ستكون قد قرأت الكتاب بحلول الغد؟"],tip:"احفظ التركيب: will have + V3 (التصريف الثالث). نستخدمه عندما يكون التركيز على اكتمال الحدث قبل موعد مستقبلي، وليس على استمراره.",quiz:[
["By tomorrow, I ___ finished the report.",["will","will have","have","am"],1],["She will have ___ by 6 o'clock.",["leave","leaving","left","leaves"],2],["They ___ have arrived by noon.",["won't","don't","aren't","haven't"],0],["___ you have finished by Friday?",["Do","Have","Will","Are"],2],["He will have ___ his homework.",["do","did","done","doing"],2],["By next year, we ___ have moved house.",["will","will have","are","have"],1],["Choose the correct sentence.",["I will has finished.","I will have finished.","I will have finish.","I will finished."],1],["Future Perfect focuses on an action that ___ before a future time.",["is happening now","will be completed","happened yesterday","happens daily"],1],["Which phrase often signals Future Perfect?",["now","every day","by next Monday","yesterday"],2],["She won't have ___ the email by then.",["send","sent","sending","sends"],1],["By 2030, they ___ built the bridge.",["will have","will be","have","are"],0],["Will he have ___ dinner before we come?",["eat","ate","eaten","eating"],2],["By the time you arrive, the film ___ have started.",["will","has","is","does"],0],["We will have ___ the work by 5.",["complete","completed","completing","completes"],1],["The negative form is:",["will not have + V3","will not be + ing","do not have + V1","will have not + V-ing"],0]]},
{id:"pastSimple",name:"Past Simple",ar:"الماضي البسيط",use:"نستخدمه للتحدث عن حدث بدأ وانتهى في الماضي، وغالباً نعرف متى حدث.",signals:"yesterday, last night, last week, ago, in 2020, yesterday morning",forms:["الإثبات: Subject + V2. She visited her aunt. (الفعل المنتظم نضيف له غالباً ed، وغير المنتظم له تصريف ثانٍ V2).","النفي: Subject + did not (didn't) + V1. She didn't visit her aunt.","السؤال: Did + subject + V1? Did she visit her aunt?"],examples:["I watched a movie yesterday. — شاهدت فيلماً أمس.","He went to school last Monday. — ذهب إلى المدرسة الاثنين الماضي.","They didn't play football. — لم يلعبوا كرة القدم.","Did you see Ali? — هل رأيت علياً؟"],tip:"مع did وdidn't نستخدم الفعل بالمصدر V1، أما في الإثبات فنستخدم التصريف الثاني V2.",quiz:[
["I ___ my grandmother yesterday.",["visit","visited","visiting","visits"],1],
["She ___ to the market last week.",["go","goes","went","going"],2],
["They didn't ___ the match.",["watched","watching","watch","watches"],2],
["___ you finish your homework?",["Do","Did","Does","Are"],1],
["We ___ a new film last night.",["see","seen","saw","seeing"],2],
["He ___ breakfast two hours ago.",["ate","eats","eating","eat"],0],
["Choose the correct sentence.",["She didn't went.","She didn't go.","She doesn't went.","She not go."],1],
["My father ___ home late yesterday.",["come","comes","came","coming"],2],
["I ___ at home last Friday.",["was","were","am","be"],0],
["The children ___ happy yesterday.",["was","were","is","be"],1],
["What time ___ they arrive?",["do","does","did","are"],2],
["Sara ___ her room yesterday.",["clean","cleaned","cleans","cleaning"],1],
["He ___ his keys last night.",["lose","loses","lost","losing"],2],
["We ___ not go to school yesterday.",["do","does","did","were"],2],
["Which word is a past-time signal?",["now","tomorrow","yesterday","every day"],2]]},
{id:"pastContinuous",name:"Past Continuous",ar:"الماضي المستمر",use:"نستخدمه لحدث كان مستمراً في وقت محدد في الماضي، أو حدث طويل قطعه حدث قصير، أو حدثين كانا مستمرين معاً.",signals:"while, when, at 8 yesterday, at that time, all evening",forms:["الإثبات: Subject + was/were + verb-ing. I was studying.","النفي: Subject + was/were + not + verb-ing. They weren't sleeping.","السؤال: Was/Were + subject + verb-ing? Were you reading?"],examples:["I was studying at 8 yesterday. — كنت أدرس الساعة الثامنة أمس.","She was cooking when I called. — كانت تطبخ عندما اتصلت.","While Ali was reading, Sara was writing. — بينما كان علي يقرأ، كانت سارة تكتب.","They weren't playing outside. — لم يكونوا يلعبون في الخارج."],tip:"نستخدم was مع I/he/she/it، وwere مع you/we/they، ثم نضيف ing للفعل. غالباً يأتي Past Simple بعد when لحدث قصير قاطع الحدث المستمر.",quiz:[
["I ___ watching TV at 9 yesterday.",["was","were","am","be"],0],
["They ___ playing when it started to rain.",["was","were","are","is"],1],
["She was ___ dinner.",["cook","cooked","cooking","cooks"],2],
["He wasn't ___ at that time.",["sleep","slept","sleeping","sleeps"],2],
["___ you studying at 7?",["Was","Were","Did","Are"],1],
["While I ___, my brother was reading.",["was writing","write","wrote","am writing"],0],
["The phone rang while we ___ dinner.",["have","had","were having","are having"],2],
["At midnight, she ___.",["was sleeping","sleep","slept","is sleeping"],0],
["Choose the correct sentence.",["They was running.","They were running.","They running.","They did running."],1],
["What ___ he doing when you saw him?",["were","was","did","is"],1],
["I ___ not listening to music.",["were","did","was","am"],2],
["While the boys were playing, it ___.",["rained","was raining","rains","rain"],1],
["We ___ walking home when we met Sam.",["was","were","are","did"],1],
["Which word often introduces an interrupting event?",["while","when","every","tomorrow"],1],
["Past Continuous is formed with:",["did + V1","was/were + verb-ing","have + V3","will + V1"],1]]},

{id:"pastPerfect",name:"Past Perfect",ar:"الماضي التام",use:"نستخدم الماضي التام للتعبير عن حدث وقع واكتمل قبل حدث آخر أو وقت محدد في الماضي. الحدث الأسبق يأخذ Past Perfect، والحدث اللاحق غالباً يأخذ Past Simple.",signals:"before = قبل، after = بعد، by the time = بحلول الوقت الذي، already = بالفعل، just = للتو، never = أبداً، until then = حتى ذلك الوقت، when (عندما) إذا كان السياق يوضح أن حدثاً سبق الآخر. الكلمات الدالة تساعدك، لكن الأهم تحديد أي الحدثين وقع أولاً.",forms:["الإثبات: Subject + had + V3. مثال: She had finished her homework.","النفي: Subject + had not (hadn't) + V3. مثال: They hadn't arrived.","السؤال: Had + subject + V3? مثال: Had you eaten?", "مع حدثين في الماضي: الحدث الأسبق = Past Perfect (had + V3)، والحدث اللاحق = Past Simple (V2). مثال: The train had left before we arrived."],examples:["When I arrived, the film had started. — عندما وصلت، كان الفيلم قد بدأ.","She had finished her homework before her mother came. — كانت قد أنهت واجبها قبل أن تأتي أمها.","They hadn't eaten before the trip. — لم يكونوا قد أكلوا قبل الرحلة.","Had you seen that movie before? — هل كنت قد شاهدت ذلك الفيلم من قبل؟", "By the time we got to the station, the bus had left. — بحلول وقت وصولنا إلى المحطة، كانت الحافلة قد غادرت."],tip:"اسأل نفسك: أي حدث وقع أولاً؟ ضع had + V3 للحدث الأسبق، وPast Simple للحدث الذي وقع بعده. had ثابتة مع جميع الفواعل (I/he/she/they). انتبه أن التصريف الثالث V3 قد يكون منتظماً أو شاذاً: finished, gone, eaten, seen.",quiz:[
["When I arrived, the bus ___ already ___.",["has / left","had / left","have / leave","was / leaving"],1],
["She ___ her homework before dinner started.",["finished","has finished","had finished","finishes"],2],
["They hadn't ___ before the journey.",["ate","eating","eat","eaten"],3],
["___ you seen the film before last night?",["Did","Have","Had","Do"],2],
["By the time we got there, the shop ___.",["closes","had closed","has close","closing"],1],
["Choose the correct Past Perfect form.",["He had went.","He has gone yesterday.","He had gone.","He have gone."],2],
["The children ___ asleep before their father came home.",["had fallen","fall","have fell","were fall"],0],
["I was hungry because I ___ breakfast.",["didn't have","hadn't had","don't have","not had"],1],
["Which event happened first? 'After Sara had called, Ali arrived.'",["Ali arrived","Sara called","They arrived together","It is in the future"],1],
["He ___ never ___ sushi before he visited Japan.",["has / tried","had / tried","did / tried","was / try"],1],
["Past Perfect is formed with:",["have + V1","had + V3","was + verb-ing","will + V1"],1],
["We ___ the game before it started to rain.",["had finished","finish","have finish","finishing"],0],
["Choose the correct negative form.",["She hadn't seen him.","She didn't had seen him.","She hadn't saw him.","She not had seen him."],0],
["___ they left before you arrived?",["Did","Have","Had","Were"],2],
["In a sentence with two past events, Past Perfect usually describes:",["the later event","the event happening now","the earlier event","a future event"],2]
]},
{id:"usedTo",name:"Used to / Would",ar:"العادات والأفعال المتكررة في الماضي",use:"نستخدم used to للحديث عن عادة أو حالة كانت موجودة في الماضي ولم تعد موجودة الآن. ونستخدم would أيضاً للحديث عن أفعال متكررة اعتدنا القيام بها في الماضي، خصوصاً عند سرد الذكريات. لكن would لا يُستخدم عادةً لوصف الحالات أو الصفات القديمة؛ لذلك نقول I used to be shy ولا نقول I would be shy بهذا المعنى.",signals:"used to: when I was young, in the past, years ago, but now, no longer. | would (للعادات الماضية): every summer, every day, whenever, when we were children, often, always (ضمن سياق ماضٍ واضح)",forms:["Used to - الإثبات: Subject + used to + V1. مثال: I used to play outside.","Used to - النفي: Subject + didn't use to + V1. مثال: I didn't use to drink coffee.","Used to - السؤال: Did + subject + use to + V1? مثال: Did you use to live here? ملاحظة: بعد did نكتب use بدون d.","Would - العادة الماضية: Subject + would + V1. مثال: Every summer, we would visit our grandparents.","Would - النفي في سياق العادات: Subject + wouldn't + V1. مثال: As a child, he wouldn't eat vegetables. (كان يرفض/لا يأكلها عادةً). بعد would أو wouldn't نستخدم V1 مباشرة."],examples:["I used to ride my bike to school. — اعتدت أن أذهب إلى المدرسة بالدراجة.","She used to have long hair. — كان شعرها طويلاً في الماضي. (حالة؛ نستخدم used to)","When we were children, we would play outside every evening. — عندما كنا أطفالاً، كنا نلعب في الخارج كل مساء.","Every winter, my family would visit my grandparents. — كل شتاء، كانت عائلتي تزور أجدادي.","We didn't use to watch TV. — لم نكن نشاهد التلفاز في الماضي.","Did he use to play tennis? — هل كان يلعب التنس في الماضي؟"],tip:"الفرق السريع: used to = عادة أو حالة في الماضي لم تعد موجودة، ويصلح للأفعال والحالات (used to be/live/like). would = فعل متكرر في الماضي فقط، وليس للحالات أو الصفات. بعد used to نستخدم V1، وبعد didn't وDid نكتب use to، أما بعد would فنستخدم V1 مباشرة.",quiz:[
["I ___ play football when I was young.",["use to","used to","using to","uses to"],1],
["She used to ___ in Irbid.",["lived","living","live","lives"],2],
["They didn't ___ eat vegetables.",["used to","use to","using to","uses to"],1],
["___ you use to walk to school?",["Do","Were","Did","Are"],2],
["He ___ have a red bicycle, but now he doesn't.",["use to","used to","uses to","using to"],1],
["Choose the correct negative sentence.",["I didn't used to swim.","I didn't use to swim.","I don't used to swim.","I not use to swim."],1],
["When we were children, we ___ play in the garden every evening.",["would","will","are","have"],0],
["Every summer, my family would ___ to Aqaba.",["went","going","go","goes"],2],
["Which sentence describes a past state correctly?",["I would be shy.","I used to be shy.","I would being shy.","I use be shy."],1],
["My grandfather ___ tell us stories every night.",["would","will","is","has"],0],
["After would in a past-habit sentence, we use:",["V2","V3","V1","verb-ing"],2],
["Which sentence is correct?",["She would visited us every Friday.","She would visits us every Friday.","She would visit us every Friday.","She would visiting us every Friday."],2],
["I used to be shy, but now I ___.",["am not","wasn't","didn't","not be"],0],
["Which form is best for a repeated past action?",["When I was young, I would ride my bike every day.","When I was young, I would be tall.","When I was young, I would know the answer.","When I was young, I would own a house."],0],
["After 'did' in a question about used to, we write:",["used to","use to","using to","uses to"],1],
["Used to can describe:",["only future plans","past habits and past states","only actions happening now","only completed actions today"],1],
["Would for past habits is mainly used for:",["past repeated actions","past states and qualities","future facts","present routines"],0],
["Choose the correct sentence.",["We would to visit them every year.","We would visiting them every year.","We would visit them every year.","We would visited them every year."],2]
]},
 {id:"futureWill",name:"Will / Won't",ar:"المستقبل البسيط باستخدام will و won't",use:"نستخدم will للتحدث عن قرارات نتخذها لحظة الكلام، والتوقعات والوعود والعروض. ونستخدم won't وهي اختصار will not للنفي.",signals:"tomorrow, next week, next year, soon, later, I think, probably, perhaps",forms:["الإثبات: Subject + will + V1. مثال: I will study tomorrow.","النفي: Subject + will not (won't) + V1. مثال: She won't be late.","السؤال: Will + subject + V1? مثال: Will they come?","الإجابات القصيرة: Yes, I will. / No, I won't."],examples:["I will call you tonight. — سأتصل بك الليلة.","She won't forget your birthday. — لن تنسى عيد ميلادك.","They will travel next week. — سيسافرون الأسبوع القادم.","Will you help me? — هل ستساعدني؟"],tip:"بعد will وwon't نستخدم الفعل بالمصدر V1 بدون s أو ed أو ing. لا نستخدم do/does معها في السؤال أو النفي.",quiz:[
["I ___ visit my grandmother tomorrow.",["will","am","did","was"],0],
["He ___ come to the party. He is busy.",["will","won't","isn't","doesn't"],1],
["___ you help me with this box?",["Do","Are","Will","Did"],2],
["She will ___ a new book next week.",["buys","bought","buying","buy"],3],
["Choose the correct negative sentence.",["I don't will go.","I won't go.","I won't going.","I not will go."],1],
["They ___ arrive soon, I think.",["will","are","did","have"],0],
["Will Ali play tomorrow? — No, he ___.",["will","doesn't","won't","isn't"],2],
["Which sentence is correct?",["She will studies.","She wills study.","She will study.","She will studying."],2],
["We ___ be late; the bus is already here.",["won't","aren't will","don't will","not will"],0],
["The phone is ringing. I ___ answer it.",["will","am","did","have"],0],
["___ it rain tomorrow?",["Does","Will","Is","Did"],1],
["My brother won't ___ the secret.",["tells","telling","told","tell"],3],
["I think our team ___ win the match.",["will","was","does","has"],0],
["Choose the correct short answer: Will she join us? — Yes, she ___.",["does","is","will","won't"],2],
["After will, we use:",["V2","V3","verb-ing","V1"],3]
]},
 {id:"verbPatterns",name:"Verb Patterns",ar:"أنماط الأفعال: الفعل الذي يأتي بعده to أو ing أو مفعول",use:"نستخدم Verb Patterns عندما يحدد الفعل الأول شكل الفعل الذي يأتي بعده. بعض الأفعال يأتي بعدها to + V1، وبعضها يأتي بعدها verb-ing، وبعضها يقبل الشكلين مع اختلاف المعنى أو بدونه. كذلك قد يأتي مفعول بين الفعلين في بعض التراكيب.",signals:"To-infinitive (to + V1): want (يريد), need (يحتاج), decide (يقرر), hope (يأمل), plan (يخطط), promise (يعد), agree (يوافق), refuse (يرفض), offer (يعرض), expect (يتوقع), choose (يختار), learn (يتعلم), manage (ينجح في), would like (يود). يدل غالباً على رغبة أو حاجة أو قرار أو خطة أو وعد أو هدف. | Bare infinitive (V1 بدون to): بعد modal verbs: can, could, may, might, must, should, will, would, shall؛ وبعد let, make, had better, would rather. | verb-ing: enjoy, avoid, finish, mind, suggest, keep, consider, practise, admit, deny, miss. | preposition + verb-ing: interested in, good at, look forward to, think about, succeed in.",forms:[
"1) To-infinitive (to + V1): يتكوّن من to + الفعل بصيغته الأساسية دون s أو ed أو ing. نستخدمه غالباً للتعبير عن الرغبة أو الحاجة أو القرار أو الأمل أو الخطة أو الوعد أو الهدف. أمثلة: I want to learn. / She decided to leave. / He hopes to win.",
"الكلمات المفتاحية ومعانيها التي يأتي بعدها to + V1: want = يريد، need = يحتاج، decide = يقرر، hope = يأمل، plan = يخطط، promise = يعد، agree = يوافق، refuse = يرفض، offer = يعرض، expect = يتوقع، choose = يختار، learn = يتعلم، manage = يتمكن/ينجح في، would like = يود. احفظ النمط: هذه الأفعال + to + V1.",
"2) Bare infinitive (V1 بدون to): نستخدم الفعل بصيغته الأساسية مباشرة دون to أو s أو ed أو ing. يأتي بعد الأفعال الناقصة (Modal verbs): can, could, may, might, must, should, will, would, shall. معانيها الشائعة: can = يستطيع، could = استطاع/قد، may = قد/مسموح له، might = ربما، must = يجب، should = ينبغي، will = سوف، would = كان سوف/للطلب المهذب، shall = سوف. أمثلة: She can swim. / You must study.",
"كلمات وتراكيب مفتاحية أخرى يأتي بعدها bare infinitive: let = يدع/يسمح، make = يجعل/يجبر، had better = من الأفضل أن، would rather = يفضّل أن. أمثلة: Let me go. / The teacher made us rewrite the answer. / You had better leave. / I would rather stay. (بعد help يجوز وجود to أو عدمه: Help me (to) carry this.)",
"مهم: لا نخلط بين to-infinitive وbare infinitive؛ الأول فيه to (to + V1)، والثاني فعل V1 مباشرة بدون to.",
"3) Verb + verb-ing: نضع الفعل الثاني مع ing مباشرة دون to. أمثلة: I enjoy reading. / He finished doing his homework.",
"أفعال شائعة يتبعها ing: enjoy, avoid, finish, mind, suggest, keep, practise, consider, admit, deny, miss, risk, imagine, postpone.",
"3) Verb + object + to + V1: يأتي مفعول به بين الفعل وto. أمثلة: She told me to wait. / My teacher encouraged us to study. أفعال شائعة: ask, tell, advise, allow, encourage, invite, remind, want.",
"4) Preposition + verb-ing: إذا جاء حرف جر قبل الفعل، نستخدم غالباً ing وليس to + V1. أمثلة: good at drawing / interested in learning / think about moving.",
"5) أفعال تقبل to أو ing مع معنى متقارب غالباً: start, begin, continue, like, love, hate, prefer. مثال: It started to rain / It started raining.",
"6) أفعال يتغير معناها حسب الشكل: stop + ing = يتوقف عن فعل شيء؛ stop + to + V1 = يتوقف لكي يفعل شيئاً. remember/forget + ing = يتذكر/ينسى شيئاً حدث؛ remember/forget + to + V1 = يتذكر/ينسى أن يقوم بمهمة. try + ing = يجرب طريقة؛ try + to + V1 = يحاول القيام بشيء.",
"ملاحظة مهمة: كلمة to ليست دائماً علامة مصدر؛ في look forward to وbe used to تكون to حرف جر، لذلك يأتي بعدها اسم أو verb-ing: I look forward to meeting you."
],examples:[
"I want to travel. — أريد أن أسافر. (want + to + V1)",
"She can speak English. — تستطيع التحدث بالإنجليزية. (can + bare infinitive)",
"Let him try. — دعه يحاول. (let + object + bare infinitive)",
"The joke made us laugh. — جعلتنا النكتة نضحك. (make + object + bare infinitive)",
"They enjoy playing football. — يستمتعون بلعب كرة القدم. (enjoy + ing)",
"The doctor advised him to rest. — نصحه الطبيب أن يرتاح. (advise + object + to + V1)",
"She is good at drawing. — هي جيدة في الرسم. (at + ing)",
"He stopped smoking. — أقلع عن التدخين. (stop + ing)",
"He stopped to answer the phone. — توقف لكي يجيب على الهاتف. (stop + to + V1)",
"Remember to lock the door. — تذكّر أن تقفل الباب. (مهمة يجب القيام بها)",
"I remember meeting her. — أتذكر أنني قابلتها. (حدث حصل في الماضي)"
],tip:"قبل اختيار شكل الفعل الثاني، انظر إلى الفعل الأول واحفظ النمط الذي يتبعه. إذا سبق الفعلَ حرفُ جر، فغالباً نستخدم ing. وإذا وجدت مفعولاً بعد أفعال مثل tell أو ask أو advise، فغالباً يأتي بعده to + V1. انتبه للأفعال التي يتغير معناها مثل stop وremember وtry.",quiz:[
["I want ___ a new language.",["learn","learning","to learn","learned"],2],
["She enjoys ___ novels.",["read","to read","reading","reads"],2],
["They decided ___ early.",["leave","leaving","to leave","left"],2],
["He finished ___ his homework.",["do","to do","doing","does"],2],
["My parents encouraged me ___ harder.",["study","studying","to study","studied"],2],
["You should avoid ___ too much sugar.",["eat","to eat","eating","eats"],2],
["She is interested in ___ Japanese.",["learn","to learn","learning","learned"],2],
["The teacher told us ___ quiet.",["be","being","to be","been"],2],
["He stopped ___ because it was unhealthy. (توقف عن العادة)",["smoke","to smoke","smoking","smoked"],2],
["He stopped ___ some water. (توقف لكي يشرب)",["drink","drinking","to drink","drank"],2],
["I look forward to ___ you.",["see","seeing","to see","saw"],1],
["After the verb 'promise', we usually use:",["verb-ing","to + V1","V2","object + V-ing"],1],
["Which phrase is correct?",["good at draw","good at drawing","good at to draw","good at drew"],1],
["Remember ___ the door before you leave. (لا تنسَ المهمة)",["locking","to lock","lock","locked"],1],
["After 'make' in the active pattern, we usually use:",["object + to + V1","object + V1","verb-ing","V3"],1],
["Choose the correct form: She can ___ very fast.",["runs","to run","run","running"],2],
["After 'let + object', we usually use:",["to + V1","V1 without to","V-ing","V2"],1],
["Which sentence uses the to-infinitive correctly?",["I hope pass the test.","I hope to pass the test.","I hope passing the test.","I hope passed the test."],1],
["Which sentence uses the bare infinitive correctly?",["He must to go.","He must going.","He must goes.","He must go."],3]
]},
 {id:"articles",name:"Articles: A / An / The",ar:"أدوات التعريف والتنكير",use:"نستخدم a وan مع الاسم المفرد المعدود عندما نتحدث عن شيء غير محدد أو نذكره لأول مرة. ونستخدم the عندما يكون الشيء محدداً أو معروفاً للمتحدث والمستمع، أو عندما يكون فريداً.",signals:"a = قبل صوت ساكن؛ an = قبل صوت متحرك؛ the = شيء محدد أو معروف",forms:["A + اسم مفرد يبدأ صوته بصوت ساكن: a book, a university.","An + اسم مفرد يبدأ صوته بصوت متحرك: an apple, an hour.","The + اسم محدد أو معروف: the book on the table.","لا نستخدم a/an مع الجمع أو الأسماء غير المعدودة: books, water."],examples:["I saw a cat. The cat was black. — رأيت قطة. كانت القطة سوداء.","She ate an orange. — أكلت برتقالة.","Please close the door. — من فضلك أغلق الباب.","Water is important. — الماء مهم."],tip:"اختَر a أو an حسب الصوت الأول للكلمة وليس الحرف فقط؛ نقول an hour لأن h لا تُنطق، وa university لأن بدايتها تُنطق /يو/.",quiz:[
["I have ___ apple.",["a","an","the","no article"],1],
["She is ___ teacher.",["a","an","the","no article"],0],
["___ sun is very bright today.",["A","An","The","No article"],2],
["He waited for ___ hour.",["a","an","the","no article"],1],
["I need ___ new phone.",["a","an","the","no article"],0],
["Please open ___ window next to you.",["a","an","the","no article"],2],
["We usually drink ___ water.",["a","an","the","no article"],3],
["She bought ___ umbrella.",["a","an","the","no article"],1],
["My father is ___ doctor.",["a","an","the","no article"],0],
["I saw a dog. ___ dog was very small.",["A","An","The","No article"],2],
["He studies at ___ university.",["a","an","the","no article"],0],
["There are ___ books on the desk.",["a","an","the","no article"],3],
["This is ___ interesting story.",["a","an","the","no article"],1],
["___ moon looks beautiful tonight.",["A","An","The","No article"],2],
["She wants to be ___ engineer.",["a","an","the","no article"],1]
]}

];
function renderGrammarTopics(){
 const box=document.getElementById("grammarTopics");
 if(!box) return;
 // اترك بطاقة Verb Patterns الثابتة، واجمع أزمنة الماضي والمضارع تحت كبسة مستقلة لكل مجموعة.
 box.querySelectorAll(".generated-grammar-card").forEach(c=>c.remove());
 const pastIds=["pastSimple","pastContinuous","pastPerfect"];
 const presentIds=["simple","continuous","perfect","perfectcontinuous"];
 const futureIds=["futureContinuous","futurePerfect"];
 grammarData.filter(g=>g.id!=="verbPatterns" && !pastIds.includes(g.id) && !presentIds.includes(g.id) && !futureIds.includes(g.id)).forEach(g=>{
  const c=document.createElement("div");
  c.className="grammar-card generated-grammar-card";
  c.innerHTML=`<h3>${g.name}</h3><p>${g.ar}</p><br><button type="button" onclick="openGrammar('${g.id}')">شرح القاعدة والامتحان</button>`;
  box.appendChild(c);
 });
 const pastCard=document.createElement("div");
 pastCard.className="grammar-card generated-grammar-card past-tenses-card";
 pastCard.innerHTML=`
  <h3>Past Tenses</h3>
  <p>أزمنة الماضي: اختر الزمن الذي تريد شرحه والتدرب عليه.</p>
  <br>
  <button type="button" onclick="togglePastTenses()" aria-expanded="false" id="pastTensesToggle">اختيار زمن من أزمنة الماضي</button>
  <div id="pastTensesOptions" style="display:none;margin-top:14px;gap:9px;flex-wrap:wrap">
   <button type="button" onclick="openGrammar('pastSimple')">Past Simple - الماضي البسيط</button>
   <button type="button" onclick="openGrammar('pastContinuous')">Past Continuous - الماضي المستمر</button>
   <button type="button" onclick="openGrammar('pastPerfect')">Past Perfect - الماضي التام</button>
  </div>`;
 box.appendChild(pastCard);
 const presentCard=document.createElement("div");
 presentCard.className="grammar-card generated-grammar-card present-tenses-card";
 presentCard.innerHTML=`
  <h3>Present Tenses</h3>
  <p>أزمنة المضارع: اختر الزمن الذي تريد شرحه والتدرب عليه.</p>
  <br>
  <button type="button" onclick="togglePresentTenses()" aria-expanded="false" id="presentTensesToggle">اختيار زمن من أزمنة المضارع</button>
  <div id="presentTensesOptions" style="display:none;margin-top:14px;gap:9px;flex-wrap:wrap">
   <button type="button" onclick="openGrammar('continuous')">Present Continuous - المضارع المستمر</button>
   <button type="button" onclick="openGrammar('simple')">Present Simple - المضارع البسيط</button>
  </div>`;
 box.appendChild(presentCard);
 const presentPerfectCard=document.createElement("div");
 presentPerfectCard.className="grammar-card generated-grammar-card present-perfect-tenses-card";
 presentPerfectCard.innerHTML=`
  <h3>Present Perfect Tenses</h3>
  <p>أزمنة المضارع التام: اختر الزمن الذي تريد شرحه والتدرب عليه.</p>
  <br>
  <button type="button" onclick="togglePresentPerfectTenses()" aria-expanded="false" id="presentPerfectTensesToggle">اختيار زمن من أزمنة المضارع التام</button>
  <div id="presentPerfectTensesOptions" style="display:none;margin-top:14px;gap:9px;flex-wrap:wrap">
   <button type="button" onclick="openGrammar('perfect')">Present Perfect Simple - المضارع التام البسيط</button>
   <button type="button" onclick="openGrammar('perfectcontinuous')">Present Perfect Continuous - المضارع التام المستمر</button>
  </div>`;
 box.appendChild(presentPerfectCard);
 const futureCard=document.createElement("div");
 futureCard.className="grammar-card generated-grammar-card future-tenses-card";
 futureCard.innerHTML=`
  <h3>Future Tenses</h3>
  <p>أزمنة المستقبل: اختر الزمن الذي تريد شرحه والتدرب عليه.</p>
  <br>
  <button type="button" onclick="toggleFutureTenses()" aria-expanded="false" id="futureTensesToggle">اختيار زمن من أزمنة المستقبل</button>
  <div id="futureTensesOptions" style="display:none;margin-top:14px;gap:9px;flex-wrap:wrap">
   <button type="button" onclick="openGrammar('futureContinuous')">Future Continuous - المستقبل المستمر</button>
   <button type="button" onclick="openGrammar('futurePerfect')">Future Perfect - المستقبل التام</button>
  </div>`;
 box.appendChild(futureCard);
 const mixedCard=document.createElement("div");
 mixedCard.className="grammar-card generated-grammar-card mixed-grammar-card";
 mixedCard.innerHTML=`
  <h3>🎯 Mixed Grammar Challenge - امتحان القواعد المختلط</h3>
  <p>امتحان جديد يجمع أسئلة من قواعد مختلفة بترتيب عشوائي، مع تصحيح ومراجعة لكل إجابة.</p>
  <br>
  <button type="button" onclick="startMixedGrammarExam()">ابدأ التحدي المختلط</button>`;
 box.appendChild(mixedCard);
}
function toggleFutureTenses(){
 const options=document.getElementById("futureTensesOptions");
 const toggle=document.getElementById("futureTensesToggle");
 if(!options || !toggle) return;
 const isHidden=options.style.display==="none";
 options.style.display=isHidden?"flex":"none";
 toggle.setAttribute("aria-expanded",String(isHidden));
 toggle.textContent=isHidden?"إخفاء أزمنة المستقبل":"اختيار زمن من أزمنة المستقبل";
}
function togglePresentPerfectTenses(){
 const options=document.getElementById("presentPerfectTensesOptions");
 const toggle=document.getElementById("presentPerfectTensesToggle");
 if(!options || !toggle) return;
 const isHidden=options.style.display==="none";
 options.style.display=isHidden?"flex":"none";
 toggle.setAttribute("aria-expanded",String(isHidden));
 toggle.textContent=isHidden?"إخفاء أزمنة المضارع التام":"اختيار زمن من أزمنة المضارع التام";
}
function togglePresentTenses(){
 const options=document.getElementById("presentTensesOptions");
 const toggle=document.getElementById("presentTensesToggle");
 if(!options || !toggle) return;
 const isHidden=options.style.display==="none";
 options.style.display=isHidden?"flex":"none";
 toggle.setAttribute("aria-expanded",String(isHidden));
 toggle.textContent=isHidden?"إخفاء أزمنة المضارع":"اختيار زمن من أزمنة المضارع";
}
function togglePastTenses(){
 const options=document.getElementById("pastTensesOptions");
 const toggle=document.getElementById("pastTensesToggle");
 if(!options || !toggle) return;
 const isHidden=options.style.display==="none";
 options.style.display=isHidden?"flex":"none";
 toggle.setAttribute("aria-expanded",String(isHidden));
 toggle.textContent=isHidden?"إخفاء أزمنة الماضي":"اختيار زمن من أزمنة الماضي";
}
let activeGrammarQuiz=[];
function shuffleArray(array){return array.slice().sort(()=>Math.random()-.5);}

// أقسام قاعدة Verb Patterns الأربعة، ولكل قسم شرح ودلالات وكلمات مفتاحية وامتحان مستقل.
const verbPatternSections = [
 {id:"ing",title:"Verb + ing",formula:"Verb + verb-ing",use:"نستخدم هذا النمط عندما يأتي بعد الفعل الأول فعلٌ آخر ينتهي بـ ing. لا نضع to قبل الفعل الثاني.",signals:["enjoy = يستمتع بـ","avoid = يتجنب","finish = ينهي","mind = يمانع","suggest = يقترح","keep = يستمر في","consider = يفكر في / يدرس خياراً","practise = يتدرب على","admit = يعترف بـ","deny = ينكر","miss = يفتقد / يشتاق إلى","risk = يخاطر بـ"],examples:["I enjoy reading. — أستمتع بالقراءة.","She avoided answering. — تجنبت الإجابة.","He finished doing his homework. — أنهى واجبه.","Do you mind opening the window? — هل تمانع فتح النافذة؟"],tip:"إذا وجدت فعلاً من الكلمات المفتاحية مثل enjoy أو avoid أو finish، فغالباً يكون الفعل الذي بعده verb-ing. انتبه: بعد حرف الجر نستخدم أيضاً ing.",quiz:[
 ["I enjoy ___ books.",["read","to read","reading","reads"],2],
 ["She avoids ___ late.",["arrive","to arrive","arriving","arrives"],2],
 ["They finished ___ the room.",["clean","to clean","cleaning","cleans"],2],
 ["Would you mind ___ the door?",["close","to close","closing","closed"],2],
 ["He suggested ___ a taxi.",["take","to take","taking","takes"],2],
 ["Keep ___ until you understand.",["practise","to practise","practising","practised"],2],
 ["She is good at ___.",["draw","to draw","drawing","draws"],2],
 ["I look forward to ___ you.",["meet","to meet","meeting","met"],2]
 ]},
 {id:"objectTo",title:"Verb + Object + To-Infinitive",formula:"Verb + object + to + V1",use:"نستخدم هذا النمط عندما يأتي مفعول به بعد الفعل الأول، ثم to وبعدها الفعل بصيغته الأساسية. المفعول يوضح مَن سيقوم بالفعل الثاني.",signals:["ask someone to = يطلب من شخص أن","tell someone to = يخبر / يأمر شخصاً أن","want someone to = يريد من شخص أن","advise someone to = ينصح شخصاً أن","allow someone to = يسمح لشخص أن","encourage someone to = يشجع شخصاً أن","invite someone to = يدعو شخصاً أن","remind someone to = يذكّر شخصاً أن","expect someone to = يتوقع من شخص أن","teach someone to = يعلّم شخصاً أن"],examples:["My teacher told me to study. — طلب مني معلمي أن أدرس.","They invited us to join. — دعونا للانضمام.","I want you to listen. — أريد منك أن تستمع.","The doctor advised him to rest. — نصحه الطبيب أن يرتاح."],tip:"ابحث عن الترتيب: فعل أول + شخص/مفعول + to + V1. لا تحذف المفعول في هذا النمط، ولا تضع ing بعد to.",quiz:[
 ["The teacher told us ___ quiet.",["be","being","to be","been"],2],
 ["My parents want me ___ hard.",["study","studying","to study","studied"],2],
 ["She advised him ___ a doctor.",["see","seeing","to see","saw"],2],
 ["They invited us ___ dinner.",["join","joining","to join","joined"],2],
 ["Please remind me ___ my book.",["bring","bringing","to bring","brought"],2],
 ["The coach encouraged the team ___.",["try","trying","to try","tried"],2],
 ["Our teacher allowed us ___ early.",["leave","leaving","to leave","left"],2],
 ["I asked Ali ___ me.",["help","helping","to help","helped"],2]
 ]},
 {id:"bare",title:"Bare Infinitive (V1 بدون to)",formula:"V1 مباشرةً بدون to",use:"نستخدم الفعل بصيغته الأساسية مباشرةً، دون to أو s أو ed أو ing، بعد الأفعال الناقصة وبعض الأفعال والتراكيب الخاصة.",signals:["can = يستطيع","could = يستطيع / استطاع أو قد","may = قد / يُسمح له","might = ربما","must = يجب","should = ينبغي","will = سوف","would = سوف / للطلب المهذب","let + object + V1 = يدع شخصاً يفعل","make + object + V1 = يجعل شخصاً يفعل","had better + V1 = من الأفضل أن","would rather + V1 = يفضّل أن"],examples:["She can swim. — تستطيع السباحة.","You should study. — ينبغي أن تدرس.","Let me explain. — دعني أشرح.","The joke made us laugh. — جعلتنا النكتة نضحك.","You had better leave. — من الأفضل أن تغادر."],tip:"بعد can وmust وshould وwill وغيرها من Modal verbs نستخدم V1 مباشرة. وبعد let وmake في المبني للمعلوم يأتي المفعول ثم V1 بدون to.",quiz:[
 ["She can ___ very fast.",["runs","to run","run","running"],2],
 ["You must ___ your homework.",["to do","doing","do","does"],2],
 ["He should ___ more water.",["drinks","to drink","drink","drinking"],2],
 ["They will ___ tomorrow.",["arrives","to arrive","arrive","arriving"],2],
 ["Let him ___.",["to speak","speaking","speak","speaks"],2],
 ["The film made us ___.",["to cry","crying","cry","cries"],2],
 ["You had better ___ now.",["to go","going","go","goes"],2],
 ["I would rather ___ at home.",["to stay","staying","stay","stays"],2]
 ]},
 {id:"to",title:"To-Infinitive (to + V1)",formula:"to + V1",use:"يتكوّن من to ثم الفعل بصيغته الأساسية. يأتي بعد أفعال تعبّر غالباً عن الرغبة أو الحاجة أو القرار أو الأمل أو الخطة أو الوعد أو الهدف.",signals:["want = يريد","need = يحتاج","decide = يقرر","hope = يأمل","plan = يخطط","promise = يعد","agree = يوافق","refuse = يرفض","offer = يعرض","expect = يتوقع","choose = يختار","learn = يتعلم","manage = يتمكن من","would like = يود"],examples:["I want to learn English. — أريد أن أتعلم الإنجليزية.","She decided to leave. — قررت أن تغادر.","We hope to win. — نأمل أن نفوز.","He promised to help. — وعد أن يساعد."],tip:"إذا جاء بعد الفعل الأول فعلٌ آخر وكان الفعل الأول من الكلمات المفتاحية مثل want أو decide أو hope، استخدم to ثم V1. بعد to لا نستخدم s أو ed أو ing في هذا النمط.",quiz:[
 ["I want ___ a new language.",["learn","learning","to learn","learned"],2],
 ["She decided ___ early.",["leave","leaving","to leave","left"],2],
 ["We hope ___ the match.",["win","winning","to win","won"],2],
 ["He promised ___ me.",["help","helping","to help","helped"],2],
 ["They plan ___ abroad.",["travel","travelling","to travel","travelled"],2],
 ["I need ___ some water.",["drink","drinking","to drink","drank"],2],
 ["She agreed ___ us.",["join","joining","to join","joined"],2],
 ["He refused ___ the question.",["answer","answering","to answer","answered"],2]
 ]}
];

function openVerbPatternsMenu(){
 const box=document.getElementById("grammarLesson");
 box.innerHTML=`<div class="card"><h2>Verb Patterns - أنماط الأفعال</h2><p style="line-height:2">اختَر القسم الذي تريد دراسته. كل قسم يحتوي على التركيب، والدلالات، والكلمات المفتاحية ومعانيها، وأمثلة، وامتحان قصير خاص به.</p><div class="grammar-grid">${verbPatternSections.map((s,i)=>`<div class="grammar-card"><h3>${i+1}. ${s.title}</h3><p dir="ltr" style="text-align:left;font-weight:bold">${s.formula}</p><p>${s.use}</p><button type="button" onclick="openVerbPatternSection('${s.id}')">افتح الشرح والامتحان</button></div>`).join("")}</div></div>`;
 box.scrollIntoView({behavior:"smooth"});
}
function openVerbPatternSection(sectionId){
 const s=verbPatternSections.find(x=>x.id===sectionId);if(!s)return;
 activeGrammarQuiz=shuffleArray(s.quiz).map(q=>{const correctText=q[1][q[2]],options=shuffleArray(q[1]);return [q[0],options,options.indexOf(correctText)];});
 const box=document.getElementById("grammarLesson");
 box.innerHTML=`<div class="card"><button type="button" onclick="openVerbPatternsMenu()">⬅ رجوع إلى أقسام Verb Patterns</button><h2>${s.title}</h2><h3>التركيب</h3><p dir="ltr" style="text-align:left;font-size:20px;font-weight:bold">${s.formula}</p><h3>متى نستخدمه؟</h3><p style="line-height:2">${s.use}</p><h3>الدلالات والكلمات المفتاحية ومعانيها</h3><ul>${s.signals.map(x=>`<li style="line-height:2">${x}</li>`).join("")}</ul><h3>أمثلة</h3><ul>${s.examples.map(x=>`<li style="line-height:2">${x}</li>`).join("")}</ul><div class="grammar-card"><strong>💡 طريقة الحل:</strong><p style="line-height:2">${s.tip}</p></div><br><h3>📝 امتحان القسم - ${s.quiz.length} أسئلة</h3><p>اختر إجابة واحدة لكل سؤال.</p><div id="verbPatternQuiz"></div><button type="button" onclick="gradeVerbPatternSection('${s.id}')">صحّح الامتحان</button><div id="verbPatternScore" style="margin-top:15px;font-size:20px"></div></div>`;
 const quiz=document.getElementById("verbPatternQuiz");
 activeGrammarQuiz.forEach((q,i)=>{const d=document.createElement("div");d.className="grammar-question";d.innerHTML=`<strong>${i+1}. ${q[0]}</strong>`+q[1].map((o,j)=>`<label style="display:block;margin:9px 0"><input type="radio" name="vpq${i}" value="${j}" style="width:auto;margin:0 7px"> <span dir="ltr">${o}</span></label>`).join("");quiz.appendChild(d);});
 box.scrollIntoView({behavior:"smooth"});
}
function gradeVerbPatternSection(sectionId){
 const s=verbPatternSections.find(x=>x.id===sectionId);if(!s)return;
 let score=0,missing=0;const review=[];
 activeGrammarQuiz.forEach((q,i)=>{const a=document.querySelector(`input[name="vpq${i}"]:checked`);if(!a){missing++;return;}const chosen=Number(a.value);review.push({question:q[0],answer:q[1][chosen],correctAnswer:q[1][q[2]],correct:chosen===q[2]});if(chosen===q[2])score++;});
 const r=document.getElementById("verbPatternScore");if(missing){r.textContent=`باقي ${missing} أسئلة بدون إجابة. جاوبها كلها ثم صحّح الامتحان.`;return;}
 r.innerHTML=`نتيجتك: <strong style="color:#64caff">${score}/${s.quiz.length} (${Math.round(score/s.quiz.length*100)}%)</strong><br>${score===s.quiz.length?"ممتاز!":score>=6?"أحسنت! راجع الأخطاء.":"راجع الشرح وحاول مرة ثانية."}<div class="card" style="margin-top:15px;text-align:right"><h3>مراجعة الإجابات</h3>${review.map((m,i)=>`<div class="grammar-question"><strong>${i+1}. ${m.question}</strong><p>إجابتك: <span style="color:${m.correct?'#75e6a5':'#ff9aa8'}">${m.answer}</span></p><p>الإجابة الصحيحة: <strong style="color:#75e6a5">${m.correctAnswer}</strong></p>${m.correct?'✅ صحيح':'❌ غير صحيح'}</div>`).join("")}</div>`;
}

// ===================================
// اختبار تحديد مستوى اللغة الإنجليزية (A1 إلى C2)
// 15 سؤال معاني لكل مستوى = 90 سؤالاً
// خمس إجابات خاطئة متتالية في المستوى نفسه توقف الاختبار
// ===================================
let assessmentLevels = ["A1","A2","B1","B2","C1","C2"];
let assessmentQuestions = [];
let assessmentLevelIndex = 0;
let assessmentQuestionIndex = 0;
let assessmentTotalScore = 0;
let assessmentLevelScore = 0;
let assessmentWrongStreak = 0;
let assessmentFinished = false;
let assessmentHistory = [];

function startLevelAssessment(){
 const panel=document.getElementById("levelAssessment");
 document.getElementById("examStart").style.display="none";
 document.getElementById("quiz").style.display="none";
 document.getElementById("quizResult").innerHTML="";
 panel.style.display="block";
 assessmentLevelIndex=0;
 assessmentQuestionIndex=0;
 assessmentTotalScore=0;
 assessmentLevelScore=0;
 assessmentWrongStreak=0;
 assessmentFinished=false;
 assessmentHistory=[];
 assessmentQuestions=[];
 // اختيار 15 كلمة من كلمات كل مستوى، مع خلط ترتيب الأسئلة والاختيارات.
 for(const level of assessmentLevels){
  const bank=words.filter(x=>x.l===level && x.w && x.t);
  if(bank.length<15){
   panel.innerHTML=`<div class="card">عذراً، لا توجد 15 كلمة كافية في المستوى ${level} لإكمال اختبار تحديد المستوى.</div>`;
   return;
  }
  const chosen=shuffleArray(bank.slice()).slice(0,15);
  assessmentQuestions.push(chosen.map(item=>{
   const distractors=shuffleArray(words.filter(x=>x.t!==item.t && x.w.toLowerCase()!==item.w.toLowerCase()))
    .slice(0,3).map(x=>x.t);
   const options=shuffleArray([item.t,...distractors]);
   return {level:level,word:item.w,translation:item.t,options:options,answer:options.indexOf(item.t)};
  }));
  if(score===s.quiz.length)celebratePerfectScore("علامة كاملة في امتحان القواعد!");
 }
 renderAssessmentQuestion();
}

function renderAssessmentQuestion(){
 const panel=document.getElementById("levelAssessment");
 const level=assessmentLevels[assessmentLevelIndex];
 const item=assessmentQuestions[assessmentLevelIndex][assessmentQuestionIndex];
 const totalDone=assessmentLevels.slice(0,assessmentLevelIndex).length*15+assessmentQuestionIndex+1;
 panel.innerHTML=`<div class="card">
  <h2>🎯 اختبار تحديد مستوى اللغة الإنجليزية</h2>
  <p style="line-height:2">المستوى الحالي: <strong style="color:#64caff">${level}</strong> — ${levelNames[level]}</p>
  <p>السؤال ${assessmentQuestionIndex+1} من 15 في هذا المستوى | السؤال ${totalDone} من 90</p>
  <div style="height:10px;background:#303a59;border-radius:10px;margin:14px 0;overflow:hidden"><div style="height:100%;width:${(totalDone/90)*100}%;background:#64caff"></div></div>
  <p>الإجابات الصحيحة في هذا المستوى: ${assessmentLevelScore}/15</p>
  <p>الأخطاء المتتالية: ${assessmentWrongStreak}/5</p>
  <hr style="border-color:#3c4770;margin:18px 0">
  <h3 dir="ltr" style="font-size:32px;margin:20px 0">${item.word}</h3>
  <p>ما معنى الكلمة باللغة العربية؟</p>
  <div id="assessmentOptions" class="levels" style="margin-top:18px"></div>
  <p id="assessmentFeedback" style="margin-top:15px;line-height:2"></p>
  <button id="assessmentNext" type="button" style="display:none" onclick="nextAssessmentQuestion()">السؤال التالي</button>
  <button type="button" onclick="cancelLevelAssessment()" style="background:#555;margin-right:8px">إنهاء الاختبار</button>
 </div>`;
 const options=document.getElementById("assessmentOptions");
 item.options.forEach((option,index)=>{
  const btn=document.createElement("button");
  btn.type="button";btn.className="option";btn.textContent=option;
  btn.style.display="block";btn.style.width="100%";btn.style.margin="8px 0";
  btn.onclick=()=>answerAssessment(index,btn);
  options.appendChild(btn);
 });
 panel.scrollIntoView({behavior:"smooth",block:"start"});
  if(reason==="complete" && assessmentTotalScore===90)celebratePerfectScore("90 من 90! مستوى أسطوري!");
}

function answerAssessment(choice,button){
 if(assessmentFinished)return;
 const item=assessmentQuestions[assessmentLevelIndex][assessmentQuestionIndex];
 const buttons=document.querySelectorAll("#assessmentOptions button");
 buttons.forEach(b=>b.disabled=true);
 const feedback=document.getElementById("assessmentFeedback");
 if(choice===item.answer){
  assessmentTotalScore++;assessmentLevelScore++;assessmentWrongStreak=0;
  button.style.background="#16834b";
  feedback.innerHTML="✅ إجابة صحيحة!";
 }else{
  assessmentWrongStreak++;
  button.style.background="#a83245";
  buttons[item.answer].style.background="#16834b";
  feedback.innerHTML=`❌ الإجابة الصحيحة: <strong>${item.translation}</strong><br>باقي ${Math.max(0,5-assessmentWrongStreak)} أخطاء متتالية حتى يتوقف الاختبار في هذا المستوى.`;
 }
 assessmentHistory.push({level:item.level,word:item.word,correct:choice===item.answer,answer:item.translation});
 const next=document.getElementById("assessmentNext");
 next.style.display="inline-block";
 next.textContent=(assessmentWrongStreak>=5 || (assessmentQuestionIndex===14 && assessmentLevelIndex===5))?"عرض النتيجة":"السؤال التالي";
}

function nextAssessmentQuestion(){
 if(assessmentWrongStreak>=5){finishLevelAssessment(assessmentLevels[assessmentLevelIndex],"streak");return;}
 if(assessmentQuestionIndex<14){
  assessmentQuestionIndex++;
  renderAssessmentQuestion();
  return;
 }
 // انتهت أسئلة المستوى الحالي دون الوصول إلى خمسة أخطاء متتالية.
 if(assessmentLevelIndex<5){
  assessmentLevelIndex++;
  assessmentQuestionIndex=0;
  assessmentLevelScore=0;
  assessmentWrongStreak=0;
  renderAssessmentQuestion();
 }else{
  finishLevelAssessment("C2","complete");
 }
}

function finishLevelAssessment(level,reason){
 assessmentFinished=true;
 const panel=document.getElementById("levelAssessment");
 const completed=assessmentHistory.length;
 const title=reason==="complete"?"ممتاز! أكملت جميع المستويات":"توقف الاختبار بعد خمسة أخطاء متتالية";
 const description=reason==="complete"?
  "أجبت عن جميع الأسئلة التسعين، وهذا يشير إلى أنك وصلت إلى مستوى C2 في هذا الاختبار.":
  `وصلت إلى خمسة أخطاء متتالية في مستوى ${level}، لذلك تم تحديد مستواك في هذا الاختبار عند ${level} (${levelNames[level]}).`;
 panel.innerHTML=`<div class="card" style="text-align:center">
  <h2>🏆 نتيجة اختبار تحديد المستوى</h2>
  <h3 style="color:#64caff;margin:18px 0">${title}</h3>
  <div style="font-size:54px;margin:15px 0">${level}</div>
  <h3>${levelNames[level]}</h3>
  <p style="line-height:2;margin:15px 0">${description}</p>
  <p>إجابات صحيحة: ${assessmentTotalScore} من ${completed}</p>
  <p>نسبة الإجابات الصحيحة: ${completed?Math.round(assessmentTotalScore/completed*100):0}%</p>
  <p>عدد الأسئلة التي أجبت عنها: ${completed}</p>
  <button type="button" onclick="startLevelAssessment()">إعادة الاختبار من A1</button>
  <button type="button" onclick="document.getElementById('levelAssessment').style.display='none';document.getElementById('examStart').style.display='block';" style="background:#555">العودة إلى الامتحانات</button>
  <div style="text-align:right;margin-top:22px"><h3>ملخص أدائك حسب المستوى</h3>${assessmentLevels.map(l=>{
   const rows=assessmentHistory.filter(x=>x.level===l);
   if(!rows.length)return '';
   const good=rows.filter(x=>x.correct).length;
   return `<p style="margin:8px 0">${l}: ${good} إجابة صحيحة من ${rows.length}</p>`;
  }).join("")}</div>
 </div>`;
 panel.scrollIntoView({behavior:"smooth",block:"start"});
}

function cancelLevelAssessment(){
 if(!confirm("هل تريد إنهاء اختبار تحديد المستوى والعودة إلى الامتحانات؟"))return;
 document.getElementById("levelAssessment").style.display="none";
 document.getElementById("examStart").style.display="block";
}

// ===================================
// نمط امتحان جديد: تحدي القواعد المختلط
// ===================================
let mixedGrammarQuestions=[];
function startMixedGrammarExam(){
 const pool=[];
 grammarData.filter(g=>g.id!=="verbPatterns" && Array.isArray(g.quiz)).forEach(g=>{
  g.quiz.forEach(q=>{
   if(!Array.isArray(q) || !Array.isArray(q[1]) || typeof q[2]!=="number") return;
   const correctText=q[1][q[2]];
   const shuffled=shuffleArray(q[1]);
   pool.push({rule:g.name,question:q[0],options:shuffled,answer:shuffled.indexOf(correctText)});
  });
 });
 if(pool.length<5){alert("لا توجد أسئلة كافية لإنشاء الامتحان المختلط.");return;}
 mixedGrammarQuestions=shuffleArray(pool).slice(0,20);
 const box=document.getElementById("grammarLesson");
 box.innerHTML=`<div class="card">
  <h2>🎯 امتحان القواعد المختلط</h2>
  <p>20 سؤالاً من قواعد مختلفة. اختَر إجابة واحدة لكل سؤال، ثم اضغط صحّح الامتحان.</p>
  <div id="mixedGrammarQuiz"></div>
  <button type="button" onclick="gradeMixedGrammarExam()">صحّح الامتحان</button>
  <div id="mixedGrammarScore" style="margin-top:18px;font-size:19px"></div>
  <button type="button" onclick="startMixedGrammarExam()">امتحان جديد بأسئلة مختلفة</button>
  <button type="button" onclick="renderGrammarTopics();document.getElementById('grammarLesson').innerHTML='';">العودة إلى القواعد</button>
 </div>`;
 const quiz=document.getElementById("mixedGrammarQuiz");
 mixedGrammarQuestions.forEach((q,i)=>{
  const d=document.createElement("div");d.className="grammar-question";
  d.innerHTML=`<strong>${i+1}. ${q.question}</strong><p style="color:#64c9ff;margin:6px 0">القاعدة: ${q.rule}</p>`+
   q.options.map((o,j)=>`<label style="display:block;margin:9px 0"><input type="radio" name="mgq${i}" value="${j}" style="width:auto;margin:0 7px"> <span dir="ltr">${o}</span></label>`).join("");
  quiz.appendChild(d);
 });
 box.scrollIntoView({behavior:"smooth"});
}
function gradeMixedGrammarExam(){
 let score=0,missing=0;const review=[];
 mixedGrammarQuestions.forEach((q,i)=>{
  const selected=document.querySelector(`input[name="mgq${i}"]:checked`);
  if(!selected){missing++;return;}
  const chosen=Number(selected.value),correct=chosen===q.answer;
  if(correct)score++;
  review.push({q,chosen,correct});
 });
 const result=document.getElementById("mixedGrammarScore");
 if(missing){result.textContent=`باقي ${missing} سؤال/أسئلة بدون إجابة. جاوبها كلها ثم صحّح الامتحان.`;return;}
 result.innerHTML=`نتيجتك: <strong style="color:#64c9ff">${score}/20 (${Math.round(score/20*100)}%)</strong><br>${score===20?"ممتاز! كل إجاباتك صحيحة.":score>=16?"أحسنت! مستوى رائع.":score>=12?"جيد، راجع الأسئلة التي أخطأت فيها.":"راجع القواعد وحاول مرة ثانية."}`+
  `<div class="card" style="margin-top:15px;text-align:right"><h3>📋 مراجعة الإجابات</h3>${review.map((x,i)=>`<div class="grammar-question"><strong>${i+1}. ${x.q.question}</strong><p>القاعدة: ${x.q.rule}</p><p>إجابتك: <span style="color:${x.correct?'#75e6a5':'#ff9aa8'}">${x.q.options[x.chosen]}</span></p><p>الإجابة الصحيحة: <strong style="color:#75e6a5">${x.q.options[x.q.answer]}</strong></p><p>${x.correct?'✅ صحيح':'❌ غير صحيح'}</p></div>`).join("")}</div>`;
 result.scrollIntoView({behavior:"smooth"});
  if(score===20)celebratePerfectScore("20 من 20 في تحدي القواعد!");
}

function openGrammar(id){
 if(id==="verbPatterns"){openVerbPatternsMenu();return;}
 const g=grammarData.find(x=>x.id===id);if(!g)return;
 // كل محاولة تحصل على ترتيب مختلف للأسئلة والاختيارات، مع بقاء الإجابة الصحيحة مرتبطة بها.
 activeGrammarQuiz=shuffleArray(g.quiz).map(q=>{
  const correctText=q[1][q[2]];
  const options=shuffleArray(q[1]);
  return [q[0],options,options.indexOf(correctText)];
 });
 const box=document.getElementById("grammarLesson");
 box.innerHTML=`<div class="card"><h2>${g.name} - ${g.ar}</h2><h3>متى نستخدمها؟</h3><p>${g.use}</p><br><h3>الدلالات والكلمات المفتاحية</h3><p dir="ltr" style="text-align:left">${g.signals}</p><br><h3>تركيب الجملة</h3><ul>${g.forms.map(x=>`<li style="line-height:2">${x}</li>`).join("")}</ul>${g.examples?`<br><h3>أمثلة</h3><ul>${g.examples.map(x=>`<li style="line-height:2">${x}</li>`).join("")}</ul>`:""}<div class="grammar-card"><strong>💡 طريقة الحل:</strong><p>${g.tip}</p><p>1. اقرأ معنى الجملة وحدد الزمن المقصود.</p><p>2. ابحث عن الكلمات الدالة، فهي تساعدك ولا تكفي وحدها.</p><p>3. حدّد الفاعل، ثم اختر الفعل المساعد والتصريف الصحيح.</p><p>4. راجع ترتيب الكلمات والنفي والسؤال.</p></div><br><h3>📝 امتحان - ${g.quiz.length} سؤالاً</h3><p>اختر إجابة واحدة لكل سؤال.</p><div id="grammarQuiz"></div><button onclick="gradeGrammar('${g.id}')">صحّح الامتحان</button><div id="grammarScore" style="margin-top:15px;font-size:20px"></div></div>`;
 const quiz=document.getElementById("grammarQuiz");
 activeGrammarQuiz.forEach((q,i)=>{const d=document.createElement("div");d.className="grammar-question";d.innerHTML=`<strong>${i+1}. ${q[0]}</strong>`+q[1].map((o,j)=>`<label style="display:block;margin:9px 0"><input type="radio" name="gq${i}" value="${j}" style="width:auto;margin:0 7px"> <span dir="ltr">${o}</span></label>`).join("");quiz.appendChild(d);});
 box.scrollIntoView({behavior:"smooth"});
}
function gradeGrammar(id){
 const g=grammarData.find(x=>x.id===id);if(!g)return;
 let score=0,missing=0;const mistakes=[],review=[];
 activeGrammarQuiz.forEach((q,i)=>{
  const a=document.querySelector(`input[name="gq${i}"]:checked`);
  if(!a){missing++;return;}
  const chosen=Number(a.value);
  const item={number:i+1,question:q[0],userAnswer:q[1][chosen],correctAnswer:q[1][q[2]],correct:chosen===q[2]};
  review.push(item);
  if(item.correct)score++;else mistakes.push(item);
 });
 const r=document.getElementById("grammarScore");
 if(missing){r.textContent=`باقي ${missing} أسئلة بدون إجابة. جاوبها كلها ثم صحّح الامتحان.`;return;}
 r.innerHTML=`نتيجتك: <strong style="color:#64caff">${score}/${g.quiz.length} (${Math.round(score/g.quiz.length*100)}%)</strong><br>${score>=13?"ممتاز!":score>=10?"جيد جداً!":score>=8?"نتيجة جيدة، راجع الأخطاء.":"راجع القاعدة ثم حاول مرة أخرى."}`+
 `<div class="card" style="margin-top:15px;text-align:right"><h3>📋 مراجعة جميع الأسئلة والإجابات</h3>${review.map(m=>`<div class="grammar-question"><strong>${m.number}. ${m.question}</strong><p style="margin-top:8px">إجابتك: <span style="color:${m.correct?'#75e6a5':'#ff9aa8'}">${m.userAnswer}</span></p><p>الإجابة الصحيحة: <strong style="color:#75e6a5">${m.correctAnswer}</strong></p><p>${m.correct?'✅ صحيح':'❌ غير صحيح'}</p></div>`).join("")}</div>`;
  if(score===g.quiz.length)celebratePerfectScore("علامة كاملة في القواعد!");
}

// ===================================
let celebrationAudioContext=null,celebrationTimer=null;
function playPerfectScoreSound(){try{const AC=window.AudioContext||window.webkitAudioContext;if(!AC)return;const ctx=celebrationAudioContext||(celebrationAudioContext=new AC());if(ctx.state==="suspended")ctx.resume();const now=ctx.currentTime;[523.25,659.25,783.99,1046.5,783.99,1046.5].forEach((f,i)=>{const o=ctx.createOscillator(),g=ctx.createGain(),t=now+i*.13;o.type="sine";o.frequency.value=f;g.gain.setValueAtTime(.0001,t);g.gain.exponentialRampToValueAtTime(.14,t+.025);g.gain.exponentialRampToValueAtTime(.0001,t+.22);o.connect(g);g.connect(ctx.destination);o.start(t);o.stop(t+.24)});[1046.5,1318.5,1568].forEach(f=>{const o=ctx.createOscillator(),g=ctx.createGain();o.type="triangle";o.frequency.value=f;g.gain.setValueAtTime(.0001,now+.78);g.gain.exponentialRampToValueAtTime(.05,now+.82);g.gain.exponentialRampToValueAtTime(.0001,now+1.25);o.connect(g);g.connect(ctx.destination);o.start(now+.78);o.stop(now+1.28)})}catch(e){}}
function celebratePerfectScore(label="علامة كاملة!"){const old=document.getElementById("celebrationLayer");if(old)old.remove();const oldBanner=document.querySelector(".celebration-banner");if(oldBanner)oldBanner.remove();if(celebrationTimer)clearTimeout(celebrationTimer);const layer=document.createElement("div");layer.id="celebrationLayer";const banner=document.createElement("div");banner.className="celebration-banner";banner.textContent="🏆 "+label+" 🎉";document.body.append(banner,layer);const palette=["#facc15","#fb7185","#38bdf8","#a78bfa","#34d399","#f97316","#f9a8d4","#fff"];const reduced=window.matchMedia&&window.matchMedia("(prefers-reduced-motion: reduce)").matches;for(let i=0;i<(reduced?24:170);i++){const p=document.createElement("i");p.className="confetti-piece";p.style.left=Math.random()*100+"vw";p.style.background=palette[i%palette.length];p.style.width=6+Math.random()*8+"px";p.style.height=9+Math.random()*13+"px";p.style.borderRadius=Math.random()>.5?"50%":"2px";p.style.setProperty("--fall-time",2.5+Math.random()*2.4+"s");p.style.setProperty("--drift",(Math.random()-.5)*260+"px");p.style.setProperty("--spin-end",540+Math.random()*1200+"deg");p.style.animationDelay=Math.random()*.65+"s";layer.appendChild(p)}for(let i=0;i<22;i++){const sp=document.createElement("i");sp.className="celebration-spark";sp.style.left=5+Math.random()*90+"vw";sp.style.top=12+Math.random()*75+"vh";sp.style.animationDelay=Math.random()*.7+"s";layer.appendChild(sp)}playPerfectScoreSound();celebrationTimer=setTimeout(()=>{layer.remove();banner.remove()},5600)}

// تشغيل الموقع
// ===================================

buildLevels();
renderGrammarTopics();
renderWords();
updateStats();

</script>

</body>
</html>
