<!DOCTYPE html>
<html>
<head>
    <title>My Panel</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="box">

<h1>Welcome to Panel</h1>

<input id="user" placeholder="Username"><br><br>
<input type="password" placeholder="Password"><br><br>

<button onclick="login()">Login</button>

</div>

<script>
function login(){
    let user = document.getElementById("user").value;
    if(user){
        window.location.href = "dashboard.html";
    } else {
        alert("Enter username");
    }
}
</script>

</body>
</html>
