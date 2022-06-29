# Resumo GIT e GITHUB

**Resumo compilado das aulas de GIT e GITHUB da DIO e StartSe** 

# O formato usará o resumo das aulas da StartSe, porém como a DIO abordou questões importantes de segurança, então esse conteúdo será acrescentado.

StartSe

Aula 1 Introdução

- PDF
    
    [1-modulo-vi-introducao-ao-git.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1-modulo-vi-introducao-ao-git.pdf)
    
- Principais controladores de versão
    
    [Apache Subversion](https://subversion.apache.org/)
    
    [Mercurial SCM](https://www.mercurial-scm.org/)
    

### Controle de versão

- Nos dá uma linha do tempo do projeto (Timeline).
- Trabalha com alteração de estados do arquivo.
- Cada estado, chamamos de snapshot.
- Cada mudança realizada em um arquivo aumenta a sua versão.
- Podemos ter modificações paralelas.
- Possibilita recuperação para qualquer estado anterior.
- Podemos comparar documentos com características diferentes.
- Exemplo de linha do tempo
    
    ![temp.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/temp.jpg)
    

---

# Aula 2 Configuração do ambiente

- Instalação e documentação :
    
    [Documentation](https://git-scm.com/doc)
    
    [Downloads](https://git-scm.com/downloads)
    
    [GitHub Desktop](https://desktop.github.com/)
    
- PDF e material
    
    [2-modulo-vi-configuracao-do-ambiente.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2-modulo-vi-configuracao-do-ambiente.pdf)
    
    [](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f33bd948-c45b-4cba-b651-a2d0283f5785/2-tutorial-instalacao-gitbash-no-windows.docx)
    

### Para ver se o git está instalado e a versão:

```bash
git version
```

### Vamos realizar a configuração do git bash

```bash
#Vamos abrir o git bash
#Para configurar o nosso nome:
git config --global user.name "Hugo"

#Para configurar o email:
git config --global user.email "hugodiscord@outlook.com"

#Por configurar a branch
git config --global init.defaultBranch main

#OBS
#->Para saber se as configurações estão setadas use:
git config --list
```

### Após abrir o diretório que queremos, vamos controlar a versão  com git

```bash
#O comando para iniciar o git a partir do diretório é:
git init
```

---

# Aula 3 Aula Ciclo de vida dos arquivos, commits e branches

- PDF
    
    [3-modulo-vi-ciclo-de-vida-dos-arquivos-commits-e-branches.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/3-modulo-vi-ciclo-de-vida-dos-arquivos-commits-e-branches.pdf)
    

### Git possui 4 status (ciclos) para arquivos

1. Untracked → O git não conhece a existência do arquivo em nenhuma versão (Default).
2. Staged → Arquivos que estão prontos para serem inseridos em um novo estado da aplicação (Novo Snapshot).
3. Unmodified → Indica arquivo que não sofreu nenhuma modificação em relação a ultima versão.
4. Modified → Indica arquivos que sofreram alteração em relação a ultima versão.

### Comando para ver o status dos arquivos

```bash
#Num primeiro momento todos os arquivos estarão como untraked
git status
```

### Comando para adicionar o arquivo para estado 2 Staged

```bash
#Para subir arquivo especifico:
git add nome_do_arquivo

#Caso a intenção seja adicionar todos, vamos usar o *
git add *

#OBS
#Podemos voltar o arquivo para o estado anterior com:
git reset nome_do_arquivo
```

### Comando para adicionar para o estado 3 Unmodified

```bash
#Vamos fazer um comentario indicando a mudança realizada com:
git commit -m "comentario_entre_as_aspas"
```

### Para verificar os commits realizados no nosso código vamos usar:

```bash
#Comando para verificar quantidade de commits e as branchs utilizadas.
git log
```

### Branch

- Gera ramificações do fluxo principal de trabalho.
- As ramificações geradas podem ser trabalhadas isoladamente.
- Após modificações faremos um merge para associar a linha do tempo principal.
- Exemplo
    
    ![Screenshot_1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1.jpg)
    

### Para criar nova branch:

```bash
git branch nome_da_branch
```

### Para alterar a nossa branch de trabalho usaremos

```bash
git checkout nome_da_branch
```

Para associar o trabalho da branch que criamos a linha do tempo principal usamos:

```bash
git merge nome_da_branch
```

---

# Aula 4 Branches na prática

- PDF
    
    [4-modulo-vi-branches-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/4-modulo-vi-branches-na-pratica.pdf)
    

### Observações:

- Quando criamos uma branch o projeto será salvo na posição que estamos.
- Todas as modificações geradas numa branch são ignoradas por outras.

### Para sabermos em qual branch estamos usamos :

```bash
#Esse comando vai mostrar a branch que estamos trabalhando.
#Também demostra todas as oturas banchs criadas no projeto.
git branch
```

### Para subirmos a modificação da branch para a principal vamos usar:

```bash
git merge Nome_da_branch

#OBS:
#Quando fazermos um merge o git gera um commit automático informando a mudança.
	#O commit será aberto no editor de texto para editarmos.

#Caso a nossa mudança impact alguma funcionalidade, o git irá nos informar.
	#Em caso de impacto, teremos a opção de escolher o que será mantido/descartado.
```

### Para deletar uma branch vamos usar:

```bash
git branch -d nome_da_branch
#OBS
#Geralmente depois de cumprida a finalidade, deletamos a branch
#Geralmente não fazemos commits da branch main diretamente.
```

---

# Aula 5 Reset e diff na prática

- PDF
    
    [5-modulo-vi-reset-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/5-modulo-vi-reset-na-pratica.pdf)
    

### DIFF

- Vai mostrar a diferença entre o arquivo atual e o estado anterior.

<aside>
💡 OBS:

Lembrando que o comando funciona em arquivos em staged (Quando foi feito o “git add”).

</aside>

### Para vermos a diff entre arquivos usamos:

```bash
#Nesse caso vamos ver todas as diferenças realizadas (Multiplos arquivos).
git diff

#Neste outro caso vamos ver as modificações de apenas um arquivo.
git diff nome_do_arquivo
```

### Para voltarmos ao estado anterior a modificação vamos usar:

```bash
#Iremos indicar o nome do arquivo para voltarmos ao ponto anterior a mudança.
git checkout nome_do_arquivo
```

### Reset

- Usado para voltar para o estagio anterior
- Pode ser usado de forma diferente dependendo do estado do arquivo.

### Uso do reset na fase “staged” (Depois do “git add”)

```bash
#Caso tenhamos deixado passar mudança para staged vamos ter de resetar o estado
#O comando para reset para estado anterior é:
git reset nome_do_arquivogit reset nome_do_arquivo
```

### Uso do reset na fase “unmodified” (Depois do “git commit”)

<aside>
💡 OBS:

1° - Termos que copiar o id do commit anterior antes de realizar o reset.

```bash
#Vamos pegar o id do commit anterior com:
git log

#Depois de aparecer todos os IDs, vamos copiar o que queremos voltar.
```

</aside>

> Aqui vamos ter 3 formas diferentes de reset:
> 
> - Reset soft (Podemos fazer commit novo)
>     
>     ```bash
>     #Volta po arquivo para fase de staged
>     git reset --soft  nome_do_commit_anterior
>     ```
>     
> - Reset mixed (Podemos fazer novo git add)
>     
>     ```bash
>     #Volta o arquivo para fase de modified
>     git reset --mixed  nome_do_commit_anterior
>     
>     #Podemos fazer a diff da modificação com o conteúdo anterior 
>     #Antes de fazer o "git add"
>     ```
>     
> - Reset hard (Desfaz tudo e volta ao estado do commit anterior)
>     
>     ```bash
>     #Vai desfazer qualquer mudança realizada desde o commit anterior.
>     git reset --hard  nome_do_commit_anterior
>     ```
>     

---

# Aula 6 GitHub, Gitlab e bitbucket

- PDF
    
    [6-modulo-vi-github-gitlab-e-bitbucket.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/6-modulo-vi-github-gitlab-e-bitbucket.pdf)
    
- Páginas úteis
    
    [GitHub: Where the world builds software](https://github.com/)
    
    [The One DevOps Platform | GitLab](https://about.gitlab.com/)
    
    [Bitbucket | Git solution for teams using Jira](https://bitbucket.org/)
    

### Podemos mandar nossas modificações locais para um repositório na nuvem

![1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1.jpg)

---

# ****Aula 7 GitHub na Prática****

- PDF
    
    [7-modulo-vi-github-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/7-modulo-vi-github-na-pratica.pdf)
    

### Aqui vamos criar um repositório no GitHub para trabalharmos com o projeto na nuvem.

- Pegando o código do repositório da nuvem:
    
    ![1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%201.jpg)
    
- Inserindo o código no repositório local
    
    ![Screenshot_1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1%201.jpg)
    

### Para conferir se inserimos corretamente o repositório

```bash
#Para apenas ver os repositórios remotos adicionados usamos:
git remote

#Para verificar o caminho dos repositórios adicionados vamos usar:
git remote -v
```

### Agora vamos enviar nossos arquivos locais para o repositório GitHub

```bash
#Vamos usar o comando abaixo:
git push nome_do caminho branch_que_queremos_mandar

#No nosso caso fica:
git push origin main

#OBS
#Temos a opção de salvar o caminho automaticamente 
git push -u origin main
#Após salvar, apenas com o push já enviaremos os arquivos automáticamente.
```

### Caso a gente queira pegar os arquivos do projeto da nuvem

```bash
#Lembrando que temos que pegar a URL do projeto na guia "code" no GitHub.
git clone url_do_projeto

#Todos os commits e branchs irão ser carregados também.
```

---

# ****Aula 8 Pull e Push na Prática****

- PDF
    
    [8-modulo-vi-pull-e-push-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/8-modulo-vi-pull-e-push-na-pratica.pdf)
    

### Git push

- Usado para enviar arquivos para o repositório do projeto

```bash
#Relembrando a forma de subir os arquivos 
git push caminho_do_repositório branc_que_queremos_mandar
```

### Git pull

- Usado para pegar atualizações feitas no projeto (de todas as branches)

```bash
#Para pegarmos atualizações futuras feitas no código vamos usar o pull
git pull caminho_do_repositório branc_que_vamos_receber

#Vamos receber as alterações, todas as branchs e commits feitos no repositório.
```

---

# Aula 9 ****Git Merge e Rebase****

- PDF
    
    [9-modulo-vi-git-merge-e-rebase.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/9-modulo-vi-git-merge-e-rebase.pdf)
    

### Observação:

Merge e rebase são usados para unir branches

### Merge

- Adiciona novo commit na time line principal indicando a junção das branches
- Gera fork do merge pra frente.
- Visualização
    
    ![1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%202.jpg)
    

### Rebase

- Deixa a linha do tempo linear.
- Vai gerar impacto a linhas de tempo alternativas
- Visualização
    
    ![2.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2.jpg)
    

---

# Aula 10 ****Merge e Rebase na Prática****

- PDF
    
    [10-modulo-vi-merge-e-rebase-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/10-modulo-vi-merge-e-rebase-na-pratica.pdf)
    
- Extensão para ver git log no vscode
    
    [Git History - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
    

### Para trabalhar com as branches

```bash
#Para criar
git branch nome_da_branch_nova

#para trocar de branch
git checkout nome_da_branch

#Para visualizar a branch que estamos trabalhando
git branch

#Para voltar para a branch anterior 
git checkout - 

#Para criar uma branch e já mudar para ela vamos usar:
git checkout -b nome_da_branch
```

### Para visualizarmos o fluxo dos merges e rebase vamos usar:

```bash
#Esse comando ira mostrar um log mais completo com linha do tempo na esquerda.
git log --graph
```

### Merge

- Acaba criando novo commit para nos informar que foi feito mudança e que ela foi enviada para nossa linha do tempo principal.

```bash
#Lembrando o comando para mergiar
git merge nome_da_outra_branch
```

### Rebase

- Após criar uma nova branch, fazemos um rebase com a branch “main” para atualizar a nossa time line. Vai trazer tudo na ordem cronológica.
- Rebase é mais usado em branches separadas (Não usar na nossa main)

```bash
#Para fazer um rebase de informações para a branch que estamos vamos fazer:
git rebase nome_da_outra_branch
```

---

# Aula 11 ****Stash na Prática****

- PDF
    
    [11-modulo-vi-stash-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/11-modulo-vi-stash-na-pratica.pdf)
    

Observações:

- Usado para salvar o estado do nosso projeto na area temporária.
- O stash será salvo na branch que realizamos a modificação.

### Exemplo de uso do stash

```bash
#Salvará as alterações na area temporária.
git stash

#OBS:
#Também podemos incluir arquivos untracked no nosso stash. Ficaria:
git stash --include-untracked 
```

### Para consultar a lista com conteúdo stash salvos usaremos:

```bash
#Aqui teremos acesso a todas os "stash" salvos.
git stash list
```

### Para incorporar as alterações temporárias vamos usar:

```bash
#Pegando as modificações da area temporaria
git stash aply
```

### Para limpar a lista temporária vamos usar:

```bash
#Limpando lista dos "stash's"
git stash clear
```

---

# ****Aula 12 Conhecendo o .gitignore****

- PDF
    
    [12-modulo-vi-conhecendo-o-.gitignore.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/12-modulo-vi-conhecendo-o-.gitignore.pdf)
    
- Paginas úteis
    
    [GitHub - github/gitignore: A collection of useful .gitignore templates](https://github.com/github/gitignore)
    
    [Git - gitignore Documentation](https://git-scm.com/docs/gitignore)
    

### Observações:

- Delimita arquivos que não serão enviados para o repositório do nosso projeto
- O nome do arquivo deve ser posto dentro do documento “.gitignore” para ser ignorado.

### Primeiro vamos ter de criar um arquivo dentro da pasta que estamos

```bash
#O nome do arquivo vai ser ".gitignore" (Sem apastas)
#No terminal fica:
touch .gitignore

#Também podemos criar direto do VS code com botão direito "new file".
```

### Agora é só adicionar o nome do arquivo dentro do arquivo criado anteriormente.

```bash
#Se for pelo terminal fica:
vim .gitignore

#Também podemos fazer isso de forma facilitada pelo VSCode
```

---

# ****Aula 13 - Git Revert na Prática****

- PDF
    
    [13-modulo-vi-git-revert-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/13-modulo-vi-git-revert-na-pratica.pdf)
    

### Observações:

- Desfaz a alteração na time line principal.
- Mantem a alteração na branch de origem.
- Geralmente usamos para desfazer algo na branch main.

### Podemos visualizar os commits com:

```bash
#Revisando
git log
```

### Para visualizar a mudança realizada em detalhes pelo commit vamos:

```bash
#Depois de copiar o commit no git log, iremos usar:
git show nome_do_commit

#Será mostrada toda modificação que foi gerada.
```

### Para reverter vamos fazer

```bash
#Pegamos o id do commit que queremos reverter
git revert nome_do_commit_para_reverter
```

---

# ****Aula 14 Workflows com Git****

- PDF
    
    [14-modulo-vi-workflows-com-git.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/14-modulo-vi-workflows-com-git.pdf)
    

Observações:

Possibilita rotina de trabalho mais consistente e produtiva.

### Temos 3 fluxos de trabalho diferentes

### 1 - Centralized

- Todos os desenvolvedores trabalham na mesma branch main.
- Facilita para ter organização na ordem de commits.
- Geralmente usado em times muito pequenos.
- Modelo exemplo:
    
    ![Screenshot_2.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2.jpg)
    

### 2 - Feature branch

- Cada nova funcionalidade terá uma branch especifica.
- Geralmente mais usada em times grandes.
- Nesse modelo nenhum push é feito na branch main.
- Modelo exemplo:
    
    ![Screenshot_2.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2%201.jpg)
    

### 3 - Gitflow

- Cada dev vai usar um modelo estrito de branch projetada em torno do projeto.
- Modelo
    
    ![Screenshot_3.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_3.jpg)
    

---

# ****Aula 15 - Workflow Centralizado na Prática****

- PDF
    
    [15-modulo-vi-workflow-centralizado-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/15-modulo-vi-workflow-centralizado-na-pratica.pdf)
    

### Observação:

- Neste modelo de trabalho, precisamos sempre prezar pela organização da timeline.
- Antes de fazermos push, vamos ter de fazer um pull pra organizar a cronologia do nosso trabalho (Importante !).

### Primeiro vamos organizar a nossa timeline

```bash
#Nosso commit vai ficar no topo sempre.
git pull orgin main --rebase
```

### Depois de organizada, vamos fazer o push dos nossos commits

```bash
#Lembrando o comando visto anteriormente:
git push origin main
```

---

# ****Aula 16 Pull Request e Feature Branch na Prática****

- PDF
    
    [16-modulo-vi-pull-request-e-feature-branch-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/16-modulo-vi-pull-request-e-feature-branch-na-pratica.pdf)
    

### Pull requests (PR)

- Solicitação de merge de uma branch em outra branch.
- Geralmente usada para passar conteúdo de uma branch nossa para a main do nosso repositório remoto.
- O processo de solicitação request permite que a modificação do código passe por uma avaliação antes do merge.

### Fases até o pull request

1. Vamos criar uma branch da funcionalidade e fazer as mudanças.
2. Vamos fazer o git add e depois fazer o commit da mudança.
3. Vamos fazer o pull para o repositório remoto informando a branch
    
    ```bash
    git push nome_do_rep_remoto nome_da_branch_que_queremos_enviar
    ```
    
4. Agora vamos ir na página do projeto e clicar no pool request
5. Na página de request, vamos informar pra qual branch estamos querendo mandar o conteúdo.
    - Podemos fazer uma descrição do request e comentar o que foi feito
    - Podemos marcar os revisores do código (Na opção a direita).
    - Podemos fazer sugestão para melhoria dos requests
    

---

# ****Aula 17 Resolvendo Conflitos na Prática****

- PDF
    
    [17-modulo-vi-resolvendo-conflitos-na-pratica.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/17-modulo-vi-resolvendo-conflitos-na-pratica.pdf)
    
- Exemplo de conflito
    
    ![1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%203.jpg)
    

### No conflito temos 3 opções:

Accept both changes

- Vai incluir as 2 modificações paralelamente.

Accept incoming changes

- Vai  aceitar a melhoria proposta pela outra branch.

Accept current changes

- Vai  aceitar a melhoria proposta pela branch que estamos.

### Após fazer a escolha da melhor opção vamos ter de fazer o git continuar

<aside>
💡 Lembrando que o git vai salvar o conflito e isso precisa ser enviado para a time line.

```bash
#Se for rebase vamos usar
git status
```

- Precisamos adicionar o conflito no staged antes de prosseguir
    
    ```bash
    #Adicionando arquivo 
    git add nome_do_arquivo_com_conflito
    ```
    
</aside>

### Depois de adicionar, vamos ter de continuar com o rebase ou merge

Se o conflito for no rebase vamos usar:

```bash
git rebase --continue
```

Se o conflito foi no merge vamos usar

```bash
git merge --continue
```

<aside>
💡 O git irá criar um commit informando o conflito.

- O código do conflito pode ser analisado separadamente e reincorporado caso necessário.
</aside>

---

# ****Aula 18 Adicionando o site no Github Pages****

- PDF
    
    [18-modulo-vi-adicionando-o-site-no-github-pages.pdf](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/18-modulo-vi-adicionando-o-site-no-github-pages.pdf)
    

### Observações:

- Podemos hospedar nosso projeto para gerar link externo.
- Só consigo hospedar projetos que contem HTML, CSS e JavaScript

### Para hospedar teremos que fazer :

![1.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%204.jpg)

![2.jpg](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2%201.jpg)

<aside>
💡 Após a hospedagem sera gerado um link que podemos compartilhar.

A base do link fica: id_do_usuário_+.github.io+nome_do_projeto

</aside>

---

# DIO

# Tópicos fundamentais para entender o funcionamento do Git

- **Entendendo como o Git funciona por baixo dos panos.**

## Sha1

A sigla SHA significa Secure Hash Algorithm, que é um conjunto de funcões hash criptográficas projetadas pela NSA (Agência Nacional de Segurança dos EUA)

Essa encriptação gera um conjunto de caracteres identificadores com 40 dígitos.

![echo 1.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/echo_1.png)

- **Exemplos práticos de Sha1** 

Vamos criar um bloco de notas com o nome texto.

E dentro desse desse bloco de notas, vamos escrever “Olá, meu nome é Hugo”

 

Agora vamos gerar a chave criptográfica do bloco de notas com o comando 
“openssl sha1”
O comando será escrito da seguinte forma:

Então é gerado uma chave criptografada do arquivo de texto no estado atual. 

E se mudarmos o arquivo? 
Vamos adicionar uma excalamação no final, deixando “Olá, meu nome é Hugo!”

Vamos usar novamente o comando:

```bash
openssl sha1 texto.txt
```

![Texto.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Texto.png)

![Hugo1.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo1.png)

```bash
openssl sha1 texto.txt
```

![sha1 1.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_1.png)

![Hugo2.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo2.png)

![sha1 2.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_2.png)

Com isso podemos ver que uma chave diferente foi gerada.  
devido ao ponto de exclamação no final que alterou o estado do arquivo.

E se mudarmos o arquivo mais uma vez?

![Hugo3.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo3.png)

Novamente gera uma chave diferente.

![sha1 3.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_3.png)

Então se eu mudar de volta para o estado inicial do primeiro exemplo, a chave de identificação volta ao mesmo estado também.

# Gerando chaves SSH e Token

- Chave SSH

A chave SSH é a autenticação da sua máquina no Github, você gera uma chave SSH para declarar a sua máquina para o seu perfil no Github como máquina confiável.
Ideal para maquinas pessoais ou máquinas que somente você usa em uma empresa, pois não pede autenticações de senha durante o uso do Git e Github em conjunto.
Tornando o processo mais fácil e até mais seguro do que digitando a senha durante o uso.

Como gerar a chave?

```bash
ssh-keygen -t ed25519 -C hugodiscord@outlook.com
```

Observações: O ed25519 é o tipo de criptografia de segurança usada na chave, há outros tipos criptografias usados como o ed448 por exemplo, mas a mais usada, mais atual e considerada mais segura é a ed25519.
O Email é o do Github.
E o -C é usado maiúsculo mesmo.

![ssh keygen 1.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_1.png)

Essa parte será digitavel, é onde você poderá escolher o local/repositório onde a sua chave vai ficar armazenada. Caso aperte Enter sem digitar nada, ela irá para o repositório padrão conforme o ilustrado na imagem.

Se for mudar o diretório, é ideal que saiba o que está fazendo.
Por enquanto faremos o procedimento na pasta padrão mesmo.

O .ssh com espaço e ponto antes do nome “ssh” simboliza uma pasta oculta.

![ssh keygen 2.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_2.png)

Aqui vai pedir para digitar uma senha e depois confirmar essa senha.
Observação: Essa senha é a senha de acesso do arquivo da chave e não a senha do Github.

Após as confirmações, irá para a tela da imagem logo a seguir:

![ssh keygen 3.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_3.png)

A suas chaves públicas e privadas foram geradas e salvas no diretório especificado acima. (/c/Users…. )
O SHA256 é a criptografia da sua chave SSH
E a arte aleatória criptográfica da sua chave.

Então agora vamos ver a chave nos diretórios

![chave privada e publica.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_privada_e_publica.png)

Usaremos o cd para ir no diretório da chave e o ls para vermos as chaves salvas no diretório.
Lembrando que será a chave publica que vamos expor no Github. 

Então usaremos um comando para pegarmos o código na chave pública.

```bash
cat id_ed25519.pub
```

![chave publica.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica.png)

Você receberá esse desde o ssh-ed25519, , código enorme e com o email no final, você copiará tudo, incluindo o e-mail e será usado no Github.

![chave publica 2.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica_2.png)

Ok, agora vamos ao Github.
E faremos o seguinte caminho:
Clique na sua foto no canto superior direto > Settings > e na parte esquerda selecione SSH and GPG Keys.

![ssh chave no github.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_chave_no_github.png)

No Titile você vai dar um nome para o seu PC
E no Key você vai usar o código copiado.

![ssh key salva.png](Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_key_salva.png)

E aqui você terá a confirmação da sua chave salva.

E por fim os últimos passos no Git. 
Primeiro você vai usar o comando 

```bash
eval $(ssh-agent -s)
```

Sera gerado um Agent Pid de alguns algarismos que é o começo do processo. 
E por fim o comando: 

```bash
ssh-add id_ed25519
```

- Token 

Por fim o Token de acesso pessoal, que é a sua chave da conta por Token.

Faça o seguinte caminho:
Developer Settings > Personal acess tokens > Generate new token

Então na opção Note, você dará o nome da sua Token, escolherá a data de Expiração para essa Token e terá outras opções de segurança da Token. 

Por enquanto só é necessário marcar a opção repo
Você cria a chave e você receberá um código dessa chave.

**Observação:** O Github só te vai mostrar essa chave uma **ÚNICA** vez, então tenha certeza de guardar em um local bem seguro.