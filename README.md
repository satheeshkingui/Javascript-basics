# Javascript-basics

Object declaration in Javascript<br/> 
 
In javavascript can declare the Object in 2 ways.<br/>
First one is object construtor and Secound one is object literal<br/>

Object Construtor<br/>
syntax<br/>
 var user = new Object(); // var data type, user variable name<br/>
 Ex:<br/>
 <p><script type="text/javascript"><br/>
 	var carBmw = new Object();<br/>
 	carBmw.series = "BMW 5 Series";<br/>
 	carBmw.fuel = "Diesel / Petrol";<br/>
 	carBmw.transmission = "Automatic";<br/>
 	console.log(carBmw.series);<br/>
 </script></p><br/>

object literal<br/>
syntax<br/>
var user = {}; // var data type, user variable name<br/>
EX:<br/>
<p><script type="text/javascript"><br/>
    var carBmw = {   <br/>
    	series:"BMW 5 Series", <br/>
 		fuel:"Diesel / Petrol",<br/>
 		transmission:"Automatic", <br/> 
    }; <br/>
   console.log(carBmw.series);<br/>
 </script></p><br/>
