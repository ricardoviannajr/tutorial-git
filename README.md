Tutorial de GitHub e Git

Agora eu sei mandar o código para o github ...

Primeiro passo: Instalação do git
Para começar tudo, precisamos começar a nossa instalação do git, e ele pode ser feito através do link: Git

O que é o git?
Git é nossa ferramenta de controle de versionamento, ou seja, através dela, vamos conseguir ter todo um histórico de mudanças do nosso código, além de outras ferramentas muito úteis, principalmente se estamos falando de código em empresas com muitos funcionários!

Configurações iniciais do git
Nosso primeiro passo é configurar nosso git para conectar com nossa conta aqui do github!

Para isso vamos digitar no nosso Git Bash (ou terminal de sua preferência):

 git config --global user.name 'seunomedeusuariodogithub'
 
e

 git config --global user.email 'seuemaildogithub'
Começando um repositório vazio no github
Para nosso projeto estamos considerando que começaremos esse projeto do zero, ou seja, não possuimos nenhum código em nossa máquina, e que ele ainda será desenvolvido.

Para criar nosso repositório precisamos ir ao nosso perfil do github, clicar em Repositories e no botão verde escrito New

Assim que preencher o nome do repositório, basta clicar em Create repository

Clonando um repositório
Agora precisamos trazer esse repositório que estava apenas no nosso github, para a nossa máquina também!

Para isso faremos no terminal:

git clone 'link do repositório'
Após isso vamos perceber que aparecerá uma pasta no nosso computador com o mesmo nome do Github, e dentro dela vamos ter uma pasta .git

Essa pasta .git ficará na nossa pasta principal e não vamos mexer nela!

Criando um arquivo que vamos mandar para o Github!
Agora chegou a hora de botar a mão na massa e mandar um arquivo para nosso github! Para isso vamos abrir nosso VS Code, e abrir nele nossa pasta que clonamos do Github!

Depois de abrir essa pasta, vamos criar um arquivo Readme.md

Com isso já conseguimos ter um arquivo para mandar para o github

Para isso vamos seguir três passos principais:

 git add .
ou
 git add nomedoarquivo
Com esses comandos você pode tanto adicionar todos os arquivos que existir (com git add .), ou adicionar um arquivo apenas, usando o segundo comando. Isso faz com que as mudanças fiquem na área de stagging

Depois isso faremos o nosso commit

 git commit -m 'mensagem que descreve brevemente o que você fez'
O commit serve basicamente para mandar nossa mudança com uma mensagem, que descreve de forma breve as alterações que aconteceram naquele codigo que você está mandando!

O último passo é dar o empurrão final para o nosso código subir para o github, para isso vamos usar o comando

 git push -u origin main
E tchanan! Se atualizarmos nosso navegador, vamos ver as mudanças refletidas no repositório aqui no Github!
