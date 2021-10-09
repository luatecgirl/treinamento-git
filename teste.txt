1. Criar uma pasta no seu PC
2. Abrir o git bash (windows) ou o terminal (linux/mac) nessa pasta
3. Dar git init para iniciar o git na pasta
4. Fazer "code .gitignore" para colocarmos o lixo em um arquivo (vai abrir o vscode automaticamente no arquivo .gitignore
5. Ir no site [https://www.toptal.com/developers/gitignore](https://www.toptal.com/developers/gitignore) e colocar: "windows", "linux" e "macOS" e criar o arquivo
6. Copiar o código gerado pelo site para o arquivo .gitignore
7. voltar para o gitbash/terminal, e digitar ' git add .gitignore '
8. Digitar ' git status ' - vai aparecer o .gitignore em verde, e o teste.txt em vermelho
9. Fazer o commit do .gitignore - ' git commit -m "ignorando logs com o arquivo .gitignore" '
10. Adicionar o restante dos arquivos da pasta em outro commit - ' git add . '
11. Fazer o commit desses arquivos - ' git commit -m "mensagem" '
12. Ver o histórico de alterações, com as chaves dos commits - ' git log '
13. Histórico com preview - mostra as alterações dos arquivos - ' git log -p '
14. Ir no github, adicionar um novo repositório chamado 'treinando-git'
15. Seguir as instruções da parte "or push an existing repository from the command line" -- copiar as três linhas no terminal