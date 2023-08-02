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

Inicialozar um repositório (executado dentro da pasta).

`git status`

Verificar o status atual do repositório.

`git add nomearquivo` ou `git add .`

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração"`

Fazer commit das alterações (salvar no histórico).

`git remote add origin endereço-do-repositorio.git`

Adicionar/conectar o repositório remoto ao local.