# operadores

teste em php, com operadores aritméticos

<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>operadores</title>
    
</head>

<body>

   <?php
   
   //declaração de variaveis
   
   $num1 = 10; $num2 = 15; $soma = 0; $restoNum1 = 0; $restoNum2 = 0; 
   
   //Projeto 1909 - trablhando com operadores
   
   echo "Trabalhando com estruturas de operadores";
   
   echo "<br> Operadores aritméticos";
   
   echo "</br> Operador soma (+) "; 
   
   echo "</br> Operador multiplicao (*)";
   
   echo "</br> Operador subtracao (-)";
   
   echo "</br> Operador divisao (/)";
   
   echo "</br> Operação de soma";
   
   $soma = $num1 + $num2 ;
   
   //saida de processo
   
   echo "</br> O resultado da soma dos valores ".$num1." e ".$num2." é = ".$soma; //saida do processo
   
   echo "</br> Operação de Multiplicacao";
   
  $soma = $num1 * $num2 ;
  
  //saida de processo
  
  echo "</br> O resultado da Multiplicacao dos valores ".$num1." e ".$num2." é = ".$soma; //saida do processo
  
  echo "</br> Operação de subtracao";
  
  $soma = $num1 - $num2 ;
  
  //saida de processo
  
echo "</br> O resultado da subtração dos valores ".$num1." e ".$num2." é = ".$soma; //saida do processo

echo "</br> Operação de divisao";

$soma = $num1 / $num2 ;

//saida de processo

echo "</br> O resultado da divisao dos valores ".$num1." e ".$num2." é = ".$soma; //saida do processo

echo "</br>" ;

echo "</br> Operador RESTO divisão (%)"; //operação devolve o resto da divisão

$restoNum1 = $num1 % 2;

$restoNum2 = $num2 % 2;

echo "</br> saida do resto de ".$num1." é = ".$restoNum1;

echo "</br> saida do resto de ".$num2." é = ".$restoNum2;

echo "</br>*********************************************";

echo "</br> Operadores de incremento/Decremento";

echo "</br> Operador de incremento (++)";

$num1++; //soma + 1 ao valor da variavel, o mesmo que $num1 = $num1+1

echo "</br> Novo valor apos uso do operador decremento = ".$num2;

echo "</br> Novo valor apos uso do operador incremento =".$num1;

echo "</br>***********************************************";

echo "</br> Operadores Relacionais ";

echo "</br> Operadores MAIOR (>)";

echo "</br> valor1 = ".$num1." e .valor2 = ".$num2;

echo "</br> valor 1 > valor 2 = ".(boolval($num1 > $num2)?'true':'false');

echo "</br>";

echo "</br> Operador MAIOR/IGUAL (>=)";

echo "</br> valor 1 = ".$num1." e valor2 = ".$num2;

echo "</br> valor1 >= valor2 = ". (boolval($num1 >= $num2)?'true':'false');

// a linha anterior é uma condicional SE reduzida, o mesmo que IF (condicao) {<instrução>}. veja abaixo

/*if ($num1 >= $num2) (

    echo "true";
    
)else{

    echo "false";
}
    */ 

    echo "</br> Operador MENOR/IGUAL (<=)";
    
    echo "</br> valor 1 <= ".$num1." e valor2 = ".$num2;
    
    echo "</br> valor1 <= valor2 = ". (boolval($num1 <= $num2)?'true':'false');

    echo "</br> Operador DIFERENÇA/IGUAL (!=)";
    
    echo "</br> valor 1 = ".$num1." e valor2 = ".$num2;
    
    echo "</br> valor1 != valor2 = ". (boolval($num1 != $num2)?'true':'false');


?>

</body>

</html>
