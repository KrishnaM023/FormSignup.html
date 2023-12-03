<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Document</title>
    <style>
       
       h2{
        color: orange;
        text-align: center;
        width: auto;
       }

       form{
        background-color: grey;
        text-align: center;
        width: auto;
       }

       input{
        font-size: 30px;
        width: 500px;
        border-color: black;
       }

       button{
        cursor: pointer;
        transition: background-color 0.3s;
        background-color: palegoldenrod;
       }

    </style>
</head>
<body>
    <h2>Book a Call</h2>
   <!-- <div id="container"> -->
       <form action="#" onsubmit="onsignup(event)">
            <label >Name</label><br>
            <input type="text" name="username" required><br>
            <label >Email</label><br>
            <input type="email" name="email" required><br>
            <label >Phone</label><br>
            <input type="tel" name="phone" value=""><br><br>
            <label >Time for Call</label><br>
            <input type="datetime-local" name="timeforcall"><br><br>
            <button>Sign Up</button>
       </form>

       <script src="Pscript.js"></script>
    
</body>
</html>
