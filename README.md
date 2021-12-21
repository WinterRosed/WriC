<!DOCTYPE html>
<html>
<body>

<h1>WirC,
Winter Rose Infinite Cosmos
</h1>

<button onclick="typeWriter()">روی من کلیک کن.</button>

<p id="demo"></p>

<script>
var i = 0;
var txt = 'Hello there. my name is Winter Rose and i am from former Persia. its a testing net website. ill be developing this page';
var speed = 50;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("demo").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
</script>

</body>
</html>
