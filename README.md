<script>
var nama = prompt("Siapa nama kamu?", "");
var Alamat = prompt("Dimana alamat kamu?", "");
document.write("-------------------------------------------------------------------------------</h1></p>");
document.write("<p><h1>Nama : "+ nama +"</h1></p>");
document.write("-------------------------------------------------------------------------------</h1></p>");
document.write("<p><h1>alamat : "+ Alamat +"</h1></p>");
document.write("-------------------------------------------------------------------------------</h1></p>");
</script>
<!DOCTYPE html>
<html>
<head>
<title>soal</title>
</head>
<body bgcolor=" ffff32ae ">
<h1>Contoh audio sebagai background</h1> <h1>1. Apa nama presiden kita?</h1> <br>
<h2><input type="radio" name="question1" id="correct1">jokowi<br>
<input type="radio" name="question1" >datuk ranggi<br>
<input type="radio" name="question1" >ratu elizabeth<br>
<input type="radio" name="question1" >donald trump</h2><br>
<br>
<h1>2. Dimana sungai nil berada?</h1> <br>
<h2><input type="radio" name="question2" >malaysia<br>
<input type="radio" name="question2" >australia<br>
<input type="radio" name="question2" id="correct2" >mesir<br>
<input type="radio" name="question2" >turki</h2><br>
<h1>3. Nama nabi pertama?</h1> <br>
<h2><input type="radio" name="question3" >Muhammad SAW<br>
<input type="radio" name="question3" >Nuh A.S<br>
<input type="radio" name="question3"  >Dajjal<br>
<input type="radio" name="question3" id="correct3" >Adam A.S</h2><br>
<h1>4. Siapa yg bergelar Bapak Pembangunan?</h1> <br>
<h2><input type="radio" name="question4" >Jokowi<br>
<input type="radio" name="question4" >Soekarno<br>
<input type="radio" name="question4" id="correct4" >Soeharto<br>
<input type="radio" name="question4" >Habibie</h2><br>
<h1>5. Ilmu dasar agama islam?</h1> <br>
<h2><input type="radio" name="question5" >marifat<br>
<input type="radio" name="question5"  id="correct5">syariat<br>
<input type="radio" name="question5" >harekat<br>
<input type="radio" name="question5" >tarekat</h2><br>
<h1>6. Kepanjangan dari HP?</h1> <br>
<h2><input type="radio" name="question6" >Handped<br>
<input type="radio" name="question6"  id="correct6">HandPhone<br>
<input type="radio" name="question6"  >HeadPhone<br>
<input type="radio" name="question6" >HitPad</h2><br>
<h1>7. Apa saja agama di palestina kecuali?</h1> <br>
<h2><input type="radio" name="question7" >nasrani<br>
<input type="radio" name="question7" >yahudi<br>
<input type="radio" name="question7" id="correct7" >konghucu<br>
<input type="radio" name="question7" >islam</h2><br>
<h1>8. Dinegara manakah letak kabah?</h1> <br>
<h2><input type="radio" name="question8" id="correct8">Arab Saudi<br>
<input type="radio" name="question8" >Mesir<br>
<input type="radio" name="question8"  >Palestina<br>
<input type="radio" name="question8" >turki</h2><br>
<h1>9. Ibukota Sumatera Utara?</h1> <br>
<h2><input type="radio" name="question9" >Dumai<br>
<input type="radio" name="question9" >Binjai<br>
<input type="radio" name="question9" id="correct9" >Medan<br>
<input type="radio" name="question9" >Padang</h2><br>
<h1>10. Siapa nama bapak habil?</h1> <br>
<h2><input type="radio" name="question10" >ugu<br>
<input type="radio" name="question10" >alam<br>
<input type="radio" name="question10" id="correct10" >adam<br>
<input type="radio" name="question10" >adi</h2><br>

<br>

<input type="submit" name="submit" value="submitquiz" onclick="result()">
<script type="text/javascript">
function result(){

var score=0;
if(document.getElementById("correct1").checked) 
{ score+10;
}
if(document.getElementById("correct2").checked) 
{ score+10;
}
if(document.getElementById("correct3").checked) 
{ score+10;
}
if(document.getElementById("correct4").checked) 
{ score+10;
}
if(document.getElementById("correct5").checked) 
{ score+10;
}
if(document.getElementById("correct6").checked) 
{ score+10;
}
if(document.getElementById("correct7").checked) 
{ score+10;
}
if(document.getElementById("correct8").checked) 
{ score+10;
}
if(document.getElementById("correct9").checked) 
{ score+10;
}
if(document.getElementById("correct10").checked) 
{ score+10;
}

document.write("<p>Nama : "+ nama +"</p>");
document.write("<p>alamat : "+ Alamat +"</p>");

document.write("Hasil Test Kamu adalah = "+ score);

}

</script>
</body>
</html> 


