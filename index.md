<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>���еȿ���</title>
  <style>
    /* ����ҳ��������ʽ */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }

    /* ����������ʽ */
    .container {
      display: flex; /* ʹ�� Flexbox ���� */
      justify-content: space-between; /* ����֮��ȼ�� */
      align-items: stretch; /* ʹ�����еĸ߶�һ�� */
      padding: 20px;
      max-width: 1200px; /* ����� */
      margin: 0 auto; /* ������ʾ */
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    /* ����ÿ�е���ʽ */
    .column {
      flex: 1; /* ÿ�еȿ� */
      margin: 0 10px; /* ��֮��ļ�� */
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
      <h2>��1</h2>
      <p>����A</p>
    </div>
    <div class="column">
      <h2>��2</h2>
      <p>����B</p>
    </div>
    <div class="column">
      <h2>��3</h2>
      <p>����C</p>
    </div>
  </div>
</body>
</html>