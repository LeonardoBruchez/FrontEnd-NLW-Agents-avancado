# NLW Agents

Projeto desenvolvido durante o evento **NLW (Next Level Week)** da Rocketseat, focado em criar uma aplicação web moderna com React e TypeScript.

## 🚀 Tecnologias

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

### Ferramentas
- **Biome** - Linter e formatter (substituindo ESLint + Prettier)
- **Ultracite** - Configuração de linting otimizada

## 📁 Estrutura

```
src/
├── components/     # Componentes reutilizáveis
├── pages/         # Páginas da aplicação
├── http/          # Hooks e tipos para API
├── lib/           # Utilitários e configurações
├── app.tsx        # Componente principal
└── main.tsx       # Ponto de entrada
```

## ⚡ Setup

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

3. Execute o projeto:
```bash
npm run dev
```

4. Acesse: `http://localhost:5173`

### Scripts

- `npm run dev` - Servidor de desenvolvimento
- `npm run build` - Build de produção
- `npm run preview` - Visualizar build

## 🔧 Configurações

- **Vite** com alias `@` para `./src`
- **Tailwind CSS** integrado via plugin
- **Biome** com preset Ultracite
- **TypeScript** configurado para React

## 📝 Licença

Este projeto foi desenvolvido durante o evento NLW da Rocketseat. 