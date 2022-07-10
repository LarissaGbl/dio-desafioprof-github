# DIÁRIO DA APRENDIZAGEM - BOOTCAMP Santander Code Girls

### DIA 3

No terceiro dia, iniciei o curso de **Introdução ao Git e aoGitHub**, ainda do **Módulo 1**. Entendi que Git é um sistema distribuído seguro, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo. Ele conecta o ambiente de desenvolvimento com o servidor, no caso, GitHub, uma forma de nuvens de projetos.

### Comandos básicos:

**dir ou ls**: listagem de conteúdo dentro de uma pasta.

**cd**: navegar entre pastas.

**cd ..**: sair da pasta, volta um nível.

**clear ou Ctrl+L**: limpa a tela.

**Tab**: auto completa os comandos.

**mkdir + nome**: criar uma pasta.

**echo**: printa algo no terminal.

**echo > doc** redireciona algo para um doc.

**rm -rf**: remove -recursivo (deleta todas as pastas dentro da pasta) force (sem perguntar se é certeza)

### Tópicos fundamentais:

**SHA**: Conjunto de funções hash criptografada projetada pela NSA. Essa ação gera um conjunto de caracteres único e de identificação de 40 dígitos. É uma forma curta de representar um arquivo, e, toda vez que é alterado, gera um novo identificador.

### Objetos fundamentais:

![Git - Git Objects](https://git-scm.com/book/en/v2/images/data-model-1.png)

**Blobs:** onde os arquivos ficam guardados no git.

**Tree:** armazena blobs e aponta o tipo. Responsável por montar toda a estrutura do arquivo.

**Commit:** é o objeto que vai juntar tudo, todas as alterações.

### Iniciando o GIT e criando um commit

Passo a passo:

1.      Criar um repositório no disco local (c:/workspace)

2.      Abre o Git bash here no disco local

3.      Cd workspace

4.      Mkdir livro-receitas (criar uma pasta para um novo projeto)

5.      Cd livro-receitas

6.      Git init (mandar para o git gerenciar e inicia um repositório git na pasta)

7.      Echo > strogonoff.md (criar um arquivo dentro da pasta)

8.      Comitar o arquivo:

                Git add * (move o arquivo modificado para a starged)  
                git commit -m “comentário da ação realizada”

### Ciclo de vida

Unmodified -> modified -> stage -> commit -> unmodified

O commit envelopa todas as alterações com um significado.Move todos para unmodified novamente para iniciar o ciclo, para que eles fiquema espera de novas modificações.

### Introdução ao GIT

Como mandar um repositório local para o servidor:

1.      Criar um repositório no GitHub

2.      Copiar o link dele (https)

3.      Git remote add origin (apelido dado ao arquivo)+ colar o https do repositório

4.      Git remote -v (lista de repositório cadastrado)

5.      Git push origin master (branch – linha principal)

6.      Colocar senha

7.      Lançado no GitHub

- Para pegar a última versão do repositório: Git pull originmaster

- Clonar repositório: git clone








