<!DOCTYPE html>
<html>
<head>
    <title>Student Register Form</title>
    <style>
        body {
            background-color: #e6f2ff;
            font-family: "Lucida Sans", "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
            text-align: center;
        }

        form {
            background-color: #ffffff;
            width: 300px;
            margin: auto;
            padding: 20px;
            border: 2px solid #4CAF50;
            border-radius: 5px;
        }

        input {
            width: 90%;
            padding: 8px;
            border: 1px solid #999;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h2>Student Registration Form</h2>

    <form>
        <label>Name:</label><br>
        <input type="text" name="name" required><br><br>

        <label>Age:</label><br>
        <input type="number" name="age" required><br><br>

        <label>Email:</label><br>
        <input type="email" name="email" required><br><br>

        <input type="submit" value="Submit">
    </form>

</body>
</html>
