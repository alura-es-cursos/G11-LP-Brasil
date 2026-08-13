# G11 - ONE AI FOR BUSINESS | Landing Page

Landing page para o programa **G11 - ONE AI FOR BUSINESS**, uma colaboração entre a **Oracle Next Education (ONE)** e a **Alura**. O site ajuda os estudantes a escolher sua trilha de aprendizagem antes do challenge individual do programa.

## Sobre o projeto

O site apresenta:

- **Orientação por perfil**: 4 trilhas sugeridas conforme o interesse do estudante (liderança/estratégia, vendas & marketing, RH, finanças & operações).
- **Catálogo de formações**: 7 formações (G1-G3 gerais, T1-T4 eletivas) com seus cursos, carga horária, ferramentas utilizadas e links diretos para a Alura.
- **Challenge individual**: seção com o conteúdo obrigatório do programa (a preencher).
- Suporte a tema claro/escuro.

## Stack

- [React 19](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS 4](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Lucide React](https://lucide.dev/) (ícones)

## Requisitos

- [Node.js](https://nodejs.org/) 18 ou superior
- npm

## Como executar

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

O site ficará disponível em `http://localhost:5173`.

## Scripts disponíveis

| Comando           | Descrição                                          |
| ------------------ | --------------------------------------------------- |
| `npm run dev`     | Inicia o servidor de desenvolvimento com hot-reload |
| `npm run build`   | Gera a build de produção na pasta `dist/`          |
| `npm run preview` | Serve localmente a build de produção para testes    |
| `npm run lint`    | Executa o ESLint no projeto                          |

## Estrutura do projeto

```
src/
├── assets/                          # Imagens e logos
├── components/
│   ├── ui/                          # Componentes de UI reutilizáveis (Button, Card)
│   └── sitio_formaciones_g_11_pt.jsx # Componente principal da página
├── data/
│   └── g11ContentPT.js              # Conteúdo das formações e trilhas (PT-BR)
├── App.jsx
├── main.jsx
└── index.css
```
