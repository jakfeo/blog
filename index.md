<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>三列等宽布局</title>
  <style>
    /* 设置页面整体样式 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }

    /* 设置容器样式 */
    .container {
      display: flex; /* 使用 Flexbox 布局 */
      justify-content: space-between; /* 三列之间等间距 */
      align-items: stretch; /* 使所有列的高度一致 */
      padding: 20px;
      max-width: 1200px; /* 最大宽度 */
      margin: 0 auto; /* 居中显示 */
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    /* 设置每列的样式 */
    .column {
      flex: 1; /* 每列等宽 */
      margin: 0 10px; /* 列之间的间距 */
      padding: 20px;
      background-color: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 5px;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="column">
      <h2>列1</h2>
      <p>内容A</p>
    </div>
    <div class="column">
      <h2>列2</h2>
      <p>内容B</p>
    </div>
    <div class="column">
      <h2>列3</h2>
      <p>内容C</p>
    </div>
  </div>
</body>
</html>