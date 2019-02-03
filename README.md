# homepage
<h2>加油吧！的小站</h2>
<script type="text/javascript">
function startTime()
{
var today=new Date()
var h=today.getHours()
var m=today.getMinutes()
var s=today.getSeconds()
// add a zero in front of numbers<10
m=checkTime(m)
s=checkTime(s)
document.getElementById('txt').innerHTML=h+":"+m+":"+s
t=setTimeout('startTime()',500)
}

function checkTime(i)
{
if (i<10) 
  {i="0" + i}
  return i
}
</script>


<body onload="startTime()">
<div id="txt"></div>
<img src="https://thirdqq.qlogo.cn/g?b=sdk&k=91mghJRwGdmfCPG8ChRicGw&s=100&t=1483302994"/>
<hr/>
<font color="brown">实用网站:</font>
<p><a href="https://www.jiumodiary.com">鸠摩搜书</a></p>
<p><a href="http://m.panduoduo.net">盘多多</a></p>
<p><a href="https://github.com/Dictionaryphile/All_Dictionaries/blob/master/README.md">宇宙最全在线词典网站导航</a></p>
<p><a href="http://www.jisutiyu.com">极速体育</a></p>
