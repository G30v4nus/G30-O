esboço.js
1
função setup () { 
2
  criarCanvas ( 600 , 600 );
3
   fundo ( "branco" );
4
}
5
​
6
​
7
função  draw () {
8
  
9
  AVC ( "azul" );
10
  preencher ( "vermelho" );
11
 
12
  
13
  // console.log(mouseIsPressed);
14
  
15
  se ( mouseIsPressed ) {
16
    retângulo ( mouseX , mouseY , 20 , 35 );
17
  
