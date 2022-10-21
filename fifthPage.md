<!DOCTYPE html>
<html>

<head>
<meta charset="UTF-8">
<title>Number Guesser</title>
  <script>
  function randomNumCompare() {
    var machineNum = Math.floor(Math.random() * 11)
    var textBoxSum = document.getElementById("textBox")

  if (textBoxSum == machineNum) {
    document.getElementById("output").innerHTML = "The numbers match!"
  } else if (textBoxSum != machineNum) {
    document.getElementById("output").innerHTML = "The numbers did not match!"
  }}
  </script>
</head>
  
<body>

<form action="randomNumCompare()">
  <label for= "textBox">Put in a number and see if its the same number the random function gives (0 to 10):</label></br>
  <input type="text" id="textBox" name="textBox"></input></br>
  <input type="submit value="Submit">
</form>

<p="output"></p>

</body>
</html>
