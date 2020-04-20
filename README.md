<!DOCTYPE html>   
<html>   
    <head>  
        <title></title> 
    </head>  
        
    <body style = "text-align:center;">   
        <input id = "input" type="text" name="input"/>  
        <button onclick="capitalizeFLetter()">  
            Click this to capitalize first letter of each phrase 
        </button>  
        <h3 id = "div" style="color: blue"> 
        </h3>  
        <script>  
        function capitalizeFLetter() { 
          var input = document.getElementById("input"); 
          var x = document.getElementById("div"); 
          var string = input.value; 
          x.innerHTML = string[0].toUpperCase() +  
            string.slice(1); 
        } 
        </script>  
    </body>   
</html> 
