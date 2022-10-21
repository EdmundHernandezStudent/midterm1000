### midterm1000

This is _Edmund Hernandez's_ page for a midterm project.

![A panda](https://cdn.britannica.com/80/150980-050-84B9202C/Giant-panda-cub-branch.jpg)

> Below are some **links** to other pages.
> Hope you enjoy!
- [Here's the source for the Panda image above](https://www.britannica.com/animal/giant-panda)
- [Here's a page with a donut](secondPage.md)
- [Here's a page with bananas](thirdPage.md)
- [Here's a page with a pineapple](fourthPage.md)
- [Here's a page with a coconut](fifthPage.md)
- [Here's a page about the prisoner's dilemma which I made years ago](https://edmundhernandezstudent.github.io/midterm1000/prisonchoice.html)

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Number Guesser</title>
<script>
  
  function randomNumCompare() {
    var machineNum = Math.floor(Math.random() * 11);
    var textBoxSum = Math.floor(Math.random() * 11);

  if (textBoxSum == machineNum) {
    document.getElementById("output").innerHTML = "The numbers match!";
  } else if (textBoxSum != machineNum) {
    document.getElementById("output").innerHTML = "The numbers did not match!";
  }}
</script>

</head>
  
<body onload="randomNumCompare()">

<p="output"></p>

</body>
</html>
