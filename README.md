# Kalambio
This is my first project.In which I created html page which is about A.P.J Abdul Kalam.
<!DOCTYPE html>
<head>
<title>Abdul kalam</title>
</head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script>
function display()
{
document.getElementById("demo").innerHTML="@developed by deepika";
}
</script>
<style>
p{
color:darkcyan;
}
body{
background-image:linear-gradient(gray,lightblue,cadetblue);
background-repeat:norepeat;
background-attachment:scroll;
padding:10%;
}
h1{
font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
text-shadow:6px 6px 5px lightgreen;
}
img{
border-radius:40px;
display:center;
width: 200px;
height:200px;
}
div#data{
background-color:bisque;
border:10px solid burlywood;
margin:5%;
padding:10%;
box-shadow:12px 15px 10px black;
font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
color:cadetblue;
}
.heading{
text-align:center;
color:darkgreen;
}
#subhead{
font-family: 'Times New Roman', Times, serif;
font-size: larger;
font-style:bold;
color:dodgerblue;
}
</style>
</head>
<body>
<h1 class="heading"><strong><bold><ins>A.P.J.Abdul Kalam</strong></bold></ins></h1>
<hr/>
<center>
<img src="C:\Users\Kesav\Desktop\apj.jpg" alt="Abdul Kalam"/>
</center>
<h2 style="color:darkmagenta;"><Strong><bold>About Abdul Kalam</bold></Strong></h2>
<p style="font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;"><q><i>Avul Pakir Jainulabdeen Abdul Kalam</i> was an Indian aerospace
scientist and statesman who served as the 11th president of India
from 2002 to 2007. He was born and raised in <em>Rameswaram, Tamil Nadu</em>
and studied physics and aerospace engineering. He spent the next
four decades as a scientist and science administrator, mainly at
the Defence Research and Development Organisation <abbr title="Defence Research
and Development Organisation">(DRDO)</abbr>
and Indian
Space Research Organisation <abbr title="Indian Space Research Organisation">(ISRO)</abbr>
and was intimately involved in India's
civilian space programme and military missile development efforts.
He thus came to be known as the Missile Man of India for his work on
the development of ballistic missile and launch vehicle technology.</q></p>
<h2 class="heading" style="color:darkblue;"><bold>Some interesting facts about Abdul Kalam</bold></h2>
<div id="data">
<p> <div id="subhead">1.Avul Pakir Jainulabdeen Abdul Kalam was his full name</div>
He had a huge name but he is better known as APJ or Abdul Kalam
or Kalam or Dr. Kalam or APJ Abdul Kalam.<br><br>
<div id="subhead">2.Born in a Tamil Muslim family in Rameshwaram</div>
He was born and raised in the town of Rameswaram in Tamil Nadu.
His father owned a ferry that transported Hindu pilgrims between
Rameswaram and the now-deserted Dhanushkodi.<br><br>
<div id="subhead">3.Hard Childhood</div>
Kalam’s father, Jainulabudeen, was a boat owner and imam at a local
mosque. His forefathers were wealthy, but due to business failures,
the former President’s fortunes were lost, and he was forced to work
odd jobs. In his family, Kalam was the youngest of four brothers and
one sister. To supplement his father’s income, Kalam used to distribute
newspapers after school.<br><br>
<div id="subhead">4.Academic Excellenc</div>
Abdul Kalam had 7 doctorates, which may surprise you. During his lifetime,
former President APJ Abdul Kalam, who was born on October 15, 1931,
received honorary doctorates from 40 national and international universities.<br/>
<div id="subhead">5.Awards that no one gets more than once in a lifetime.</div>
Legends do exist, to be sure. You would agree if you looked at Kalam’s
life. Dr. Kalam has been awarded the Padma Bhushan (1981) and
Padma Vibhushan (1990) civilian awards, as well as the highest civilian
honour, the Bharat Ratna (1997).<br><br>
<div id="subhead">6..Missile Man</div>
If you’ve seen the film Parmanu, you’ll recognize Dr. APJ Abdul Kalam as
the mastermind behind the initiative to use missiles as a deterrent.
He was in charge of the Agni and Prithvi missiles’ development and deployment.
It is for this reason that he is known as India’s Missile Man. He was a
firm believer in the concept of power commanding respect, and he believed
that other nations would only respect India if we were powerful.<br><br>
</p>
</div>
<small>to know who did this</small>
<button type="button" onclick="display()">click here</button>
<p id="demo" style="color:chartreuse;"></p>
</body>
</html>
