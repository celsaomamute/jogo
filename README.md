# jogo
<html>
<head>
  <center><center>
<title>Jogo da Velha</title>
<style type="text/css">
<!--
.bla{
width: 100px;
height: 100px;
background: #99ccff;
font-size: 90px;
color: #f000;
cursor: pointer;
}
.ble{
background: #000066;
}
-->
</style>
<script language="JavaScript" type="text/javascript">
<!--
letra = "X";
 
function joga(celula){
    celulaclicada = document.getElementById(celula).innerHTML;
   if (celulaclicada == "X" || celulaclicada == "O"){
       alert("Opa, este quadrado já foi escolhido!");
   }else{
        document.getElementById(celula).innerHTML = letra;
        if (letra == "X"){
            letra = "O";
        }else{
            letra = "X";
        }
   }
}
 
function verif(){
   c11 = document.getElementById('cel11').innerHTML;
   c12 = document.getElementById('cel12').innerHTML;
   c13 = document.getElementById('cel13').innerHTML;
   c21 = document.getElementById('cel21').innerHTML;
   c22 = document.getElementById('cel22').innerHTML;
   c23 = document.getElementById('cel23').innerHTML;
   c31 = document.getElementById('cel31').innerHTML;
   c32 = document.getElementById('cel32').innerHTML;
   c33 = document.getElementById('cel33').innerHTML;
   if (((c11 != '') && (c12 != '') && (c13 != '') && (c11 == c12) && (c12 == c13)) || ((c11 != '') && (c22 != '') && (c33 != '') && (c11 == c22) && (c22 == c33)) || ((c11 != '') && (c21 != '') && (c31 != '') && (c11 == c21) && (c21 == c31)) || ((c21 != '') && (c22 != '') && (c23 != '') && (c21 == c22) && (c22 == c23)) || ((c31 != '') && (c32 != '') && (c33 != '') && (c31 == c32) && (c32 == c33)) || ((c12 != '') && (c22 != '') && (c32 != '') && (c12 == c22) && (c22 == c32)) || ((c13 != '') && (c23 != '') && (c33 != '') && (c13 == c23) && (c23 == c33)) || ((c31 != '') && (c22 != '') && (c13 != '') && (c31 == c22) && (c22 == c13))){
       alert('VocÃª ganhou! ParabÃ©ns campeÃ£o!');
      novo();
   }
}
 
function novo(){
    for (i=1; i<4; i++){
       for (j=1; j<4; j++){
          nomecelula = 'cel' + i + j
           document.getElementById(nomecelula).innerHTML = '';
      
      }
   }
}
 
 
//-->
</script>
 
</head>
<body>
<table class="ble">
 
<tr>
<td align="center" valign="middle" id="cel11" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel12" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel13" class="bla" onclick="joga(this.id);verif();"></td>
</tr>
 
<tr>
<td align="center" valign="middle" id="cel21" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel22" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel23" class="bla" onclick="joga(this.id);verif();"></td>
</tr>
 
<tr>
<td align="center" valign="middle" id="cel31" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel32" class="bla" onclick="joga(this.id);verif();"></td>
<td align="center" valign="middle" id="cel33" class="bla" onclick="joga(this.id);verif();"></td>
</tr>
 
</table>
<br><input type="button" name="limpar" value="Novo jogo" onclick="novo();" />
<center>
</body>
</html>
