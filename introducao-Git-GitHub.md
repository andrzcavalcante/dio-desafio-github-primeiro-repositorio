# Introdução ao Git/GitHub

## O que é o Git?

Criado pelo engenheiro de software Linus Torvalds, conhecido por ter desenvolvido, também, o núcleo Linux, o GIT é um *Sistema de Controle de Versões Distribuído* — ou DVCS.

 Estes sistemas de controle possuem a função de registrar quaisquer alterações feitas em cima de um código, armazenando essas informações e permitindo que, caso seja necessário, um(a) programador(a) possa regredir a versões anteriores de uma aplicação de modo simples e rápido.

 Este tipo de sistema também simplifica muito o processo de compartilhamento de um projeto com um time, por exemplo, ou com outros(as) programadores(as).

## Navegação Básica pelo Terminal

- #### Comandos Básico (Windons):

1. Listar =  "dir"- Listar diretórios.

2. Navegar entre as pastas = "cd" + usando o "/" + "Nome do diretório" dará um caminho específico.

   2.1. Para voltar para o repositório anterior usar "cd" + ".." .

3. Limpar o terminal = "cls"

4. Criar pasta = "mkdir"

5. Deletar apenas arquivos = "del" + "Nome da pasta"

   5.1. Deletar a pasta completa = "rmdir" + "Nome da pasta" + "/S" + "/Q".

## Primeiros Comandos com o Git

- "git init" - Criar o repositório.  == Acesso ao Git para começar a gerenciar e versionar o código.

- "ls -a" - Listar arquivos ocultos.

- #### Caso seja sua primeira vez usando o Git:

  -  Inicialmente o Git pedirá um email e um nickname.
  - **Use os comandos abaixo:**
  - " git config --global user.email "exemplo@email.com" " == Usar o mesmo email do Git.
  - " git config --global user.name exemplodenickname " == Usar o mesmo nick do Git.



## Adicionando Arquivo

- Entrará na pasta referente: "cd" + "nome da pasta/"
- Para commitar o arquivo será necessário os seguintes comandos:
  -  " git add * " 
  - " git commit -m "Nome do commit" "
  - "git push origin master"

### Comandos adicionais 

- Para ver as características do arquivo use: 
  - "git status"
- Mover arquivos/pastas para outras pastas:
  - "mv + "Nome da Pasta(A que moverá)" + ./ + "Nome da Pasta(recebará o novo arq.)"  
- Criar arquivos:
  -  "echo + "Nome do Novo arquivo" "
- Visualizar todas as configurações do seu git:
  - "git config --list"
- Para pegar um repositório do GitHub e passar para sua máquina:
  - " git clone + url do repositório"

**Vimos alguns comandos básicos para darmos os primeiros passos no Git/GitHub**

**Agora é com você, aprofunde no tema e não deixe de praticar** :wink:







​	





 
