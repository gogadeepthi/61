<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anonymous Function </title>
</head>
<body>
    <h2> Anonymous Function </h2>
    <button id="btn">Click Me </button>
    <p id="demo3" class="out"> </p>
    <script>
        document.getElementById("btn").onclick=function() {
            document.getElementById("demo3").innerText="Button Clicked using Anonymous function";
        };
    </script>
</body>
</html>
