# JogoTrex
## Trex criado até a aula 17 
- No meu jogo a primeira coisa que eu criei foram as minha variáveis do trex e do solo. 
~~~javascript
var trex, imgTrex; 
var solo, imgSolo;
~~~
- Fiz o upload de todas as imagens 
~~~javascript 
function preload(){
  trex_correndo =   loadAnimation("trex1.png","trex3.png","trex4.png");
  trex_colidiu = loadAnimation("trex_collided.png");
  
  imagemDoSolo = loadImage("ground2.png");
 }
 ~~~
- Criei a sprite do solo e do trex fazendo ele `collide` no solo. 
- 
<img align="right" alt="StefaneAL" height="230" width="220" src="https://media.giphy.com/media/dxODB9UE879RDqAh3o/giphy.gif">

