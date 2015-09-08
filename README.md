# Documentos
Documentos de ajuda

Adicionando um projeto existente ao Bitbucket

1 - Deve trasnsformar o projeto em projeto para versionamento
Para isso deve acessar o CMD e ir até o diretório do projeto e digitar "Git Init"
Com isso ele criar o arquivo ".git"

2 - Deve-se criar o arquivo ".gitignore" 
Na pasta do projeto crie um arquivo .txt, mas renomeio para ".gitignore.", não esqueça do ponto no final
Depois adicione o texto de acordo com o que você for usar (https://github.com/github/gitignore)
Maven, Eclipse e etc

3 - Crie o repositorio no bitbucket

4 - Selecione a opção "I have an existing project"

5 - no CMD digite o que o bitckut pedir
- git remote add origin git@bitbucket.org:..nameuser../..namerepositorio..
- git push -u origin --all # pushes up the repo and its refs for the first time
- git status
- git add .
- git commit -m"meu primeiro commit"
- git push -u origin --all

/-  http://www.mateuspaduaweb.com.br/versionando-com-o-git-utilizando-o-bitbucket-como-repositorio-remoto/ -/
