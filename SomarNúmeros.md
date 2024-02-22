# SomarNumeros
Uma calculadora que só executa operações de adição com núemros reais, programada em Javascript e utilizando HTML e CSS

#CÓDIGO COMPLETO

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Somar Números</title>
    <style>
        body{
            font: normal 10pt Arial;

        }
        input{

            font:italic 10pt Arial;
        }
        div#res{
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Somando Valores</h1>
    <input type="number" name="txtn1" id="txtn1">
    <input type="number" name="txtn2" id="txtn2">
    <input type="button" value="Somar" onclick="somar()"
    >
    <div id="res"> Resultado</div>
    <script>
        function somar(){
       var tn1= window.document.getElementsByName('txtn1')
       var tn2= window.document.querySelector('input#txtn2')
       var res= window.document.getElementById('res')
       var n1=Number(txtn1.value)
       var n2=Number(txtn2.value)
       var s= n1 + n2
       res.innerHTML= `A soma entre ${n1} e ${n2} é igual a: ${s}`
        }
    </script>
</body>
</html>


