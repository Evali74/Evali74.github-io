<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Поиск максимального или минимального числа</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Поиск максимального или минимального числа</h1>
        <label for="num1">Введите число 1:</label>
        <input type="number" id="num1" required>
        <label for="num2">Введите число 2:</label>
        <input type="number" id="num2" required>
       
        <div>
            <button id="maxBtn" onclick="findMax()">Найти максимальное</button>
            <button id="minBtn" onclick="findMin()">Найти минимальное</button>
        </div>
        <div id="result"></div>
    </div>

    <script src="script (1).js"></script>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  background-color: #535353;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 400px;
  margin: 10px auto;
  padding: 10px;
  background-color: rgb(255, 217, 217);
  border-radius: 5px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

label {
  display: block;
  margin-bottom: 15px;
}

input {
  width: 100%;
  padding: 5px;
  margin-bottom: 10px;
  box-sizing: border-box;
}

button {
  padding: 5px 10px;
  margin-right: 10px;
  background-color: #990054;
  color: #fff;
  border: none;
  border-radius: 3px;
  cursor: pointer;
}

button:hover {
  background-color: #990054;
}

#result {
  margin-top: 10px;
  font-weight: bold;
}
.input-field {
  margin: 10px;
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 5px;
}
