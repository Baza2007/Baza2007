<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Меню</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      padding: 20px;
    }
    .menu-container {
      max-width: 400px;
      margin: auto;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #333;
    }
    .menu-item {
      border-bottom: 1px solid #ddd;
      padding: 10px 0;
    }
    .menu-item:last-child {
      border-bottom: none;
    }
    .item-name {
      font-weight: bold;
    }
    .item-price {
      float: right;
      color: #888;
    }
  </style>
</head>
<body>
  <div class="menu-container">
    <h1>Меню</h1>
    <div class="menu-item">
      <span class="item-name">Пицца Маргарита</span>
      <span class="item-price">350₽</span>
    </div>
    <div class="menu-item">
      <span class="item-name">Цезарь с курицей</span>
      <span class="item-price">420₽</span>
    </div>
    <div class="menu-item">
      <span class="item-name">Паста Болоньезе</span>
      <span class="item-price">390₽</span>
    </div>
    <div class="menu-item">
      <span class="item-name">Чай чёрный</span>
      <span class="item-price">80₽</span>
    </div>
    <div class="menu-item">
      <span class="item-name">Кофе американо</span>
      <span class="item-price">120₽</span>
    </div>
  </div>
</body>
</html>
