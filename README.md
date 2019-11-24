













<html>
<head>
</head>
 <body>
       <a id="foto"></a><img src="https://st2.depositphotos.com/3482063/10518/v/950/depositphotos_105183202-stock-illustration-hand-drawn-cosmetic-icon-cosmetic.jpg" height="255"></a>
  
    <h1>TABELA COBRANÇA</h1>
    <P>MELHORES PREÇOS VOCÊ ENCONTRA AQUI!</P>

    <input name="opt" value= "Cliente" />
    <input name="opt" value= "Produto" />
    <input name="opt" value= "Valor" />
    <input name="opt" value= "Data Da Compra" />
    <input name="opt" value= "Data Do Pagamento" />
    <input name="opt" value= "Status" />
    <input name="opt" value= "Tipo Do Pagamento" /><br>

    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" /><br>

    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />
    <input name="opt" value= "" />

   <div class= "tipo">
       <h2>Para o tipo do pagamento ultilizar a numeração a abaixo:</h2>
       <ol>1.A vista</ol>
       <ol>2.Carnê</ol>
       <ol>3.Cartao De Credito</ol>
   </div>

   <p></p>Atenciosamente Gerente Geral</p>
     
    <script>

        //sobre classes 
        var classe= document.getElementsByClassName('teste');
        console.log(classe);

        

        // sobre tags
        var elementos= document.getElementsByName('opt');
        console.log(elementos);
        console.log(elementos[0].value); //Cliente
        console.log(elementos[1].value); //Poduto
        console.log(elementos[2].value); //Valor
        console.log(elementos[3].value); //Data Da Compra
        console.log(elementos[4].value); //Data Do Pagamento
        console.log(elementos[5].value); //Status
        console.log(elementos[6].value); //Tipo Do Pagamento

         var paragrafo= document.getElementsByTagName('p');
         console.log(paragrafo);

         var h= document.getElementsByTagName('h1');
         console.log(h);

        // sobre id
        var elemento = document.getElementById("foto");
        console.log(elemento);

    
    </script>
 </body>

</html>
