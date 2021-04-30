# Calculation
Efetuar cálculos 

<html>
  <body>
   
     <meta charset="UTF-8">
    
    <title> Tabuada </title>

    <h1> Calculos </h1>


     <label for=vartab>Informar tabuada:</label>
     <input type= "text" id="varTab" > <br> <br>;
     <input type= "button" onclick= "confirm ()" value= "Confirmar" >
     <p id="ptab"></p>
  
    <script> (
     
       Var ix = 0 ;
       Var tabx = "" ;
       Var tab = Document.getElementById("ptab") ;
       function confirm () 
       tabx = Document.getElementById( "varTab" ).value ;
       tabx = parsetInt(tabx, 10);
       tab .innerHTML= "Tabuada do" + tabx ;
       ix = 1 ;
        do (
        tab.innerHTML += "</br>" + tabx + "x" + ix +" = " + tabx * ix 
        ix += 1 ;
        ) while ix<= 10) ;

     ) 

     </script>
    </body>
</html>
