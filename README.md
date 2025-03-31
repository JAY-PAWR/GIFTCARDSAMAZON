<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>April Fool</title>
</head>
<body>
    <a href="#" id="foolLink">Click me!</a>

    <script>
        document.getElementById('foolLink').addEventListener('click', function(event) {
            event.preventDefault();
            alert('April Fool!');
        });
    </script>
</body>
</html>
