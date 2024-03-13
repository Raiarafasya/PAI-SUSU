<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penjualan Pai Susu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        .form-group {
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"], input[type="number"] {
            width: 100%;
            padding: 8px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Penjualan Pai Susu</h1>
        <form action="#" method="post">
            <div class="form-group">
                <label for="flavor">Rasa Pai Susu:</label>
                <input type="text" id="flavor" name="flavor" required>
            </div>
            <div class="form-group">
                <label for="quantity">Jumlah:</label>
                <input type="number" id="quantity" name="quantity" min="1" required>
            </div>
            <div class="form-group">
                <label for="price">Harga Satuan:</label>
                <input type="number" id="price" name="price" min="0" step="0.01" required>
            </div>
            <input type="submit" value="Tambahkan ke Keranjang">
        </form>
    </div>
</body>
</html>
