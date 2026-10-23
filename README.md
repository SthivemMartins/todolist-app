# Minha lista de tarefas

Um app simples e responsivo para organizar tarefas do dia a dia. Este projeto foi feito com React e TypeScript e tem uma interface minimalista com temas claro e escuro.

## O que dá para fazer

- Adicionar tarefas.
- Marcar tarefas como concluídas e removê-las individualmente.
- Filtrar a lista por todas, ativas ou concluídas.
- Limpar todas as tarefas concluídas de uma vez.
- Alternar entre os temas claro e escuro.

> **Atenção:** as tarefas e o tema ficam apenas na memória da aplicação. Ao atualizar ou fechar a página, eles são reiniciados.

## Tecnologias

- React 19
- TypeScript
- Vite
- Tailwind CSS 4

## Como executar

Você precisa ter o [Node.js](https://nodejs.org/) e o npm instalados.

```bash
# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

O Vite exibirá no terminal o endereço local para abrir no navegador.

## Outros comandos

```bash
# Verifique os tipos e gere a versão de produção
npm run build

# Execute o ESLint
npm run lint

# Pré-visualize a versão de produção
npm run preview
```

## Organização do projeto

```text
src/
├── components/
│   ├── TodoContainer/
│   ├── TodoForm/
│   ├── TodoHeader/
│   └── TodoList/
├── contexts/       # Contexto e configuração dos temas
├── hooks/          # Lógica e estado das tarefas
├── styles/         # Estilos globais e tema do Tailwind
├── App.tsx
└── main.tsx
public/
└── images/         # Ícones e imagens de fundo
```
