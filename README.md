
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
</head>
<body style="text-align:center; font-family:Arial; padding:50px;">

    <h1>Welcome to My Website!</h1>
    <p id="msg">This is a simple HTML program.</p>

    <button onclick="changeText()">Click Me</button>

    <script>
        function changeText() {
            document.getElementById("msg").innerHTML =
                "Hello! The button is working!";
            document.body.style.backgroundColor = "lightblue";
        }
    </script>

</body>
</html>
