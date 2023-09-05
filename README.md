<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cerciles</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        body{
            background :linear-gradient(90deg, black, white , brown ,white,black) no-repeat;
            height: 100vh;
            overflow: hidden;
        }
        .cer *{
            border-radius: 50%;
            position: absolute;
            top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) ;
        transition: all 0.3s;
         
        }
      .cer .red{
        width: 300px;
        height: 300px;
        background-color: red;
        
       }

       .cer .green{
        width: 250px;
        height: 250px;
        background-color: green;
        
       }
       .cer .blue{
        width: 200px;
        height: 200px;
        background-color: blue;
       
      
  }


  .cer:hover .red{
    width: 350px;
    height: 350px;
    background-color: blue;
}
.cer:hover .green{
        width: 300px;
        height: 300px;
        background-color: red;
        
       }
       .cer:hover .blue{
        width: 250px;
        height: 250px;
        background-color: green;}
        
        
        .cer:active .red{
    width: 300px;
    height: 300px;
    background-color: green;
}
.cer:active .green{
        width: 270px;
        height: 270px;
        background-color: blue;
        
       }
       .cer:active .blue{
        width: 230px;
        height: 230px;
        background-color: red;}
        .cer .black{

        background-color: black;
        height: 30px;
        width: 30px;
        user-select: none;
        pointer-events: none;
        }

.cer #checkbox:checked + .black{
    transform: scale(50);
}
    </style>
</head>
<body> 
    
    <label for="checkbox" class="cer">
        <input type="checkbox" id="checkbox"/>
        <div class="black"></div>
    <div class="red"></div> 
    <div class="green"></div>  
    <div class="blue"></div>
   
   

    
</body>
</html>
