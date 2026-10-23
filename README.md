#Este repositório tem como objetivo o aprendizado e treino de git e github. 

Seguindo os seguintes tutoriais:
  1. https://youtu.be/FF1f4bKYhoo?si=dJKS0uPaBifIiZHX
  2. https://www.youtube.com/live/xEKo29OWILE?si=KWfN7o5pZyUlVUpa

Com grande foco na parte prática, para entender com completude como funcionam git e github e como o ecossistema se conversa.

############

Aqui, vou tomar a liberdade de fazer minhas anotações de estudo, de forma que seja mais prático para mim entender. 

Git: 
- Git é um software de versionamento. 
- Criando uma nova pasta, abra o terminal e de o comando git init. Com isso, uma pasta oculta será criada e lá é onde será armazenado as informações de versionamento dos seus arquivos.
- Quando você criar os arquivos partindo do zero, você precisa realizar o primeiro commit. O commit é como se fosse um save de jogos de videogame, que você sempre pode voltar se algo de ruim acontecer depois.
- Sempre que você alterar alguma coisas nos arquivos você precisa adicionar isso com git add e depois realizar um commit para deixar salvo.
- Também é possível criar uma ou mais branch, que são linhas paralelas da linha do tempo principal, e com isso você pode trabalhar com várias frentes sem alterar o projeto principal.
- É possível dar um merge entre as branches criadas, e caso existe conflito, é preciso que você resolva os conflitos e depois dê o merge, que significa unir a branch main ou master com a branch paralela que você estava trabalhando.
- O .gitignore só funciona para arquivos que ainda não foram rastreados. Se você já deu git add e git commit em um arquivo e só depois colocou o nome dele no .gitignore, o Git ignorará a regra e continuará versionando esse arquivo.

- Comandos git utilizados:
- git log
- git log --graph --all
- git log --oneline
- git status
- touch nome_arquivo
- git branch
- git commit -m "nome_branch"
- git diff
- git reset HEAD
- git checkout -b nome_branch
- git commit -am "nome_branch"



Github: 
- Github é uma rede social e um repositório remoto. As pessoas criam perfis, podem colocar seus códigos lá e também interagir e contribuir com os códigos de outras pessoas.  
- O que é FORK: Quando você via no perfil de outra pessoa, você pode ver os repositórios que ela tem lá. Com isso você pode realizar um FORK do projeto da pessoa, que é uma cópia do projeto que vai para o seu github. Assim, você tem uma cópia do repositórioa da outra pessoa para poder trabalhar e caso você faça uma alteração e queira enviar para o código principal original, você pode realizar um commit e um pull request e enviar sua alteração para o dono original do repositório.


Assim, o git é um repositório local, um software que fica na sua máquina, que consegue versionar seus arquivos. E, o github, é um repositório remoto e uma plataforma de colaboração de código. Os dois juntos, e mais uma IDE de código, te auxiliam nos projetos tanto pessoais quanto nos projetos colaborativos.
Pois é possível trabalhar na sua IDE e assim, realizar os commits tanto para o git quanto para o github. 

Alguns concorrente do git, que tb são VCS: Mercurial, Apache Subversion ...
Alguns concorrente do github, que tb são repositórios remotos: gitlab, bitbucket ...


#############
