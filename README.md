# cyberedu
Киберқауіпсіздік негіздері
<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>AI Academy — Жасанды интеллект негіздері</title>
<style>
*{box-sizing:border-box;scroll-behavior:smooth}body{margin:0;background:#091225;color:#f4f7ff;font:16px/1.65 Arial,sans-serif}
header{position:sticky;top:0;z-index:5;background:#0b1730f2;border-bottom:1px solid #304263;padding:12px}
nav{max-width:1100px;margin:auto;display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
a.btn,button{display:inline-block;text-decoration:none;border:0;border-radius:10px;padding:10px 15px;background:linear-gradient(100deg,#62e4df,#a58cff);color:#071426;font-weight:bold;cursor:pointer}
a.btn:hover,button:hover{filter:brightness(1.12)}
.wrap{max-width:1050px;margin:auto;padding:25px 18px 60px}
section{scroll-margin-top:95px;margin:26px 0 45px;padding:26px;background:linear-gradient(145deg,#142342,#101a31);border:1px solid #304263;border-radius:20px}
.hero{padding:55px 30px;background:radial-gradient(circle at 85% 20%,#334c86,transparent 38%),linear-gradient(130deg,#172c50,#111a35)}
.tag{color:#64e6df;font-size:12px;font-weight:bold;letter-spacing:2px}
h1{font-size:clamp(30px,6vw,52px);line-height:1.12;margin:12px 0}
h2{font-size:30px;margin:5px 0 18px}h3{color:#73e5e0;margin-bottom:5px}
p,li{color:#c4cee1}.muted{color:#aab8d2}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
.card{padding:17px;border:1px solid #304263;background:#1a2a49;border-radius:14px}
.call{padding:13px 16px;border-left:4px solid #62e4df;background:#102e3e;border-radius:8px;margin:15px 0;color:#e2faff}
.q{padding:15px;margin:13px 0;border:1px solid #34486c;background:#0d1930;border-radius:13px}
.q label{display:block;background:#1b2b49;padding:8px 10px;border-radius:8px;margin:6px 0;color:#dce5f6}
textarea,input[type=text]{width:100%;padding:12px;border:1px solid #415578;border-radius:9px;background:#09152a;color:white;font:inherit}
textarea{min-height:90px} .answer{margin-top:8px;color:#6fe4dc;font-size:14px}
footer{text-align:center;padding:25px;color:#9cabc5;border-top:1px solid #304263}
@media(max-width:600px){nav{justify-content:flex-start}a.btn{font-size:13px;padding:8px 10px}section{padding:18px}.hero{padding:32px 20px}}

.task summary{cursor:pointer;list-style:none;font-weight:bold;color:#f4f7ff;display:flex;justify-content:space-between;gap:10px;align-items:center}
.task summary::-webkit-details-marker{display:none}.task summary span{color:#67e5df;font-size:14px;white-space:nowrap}
.task[open] summary span{font-size:0}.task[open] summary span:after{content:'Жабу −';font-size:14px}
.task-body{padding-top:12px}.assistant-buttons button{min-height:54px}.q input[type=text]{margin:8px 0 12px}.score{font-size:38px;font-weight:800;color:#68e6df;line-height:1.3}.result-card{background:linear-gradient(135deg,#183b50,#1a2a49)}

</style>
</head>
<body>
<header><nav>
<a class="btn" href="#home">Басты бет</a><a class="btn" href="#about">Жоба туралы</a><a class="btn" href="#theory">Теория</a><a class="btn" href="#practice">Практика</a><a class="btn" href="#quiz">Тест</a><a class="btn" href="#assistant">ЖИ көмекші</a><a class="btn" href="#analysis">Нәтиже</a>
</nav></header>
<main class="wrap">
<section id="home" class="hero">
<div class="tag">ИНТЕРАКТИВТІ ЭЛЕКТРОНДЫ ОҚУ ҚҰРАЛЫ</div>
<h1>AI ACADEMY<br><span style="color:#65e4df">Жасанды интеллект негіздері</span></h1>
<p>Жасанды интеллект әлемін зертте! Теорияны оқы, практикалық тапсырмаларды орында, тест сұрақтарына жауап бер және біліміңді бағала.</p>
<div class="grid">
<div class="card"><h3>📘 Теория</h3><p>5 негізгі тақырып</p><a class="btn" href="#theory">Теорияны ашу →</a></div>
<div class="card"><h3>🧩 Практика</h3><p>3 практикалық тапсырма</p><a class="btn" href="#practice">Тапсырмалар →</a></div>
<div class="card"><h3>📝 Тест</h3><p>10 сұрақ және бағалау</p><a class="btn" href="#quiz">Тестті бастау →</a></div>
<div class="card"><h3>🤖 ЖИ көмекші</h3><p>Тақырып бойынша сұрақ-жауап</p><a class="btn" href="#assistant">Көмекшіні ашу →</a></div>
<div class="card"><h3>📊 Нәтиже</h3><p>Бағалау шкаласы мен ұсыныстар</p><a class="btn" href="#analysis">Нәтижені көру →</a></div>
<div class="card"><h3>🎯 Мақсаты</h3><p>Жоба туралы ақпарат</p><a class="btn" href="#about">Толығырақ →</a></div>
</div>
</section>

<section id="about"><div class="tag">01 / БАСТЫ АҚПАРАТ</div><h2>Оқу құралы туралы</h2>
<div class="grid"><div class="card"><h3>🎯 Мақсаты</h3><p>Білім алушыларға жасанды интеллект туралы негізгі түсінік беру, оның жұмыс істеу принциптері мен қолданылу салаларын түсіндіру.</p></div>
<div class="card"><h3>📌 Міндеттері</h3><p>Теориялық білім қалыптастыру, практикалық дағдыларды дамыту, ЖИ нәтижелерін сыни бағалауға үйрету.</p></div>
<div class="card"><h3>👩‍🎓 Автор</h3><p>Орындаған: Ақерке<br>Тобы: ИОК 242<br>Пәні: Информатика</p></div></div>
<div class="call">Қолдану тәртібі: теорияны оқы → практиканы орында → тест тапсыр → нәтижені бағала.</div>
</section>

<section id="theory"><div class="tag">02 / ТЕОРИЯЛЫҚ МАТЕРИАЛ</div><h2>Жасанды интеллект туралы 5 тақырып</h2>
<div class="card"><h3>1. Жасанды интеллект дегеніміз не?</h3><p>Жасанды интеллект (ЖИ) — компьютерлік жүйелердің үйрену, ақпаратты талдау, тіл түсіну, үлгілерді тану және белгілі бір міндеттерді орындау сияқты адам интеллектісімен байланысты әрекеттерді жүзеге асыруына мүмкіндік беретін технологиялар жиынтығы.</p><p>Мысалы, дауыстық көмекші айтылған сөзді танып, сұраққа жауап береді. Суретті тану жүйесі фотодағы нысандарды анықтай алады.</p></div>
<div class="card"><h3>2. Жасанды интеллект түрлері</h3><ul><li><b>Тар бағыттағы ЖИ:</b> нақты бір міндетті орындайды. Мысалы, аудармашы немесе спам сүзгісі.</li><li><b>Жалпы ЖИ:</b> адам сияқты әртүрлі міндеттерді орындай алатын теориялық жүйе. Толыққанды жалпы ЖИ әзірге жасалды деп есептелмейді.</li><li><b>Генеративті ЖИ:</b> нұсқау бойынша мәтін, сурет, дыбыс немесе код жасайды.</li></ul></div>
<div class="card"><h3>3. Машиналық оқыту</h3><p>Машиналық оқыту — компьютердің деректерден заңдылықтарды үйрену әдісі.</p><ul><li><b>Мұғаліммен оқыту:</b> дұрыс жауабы көрсетілген мысалдар қолданылады.</li><li><b>Мұғалімсіз оқыту:</b> жүйе деректердің ішінен ұқсастықтар мен топтарды табады.</li><li><b>Марапаттау арқылы оқыту:</b> жүйе әрекет нәтижесіне қарай кері байланыс алып үйренеді.</li></ul></div>
<div class="card"><h3>4. Жасанды нейрондық желілер</h3><p>Нейрондық желі — адам миындағы нейрондардың байланысу идеясынан шабыт алған есептеу моделі.</p><ul><li><b>Кіріс қабаты</b> бастапқы деректерді қабылдайды.</li><li><b>Жасырын қабаттар</b> деректерді өңдейді.</li><li><b>Шығыс қабаты</b> болжам немесе нәтиже береді.</li></ul></div>
<div class="card"><h3>5. ЖИ қолданылуы және этикасы</h3><p>ЖИ білім беруде, медицинада, көлікте, өндірісте, ауыл шаруашылығында және күнделікті өмірде қолданылады. Ол жұмысты жылдамдатуға көмектеседі, бірақ қате ақпарат беруі мүмкін.</p><p>Сондықтан жауапты тексеру, жеке деректерді қорғау және авторлық құқықты сақтау қажет.</p></div>
</section>

<section id="practice"><div class="tag">03 / ПРАКТИКАЛЫҚ ТАПСЫРМАЛАР</div><h2>Біліміңді тәжірибеде қолдан</h2><p class="muted">Әр тапсырманың «Тапсырманы ашу» батырмасын бас. Нұсқаулық пен жауап жазатын орын ашылады.</p>
<details class="q task"><summary>🧩 Тапсырма 1. ЖИ құралдарын зерттеу <span>Ашу +</span></summary><div class="task-body"><p>ChatGPT, Gemini немесе басқа ЖИ құралын таңда. Оның қандай міндеттерді орындай алатынын 2–3 сөйлеммен жаз.</p><ul><li>Құралдың атауын көрсет.</li><li>Кемінде екі мүмкіндігін жаз.</li><li>Қандай жағдайда қолдануға болатынын түсіндір.</li></ul><textarea placeholder="Жауабыңды осында жаз..."></textarea></div></details>
<details class="q task"><summary>✍️ Тапсырма 2. Дұрыс промпт құрастыру <span>Ашу +</span></summary><div class="task-body"><p>«Жасанды интеллект» тақырыбын 7-сынып оқушысына түсіндіру үшін нақты нұсқау құрастыр.</p><ul><li>ЖИ-ге рөл бер.</li><li>Тапсырманы нақты жаз.</li><li>Жауаптың көлемі мен стилін көрсет.</li></ul><textarea placeholder="Мысалы: Сен информатика мұғалімісің..."></textarea></div></details>
<details class="q task"><summary>🔎 Тапсырма 3. Пайдасы мен шектеулері <span>Ашу +</span></summary><div class="task-body"><p>Жасанды интеллектінің екі пайдасын және бір шектеуін жаз.</p><p class="muted">Жауабыңды нақты мысалдармен негізде.</p><textarea placeholder="Жауабыңды осында жаз..."></textarea></div></details>
</section>

<section id="quiz"><div class="tag">04 / ИНТЕЛЛЕКТУАЛДЫ ТЕСТ</div><h2>10 тест сұрағы</h2><p>Әр сұрақта бір дұрыс жауап бар. Жауаптарыңды белгілеп, соңында «Тексеру» батырмасын бас.</p>
<form id="quizForm">
<div class="q"><b>1. Жасанды интеллект дегеніміз не?</b><label><input type="radio" name="q1" value="0"> Компьютер мониторы</label><label><input type="radio" name="q1" value="1"> Интеллектуалды міндеттерді орындайтын технологиялар жиынтығы</label><label><input type="radio" name="q1" value="0"> Тек интернет желісі</label></div>
<div class="q"><b>2. Тар бағыттағы ЖИ қандай міндет атқарады?</b><label><input type="radio" name="q2" value="0"> Кез келген адам жұмысын</label><label><input type="radio" name="q2" value="1"> Нақты бір немесе шектеулі міндеттерді</label><label><input type="radio" name="q2" value="0"> Электр өндіреді</label></div>
<div class="q"><b>3. Генеративті ЖИ не істей алады?</b><label><input type="radio" name="q3" value="0"> Компьютерді жөндейді</label><label><input type="radio" name="q3" value="1"> Жаңа мәтін, сурет немесе код жасайды</label><label><input type="radio" name="q3" value="0"> Интернетті өшіреді</label></div>
<div class="q"><b>4. Машиналық оқыту дегеніміз не?</b><label><input type="radio" name="q4" value="1"> Деректерден заңдылықтарды үйрену</label><label><input type="radio" name="q4" value="0"> Жылдам теру</label><label><input type="radio" name="q4" value="0"> Экран жарығын реттеу</label></div>
<div class="q"><b>5. Мұғаліммен оқытуда қандай деректер қолданылады?</b><label><input type="radio" name="q5" value="0"> Жауабы белгісіз деректер ғана</label><label><input type="radio" name="q5" value="1"> Дұрыс жауабы бар мысалдар</label><label><input type="radio" name="q5" value="0"> Дерек қолданылмайды</label></div>
<div class="q"><b>6. Нейрондық желі неден шабыт алған?</b><label><input type="radio" name="q6" value="0"> Күн жүйесінен</label><label><input type="radio" name="q6" value="1"> Адам миындағы нейрондар байланысынан</label><label><input type="radio" name="q6" value="0"> Ғимараттан</label></div>
<div class="q"><b>7. Нейрондық желінің кіріс қабаты не істейді?</b><label><input type="radio" name="q7" value="1"> Бастапқы деректерді қабылдайды</label><label><input type="radio" name="q7" value="0"> Компьютерді өшіреді</label><label><input type="radio" name="q7" value="0"> Нәтижені басып шығарады</label></div>
<div class="q"><b>8. ЖИ жауабын не үшін тексеру қажет?</b><label><input type="radio" name="q8" value="0"> ЖИ жауап бермейді</label><label><input type="radio" name="q8" value="1"> Жауап қате немесе толық емес болуы мүмкін</label><label><input type="radio" name="q8" value="0"> Тексеру мүмкін емес</label></div>
<div class="q"><b>9. ЖИ қолданғанда не маңызды?</b><label><input type="radio" name="q9" value="0"> Құпиясөзді жариялау</label><label><input type="radio" name="q9" value="1"> Жеке деректерді қорғау</label><label><input type="radio" name="q9" value="0"> Авторлық құқықты елемеу</label></div>
<div class="q"><b>10. Промпт дегеніміз не?</b><label><input type="radio" name="q10" value="1"> ЖИ-ге берілетін нұсқау немесе сұрау</label><label><input type="radio" name="q10" value="0"> Компьютер бөлшегі</label><label><input type="radio" name="q10" value="0"> Файл форматы</label></div>
<button type="button" onclick="checkQuiz()">Тестті тексеру</button> <button type="reset" onclick="resetResults()">Қайта бастау</button>
</form><div id="quizResult" class="call" aria-live="polite">Нәтиже осы жерде шығады.</div>
</section>

<section id="assistant"><div class="tag">05 / ЖИ КӨМЕКШІСІ</div><h2>AI көмекші — сұрағыңа жауап бер</h2>
<p>Төмендегі тақырып батырмаларын таңда немесе өз сұрағыңды жаз. Көмекші жасанды интеллект негіздері бойынша түсіндірме береді.</p>
<div class="grid assistant-buttons">
<button type="button" onclick="askAI('Жасанды интеллект дегеніміз не?')">ЖИ дегеніміз не?</button>
<button type="button" onclick="askAI('Машиналық оқыту қалай жұмыс істейді?')">Машиналық оқыту</button>
<button type="button" onclick="askAI('Нейрондық желі дегеніміз не?')">Нейрондық желі</button>
<button type="button" onclick="askAI('Промптты қалай дұрыс жазуға болады?')">Промпт құрастыру</button>
<button type="button" onclick="askAI('ЖИ-дің пайдасы мен қауіптері қандай?')">Пайдасы мен қауіптері</button>
<button type="button" onclick="askAI('ЖИ-ді білім беруде қалай қолданады?')">Білім берудегі ЖИ</button>
</div>
<div class="q"><label for="aiQuestion"><b>Сұрағыңды енгіз:</b></label><input id="aiQuestion" type="text" placeholder="Мысалы: Генеративті ЖИ деген не?"><button type="button" onclick="askAI(document.getElementById('aiQuestion').value)">Жауап алу →</button></div>
<div id="aiAnswer" class="call" aria-live="polite"><b>🤖 AI көмекші:</b><br>Сұрағыңды таңда немесе енгіз. Мен тақырыпты қарапайым тілмен түсіндіремін.</div>
<div class="call">Ескерту: бұл оқу құралына енгізілген тақырыптық виртуалды көмекші. Ол алдын ала дайындалған білім базасы бойынша жауап береді; нақты онлайн ЖИ моделіне қосылмаған.</div>
</section>
<section id="analysis"><div class="tag">06 / БІЛІМДІ БАҒАЛАУ ЖӘНЕ ТАЛДАУ</div><h2>Менің оқу нәтижем</h2>
<p>Тестті аяқтап, «Тестті тексеру» батырмасын басқаннан кейін ұпайың мен ұсыныстарың осы бөлімде де көрсетіледі.</p>
<div class="grid">
<div class="card result-card"><div class="tag">ЖИНАЛҒАН ҰПАЙ</div><div id="finalScore" class="score">— / 10</div><p id="finalPercent">Тест әлі тапсырылған жоқ.</p></div>
<div class="card"><h3>📈 Деңгейің</h3><p id="finalLevel">Нәтиже шыққан соң деңгейің көрсетіледі.</p></div>
<div class="card"><h3>🎯 Ұсыныс</h3><p id="finalAdvice">Алдымен 10 сұрақтан тұратын тестті орында.</p></div>
</div>
<h3>Бағалау шкаласы</h3><div class="grid">
<div class="card"><h3>90–100% · Өте жақсы</h3><p>Тақырыпты өте жақсы меңгергенсің. Біліміңді күрделі тапсырмаларда қолдан.</p></div>
<div class="card"><h3>75–89% · Жақсы</h3><p>Негізгі ұғымдарды түсінесің. Қате кеткен сұрақтарды қайтала.</p></div>
<div class="card"><h3>50–74% · Орташа</h3><p>Теорияның кейбір бөлімдерін қайта қарап, тестті тағы орында.</p></div>
<div class="card"><h3>0–49% · Қайталау қажет</h3><p>Теорияны басынан оқып, практикалық мысалдарды орында.</p></div>
</div>
<div class="call">Бағалау тесттегі 10 сұрақтың дұрыс жауап санына негізделеді. Әр дұрыс жауап — 1 ұпай, ең жоғары нәтиже — 10 ұпай.</div>
<a class="btn" href="#quiz">Тестке өту →</a> <a class="btn" href="#home">Басты бетке қайту ↑</a>
</section>
</main>
<footer>AI ACADEMY · Жасанды интеллект негіздері · 2026</footer>
<script>
function checkQuiz(){
 const key={q1:'1',q2:'1',q3:'1',q4:'1',q5:'1',q6:'1',q7:'1',q8:'1',q9:'1',q10:'1'};
 let score=0,missing=0;
 for(const [name,correct] of Object.entries(key)){
  const chosen=document.querySelector('input[name="'+name+'"]:checked');
  if(!chosen) missing++;
  else if(chosen.value===correct) score++;
 }
 const pct=score*10;
 let level=pct>=90?'Өте жақсы':pct>=75?'Жақсы':pct>=50?'Орташа':'Қосымша дайындық қажет';
 const advice=pct>=90?'Өте жақсы! Біліміңді практикада қолдануды жалғастыр.':pct>=75?'Жақсы нәтиже! Қате кеткен сұрақтарды қайталап, біліміңді бекіт.':pct>=50?'Теорияның 2–5 тақырыптарын қайталап, тестті қайта орында.':'Теорияны басынан оқып, әр ұғымға мысал келтіріп көр.';
 const result='<b>Нәтиже: '+score+'/10 — '+pct+'%</b><br>Деңгей: '+level+'.<br>Жауап берілмеген сұрақ: '+missing+'.<br>'+advice;
 document.getElementById('quizResult').innerHTML=result;
 document.getElementById('finalScore').textContent=score+' / 10';
 document.getElementById('finalPercent').textContent='Жалпы нәтиже: '+pct+'%';
 document.getElementById('finalLevel').textContent=level;
 document.getElementById('finalAdvice').textContent=advice;

}

function askAI(question){
 const q=(question||'').trim().toLowerCase();
 const answers=[
  {keys:['жасанды интеллект','жи деген','ai деген'],title:'Жасанды интеллект',body:'Жасанды интеллект (ЖИ) — компьютерге деректерді талдау, үйрену, мәтінді түсіну, суретті тану және шешім ұсыну сияқты міндеттерді орындауға көмектесетін технологиялар. Мысалы: дауыстық көмекші, аударма жүйесі және мәтін құрастыратын құралдар.'},
  {keys:['машиналық оқыту','оқыту'],title:'Машиналық оқыту',body:'Машиналық оқыту — компьютердің көптеген мысалдар мен деректерді талдау арқылы заңдылықтарды үйренуі. Мысалы, спамды анықтау жүйесі бұрынғы хаттардың үлгілеріне сүйеніп, жаңа хаттың спам екенін болжайды.'},
  {keys:['нейрон','желі'],title:'Нейрондық желі',body:'Нейрондық желі — өзара байланысқан есептеу элементтерінен тұратын модель. Ол кіріс деректерін қабылдайды, бірнеше қабатта өңдейді және соңында нәтиже немесе болжам береді.'},
  {keys:['промпт','нұсқау','сұрау'],title:'Промпт құрастыру',body:'Промпт — ЖИ-ге берілетін тапсырма немесе нұсқау. Жақсы промптта рөл, нақты тапсырма, аудитория және жауап форматы көрсетіледі. Мысал: «Сен информатика мұғалімісің. Жасанды интеллектіні 7-сынып оқушысына 5 қарапайым сөйлеммен түсіндір». '},
  {keys:['пайда','қауіп','шектеу','зиян'],title:'ЖИ-дің пайдасы мен қауіптері',body:'ЖИ ақпаратты жылдам өңдеуге, қайталанатын жұмысты жеңілдетуге және идея ұсынуға көмектеседі. Бірақ қате немесе біржақты жауап беруі мүмкін. Сондықтан ақпаратты тексеріп, жеке деректерді жарияламау және авторлық құқықты сақтау керек.'},
  {keys:['білім','мектеп','оқытуда','сабақ'],title:'Білім берудегі ЖИ',body:'Білім беруде ЖИ күрделі тақырыпты түсіндіруге, жаттығу құрастыруға, мәтінді талдауға және оқушының біліміндегі олқылықты байқауға көмектеседі. Дегенмен мұғалімнің түсіндіруі мен оқушының өз бетінше ойлауы маңызды болып қала береді.'},
  {keys:['генератив'],title:'Генеративті ЖИ',body:'Генеративті ЖИ — берілген нұсқау негізінде жаңа мәтін, сурет, дыбыс немесе бағдарламалық код жасайтын жасанды интеллект түрі.'}
 ];
 let found=answers.find(a=>a.keys.some(k=>q.includes(k)));
 const box=document.getElementById('aiAnswer');
 if(!q){box.innerHTML='<b>Сұрақ енгізілмеді.</b><br>Жоғарыдағы батырмалардың бірін таңда немесе сұрақ жаз.';return;}
 if(found){box.innerHTML='<b>🤖 '+found.title+'</b><br>'+found.body+'<br><span class="muted">Тағы сұрағың болса, басқа тақырыпты таңда.</span>';}
 else{box.innerHTML='<b>Бұл сұрақ бойынша нақты жауап табылмады.</b><br>«ЖИ дегеніміз не?», «Машиналық оқыту», «Нейрондық желі», «Промпт», «ЖИ пайдасы» немесе «Білім берудегі ЖИ» тақырыптарының бірін сұрап көр.';}
}
function resetResults(){
 document.getElementById('quizResult').innerHTML='Нәтиже осы жерде шығады.';
 document.getElementById('finalScore').textContent='— / 10';
 document.getElementById('finalPercent').textContent='Тест әлі тапсырылған жоқ.';
 document.getElementById('finalLevel').textContent='Нәтиже шыққан соң деңгейің көрсетіледі.';
 document.getElementById('finalAdvice').textContent='Алдымен 10 сұрақтан тұратын тестті орында.';
}

</script>
</body></html>
