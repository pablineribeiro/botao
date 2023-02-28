# botao
Criando 1 Botão em html
<!DOCTYPE html>
<html>
    <body>
    
        <button onclick="myFunction()">Clique Aqui!</button>
             <p id="demo"></p>
             <button onclick="myFunction2()">Quem sou eu</button>
             <p id="demo2"></p>

<p>Uma função é executada quando o botão é clicado.
    A função revela um texto em um elemento p com
    id ="demo".</p>

<script>
    function myFunction() {
        document.getElementById("demo").innerHTML="Olá,mundo!";
        }
    function myFunction2(){document.getElementById("demo2").innerHTML="Meu nome é Pabline";}
</script>

    </body>
</html> 
