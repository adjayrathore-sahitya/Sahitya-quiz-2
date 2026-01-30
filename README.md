# Sahitya-quiz-2
Quiz 2
<!DOCTYPE html>
<html>
<head>
  <title>Sahitya Boss Quiz</title>
  <style>
    body {
      font-family: sans-serif;
      background: #111827;
      color: white;
      text-align: center;
      padding-top: 60px;
    }
    button {
      padding: 12px 20px;
      margin: 10px;
      font-size: 16px;
      border-radius: 10px;
      border: none;
      background: #22c55e;
    }
  </style>
</head>
<body>

<h1>SAHITYA BOSS QUIZ</h1>
<p>10 + 5 = ?</p>

<button onclick="check(15)">15</button>
<button onclick="check(20)">20</button>
<button onclick="check(10)">10</button>

<p id="msg"></p>

<audio id="ok" src="https://actions.google.com/sounds/v1/cartoon/pop.ogg"></audio>
<audio id="no" src="https://actions.google.com/sounds/v1/cartoon/boing.ogg"></audio>

<script>
function check(x){
  if(x===15){
    msg.innerText="Correct ✅";
    ok.play();
  } else {
    msg.innerText="Wrong ❌";
    no.play();
  }
}
</script>

</body>
</html>
