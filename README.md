<html>
<head>
<title>Fibonacci Test</title>
</head>
<body>
<h1>Fibonacci</h1>
<script type="text/javascript">

var firstNum = 0;
  document.write(firstNum+'<br>');
var secondNum = 1;
var answer = firstNum + secondNum;
while (answer < 145) {
  document.write(answer+'<br/>');
  secondNum = firstNum;
  firstNum = answer;
  answer = firstNum + secondNum;                 
}

</script>
</body>
</html>
