# Minhas anotações sobre - Git e GitHub: #

1. Baixar o Git.
2. Criar uma conta no GitHub.
3. Criar uma "linha do tempo main" usando o Git na pasta do meu projeto.
4. Upar o projeto com o Git para o GitHub.
5. Trabalhar no projeto pelo GitHub e localmente.
6. O Git fara o versionamento do codigo.


## Comandos do Git: 

```powershell
cd [link_do_projeto] (C:/local/do/meu/projeto) #Vá ate a pasta do seu projeto!

git init #Inicie o Git no seu projeto.

git add . #Obtenha o seu projeto.

git commit -m "Seu commit..." #Escreva o seu commit, descrição breve da sua modificação.

git branch -M main #Defina como sua "linha do tempo" principal.

git remote add origin [link_do_repositorio] (https://github.com/Sr-M4rkoz/projeto) #Defina a origem para onde seu projeto vai ser mandado. (seu repositorio no Github)

git push -u origin main #Envie o projeto para o repositorio.
```