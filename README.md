<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Propose Day ❤️</title>
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #ff9a9e, #fad0c4);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .box {
    background: white;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    max-width: 350px;
  }

  h1 {
    color: #ff4d6d;
  }

  button {
    padding: 10px 20px;
    margin: 10px;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    cursor: pointer;
  }

  .yes {
    background: #28a745;
    color: white;
  }

  .no {
    background: #dc3545;
    color: white;
  }

  #message {
    margin-top: 20px;
    font-size: 18px;
    color: #333;
    display: none;
    white-space: pre-line;
  }
</style>
</head>

<body>

<div class="box">
  <h1>Will You Be Mine? 💍</h1>
  <p>I really like you… Will you go on date with me ?</p>

  <button class="yes" onclick="showYes()">Yes ❤️</button>
  <button class="no" onclick="showNo()">No 💔</button>

  <div id="message"></div>
</div>

<script>
  function showYes() {
    let msg = document.getElementById("message");
    msg.style.display = "block";
    msg.innerHTML = `Yay! You made my day! love you forever ❤️ , bas keje kyare ane kya javanu che😚😁
Chand si mehbooba ho meri kab
Esa mene socha tha 
Ha tum bilkul wesi ho 
Jesa mene socha tha`;
  }

  function showNo() {
    let msg = document.getElementById("message");
    msg.style.display = "block";
    msg.innerHTML = `Shut up I know you already love me Titi , tamare ko mere sath date per chalna hi padega , you have no other choices 😚💞`;
  }
</script>

</body>
</html>
