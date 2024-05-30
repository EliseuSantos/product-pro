# Contribuindo para o ProjectPRO

Obrigado por considerar contribuir para o ProjectPRO! Este documento descreve algumas diretrizes para contribuir para este projeto, seguindo o fluxo de trabalho GitFlow e utilizando Commitizen para mensagens de commit.

## Fluxo de trabalho (GitFlow)

Este projeto segue o modelo de fluxo de trabalho GitFlow. O GitFlow é um modelo de ramificação para o Git que define um conjunto de regras robustas e bem definidas em relação ao gerenciamento de branches em um projeto.

### Branches principais:

- **main**: Representa a versão de produção do software.
- **dev**: É a branch de desenvolvimento, onde as novas funcionalidades são integradas.

### Branches de funcionalidades:

Para cada nova funcionalidade, é recomendado criar uma nova branch a partir da branch `dev`. O nome da branch deve ser descritivo e incluir o número da issue correspondente, se aplicável.

Exemplo:

git checkout -b feature/new-feature-123 dev

### Pull Requests:

Ao concluir o desenvolvimento de uma funcionalidade, abra um Pull Request para mesclar sua branch de funcionalidade na branch `dev`. Todos os Pull Requests devem ser revisados por pelo menos um outro desenvolvedor antes de serem mesclados.

## Mensagens de Commit

Para manter um histórico de commits limpo e legível, este projeto utiliza o Commitizen para padronizar as mensagens de commit. O Commitizen facilita a criação de mensagens de commit seguindo um formato específico.

### Como usar Commitizen:

1. Instale o Commitizen globalmente, se ainda não estiver instalado:

npm install -g commitizen

2. Após fazer suas alterações no código, adicione os arquivos modificados ao stage.
   
3. Em seguida, execute o seguinte comando para criar sua mensagem de commit:

git cz

Isso abrirá uma interface interativa para ajudá-lo a criar sua mensagem de commit.

4. Siga as instruções para preencher os campos obrigatórios.

### Exemplo de mensagem de commit:

- feat: Adiciona nova funcionalidade de notificação
- fix: Corrige erro de renderização no dashboard
- docs: Atualiza documentação do Contributing.md

Lembre-se de que cada mensagem de commit deve ser clara, concisa e começar com um verbo no imperativo.

## Problemas ou Dúvidas

Se você tiver algum problema ou dúvida sobre o fluxo de trabalho ou sobre como contribuir para o projeto, não hesite em abrir uma issue ou entrar em contato com a equipe de
