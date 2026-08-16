# NT Engenharia | Site Institucional

Site institucional da **NT Engenharia**, empresa especializada em soluções de engenharia civil para indústrias de grande porte — projetos em concreto armado, estruturas metálicas, fundações, contenções, BIM LOD 300 e ATP conforme NBR 6118.

## 📋 Sobre o projeto

O site apresenta a empresa, seus serviços, portfólio de obras, certificações e canais de contato, incluindo geração de laudos/documentos em PDF e um formulário de contato integrado via API.

### Páginas principais

- **Home** — apresentação institucional
- **Quem Somos** — sobre a empresa
- **Serviços** — soluções oferecidas
- **Portfólio** — projetos e obras realizadas
- **Certificações** — qualificações e normas atendidas
- **Contato** — formulário de contato com envio via API

## 🛠️ Tecnologias e ferramentas

- **[Next.js 14](https://nextjs.org/)** — framework React com App Router
- **[TypeScript](https://www.typescriptlang.org/)** — tipagem estática
- **[Tailwind CSS](https://tailwindcss.com/)** — estilização utilitária
- **[Framer Motion](https://www.framer.com/motion/)** — animações
- **[React Hook Form](https://react-hook-form.com/)** — gerenciamento de formulários
- **[Sharp](https://sharp.pixelplumbing.com/)** — otimização de imagens
- **ESLint** — padronização e qualidade de código

## 🚀 Como rodar localmente

\`\`\`bash
# Instalar dependências
npm install

# Rodar em modo desenvolvimento
npm run dev

# Build de produção
npm run build

# Rodar build de produção
npm start
\`\`\`

Acesse [http://localhost:3000](http://localhost:3000) no navegador.

## 📁 Estrutura do projeto

\`\`\`
src/
├── app/              # Rotas (App Router) — home, quem-somos, servicos, portfolio, certificacoes, contato, api
├── components/       # Componentes reutilizáveis (layout, seções, PDF, UI)
├── hooks/            # Hooks customizados
└── lib/              # Dados e utilitários
\`\`\`

## 📄 Licença

Projeto privado — todos os direitos reservados à NT Engenharia.
