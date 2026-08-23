# Sistema de Agenda em C

Aplicação de terminal para cadastrar, listar, editar, remover e buscar contatos, com persistência em arquivo. Fiz esse projeto pra praticar structs, manipulação de arquivos e organização de código em C, sem bibliotecas externas — só stdio, stdlib e string da biblioteca padrão.

## Funcionalidades

- Adicionar contato
- Listar contatos cadastrados
- Editar contato existente
- Remover contato
- Buscar contato
- Armazenamento persistente em arquivo (leitura e escrita via fopen/fread/fwrite)

## Tecnologias

- C
- Biblioteca padrão (stdio, stdlib, string)
- Structs para modelar os contatos
- Manipulação de arquivos para persistência dos dados

## Como executar

\`\`\`
gcc agenda.cpp -o agenda
./agenda
\`\`\`

## Estrutura do projeto

\`\`\`
c-agenda-system/
├── agenda.cpp
└── README.md
\`\`\`

## Autor

Daniel Augusto Silva
