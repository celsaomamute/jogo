# arauto

<html>
<body>
  <body background = 05.jpg
  <center>
     <img src = '08.jpg' width = '980px' height = '550px' />
    <center>
   <center>
           <input type="button" value="porta do motorista aberta" style="width: 300px; height: 100px">
                 <button onclick="window.location.href='pag3.html'"></button>
    <center>
      <center>
         <input type="button" name="botao" value="porta do motorista fechada" style="width: 300px; height: 100px">
         <button onclick="window.location.href='pag4.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="porta do carona aberta" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag5.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="porta do carona fechada" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag6.html'"></button>
     <center>
      <center>
    <input type="button" name="botao" value="porta trazeira esquerda aberta" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag7.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="porta trazeira esquerda fechada" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag8.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="porta trazeira direita aberta" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag9.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="porta trazeira direita fechada" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag10.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="mala aberta" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag11.html'"></button>
    <center>
      <center>
    <input type="button" name="botao" value="mala fechada" style="width: 300px; height: 100px">
    <button onclick="window.location.href='pag12.html'"></button>
    <center>
</body>
</html>


<html>
<head>
    
    <input type='button' value= "Situação do Carro" onclick='(SitFM() + SitFC() + SitTE() + SitTD() + SitM())'/> <p>
    
<body>
<script>

function SitFM() {
    if( document.cookie.indexOf('PM=1')==-1){
            alert("Porta do Motorista Fechada");
    }
    else{
        alert("Porta do Motorista Aberta");
    }
}
//Para verificar a situação da porta do motorista

function SitFC() {
    if( document.cookie.indexOf('PC=2')==-1){
            alert("Porta do Carona Fechada");
    }
    else{
        alert("Porta do Carona Aberta");
    }
}
//Para verificar a situação da porta do carona

function SitTE() {
    if( document.cookie.indexOf('TE=3')==-1){
            alert("Porta Traseira Esquerda Fechada");
    }
    else{
        alert("Porta Traseira Esquerda Aberta");
    }
}
//Para verificar a porta traseira esquerda

function SitTD() {
    if( document.cookie.indexOf('TD=4')==-1){
            alert("Porta Traseira Direita Fechada");
    }
    else{
        alert("Porta Traseira Direita Aberta");
    }
}
//Para verificar a situação da porta traseira direita

function SitM() {
    if( document.cookie.indexOf('M=5')==-1){
            alert("Porta Malas Fechada");
    }
    else{
        alert("Porta Malas Aberto");
    }
}
//Para verificar a situação do porta malas

</script>
</body>
</html>

<html>
<head>
    
    <input type='button' value= "Situação do Carro" onclick='(SitFM() + SitFC() + SitTE() + SitTD() + SitM())'/> <p>
    
<body>
<script>

function SitFM() {
    if( document.cookie.indexOf('PM=1')==-1){
            alert("Porta do Motorista Fechada");
    }
    else{
        alert("Porta do Motorista Aberta");
    }
}
//Para verificar a situação da porta do motorista

function SitFC() {
    if( document.cookie.indexOf('PC=2')==-1){
            alert("Porta do Carona Fechada");
    }
    else{
        alert("Porta do Carona Aberta");
    }
}
//Para verificar a situação da porta do carona

function SitTE() {
    if( document.cookie.indexOf('TE=3')==-1){
            alert("Porta Traseira Esquerda Fechada");
    }
    else{
        alert("Porta Traseira Esquerda Aberta");
    }
}
//Para verificar a porta traseira esquerda

function SitTD() {
    if( document.cookie.indexOf('TD=4')==-1){
            alert("Porta Traseira Direita Fechada");
    }
    else{
        alert("Porta Traseira Direita Aberta");
    }
}
//Para verificar a situação da porta traseira direita

function SitM() {
    if( document.cookie.indexOf('M=5')==-1){
            alert("Porta Malas Fechada");
    }
    else{
        alert("Porta Malas Aberto");
    }
}
//Para verificar a situação do porta malas

</script>
</body>
</html>
