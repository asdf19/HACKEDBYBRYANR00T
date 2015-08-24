META NAME="ROBOTS" CONTENT="INDEX, NOFOLLOW">
<META NAME="ROBOTS" CONTENT="INDEX, NOFOLLOW">
<!DOCTYPE html>
<html lang="pt-br">
<head>
<link rel="SHORTCUT ICON" href="http://www.crossed-flag-pins.com/animated-flag-gif/gifs/Bangladesh_120-animated-flag-gifs.gif"/>
<meta charset="utf-8">
<link href="https://fonts.googleapis.com/css?family=Geo|Quantico|Poiret+One|Aldrich" rel="stylesheet" type="text/css">
<style type="text/css">
body{margin:0px;padding:0px;margin-top:5px;margin-left:5px;background-color:#000;
font-size: 20px;color: #EFEFEF;font-family: 'Poiret One';
cursor: url('http://hellox.persiangig.com/DefacePage/negro.cur'), progress;}
#ico{width: 750px; height: 300px;}
#logo{font-family:'Aldrich';font-size:20px;color:#EFEFEF;}
.h1{font-family:'Aldrich';font-size:25px;color:#333;text-transform:uppercase;}
.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0; }
h2{font-family:'Aldrich';font-size:35px;color:#333;text-transform:uppercase; font-weight:40px;letter-spacing: 10px}
.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0; }
h3{font-family:'Aldrich';font-size:20px;color:#fff;text-transform:uppercase;}
.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0; }
h4{font-family:'Aldrich';font-size:25px;color:#333;text-transform:uppercase;}
.neon {color: #FFFFFF;text-shadow: 0 0 5px #1ab4e7, 0 0 10px #1ab4e7, 0 0 30px #18a2d0, 0 0 45px #18a2d0, 0 0 60px #18a2d0; }
#greetz_warn {font-family:'Aldrich';font-size:25px;color:#333;text-transform:uppercase;}
#attacker_nick{font-family: 'Quantico';font-size: 15px; color: #00FF00;}
#atacante{text-align: left;}
a{color:grey;text-decoration: none;}
<!-- matrix style -->
.matrix {color: #FFFFFF; font-family:Aldrich, Courier, Monotype; font-size:14pt; text-align:center; width:10px; padding:0px; margin:0px;}
.jokitz1{
text-align : center;
}
.jokitz2{
text-align : center;
font-family : Courier;
}
</style>
<script type="text/javascript">
<!--
//Disable right click script
//visit http://www.rainbow.arch.scriptmania.com/scripts/
var message="Hacked By Bryan";
///////////////////////////////////
function clickIE() {if (document.all) {(message);return false;}}
function clickNS(e) {if
(document.layers||(document.getElementById&&!document.all)) {
if (e.which==2||e.which==3) {(message);return false;}}}
if (document.layers)
{document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS;}
else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;}
document.oncontextmenu=new Function("return false")
// -->
</script>
<!-- <script language="JavaScript1.2" type="text/javascript">
function ClearError() {return true;}
window.onerror = ClearError;
</script> -->
<script type="text/javascript" language="javascript">
<!--
var rows=1; // must be an odd number
var speed=10; // lower is faster
var reveal=2; // between 0 and 2 only. The higher, the faster the word appears
var effectalign="center" //enter "center" to center it.
var w3c=document.getElementById && !window.opera;;
var ie45=document.all && !window.opera;
var ma_tab, matemp, ma_bod, ma_row, x, y, columns, ma_txt, ma_cho;
var m_coch=new Array();
var m_copo=new Array();
window.onload=function() {
if (!w3c && !ie45) return
var matrix=(w3c)?document.getElementById("matrix"):document.all["matrix"];
ma_txt=(w3c)?matrix.firstChild.nodeValue:matrix.innerHTML;
ma_txt=" "+ma_txt+" ";
columns=ma_txt.length;
if (w3c) {
while (matrix.childNodes.length) matrix.removeChild(matrix.childNodes[0]);
ma_tab=document.createElement("table");
ma_tab.setAttribute("border", 0);
ma_tab.setAttribute("align", effectalign);
ma_tab.style.backgroundColor="#000000";
ma_bod=document.createElement("tbody");
for (x=0; x<rows; x++) {
ma_row=document.createElement("tr");
for (y=0; y<columns; y++) {
matemp=document.createElement("td");
matemp.setAttribute("id", "Mx"+x+"y"+y);
matemp.className="matrix";
matemp.appendChild(document.createTextNode(String.fromCharCode(160)));
ma_row.appendChild(matemp);
}
ma_bod.appendChild(ma_row);
}
ma_tab.appendChild(ma_bod);
matrix.appendChild(ma_tab);
} else {
ma_tab='<ta'+'ble align="'+effectalign+'" border="0" style="background-color:#000000">';
for (var x=0; x<rows; x++) {
ma_tab+='<t'+'r>';
for (var y=0; y<columns; y++) {
ma_tab+='<t'+'d class="matrix" id="Mx'+x+'y'+y+'"> </'+'td>';
}
ma_tab+='</'+'tr>';
}
ma_tab+='</'+'table>';
matrix.innerHTML=ma_tab;
}
ma_cho=ma_txt;
for (x=0; x<columns; x++) {
ma_cho+=String.fromCharCode(32+Math.floor(Math.random()*94));
m_copo[x]=0;
}
ma_bod=setInterval("mytricks()", speed);
}
function mytricks() {
x=0;
for (y=0; y<columns; y++) {
x=x+(m_copo[y]==100);
ma_row=m_copo[y]%100;
if (ma_row && m_copo[y]<100) {
if (ma_row<rows+1) {
if (w3c) {
matemp=document.getElementById("Mx"+(ma_row-1)+"y"+y);
matemp.firstChild.nodeValue=m_coch[y];
}
else {
matemp=document.all["Mx"+(ma_row-1)+"y"+y];
matemp.innerHTML=m_coch[y];
}
matemp.style.color="#81F2FF";
matemp.style.fontWeight="bold";
}
if (ma_row>1 && ma_row<rows+2) {
matemp=(w3c)?document.getElementById("Mx"+(ma_row-2)+"y"+y):document.all["Mx"+(ma_row-2)+"y"+y];
matemp.style.fontWeight="normal";
matemp.style.color="#00BBFF";
}
if (ma_row>2) {
matemp=(w3c)?document.getElementById("Mx"+(ma_row-3)+"y"+y):document.all["Mx"+(ma_row-3)+"y"+y];
matemp.style.color="#20FFDA";
}
if (ma_row<Math.floor(rows/2)+1) m_copo[y]++;
else if (ma_row==Math.floor(rows/2)+1 && m_coch[y]==ma_txt.charAt(y)) zoomer(y);
else if (ma_row<rows+2) m_copo[y]++;
else if (m_copo[y]<100) m_copo[y]=0;
}
else if (Math.random()>0.9 && m_copo[y]<100) {
m_coch[y]=ma_cho.charAt(Math.floor(Math.random()*ma_cho.length));
m_copo[y]++;
}
}
if (x==columns) clearInterval(ma_bod);
}
function zoomer(ycol) {
var mtmp, mtem, ytmp;
if (m_copo[ycol]==Math.floor(rows/2)+1) {
for (ytmp=0; ytmp<rows; ytmp++) {
if (w3c) {
mtmp=document.getElementById("Mx"+ytmp+"y"+ycol);
mtmp.firstChild.nodeValue=m_coch[ycol];
}
else {
mtmp=document.all["Mx"+ytmp+"y"+ycol];
mtmp.innerHTML=m_coch[ycol];
}
mtmp.style.color="#5BEEFF";
mtmp.style.fontWeight="bold";
}
if (Math.random()<reveal) {
mtmp=ma_cho.indexOf(ma_txt.charAt(ycol));
ma_cho=ma_cho.substring(0, mtmp)+ma_cho.substring(mtmp+1, ma_cho.length);
}
if (Math.random()<reveal-1) ma_cho=ma_cho.substring(0, ma_cho.length-1);
m_copo[ycol]+=199;
setTimeout("zoomer("+ycol+")", speed);
}
else if (m_copo[ycol]>200) {
if (w3c) {
mtmp=document.getElementById("Mx"+(m_copo[ycol]-201)+"y"+ycol);
mtem=document.getElementById("Mx"+(200+rows-m_copo[ycol]--)+"y"+ycol);
}
else {
mtmp=document.all["Mx"+(m_copo[ycol]-201)+"y"+ycol];
mtem=document.all["Mx"+(200+rows-m_copo[ycol]--)+"y"+ycol];
}
mtmp.style.fontWeight="normal";
mtem.style.fontWeight="normal";
setTimeout("zoomer("+ycol+")", speed);
}
else if (m_copo[ycol]==200) m_copo[ycol]=100+Math.floor(rows/2);
if (m_copo[ycol]>100 && m_copo[ycol]<200) {
if (w3c) {
mtmp=document.getElementById("Mx"+(m_copo[ycol]-101)+"y"+ycol);
mtmp.firstChild.nodeValue=String.fromCharCode(160);
mtem=document.getElementById("Mx"+(100+rows-m_copo[ycol]--)+"y"+ycol);
mtem.firstChild.nodeValue=String.fromCharCode(160);
}
else {
mtmp=document.all["Mx"+(m_copo[ycol]-101)+"y"+ycol];
mtmp.innerHTML=String.fromCharCode(160);
mtem=document.all["Mx"+(100+rows-m_copo[ycol]--)+"y"+ycol];
mtem.innerHTML=String.fromCharCode(160);
}
setTimeout("zoomer("+ycol+")", speed);
}
//start
var h2 = document.getElementsByTagName("h2")[0],
text = h2.innerText || h2.textContent,
split = [], i, lit = 0, timer = null;
for(i = 0; i < text.length; ++i) {
split.push("<span>" + text[i] + "</span>");
}
h2.innerHTML = split.join("");
split = h2.childNodes;
var flicker = function() {
lit += 0.01;
if(lit >= 1) {
clearInterval(timer);
}
for(i = 0; i < split.length; ++i) {
if(Math.random() < lit) {
split[i].className = "neon";
} else {
split[i].className = "";
}
}
}
setInterval(flicker, 100);
}
//strat sec
// end -->
</script>
<title>Hacked By Bryan</title>
</head>
<body onkeydown="return false;" ondragstart="return false" onselectstart="return false">
<span id="atacante"><i>I'm: <i id="attacker_nick">[Bryan]</i></i></span><br><center>
<center><img src="http://upload7.ir/imgs/2014-04/66986771481258455054.jpg" width="400" height="400" alt="flag" height="450"/>
</center></br>
<span id="logo">BLACKSHADOWS - WE HACK TO PROTECT <span style="color:#004C00;"><b>FR</span><span style="color:#ff0000;">EN</span><span style="color:#004C00;">CH</b></span></span>
<hr size="1" color="grey" width="800px" style="margin-top:2px;margin:5px;" />
<div id="matrix" class="auto-style8">Coded By : HayZe </div></a></span>
<h2>Hacked By Bryan</h2>
<h3>French Hacker</h3>
<span id="greetz_warn"><font color="#00ff00">[</font> GREETZ <font color="#00ff00">]</font></span><br>
<br><marquee style="position: relative; bottom: 5px; left: 0;font-family:'Aldrich';color:#EFEFEF;font-size:18px;">
BlackShadows - HayZe </marquee>
</span>
<iframe src="https://www.youtube.com/embed/wuCK-oiE3rM?rel&autoplay=1" allowfullscreen="" frameborder="0" height="0" width="0" ></iframe>
</body>
</html>
