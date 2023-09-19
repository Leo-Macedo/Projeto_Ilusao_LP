# Projeto Ilusão LP
# Leonardo Macêdo Aurieni<br>
# Jogo: A esperança através da música
# Link do projeto
https://drive.google.com/drive/folders/1JZxPayNxYY8WdZzjUF_dLpO7Vy5q926A?usp=sharing <br>
# Música: Ilusão - MC Hariel, MC Ryan SP, MC Davi, Djay W, Salvador da Rima e  DJ Alok
A música que é um funk, estilo musical que ganha cada vez mais espaço na cena, busca alertar e conscientizar as pessoas sobre problemas do nosso cotidiano, sem, é claro, deixar de apresentar à população as virtudes da periferia, com mensagens de alerta, esperança e fé. <br>
# Música: Saudades Mil - 509-E
Palavras de Afro-X: “'Saudades Mil' é uma música sobre sentir falta. Bate forte no coração do vagabundo.” <br>
A música relata a história de um homem que foi preso, que recebe uma carta e fica com muita saudades de amigos e família. Como a música ilusão, também foi feita para conscientizar sobre como a vida é. <br>
## Descrição do jogo
O jogo passa em uma comunidade onde o homem tem que fugir do policial por ter cometido coisas ilegais. Após ser preso, recebe uma carta com perguntas e tem que responder todas corretamente para ficar livre da prisão.<br>
# Como Jogar
<img src = "img/1.jpg"><br>
# GameObjects usados
Peguei todos da loja de assets, a prisão eu modelei no Bender 3D e os texto do própio Unity.
<img src = "img/2.png"><br>
# Cena 1 - Menu
<img src = "img/3.jpg"><br>
<img src = "img/4.png"><br>
Criei dois métodos, o jogar é para o botão 'play' onde quando eu clicar irá para a cena2. E o sair é para fechar a aplicação. Na função OnClick criei um empty, adicionei o script e arrastei na função, para selecionar o método. Nos botões adicionei uma imagem. Coloquei um panel e adicionei uma imagem para ficar de fundo.<br>
# Cena 2 - Fase 1
## Personagem
<img src = "img/5.png"><br>
No personagem adicionei scripts simples para mocimentação, rotação de câmera e 'congelar' ele para não tombar.<br>
## Policial
<img src = "img/6.png"><br>
No policial coloquei um script para ele andar para frente automático, e outro para quando colidir com o personagem ir para a cena 3, ativei a opção is trigger para ele atravessar os objetos e desativei a gravidade pois se não ele atravessaria o chão.<br>
# Cena 3 - Fase 2
















## Diagrama de Classes
<img src = "img/classe.jpg" > <br>
<h3> Descrição </h3>

Esse digrama de classes é sobre o jogo uma nova vida, onde tem as classes: Boneco; Carta; Jogo; Cela e Polícia.<br>
Onde a classe Boneco se relaciona com o Jogo que sem o Jogo ela não existe, e com a Polícia, que é uma relação simples onde o Polícia tem que prender o Boneco.<br>
A classe Carta se relaciona com o Jogo que sem ela o Jogo não existe. A relação com a cela é que precisa da Carta mas existe sem ela.<br>
Polícia tem um relacionamento simples com Cela onde ela usufuri para prender o Boneco.<br>

<h2>Diagrama de Casos de Uso</h2>
<img src = "img/uso.jpg" ><br>
<h3>Documentação</h3>
<img src = "img/documentacao.jpg" ><br>
<h3>Diagrama de atividade (prender o jogador) </h3>
<img src = "img/atividade.jpg" >
