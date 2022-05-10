# desafio-dio-github-repositorio
# Anotações Git/Github

- GIT

- Controle de versionamento de códigos .

- GIT HUB Repositório online onde se armazena o código ou projetos .

  - controle de versão
  - 2 - armazenamento em nuvem 
  - 3 - trabalho em equipe
  - 4 - melhorar seu código
  - 5 - reconhecimento. 

  ###   Navegação no Terminal

  - cd  ( navegar pela pastas ) 

  - dir   (lista todas as pastas) 

  - mkdir ( criar diretórios e pastas ) 

  - de/ rmdir (deletar os sistemas)

  - cls   ( limpar a tela) 
   
  - Tecla TAB (Alto Completa a digitação)
   
  - cd ..  (sair da pasta )

  - 

     ### Funcionamento por baixo dos panos

  - SHA1 

  - Objetos fundamentais

  - Sistema Distribuído

  - Segurança

     ### Objetos Básicos do Git Responsáveil pelo Versionamento dos Códigos.

  - BLOBS
  - TREES 
  - COMMITS 

  ### Gerar par de Chaves

  ssh-keygen -t ed25519 -C  seu email do github

  **Local da chave **
  Generating public/private ed25519 key pair.

  Enter file in which to save the key (/c/Users/****************/.ssh/id_ed25519):****

  

  ### Consultar Chaves Existentes 

  $ ls -al ~/.ssh

  **comando para monstrar arquivos ocultos no GIT**

  ls -a   

  **Definir seu email e nome de usuario no Git**

  git condig --global user,email "Seu email "

  git condig --global username "Seu nome "

  ### Adicionar ao git hub 

  git add *  

  git commit -m "msg"
  ### Criar um novo repositório

  Para **criar** um novo **repositório**, você vai usar o **comando git init** . **git init** é um **comando** único que você usa durante a configuração inicial de um novo **repositório**. A execução desse **comando** cria um novo subdiretório . **git** no diretório de trabalho atual. comando git status  ajuda monitorar  status dos arquivos .

  ### Para mover um arquivo

  É ultilizado o comando "MV" 
  ### consultar lista de usuário cadastrado

  git config --list

  ### Remover um e-mail e senha cadastrado.

   git config --global --unset user.email

   git config --global --unset user.name


  =====================================
