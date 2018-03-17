## Acessando a Pasta
cd C:/xampp/htdocs/cursogit

## Inicializando o Repositório
git init

## Criando o arquivo.txt
touch arquivo.txt

## Abrindo o arquivo pelo vim para inclusão de conteúdo por comando
vim arquivo.txt

## Saindo do Vim
Pressionar <CTRL-C> no modo de edição do vim, digite :wq! para sair e salvar

## Commit
### Verificando status do commit
git status

### Para deixar o arquivo pronto para commitar, segundo estágio
git add arquivo.txt

### Está no terceiro estágio, já entrou no repositório e foi comitado
git commit -m "Meu primeiro Commit"

## PUSH
 git remote add origin https://github.com/marciotrisotto/cursogit.git
 git push -u origin master
