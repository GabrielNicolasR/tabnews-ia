# AGENTS.md

## Sobre o Projeto

O **tabnews-ia** é uma implementação do [TabNews](https://tabnews.com.br) desenvolvida no contexto do [curso.dev](https://curso.dev), utilizando agentes de Inteligência Artificial para apoiar o fluxo de desenvolvimento e engenharia de software.

O objetivo do projeto é construir uma plataforma de conteúdo e comunidade para quem trabalha com programação e tecnologia, aplicando boas práticas de desenvolvimento web moderno.

---

## Stack Tecnológica

- **Tecnologias principais:** Next.js e React (consulte o `package.json` para verificar as versões e dependências atuais).

---

## Diretrizes para Agentes

- **Convenções:** Priorizar o App Router do Next.js (`app/`) e Server Components sempre que possível (usar `'use client'` somente quando manipulação de estado ou eventos do navegador forem estritamente necessários).
- **Simplicidade:** Manter o código enxuto, legível e com o mínimo de complexidade acidental.
- **Qualidade:** Validar builds (`npm run build`) antes de finalizar tarefas de desenvolvimento.
