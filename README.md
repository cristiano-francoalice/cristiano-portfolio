# Cristiano Alice — Portfólio Digital

Portfólio profissional de Cristiano Alice, desenvolvido para apresentar sua trajetória, projetos e competências na interseção entre **design, tecnologia, gestão de produtos e projetos e inovação**.

O site também representa a primeira etapa de um ecossistema digital em evolução: além do portfólio, poderá funcionar como laboratório de experimentação e, futuramente, como base para apresentar soluções, serviços e produtos digitais.

## Objetivos do projeto

- Apresentar a trajetória profissional, a formação e as áreas de atuação.
- Organizar projetos e experiências em estudos de caso.
- Demonstrar a aplicação prática de design, tecnologia, gestão e inovação.
- Construir uma presença digital própria, com possibilidade de expansão gradual.
- Manter uma base técnica simples, organizada e preparada para evoluir.

## Tecnologias utilizadas

| Tecnologia | Aplicação no projeto |
| --- | --- |
| [Astro](https://astro.build/) | Framework utilizado para estruturar e gerar as páginas do site. |
| [Tailwind CSS](https://tailwindcss.com/) | Apoio à estilização e à construção da interface. |
| [HTML, CSS e JavaScript](https://developer.mozilla.org/) | Tecnologias fundamentais da interface web. |
| [GitHub](https://github.com/) | Repositório do código-fonte, versionamento e documentação. |
| [Cloudflare Workers](https://workers.cloudflare.com/) | Plataforma utilizada para publicar e disponibilizar o site. |

O projeto prioriza uma arquitetura leve e páginas estáticas. Recursos adicionais — como banco de dados, painel de gerenciamento, autenticação ou serviços de backend — poderão ser considerados quando houver uma necessidade concreta.

## Estrutura principal

A estrutura abaixo destaca os diretórios e arquivos centrais do projeto:

```text
cristiano-portfolio/
├── docs/
│   └── mapa-ecossistema-digital.md
├── public/
│   └── arquivos estáticos e recursos públicos
├── src/
│   ├── components/
│   │   ├── ProjectCard.astro
│   │   ├── SiteHeader.astro
│   │   └── SiteFooter.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── sobre.astro
│   │   └── projetos/
│   │       ├── index.astro
│   │       ├── educacao-digital.astro
│   │       ├── qualidade-processos.astro
│   │       └── energia-criativa.astro
│   └── styles/
│       └── global.css
├── package.json
└── README.md
```

### Responsabilidade dos principais diretórios

- **`src/pages/`** — páginas e rotas do site. O arquivo `index.astro` corresponde à página inicial.
- **`src/components/`** — componentes reutilizáveis, como cabeçalho, rodapé e cartões de projetos.
- **`src/layouts/`** — estruturas compartilhadas entre páginas, incluindo elementos comuns de apresentação e metadados.
- **`src/styles/`** — estilos globais da interface.
- **`public/`** — arquivos estáticos disponibilizados diretamente pelo site, como imagens, ícones e outros recursos.
- **`docs/`** — documentação de planejamento, arquitetura, roadmap e decisões do projeto.

## Páginas atuais

| Página | Finalidade |
| --- | --- |
| Início | Apresentação profissional e destaques do portfólio. |
| Sobre | Trajetória, formação, experiência e visão de trabalho. |
| Projetos | Visão geral dos projetos apresentados. |
| Educação Digital | Experiências relacionadas à educação e tecnologia. |
| Qualidade e Processos | Experiências relacionadas à qualidade, processos e melhoria contínua. |
| Energia Criativa | Projeto autoral que conecta design, surf e tecnologia. |

## Desenvolvimento local

Para executar o projeto em ambiente local:

1. Instale uma versão do Node.js compatível com a versão do Astro utilizada no projeto.
2. Clone o repositório.
3. Instale as dependências.
4. Inicie o servidor de desenvolvimento.

```bash
git clone https://github.com/cristiano-francoalice/cristiano-portfolio.git
cd cristiano-portfolio
npm install
npm run dev
```

Para gerar a versão de produção:

```bash
npm run build
```

O resultado da compilação é gerado no diretório `dist/`.

## Versionamento e publicação

- **Código-fonte:** mantido neste repositório GitHub.
- **Branch principal:** `main`.
- **Publicação:** realizada pela Cloudflare Workers, com integração ao repositório.
- **Fluxo de atualização:** alterações são registradas por commits no GitHub; a integração de deploy utiliza a branch configurada para executar a compilação e publicar a versão atualizada.

Antes de considerar uma alteração concluída, é importante verificar o resultado no ambiente publicado, incluindo navegação, conteúdo e visualização em dispositivos móveis.

## Documentação do projeto

- [Mapa do Ecossistema Digital](docs/mapa-ecossistema-digital.md) — visão, objetivos, arquitetura de referência, roadmap e decisões do projeto.

## Evolução

O desenvolvimento será incremental, organizado em etapas:

1. Consolidar o portfólio profissional e revisar conteúdo, navegação e responsividade.
2. Ampliar o laboratório digital com experimentos e estudos de caso.
3. Avaliar recursos gerenciáveis e serviços de backend quando forem necessários.
4. Explorar oportunidades para oferecer soluções, serviços e produtos digitais.

As etapas e decisões devem ser acompanhadas no **Mapa do Ecossistema Digital**. A inclusão de novas tecnologias deve responder a necessidades reais do projeto, evitando complexidade prematura.

---

Projeto em desenvolvimento por **Cristiano Alice**.
