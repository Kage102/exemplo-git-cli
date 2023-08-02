# Exemplos de operações básicas via cli

## Comando de uso geral cli

- Criar pasta: mkdir nomepasta
- Listar conteúdo: mkdir 
- Limpar tela: dir
- Entrar na pasta: cd nomepasta

## comandos principais

Inicializar um repositório (executado dentro da pasta)

## Comandos principais do git

`git config user.name` e  `git config user.email`

verificar usuário/email

`git config --global user.name "seu nome como quiser"` e  
`git config --global user.email "seuemail@provedor.com"`

Mudar usuário e email de forma global

**Obs:** normalmente estes dados estão relacionados ao usuário/conta do site GitHub.

`git init`

Inicializar um repositório (executado dentro da pasta).

`git branch nome-branch-atual novo-nome-para-branch`

Renomear branches.

Renomear a branch de **master** para **main** (novo padrão),
usaríamos: `git branch master main`


`git status`

Verificar o status atual do repositório.

`git add nomearquivo` ou `git add .`

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração"`

Fazer commit das alterações (salvar no histórico).

`git remote add origin endereço-do-repositorio.git`

Adicionar/conectar o repositório remoto ao local.

`git push origin main`

Enviar as mudanças para o Github (push).

`git pull origin main`

Pegar obter as mudanças do repositório online Github (Pull).

`git clone endereço-do-repositorio.git`

copiando/baixando um repositório para a máquina remota.