## Curso Frontend
#### EBAC

## GIT
## Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2 
Arquivo B | Versão 1 | Versão 2

## Instalação do Git
https://git-scm.com/

- Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git

## Criar conta no GitHub 

## Clonar o projeto
git clone https://github.com/brunociribelli/Curso-frontend.git

## Confirma
Informação de alteração
- após testado todo seu código
> git add * 
> git commit -m "mensagem" 
> git push (enviar alterações para o repositório GitHub)
> git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

### Ramos
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto for publicado)
- desenvolver
- Definição DOD de Concluído: critérios de aceitação
- versionamento 1.0.0

> git checkout -b dev (cria uma ramificação) 
> git checkout master (mudar de branch)

### Mesclar
Mescla de ramos
Você pode precisar resolver conflitos manualmente

> git merge principal

### Solicitações pull
Mescla de filiais no repositório 
Permite revisão de código 
O repositório resolve os conflitos automaticamente

### configurar o GitFlow
> git flow init 
> git flow feature start {nome-da-feature}
