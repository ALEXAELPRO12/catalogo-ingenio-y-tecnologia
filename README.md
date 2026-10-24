<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Catálogo 2026 · Ingenio y Tecnología</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@600;700&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#f6f9f1;
  --ink:#14261a;
  --mut:#56685a;
  --line:#d6e1cd;
  --card:#fff;
  --band:#0f4a1d;
  --bandink:#f3fbe8;
  --lime:#7ac70c;
  --ins:#c2410c;
  --her:#1b6ca8;
  --fun:#7f398f;
  --nut:#4c8c0c;
  --fij:#a16207;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#0e1a12;
    --ink:#e8f2e2;
    --mut:#9db3a2;
    --line:#27412f;
    --card:#14251a;
    --band:#0a2f13;
    --ins:#f08a5d;
    --her:#6bb4e8;
    --fun:#c58bd4;
    --nut:#8fd13a;
    --fij:#e0b04a;
  }
}
:root[data-theme="dark"]{
  --bg:#0e1a12;
  --ink:#e8f2e2;
  --mut:#9db3a2;
  --line:#27412f;
  --card:#14251a;
  --band:#0a2f13;
  --ins:#f08a5d;
  --her:#6bb4e8;
  --fun:#c58bd4;
  --nut:#8fd13a;
  --fij:#e0b04a;
}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{
  margin:0;
  background:var(--bg);
  color:var(--ink);
  font:400 16px/1.5 "DM Sans",system-ui,sans-serif;
}
.band{
  background:var(--band);
  color:var(--bandink);
  padding:40px 20px 32px;
  border-bottom:6px solid var(--lime);
}
.wrap{max-width:920px;margin:0 auto}
.brand{
  font:600 18px/1 "Barlow Condensed",sans-serif;
  letter-spacing:.04em;
  margin:0 0 18px;
  opacity:.9;
}
h1{
  font:700 clamp(56px,13vw,112px)/.86 "Barlow Condensed",sans-serif;
  margin:0 0 16px;
  letter-spacing:-.01em;
}
.lead{
  max-width:46ch;
  margin:0;
  font-size:18px;
  opacity:.92;
}
.deal{
  display:inline-block;
  margin-top:20px;
  background:var(--lime);
  color:#10300a;
  font-weight:700;
  padding:8px 14px;
  border-radius:999px;
}
.tools{
  position:sticky;
  top:env(safe-area-inset-top,0px);
  background:var(--bg);
  border-bottom:1px solid var(--line);
  padding:12px 20px;
  z-index:5;
}
.tools .wrap{display:grid;gap:10px}
input[type=search]{
  width:100%;
  font:inherit;
  color:var(--ink);
  background:var(--card);
  border:1px solid var(--line);
  border-radius:10px;
  padding:11px 14px;
}
input[type=search]:focus-visible,button:focus-visible,a:focus-visible{
  outline:3px solid var(--lime);
  outline-offset:2px;
}
.chips{
  display:flex;
  gap:8px;
  flex-wrap:wrap;
}
.chips button{
  font:500 14px/1 "DM Sans",sans-serif;
  color:var(--ink);
  background:transparent;
  border:1px solid var(--line);
  border-radius:999px;
  padding:9px 14px;
  cursor:pointer;
}
.chips button[aria-pressed=true]{
  background:var(--ink);
  color:var(--bg);
  border-color:var(--ink);
}
.sizes button{
  font:700 15px/1 "Barlow Condensed",sans-serif;
  letter-spacing:.04em;
}
main{padding:8px 20px 56px}
.count{
  color:var(--mut);
  font-size:14px;
  margin:16px 0 4px;
}
.row{
  display:grid;
  grid-template-columns:8px 1fr auto;
  gap:0 16px;
  padding:16px 0;
  border-bottom:1px solid var(--line);
  align-items:start;
}
.bar{align-self:stretch;border-radius:4px;background:var(--c)}
.row h2{
  font:700 26px/1.05 "Barlow Condensed",sans-serif;
  margin:0 0 4px;
}
.cat{
  font-size:13px;
  font-weight:700;
  color:var(--c);
  margin:0 0 4px;
}
.row p{
  margin:0;
  color:var(--mut);
  max-width:60ch;
  font-size:15px;
}
.price{
  text-align:right;
  font:700 24px/1 "Barlow Condensed",sans-serif;
  white-space:nowrap;
}
.price small{
  display:block;
  font:400 12px/1.3 "DM Sans",sans-serif;
  color:var(--mut);
  margin-top:4px;
}
.ask{
  font:500 14px/1.3 "DM Sans",sans-serif;
  color:var(--mut);
  white-space:normal;
  max-width:9ch;
}
.empty{
  padding:40px 0;
  color:var(--mut);
}
.wa{
  display:inline-block;
  margin-top:10px;
  background:#25d366;
  color:#06240f;
  font:700 14px/1 "DM Sans",sans-serif;
  padding:10px 15px;
  border-radius:999px;
  text-decoration:none;
}
.wa:hover{background:#1fbd5b}
.wa.big{
  margin:0 0 16px;
  font-size:16px;
  padding:13px 20px;
}
footer{
  padding:28px 20px 40px;
  border-top:1px solid var(--line);
  color:var(--mut);
  font-size:14px;
}
footer a{color:var(--ink)}
@media (max-width:520px){
  .row{grid-template-columns:6px 1fr}
  .price{grid-column:2;text-align:left;margin-top:8px}
  .ask{max-width:none}
}
</style>
</head>
<body>
<header class="band">
  <div class="wrap">
    <p class="brand">Ingenio y Tecnología · Especialistas en cultivos</p>
    <h1>Catálogo 2026</h1>
    <p class="lead">Productos para controlar plagas, hongos y malezas, y para nutrir, enraizar y fortalecer tus cultivos.</p>
    <span class="deal">Al por mayor: 2% de descuento desde 12 unidades</span>
  </div>
</header>

<section class="tools" aria-label="Filtros">
  <div class="wrap">
    <input id="q" type="search" placeholder="Buscar producto o uso" aria-label="Buscar producto o uso">
    <div class="chips sizes" id="sizes" role="group" aria-label="Presentación"></div>
    <div class="chips" id="cats" role="group" aria-label="Tipo de producto"></div>
  </div>
</section>

<main>
  <div class="wrap">
    <p class="count" id="count" aria-live="polite"></p>
    <div id="list"></div>
  </div>
</main>

<footer>
  <div class="wrap">
    <a class="wa big" href="https://wa.me/573134524070?text=Hola%2C%20quiero%20informaci%C3%B3n%20de%20sus%20productos" target="_blank" rel="noopener">
      Escribir por WhatsApp
    </a><br>
    Precios por unidad. Los productos sin precio se cotizan por mensaje. Más información en
    <a href="https://www.ingenioytecnologia.com">www.ingenioytecnologia.com</a>.
  </div>
</footer>

<script>
var CATS={all:"Todos",ins:"Insecticidas",her:"Herbicidas",fun:"Fungicidas",nut:"Nutrición y enraizantes",fij:"Fijadores"};
var SIZES={all:"Todos","1 litro":"1 litro","1 kilo":"1 kilo","4 litros":"4 litros"};
var P=[
  ["BicBac","1 litro","ins",90000,"Control de insectos: actúa sobre larvas, huevos y adultos."],
  ["Singer","1 litro","ins",90000,"Control de hormigas y plagas molestas del cultivo."],
  ["Simpuk 75","1 litro","ins",90000,"Insecticida sistémico para el control de plagas."],
  ["Agrofol","1 litro","her",25000,"Herbicida de amplio espectro con glufosinato de amonio, contra gramíneas y arvenses."],
  ["Petenzol","1 litro","fij",30000,"Coadyuvante regulador y penetrante: mejora la mezcla y evita que el agroquímico se pierda por lluvia o escurrimiento."],
  ["Pegaplan","1 litro","fij",30000,"Fijador, humectante, adhesivo y dispersante."],
  ["Fungicida de amplio espectro","1 litro","fun",90000,"Control y manejo de hongos en tus cultivos."],
  ["Azufre 720","1 litro","nut",30000,"Fertilizante: el azufre ayuda a que los cultivos se mantengan verdes frente a heladas y frío."],
  ["Raizer","1 litro","nut",45000,"Estimula y genera raíces."],
  ["Nutrifollaje","1 litro","nut",45000,"Para plantas con mejores hojas."],
  ["Fosfitos de potasio","1 litro","nut",60000,"La vacuna perfecta para tus cultivos."],
  ["Botrizal","1 litro","fun",null,"Control de hongos, virus y bacterias, de amplio espectro."],
  ["Nutriboxer","1 litro","fij",null,"Pegante y humectante que nutre y rompe la tensión superficial."],
  ["Transformer","1 litro","nut",null,"Aminoácidos puros de origen animal y vegetal para mejorar la calidad de la fruta."],
  ["Trimix Cobre","1 litro","fun",60000,"Óxido, sulfato y pentahidrato de cobre: control de hongos y esporas."],
  ["CRE6 Arranque","1 litro","nut",45000,"Orgánico. Nutre, estimula y enraíza; ayuda al cultivo a salir del estrés."],
  ["Difanocin Top","1 litro","fun",90000,"Mezcla química para controlar sigatoka, hongos y esporas."],
  ["Fungibac","1 litro","fun",90000,"Fungicida, virucida y bactericida de amplio espectro."],
  ["Ermix Cobre","1 litro","fun",90000,"Óxido, sulfato y pentahidrato de cobre: control de hongos y esporas."],
  ["Agroquel Potasio","1 litro","nut",45000,"Engorde y llenado de frutos con óxido de potasio."],
  ["Pegaplan","1 kilo","fij",null,"Presentación de 1 kilo."],
  ["Mancozeb","1 kilo","fun",null,"Presentación de 1 kilo."],
  ["Fulviplex","1 kilo","nut",null,"Presentación de 1 kilo."],
  ["Jabón potásico con canela","4 litros","fun",null,"El cinamaldehído de la canela inhibe el crecimiento micelial y la germinación de los cuerpos fructíferos, y erradica el hongo."],
  ["Jabón potásico con Neem","4 litros","ins",null,"El extracto de Neem combate pulgones, moscas blancas, trips, cochinillas, ácaros, orugas y otras plagas."],
  ["Más llenado","4 litros","nut",null,"Presentación de 4 litros."],
  ["Germinar","4 litros","nut",null,"Estimulante para semillas."],
  ["Cuaje y amarre","4 litros","nut",null,"Calidad y sanidad sin nitrógeno."]
];
var TEL="573134524070";
function wa(t){return "https://wa.me/"+TEL+"?text="+encodeURIComponent(t);}
var st={q:"",size:"all",cat:"all"};

function norm(s){
  return s.toLowerCase().normalize("NFD").replace(/[\u0300-\u036f]/g,"");
}

function chips(id,obj,key){
  var box=document.getElementById(id);
  Object.keys(obj).forEach(function(k){
    var b=document.createElement("button");
    b.type="button";
    b.textContent=obj[k];
    b.dataset.k=k;
    b.onclick=function(){ st[key]=k; render(); };
    box.appendChild(b);
  });
}

function money(n){ return "$"+n.toLocaleString("es-CO"); }

function render(){
  document.querySelectorAll("#sizes button").forEach(function(b){
    b.setAttribute("aria-pressed", String(b.dataset.k === st.size));
  });

  document.querySelectorAll("#cats button").forEach(function(b){
    b.setAttribute("aria-pressed", String(b.dataset.k === st.cat));
  });

  var q=norm(st.q);
  var items=P.filter(function(p){
    return (st.size === "all" || p[1] === st.size) &&
      (st.cat === "all" || p[2] === st.cat) &&
      (!q || norm(p[0]+" "+p[4]+" "+CATS[p[2]]).indexOf(q)>-1);
  });

  var countNode=document.getElementById("count");
  countNode.textContent = items.length + (items.length === 1 ? " producto" : " productos") +
    (st.size === "all" ? " en total" : " en " + SIZES[st.size]);

  var list=document.getElementById("list");
  list.innerHTML="";
  if(!items.length){
    list.innerHTML='<p class="empty">No hay productos con esos filtros. Prueba otra palabra o quita el tipo de producto.</p>';
    return;
  }

  items.forEach(function(p){
    var r=document.createElement("article");
    r.className="row";
    r.style.setProperty("--c","var(--"+p[2]+")");

    var pr = p[3]
      ? '<div class="price">'+money(p[3])+'<small>por unidad</small></div>'
      : '<div class="price ask">Consultar precio</div>';

    r.innerHTML='<div class="bar"></div><div><p class="cat"></p><h2></h2><p class="d"></p></div>'+pr;

    r.querySelector(".cat").textContent=CATS[p[2]];
    r.querySelector("h2").textContent=p[0];
    r.querySelector(".d").textContent=p[4];

    var a=document.createElement("a");
    a.className="wa";
    a.target="_blank";
    a.rel="noopener";
    a.textContent="Pedir por WhatsApp";
    a.href=wa("Hola, quiero información de "+p[0]+" ("+p[1]+")");

    r.querySelector(".d").after(a);
    list.appendChild(r);
  });
}

chips("sizes",SIZES,"size");
chips("cats",CATS,"cat");

document.getElementById("q").addEventListener("input", function(e){
  st.q = e.target.value;
  render();
});

render();
</script>
</body>
</html>
