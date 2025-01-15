# Projeto Front-End Avançado - Sistema de transferência de pacientes

Este é um projeto para gerenciar informações de pacientes utilizando o framework Next.js e outras tecnologias. A aplicação permite realizar operações de CRUD de pacientes, bem como funcionalidades relacionadas a transferências.

Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:
```plaintext
├── .env                     # Arquivo de variáveis de ambiente;
├── .gitignore               # Configuração para ignorar arquivos no Git;
├── .idea/                   # Configurações do ambiente de desenvolvimento
├── app/                     # Páginas e layouts do Next.js
│   ├── api/                 # Endpoints da API
│   ├── pacientes/           # Páginas relacionadas a pacientes
│   │   ├── [id]/            # Página dinâmica para exibir detalhes de um paciente
│   │   └── page.tsx         # Listagem de pacientes
│   ├── transferencia/       # Páginas relacionadas a transferências
│   │   └── page.tsx         # Página de transferências
│   ├── globals.css          # Estilos globais
│   ├── layout/              # Layout base do projeto
│   │   ├── page.tsx         # Página principal do layout
│   │   └── layout.tsx       # Layout base
│   └── page.tsx             # Página inicial
├── components/              # Componentes reutilizáveis
│   ├── MenuLateral.tsx      # Componente de menu lateral
│   ├── PacienteForm.tsx     # Formulário para cadastro/edição de pacientes
│   └── PacienteList.tsx     # Listagem de pacientes
├── prisma/                  # Configuração e esquema do Prisma ORM
│   └── schema.prisma        # Definição do banco de dados
├── types/                   # Definições de tipos TypeScript
│   ├── Paciente.ts          # Tipo para dados de pacientes
│   └── Transferencia.ts     # Tipo para dados de transferências
├── eslint.config.mjs        # Configuração do ESLint
├── LICENSE                  # Licença do projeto
├── next.config.ts           # Configurações do Next.js
├── package.json             # Dependências do projeto
├── postcss.config.mjs       # Configuração do PostCSS
├── tailwind.config.ts       # Configuração do Tailwind CSS
├── tsconfig.json            # Configuração do TypeScript
└── README.md                # Documentação do projeto
```plaintext
Tecnologias Utilizadas

Next.js: Framework React para renderização no servidor e geração de páginas estáticas.

TypeScript: Superset do JavaScript com tipagem estática.

Prisma ORM: Para interações com o banco de dados.

# Projeto de Gerenciamento de Pacientes

Este é um projeto para gerenciar informações de pacientes, desenvolvido com **Next.js**, **Prisma** e **Tailwind CSS**. O objetivo é criar uma aplicação eficiente para lidar com transferências de pacientes, gerenciamento de dados e exibição de informações.

---

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

```plaintext
.
├── .env                # Variáveis de ambiente
├── .gitignore          # Arquivos e pastas ignorados pelo Git
├── .idea/              # Configurações da IDE (ex.: WebStorm ou IntelliJ)
├── app/
│   ├── api/
│   │   └── pacientes/[id]/ # API para manipulação de dados de pacientes
│   ├── globals.css     # Estilos globais
│   ├── layout/
│   │   ├── layout.tsx  # Layout padrão da aplicação
│   │   └── page.tsx    # Página principal do layout
│   ├── pacientes/
│   │   ├── page


