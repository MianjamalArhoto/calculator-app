<!DOCTYPE html>
<html>
<head>
<title>Calculator</title>
<style>
body{
font-family:Arial;
text-align:center;
margin-top:50px;
}
input{
padding:10px;
width:200px;
}
button{
padding:10px;
margin:5px;
}
</style>
</head>
<body>

<h1>Simple Calculator</h1>

<input type="number" id="num1" placeholder="First Number">
<br><br>

<input type="number" id="num2" placeholder="Second Number">
<br><br>

<button onclick="add()">Add</button>

<h2 id="result"></h2>

<script>
function add(){
let a=document.getElementById("num1").value;
let b=document.getElementById("num2").value;

let result=Number(a)+Number(b);

document.getElementById("result").innerHTML=
"Result: "+result;
}
</script>

</body>
</html>
