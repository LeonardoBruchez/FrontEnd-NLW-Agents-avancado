# NLW Agents

Projeto desenvolvido durante o evento **NLW (Next Level Week)** da Rocketseat, focado em criar uma aplicação web moderna com React e TypeScript.

## 🚀 Tecnologias Utilizadas

### Frontend
- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Linguagem tipada para JavaScript
- **Vite** - Build tool e dev server
- **React Router DOM** - Roteamento da aplicação
- **TanStack Query** - Gerenciamento de estado e cache de dados

### Styling
- **Tailwind CSS 4** - Framework CSS utilitário
- **Radix UI** - Componentes acessíveis
- **Lucide React** - Ícones
- **Class Variance Authority** - Utilitário para variantes de componentes

### Ferramentas de Desenvolvimento
- **Biome** - Linter e formatter (substituindo ESLint + Prettier)
- **Ultracite** - Configuração de linting otimizada

## 📁 Estrutura do Projeto

```
src/
├── components/     # Componentes reutilizáveis
├── pages/         # Páginas da aplicação
├── lib/           # Utilitários e configurações
├── app.tsx        # Componente principal
└── main.tsx       # Ponto de entrada
```

## 🛠️ Padrões de Projeto

- **Componentes Funcionais** com hooks do React
- **TypeScript** para tipagem estática
- **React Query** para gerenciamento de estado e cache
- **React Router** para navegação
- **Tailwind CSS** para estilização utilitária
- **Biome** para linting e formatação de código

## ⚡ Setup e Configuração

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd web
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
```

4. Acesse a aplicação em `http://localhost:5173`

### Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção

## 🔧 Configurações

- **Vite** configurado com alias `@` para `./src`
- **Tailwind CSS** integrado via plugin do Vite
- **Biome** configurado com preset Ultracite
- **TypeScript** configurado para React

## 📝 Licença

Este projeto foi desenvolvido durante o evento NLW da Rocketseat. 