<h1>Aula 01 - Instalando e testando o TIC-80</h1>

* O primeiro passo para criar o nosso jogo "Fuga das Sombras" é baixar a ferramenta que vamos usar durante o curso. Você pode acessar o site da TIC e baixar a versão correspondente ao seu sistema operacional:

* Depois de fazer o download, descompacte o TIC-80 para a pasta de sua preferência e depois execute ele com um duplo clique no arquivo tic80. Se tudo deu certo, você deve ver a animação de abertura e, em seguida, estará no console. Para ter certeza que está funcionando, digite o comando run no console e pressione a tecla ENTER. Isso vai executar o jogo que vem na memória do TIC-80, que mostra um robozinho piscando com a mensagem "Hello world". Para voltar ao console, basta apertar a tecla ESC.

* Por padrão, o TIC-80 guarda todos os jogos em uma pasta própria geralmente de difícil acesso. Isso dificulta nosso trabalho, por isso iremos mudar a pasta padrão executando o TIC-80 pela linha de comando (terminal), que pode ser da o da sua preferência. Depois, navegue até a pasta na qual você descompactou o TIC-80 e digite o comando ./tic80 seguido do caminho para pasta que você quer utilizar para salvar os seus jogos. Por exemplo, no Linux ou MacOS:

* ./tic80 ~/Jogos/
* Caso você tenha problemas ao executar o TIC-80 no Linux ou MacOS, talvez seja necessário instalar algumas dependências. Você pode seguir as instruções no link a seguir: https://github.com/nesbox/TIC-80/wiki/build-instructions

* Para o Windows, é necessário informar o caminho completo de preferência entre aspas para evitar ter problemas com espaços nos nomes das pastas. Certifique-se também de criar a pasta no Windows antes de executar o TIC-80:

* tic80.exe "C:\Jogos"
* Legal! Sempre que quiser saber onde o TIC-80 está salvando os jogos, basta digitar o comando folder no console e ele abrirá a pasta referente e mostrará os arquivos que estão salvos ali.

* Agora que o TIC-80 está instalado e testado, só falta criar o projeto que vamos usar durante o curso. No console, digite o comando new lua para criar um novo jogo usando a linguagem Lua. Depois, digite save fuga.tic para salvar esse novo projeto com o nome fuga.tic. Para saber se funciona corretamente, digite novamente o comando folder e confira se agora existe o arquivo fuga.tic na pasta exibida.

* Toda vez que você iniciar o TIC-80 e quiser continuar trabalhando no seu jogo, digite o comando load fuga.tic para carregar o seu jogo.

* Pronto! Agora, continue assistindo as próximas aulas e construa seu próprio jogo.