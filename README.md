<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Github Search user using Github API</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
</head>
<body>
    <div class="container">
        <br><br>
        <h1 style="text-align:center ;">
        Github Search user App</h1>
    <form id="myForm" autocomplete="off">
        <div class="form-group">
            <input type="text" class="form-control" id="search" placeholder="Search Username" required>
        </div>
        <div class="form-group">
            <button class ="btn btn-danger btn-block">
           Search User
            </button>

        </div>

    </form>
    <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>

</html>
