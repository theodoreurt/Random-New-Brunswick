<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Random Place Generator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 50px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
    #place {
      margin-top: 20px;
      font-size: 24px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>Random Place Generator</h1>
  <button onclick="generateRandomPlace()">Generate Random Place</button>
  <div id="place"></div>

  <script>
    const places = [
    "Fredericton",
    "Saint John",
    "Edmunston",
    "Acadian Peninsula",
    "Moncton",
    "Dieppe",
    "Miramichi",
    "Bathurst",
    "Campbellton",
    "Kennibecasis Valley",
    "Saint Andrews",
    "Shediac",
    "Memramcook",
    "Sussex",
    "Saint Stephen"
    ];
    function generateRandomPlace() {
      const randomIndex = Math.floor(Math.random() * places.length);
      document.getElementById('place').textContent = places[randomIndex];
    }
  </script>
  <p>You should visit {
      const randomIndex = Math.floor(Math.random() * places.length);
      document.getElementById('place').textContent = places[randomIndex];
    }, New Brunswick.</p>
</body> 
</html>
