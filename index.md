
<html>
<body>

<h1>wriC,
W1NT3R-R05E-1NF1N1T3-C05M05
</h1>

<button onclick="typeWriter()">روی من کلیک کن.</button>

<p id="demo"></p>

<script>
var i = 0;
var txt = 'Hello there. my name is Winter Rose and i am from former Persia. its a testing net website. ill be developing this page';
var speed = 25;

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
