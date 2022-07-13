# passo a passo para criar repositório:book:

### **_Iniciar o Git_**

- usando o comando Git init

### **_Iniciar o versionamento_**

- Usando o comando Git add

### **_Criando primeiro commit_**

- Usando comando Git commit 

Quando estamos lidando com o terminal colocamos sempre o nome do programa na frente, então chamando pelo terminal o Git, estamos chamando comandos específicos do Git, por isso todo comando leve a palavra git na frente, e o comando especifico do Git logo após por isso (git init, git add, git commit, e assim por diante).

### **_Criando um repositório_**

1. Cria-se em sua máquina local uma pasta, com um nome que deseja (porém é aconselhável, seguir um padrão)
2. Após a pasta criada, clica com o botão direito do mouse, abrirá uma janela de opções selecione <Git Bash Here>, isso porque o Git permite lançar a partir do Windows.
3. Abrirá o git bash here, direto no diretório C, eliminando o trabalho de navegação entre as pastas.
4. Digite o comando ls para lista todas as pastas do diretório C, localize o diretório criado.
5. Digite cd + diretório criado (exemplo cd treinamento) e <enter>
6. Procure sempre trabalhar com a tela limpa, digite o comando <Ctrl>+<L>
7. Vamos criar uma outra pasta, usando o comando mkdir, essa pasta será usada durante o projetoX.
8. Digite o comando git init e <enter>, com ele estaremos inicializando o git, dentro da pasta e possibilitando o gerenciamento e o versionamento do código.
9. O próprio git apresentará uma mensagem que foi iniciado um repositório vazio no C:/pastax/pastay
10. Ponto importante ao digitar o comando ls, verá que tem um diretório com o nome .git, porém a mensagem que será apresentada é que o diretório está vazio, isso porque o diretório fica oculto, gerencial do Git, onde estão armazenados todos os códigos e objetos.
11. Para visualizar essa pasta digite o comando ls -a + <enter>, mostrará de fato que temos a pasta .git
12. Digite o comando cd .git/  + <enter> para entrar na pasta.
13. Digite o comando ls + <enter> para verificar o conteúdo da pasta.
14. Digite cd.. + <enter> para voltar um nível.
15. Lembrando, caso esteja utilizando o git pela primeira vez, ele pedirá uma configuração simples, um e-mail e o username, que seria o autor atrelado a ele. O comando para essa configuração, você digita git config --global user.email "treina.aprenda@xpto.com.br" e <enter>. Depois repita o mesmo comando git config --global username shaun + <enter>, pronto configuração inicial feita, que o git iria pedir, caso tivéssemos deixado de lado.
16.  Digite git add * 
17. Digite commit -m "commit inicial" , são os objetos do commit que dão significado as alterações, é esse texto que colocaremos entre aspas dupla, internamente o texto carregará informações importantes como data, autor, hora de criação do commit.
18. Digite o comando git status para verificar a existência de arquivo a ser comitado na árvore.
19. 



