# project1<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width,
                       initial-scale=1">
    
    <style>
        body {
           
            height: 100%;
            font-family: Arial, sans-serif;
            margin: 0;
        }
        .bg-img {
            <img src="image2.jpg" alt="">
            background-image:url("image2.jpg");
            min-height: 100vh;
            background-size: cover;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        s
        .container {
            position: relative;
            max-width: 300px;
            padding: 16px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: black;
            -webkit-text-stroke: 1px black;
            margin-bottom: 20px;
        }

        b {
            color: black;
            font-size: 18px;
            -webkit-text-stroke: 1px black;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 12px;
            margin: 8px 0;
            border: 1px solid black;
            box-sizing: border-box;
        }

        .button {
            background-color: darkred;
            color: white;
            padding: 14px;
            border: none;
            cursor: pointer;
            width: 100%;
        }

        .button:hover {
            background-color: black;
        }
    </style>
</head>

<body>
    <div class="bg-img">
    
   
    <div align="center">
       

        <form class="container">
            <div align="center">
         <h1 center style="color:red">Sign Up</h1><br>
         <br>
       </div>

           
            <input type="text" 
                  placeholder="Enter your username" 
                   name="username" required>

           <input type="password" 
                   placeholder="Enter your password" 
                   name="password" required><br><br>

            <button type="submit" class="button">Login</button>
            <br>
            <br>
            <br>

             <div align="center" >
          <button type="button" class="cancelbtn">Foget Paasword</button>
           &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
          <button type="button" class="signupbtn">Sign Up</button>

          </div>

        </form>
    </div>
</body>
</html>
                
