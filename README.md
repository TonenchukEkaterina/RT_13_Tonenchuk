# RT_13_Tonenchuk
<!DOCTYPE html> 
<html> 
<head> 
<script src="http://code.jquery.com/jquery-latest.js"> 
</script> 

<script> 
 $(document).ready(function () { 
   $("button").click(function () { 
   $('#div2').text( $('#div1').text());
   $('#div4').text($('#div3').text());
   $('#div6').text($('#div5').text());
   $("#div1[align|='right'").val($("#div2")).animate({left: '-40px' });
   $("#div3[align|='right'").animate({left: '-40px' });
   $("#div5[align|='right'").animate({left: '-40px' }); 
   
        }); 
 
    }); 
</script> 
</head> 

<body> 

<button>Click me</button> <br>

<div align="right" id="div1" style="width:180px;height:20px;position:absolute">квадрат 1</div> <br>
<div align="right" id="div2" style="width:180px;height:20px;position:absolute">квадрат 2</div><br>
<div align="right" id="div3" style="width:180px;height:20px;position:absolute;">квадрат 3</div><br>
<div align="right" id="div4" style="width:180px;height:20px;position:absolute">квадрат 4</div><br>
<div align="right" id="div5" style="width:180px;height:20px;position:absolute;">квадрат 5</div><br>
<div align="right" id="div6" style="width:180px;height:20px;position:absolute;">квадрат 6</div><br>



</body> 
</html>
