# INF1337-POO
##Batalha Naval<br />
Programação orientada a objeto, PUC-Rio<br />
Puc rio, teste de Software <br />
Professor Ivan Mathias Filho<br /><br />

Grupo: <br />
João Pedro Garcia<br />
Tatiana Magdalena<br />

###Grau: 10.0/10.0

##Carregando a aplicação:

O projeto deve ser aberto no Eclipse (versão de desenvolvimento: Neon.1a Release (4.6.1)).<br />
A função main está localizada no arquivo BatalhaNaval.java, dentro do pacote utils.<br />

##Iniciando um novo jogo:

###1) Tela inicial

Nomes default de “Jogador 1” e “Jogador 2” são apresentados.<br />
Insira o nome dos dois jogadores.<br />
Clique em começar para ir para a tela de posicionamento de armas.<br />

###2) Tela de posicionamento de armas

Para girar uma peça, clique com o botão direito do mouse sobre ela ainda na lista de armas não posicionadas.<br />
Para selecionar uma peça, clique com o botão esquerdo do mouse sobre ela.<br />
Para posicionar uma peça selecionada, clique sobre o tabuleiro à direita. A coordenada clicada será a coordenada inicial da peça.<br />
Caso deseje desistir de uma peça que está selecionada, aperte a tecla ESC.<br />
Caso deseje desistir do posicionamento de uma peça já no tabuleiro, clique com o botão direito sobre ela e ela retornará para a lista de armas não posicionadas.<br />
O botão de “Pronto!” será habilitado somente quando todas as peças estiverem posicionadas para aquele jogador.<br />
Caso seja o primeiro jogador, o botão de “Pronto!” levará para a tela de posicionamento do segundo jogador.<br />
Caso seja o segundo jogador, o botão de “Pronto!” levará para a tela de batalha, já preparada para o início do ataque do primeiro jogador.<br />

###3) Tela de batalha

Dois tabuleiros são apresentados.<br />
Tabuleiro do Jogador: <br />
À esquerda, apresenta os tiros que o jogador ativo já levou (cor vermelha indica tiro certo e cor azul escuro indica tiro na água). Ao passar o mouse por cima do tabuleiro, apresenta o posicionamento de suas próprias armas. <br />
Tabuleiro de Ataque:<br />
À direita, apresenta os tiros que o jogador ativo já fez no jogador adversário (cor vermelha indica tiro certo e cor azul escuro indica tiro na água). <br />

A cada rodada um jogador deve dar 3 tiros, que consiste em clicar com o botão esquerdo do mouse na coordenada desejada do tabuleiro de ataque. Dois resultados possíveis são esperados:<br />
Tiro na água: a cor azul escuro indica o tiro realizado, e a mensagem “Atingiu água” é apresentada. A contagem de tiros restantes do jogador diminui de 1.<br />
Tiro certo: a cor vermelha indica o tiro realizado, e a mensagem de qual embarcação atingiu e a quantidade de quadrados já atingidos desta embarcação é apresentada.  Caso toda a embarcação já tenha sido atingida, a mensagem passa a ser de que “Afundou" tal embarcação. A contagem de tiros restantes do jogador diminui de 1.<br />

Quando os tiros restantes chegam a 0,  o botão de  “Próximo Jogador!” é habilitado, e a vez deverá ser passada.<br />

###4) Fim de jogo:

O jogo acaba quando um dos jogadores afunda todas as embarcações do adversário. <br />
Uma mensagem é exibida em uma caixa de dialogo informando quem foi o ganhador.<br />
Ao clicar em “Ok”, fecha-se o jogo atual, retornando à tela inicial, permitindo o recomeço de um novo jogo ou a recarga de um jogo existente.<br />


##Salvando um jogo

É possível salvar um jogo em andamento a partir de Tela de Batalha.<br />
A opção de salvar está na barra de menu, no menu Arquivo > Salvar.<br />
Uma janela abrirá para que se escolha onde deseja salvar (não colocar a extensão do arquivo, apenas o nome).<br />


##Carregando um jogo existente

É possível carregar um jogo existente até o momento que o primeiro jogador posiciona a primeira arma na Tela de Posicionamento.<br />
A opção de recarga está na barra de menu, no menu Arquivo > Abrir.<br />
Uma janela abrirá para que se escolha o arquivo que deseja abrir.<br />
