# 🔥 FIT.AI

O aplicativo que vai transformar a forma como você treina. Um sistema completo de gerenciamento de treinos com inteligência artificial para criar planos personalizados, acompanhar seu progresso e manter a consistência nos seus objetivos fitness.

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat&logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4-06B6D4?style=flat&logo=tailwind-css)

---

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Tecnologias](#tecnologias)
- [Bibliotecas e Ferramentas](#bibliotecas-e-ferramentas)
- [Funcionalidades](#funcionalidades)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Scripts Disponíveis](#scripts-disponíveis)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## 📖 Sobre o Projeto

FIT.AI é uma aplicação web moderna construída com as mais recentes tecnologias do ecossistema React. O projeto combina um sistema robusto de gerenciamento de treinos com capabilities de inteligência artificial para proporcionar uma experiência única e personalizada para atletas de todos os níveis.

O aplicativo permite que usuários criem, gerenciem e acompanhem seus planos de treino, com suporte a exercícios, dias de descanso, e um sistema de estatísticas que mostra a consistência do treinamento ao longo do tempo. A integração com IA permite interações conversacionais para ajudar na criação de planos e tirar dúvidas sobre exercícios.

---

## 🛠 Tecnologias

### Framework Principal

| Tecnologia     | Versão | Descrição                                                          |
| -------------- | ------ | ------------------------------------------------------------------ |
| **Next.js**    | 16.1.6 | Framework React com App Router, Server Components e Server Actions |
| **React**      | 19.2.3 | Biblioteca core para construção de interfaces de usuário           |
| **TypeScript** | ^5     | Superset JavaScript com tipagem estática opcional                  |

### Estilização e CSS

| Tecnologia       | Versão | Descrição                                 |
| ---------------- | ------ | ----------------------------------------- |
| **Tailwind CSS** | ^4     | Framework CSS utilitário com JIT compiler |
| **PostCSS**      | -      | Processador de CSS para Tailwind          |

---

## 📦 Bibliotecas e Ferramentas

### UI e Componentes

| Biblioteca                   | Versão   | Descrição                                            |
| ---------------------------- | -------- | ---------------------------------------------------- |
| **shadcn/ui**                | ^4.0.0   | Biblioteca de componentes acessíveis e customizáveis |
| **Radix UI**                 | ^1.4.3   | Primitivos de UI acessíveis e sem estilo             |
| **Lucide React**             | ^0.577.0 | Biblioteca de ícones consistentes e leves            |
| **tw-animate-css**           | ^1.4.0   | Animações CSS para componentes React                 |
| **class-variance-authority** | ^0.7.1   | Utilitário para criar variantes de componentes       |
| **tailwind-merge**           | ^3.5.0   | Merge de classes Tailwind sem conflitos              |
| **clsx**                     | ^2.1.1   | Construção de classes condicionais                   |

### Formulários e Validação

| Biblioteca              | Versão  | Descrição                                 |
| ----------------------- | ------- | ----------------------------------------- |
| **React Hook Form**     | ^7.71.2 | Gerenciamento de formulários performático |
| **Zod**                 | ^4.3.6  | Schema validation e TypeScript inference  |
| **@hookform/resolvers** | ^5.2.2  | Integração de Zod com React Hook Form     |

### Inteligência Artificial

| Biblioteca                 | Versão | Descrição                                             |
| -------------------------- | ------ | ----------------------------------------------------- |
| **AI SDK (@ai-sdk/react)** | 3.0.51 | Framework oficial para construir apps com IA em React |
| **ai**                     | 6.0.49 | SDK core para integração com modelos de linguagem     |
| **streamdown**             | 2.2.0  | Processamento de streams de dados                     |

### Autenticação

| Biblioteca      | Versão | Descrição                          |
| --------------- | ------ | ---------------------------------- |
| **better-auth** | 1.4.18 | Framework completo de autenticação |

### Gerenciamento de Estado

| Biblioteca | Versão | Descrição                                 |
| ---------- | ------ | ----------------------------------------- |
| **nuqs**   | 2.8.8  | Estado via URL (URL as State) com Next.js |

### Integração de API

| Biblioteca    | Versão | Descrição                                                             |
| ------------- | ------ | --------------------------------------------------------------------- |
| **Orval**     | 8.1.0  | Geração automática de clientes TypeScript a partir de OpenAPI/Swagger |
| **Fetch API** | -      | API nativa para requisições HTTP                                      |

### Utilitários

| Biblioteca | Versão  | Descrição                                            |
| ---------- | ------- | ---------------------------------------------------- |
| **Day.js** | 1.11.19 | Manipulação leve de datas (alternative ao Moment.js) |
| **dotenv** | ^17.3.1 | Carregamento de variáveis de ambiente                |

### Desenvolvimento

| Biblioteca               | Versão | Descrição                                   |
| ------------------------ | ------ | ------------------------------------------- |
| **ESLint**               | ^9     | Linter para identificar problemas no código |
| **eslint-config-next**   | 16.1.6 | Configuração ESLint oficial do Next.js      |
| **Prettier**             | 3.8.1  | Formatador de código automático             |
| **@types/node**          | ^20    | Tipos TypeScript para Node.js               |
| **@types/react**         | ^19    | Tipos TypeScript para React                 |
| **@types/react-dom**     | ^19    | Tipos TypeScript para React DOM             |
| **@tailwindcss/postcss** | ^4     | Plugin PostCSS para Tailwind                |

---

## ✨ Funcionalidades

### Autenticação e Usuário

- 🔐 Login com Google via Better Auth
- 📝 Fluxo de onboarding para novos usuários
- 👤 Página de perfil com configurações

### Gerenciamento de Treinos

- 📋 Planos de treino personalizados por dia
- 💪 Exercícios com séries, repetições e carga
- ⏱️ Sistema de dias de descanso
- ✅ Marcação de treino como completo

### Inteligência Artificial

- 🤖 Chatbot de IA para auxiliar nos treinos
- 💬 Interface conversacional integrada ao app
- 🎯 Sugestões personalizadas baseada no perfil

### Estatísticas e Progresso

- 📊 Dashboard de estatísticas
- 🔥 Heatmap de consistência de treino
- 🔗 Sistema de rastreamento de sequência (streak)
- 📈 Cards informativos de progresso

### Interface e UX

- 📱 Design responsivo e mobile-first
- 🎨 UI moderna com shadcn/ui
- ➕ Botão flutuante para abrir chat
- 🎯 Navegação inferior em mobile

---

## 🚀 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **Node.js** (versão 18 ou superior)
- **pnpm** (gerenciador de pacotes recomendado) ou npm/yarn
- **Git** para controle de versão

---

## 📥 Instalação

1. **Clone o repositório:**

```bash
git clone <url-do-repositorio>
cd treinos-frontend
```

2. **Instale as dependências:**

```bash
# Usando pnpm (recomendado)
pnpm install

# Ou usando npm
npm install

# Ou usando yarn
yarn install
```

3. **Configure as variáveis de ambiente:**

Crie um arquivo `.env.local` na raiz do projeto com as seguintes variáveis:

```env
# URL da API backend
NEXT_PUBLIC_API_URL=http://localhost:8080

# Configurações de autenticação (Better Auth)
BETTER_AUTH_SECRET=sua-chave-secreta-aqui
BETTER_AUTH_URL=http://localhost:3000

# Google OAuth (opcional)
GOOGLE_CLIENT_ID=seu-google-client-id
GOOGLE_CLIENT_SECRET=seu-google-client-secret

# Configurações de IA (se necessário)
OPENAI_API_KEY=sua-chave-openai
```

4. **Inicie o servidor de desenvolvimento:**

```bash
pnpm dev
```

O aplicativo estará disponível em `http://localhost:3000`

---

## ⚙️ Scripts Disponíveis

| Script           | Descrição                               |
| ---------------- | --------------------------------------- |
| `pnpm dev`       | Inicia o servidor de desenvolvimento    |
| `pnpm build`     | Cria a versão de produção               |
| `pnpm start`     | Inicia o servidor de produção           |
| `pnpm lint`      | Executa o ESLint para verificar código  |
| `pnpm typecheck` | Executa verificação de tipos TypeScript |
| `pnpm orval`     | Gera clientes API a partir do Swagger   |

---

## 📂 Estrutura do Projeto

```
treinos-frontend/
├── app/                    # Next.js App Router
│   ├── _components/        # Componentes compartilhados
│   ├── _lib/               # Utilitários e configurações
│   │   ├── api/            # API gerada pelo Orval
│   │   ├── auth-client.ts  # Cliente de autenticação
│   │   └── fetch.ts        # Configuração do fetch
│   ├── auth/               # Página de autenticação
│   ├── onboarding/         # Fluxo de onboarding
│   ├── profile/            # Página de perfil
│   ├── stats/              # Página de estatísticas
│   ├── workout-plans/      # Páginas de planos de treino
│   ├── layout.tsx          # Layout raiz
│   ├── page.tsx            # Página inicial
│   └── globals.css         # Estilos globais
├── components/
│   └── ui/                 # Componentes shadcn/ui
├── lib/
│   └── utils.ts            # Utilitários (cn function)
├── public/                 # Arquivos estáticos
├── tasks/                  # Arquivos de tarefas
├── .env                    # Variáveis de ambiente
├── components.json         # Configuração shadcn
├── orval.config.ts         # Configuração Orval
├── next.config.ts          # Configuração Next.js
├── tsconfig.json           # Configuração TypeScript
├── postcss.config.mjs      # Configuração PostCSS
├── eslint.config.mjs       # Configuração ESLint
└── package.json            # Dependências do projeto
```

---

## 🎨 Padrões e Convenções

O projeto segue diversas convenções de código:

- **Componentes**: React Server Components por padrão, com "use client" quando necessário
- **Estilização**: Tailwind CSS com classes utilitárias
- **Componentes UI**: shadcn/ui com customizações via Tailwind
- **Tipagem**: TypeScript strict mode
- **Nomenclatura**: PascalCase para componentes, camelCase para funções
- **Aliases**: `@/` para imports absolutos (configurado no tsconfig)

---

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 💡 Agradecimentos

Feito com ❤️ usando as melhores tecnologias do ecossistema React.
