<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google It</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff;
        }
        h1 {
            font-size: 4rem;
            margin-bottom: 30px;
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        input[type="text"] {
            width: 500px;
            max-width: 90vw;
            padding: 10px 15px;
            font-size: 1.2rem;
            border: 1px solid #dcdcdc;
            border-radius: 24px;
            outline: none;
        }
        input[type="submit"] {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1rem;
            border: none;
            border-radius: 4px;
            background-color: #f2f2f2;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #e2e2e2;
        }
    </style>
</head>
<body>
    <h1>Google it.</h1>
    <form action="https://www.google.com/search" method="get" target="_blank">
        <input type="text" name="q" placeholder="Search Google...">
        <input type="submit" value="Google Search">
    </form>
</body>
</html>
