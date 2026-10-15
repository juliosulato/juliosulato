# Olá, eu sou o Julio 👋

**Desenvolvedor Full Stack** · React · Next.js · TypeScript · Node.js
📍 Jaú, SP — Brasil

Construo plataformas SaaS que estão em produção e são usadas por clientes reais. Meu foco é o ecossistema JavaScript/TypeScript, com interesse especial em **arquitetura** e **qualidade de software**: testes automatizados, CI e código fácil de manter.

---

## 🔨 No que estou trabalhando

**[Domus Control](https://github.com/juliosulato) — Desenvolvedor Front-End Pleno** · jun/2026 – atual
SaaS multi-tenant (PWA) para gestão de igrejas, com front em Next.js e back-end em Laravel.

- Desenvolvo módulos estratégicos: **Dízimos**, **Painel Administrativo** e o **Gateway de Pagamento** da área de doações
- Introduzi a estratégia de **testes automatizados** do front-end (Vitest, React Testing Library e Playwright) e o pipeline de **CI no GitHub Actions** que valida os pull requests
- Projetei o **sistema de permissões** do front-end, integrado ao controle de acesso por papéis da API
- Conduzi o redesign de áreas centrais do PWA (Home, Menu e Perfil)
- Reviso PRs de um desenvolvedor júnior e escrevo as especificações técnicas que alinham front e back

**Movi — Founder** · em desenvolvimento
SaaS de gestão para academias de dança: alunos, turmas, matrículas, planos e financeiro.

- Monorepo com **Turborepo**, front-ends em **Next.js** e API em **Node.js**
- **PostgreSQL** com **Prisma** em arquitetura multi-schema para isolar tenants
- Infraestrutura própria: VPS Debian com **Docker Compose** e Nginx, front-ends na **AWS Amplify**, além de S3 e SES
- Módulo financeiro com cálculo de saldo por checkpoints e transferências atômicas entre contas

**MazzaUX — Founder** · 2024 – 2026
Agência onde desenvolvi sites, sistemas internos e aplicações web para negócios reais (academias, clínicas e eventos), do levantamento do problema ao deploy e à manutenção.

---

## 🧰 Stack

| | |
|---|---|
| **Front-end** | TypeScript, React, Next.js (App Router), Vite, Tailwind CSS, shadcn/ui, SWR, React Hook Form, Zod |
| **Back-end** | Node.js, Bun, Express, NestJS, APIs REST, better-auth |
| **Banco de dados** | PostgreSQL, Prisma, PGlite, Redis |
| **Testes** | Vitest, React Testing Library, Playwright, Jest |
| **Infra & DevOps** | Docker, Docker Compose, Nginx, AWS (Amplify, S3, SES, CloudWatch), GitHub Actions |
| **Estudando** | Angular |

---

## 📌 Projetos públicos

### [Tessera](https://github.com/juliosulato/tessera) · 🚧 em desenvolvimento
Plataforma open source de gestão pessoal, **offline-first** e **extensível por plugins**. Cada área da vida (financeiro, hábitos, agenda, treino...) é um plugin, e os módulos oficiais usam exatamente a mesma API que um plugin da comunidade usaria. *Tessera* é cada pecinha de um mosaico: cada plugin é uma peça.

- PWA que funciona sem internet, com **PostgreSQL rodando no navegador** (PGlite/WASM)
- Núcleo mínimo (dados, carregador de plugins e casca da interface) e um **plugin SDK** com fronteiras garantidas por lint no CI
- Plugins conversam por eventos e precisam de permissão declarada para ler dados de outros plugins
- Os dados são do usuário: exportação e importação com validação por schema e migrations por plugin
- Demo pública 100% no navegador e versão self-hosted com `docker compose up`, com servidor de sincronização em **NestJS** no roadmap

`TypeScript` `React` `Vite` `PGlite` `Zod` `Turborepo` `NestJS`

### [Estoque API](https://github.com/juliosulato/estoque-api) · 🚧 em desenvolvimento
Sistema de estoque para o catálogo web de uma loja: API em NestJS, painel administrativo em Angular e catálogo público em Next.js.

- Log completo de movimentações de estoque, com o saldo atualizado na **mesma transação** para nunca divergir do histórico
- Autenticação com **better-auth** e rotas separadas para o admin (`/api/admin`) e o catálogo público (`/api/catalogo`), sem expor dados internos como preço de custo
- Categorias hierárquicas com proteção contra ciclos e slugs estáveis para não quebrar URLs publicadas
- Upload de imagens direto para o **S3** via presigned URL

`NestJS` `Bun` `Prisma` `PostgreSQL` `better-auth` `AWS S3` `Angular` `Next.js`

### [Weather API](https://github.com/juliosulato/weather-api-node-postgres)
API REST de dados climáticos com histórico persistido de consultas.
Cache em memória para reduzir chamadas à OpenWeatherMap, validação com Zod, documentação via Swagger, ambiente com Docker Compose e CI (lint, testes e build) no GitHub Actions.

`Node.js` `TypeScript` `Express` `PostgreSQL` `Prisma` `Docker` `GitHub Actions`

> Os projetos da Domus Control e do Movi são privados. Fico à vontade para conversar sobre a arquitetura deles.

---

## 🎓 Formação

**Bacharelado em Engenharia de Software** — UNINTER · 2026 – 2030

---

## 📫 Contato

[LinkedIn](https://www.linkedin.com/in/juliosulatofh) · juliosulatofh@gmail.com
