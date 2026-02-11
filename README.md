# valentine-site.github.io
<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Megha, Be My Valentine ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #ffc0cb, #ff9aa2, #ff6f91);
    }

```
.card {
  background: white;
  padding: 40px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  max-width: 500px;
}

h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

p {
  font-size: 1.2em;
  color: #555;
}

.buttons {
  margin-top: 25px;
}

button {
  font-size: 1.1em;
  padding: 12px 25px;
  margin: 10px;
  border: none;
  border-radius: 12px;
  cursor: pointer;
  transition: 0.3s;
}

.yes {
  background: #28a745;
  color: white;
}

.no {
  background: #dc3545;
  color: white;
}

.yes:hover { background: #218838; }
.no:hover { background: #c82333; }

#response {
  margin-top: 20px;
  font-size: 1.3em;
  font-weight: bold;
}
```

  </style>
</head>
<body>

  <div class="card">
    <h1>Megha ❤️</h1>
    <p>
      From the moment I met you, my world became brighter.<br>
      Your smile means everything to me.
    </p>

```
<h2>Will you be my Valentine? 💌</h2>

<div class="buttons">
  <button class="yes" onclick="sayYes()">Yes 💖</button>
  <button class="no" onclick="sayNo()">No 💔</button>
</div>

<div id="response"></div>
```

  </div>

  <script>
    function sayYes() {
      document.getElementById(\"response\").innerHTML =
        \"Yayyy!! ❤️ I promise to make this Valentine’s Day unforgettable 🌹✨\";
    }

    function sayNo() {
      document.getElementById(\"response\").innerHTML =
        \"I’ll keep trying until I win your heart 💘🥺\";
    }
  </script>

</body>
</html>
