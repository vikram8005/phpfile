<!DOCTYPE html>
<html lang="en">
<head>
    <style>
form
{
background-image:url("pexels-mo-eid-9454915.jpg");
   background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
height: 98vh;
}
table{
border:solid pink;
border-radius:50px;
text-align:center;
background-color:;

}
td{
height: 15vh;
font-size:30px;
}
input{
height: 30px;
border-radius:10px;
border:1px solid;
}

      
.btn{
height: 50px;
width: 80px;
border-radius:20px;
font-size:20px;
}
.lo{

    border:solid 2px;
    height: 40px;
width: 80px;
border-radius:20px;
font-size:30px;
}

    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<form action="insert.php"  method="POST" enctype="multipart/form-data">
<table align = "right   " >
<td>Name</td><td>:</td><td><input type="text" name ="name"  required ></td><tr>
<td>Phone</td><td>:</td><td><input type="email"  name ="phone"  required></td><tr>
<td>passward</td><td>:</td><td><input type="text" name ="passward" required ></td><tr>
<td><button name="submit" value="submit" class="btn">submit</button></td>
<td><div  class="lo"> <a href="timerotation.html"  >Login</a> </div></td>
</table>
</form>    
</body>
</html>
