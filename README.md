# Javascript-basics

Object declaration in Javascript 
 
In javavascript can declare the Object in 2 ways.
First one is object construtor and Secound one is object literal

Object Construtor
syntax
 var user = new Object(); // var data type, user variable name
 Ex:
 <script type="text/javascript">
 	var carBmw = new Object();
 	carBmw.series = "BMW 5 Series";
 	carBmw.fuel = "Diesel / Petrol";
 	carBmw.transmission = "Automatic";
 	console.log(carBmw.series);
 </script>

object literal
syntax
var user = {}; // var data type, user variable name
EX:
<script type="text/javascript">
    var carBmw = {  
    	series:"BMW 5 Series",
 		fuel:"Diesel / Petrol",
 		transmission:"Automatic",  
    }; 
   console.log(carBmw.series);
 </script>
