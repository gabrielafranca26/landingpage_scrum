# Agile WorkShop - Aula 01: Landing Page Scrum

**Grupo:** Aluno 1 e Aluno 2  
**Data da Sprint:** 10/10/2026  
**Duracao da Sprint:** 2 sprints simuladas  
**Objetivos:** Simular o fluxo Scrum + Git/GitHub criando uma landing page sobre o Framework Scrum, com branches separadas para HTML5 e CSS3 e uma sprint posterior de integracao e validacao.

---

## Definition of Done (DoD)

Para considerar a atividade concluida, o grupo deve cumprir:

- [ ] Sprint 1 planejada com tarefas separadas para HTML5 e CSS3.
- [ ] Branch `feature/html5-scrum-aluno-1` criada a partir da `main`.
- [ ] Branch `feature/css3-scrum-aluno-2` criada a partir da `main`.
- [ ] `index.html` criado em HTML5 puro, sem `class`, sem `id` e sem link para CSS.
- [ ] `assets/css/styles.css` criado com CSS3 responsivo e seletores planejados.
- [ ] Commits criados com mensagens claras no padrao Conventional Commits.
- [ ] Pull Requests abertos para a `main`.
- [ ] Cada PR revisado por outra pessoa.
- [ ] Branches da Sprint 1 integradas na `main`.
- [ ] Sprint 2 criada para integrar HTML + CSS.
- [ ] Classes, ids e link do CSS aplicados no HTML durante a integracao.
- [ ] Validacao registrada pelo pelos 2 alunos.
- [ ] Landing page demonstrada na Sprint Review.
- [ ] Retrospectiva preenchida em `RETROSPECTIVE.md`.

---

## Sprint 1 - Criacao Separada dos Artefatos

Objetivo: demonstrar trabalho paralelo em branches independentes, com responsabilidades claras.

| # | Tarefa | Descricao | Responsavel | Branch | Status | Criterios de Aceitacao |
|---|--------|-----------|-------------|--------|--------|------------------------|
| 1 | Criar estrutura HTML5 da landing page | Criar `index.html` com conteudo sobre Scrum usando HTML5 semantico, sem `class`, sem `id` e sem link para CSS. | Aluno 1 | `feature/html5-scrum-aluno-1` | A fazer | Arquivo abre no navegador, comunica o tema Scrum e preserva HTML puro para integracao futura. |
| 2 | Criar estilos CSS3 responsivos | Criar `assets/css/styles.css` com layout mobile-first, variaveis CSS, grid/flex, hover/focus e seletores planejados. | Aluno 2 | `feature/css3-scrum-aluno-2` | A fazer | CSS contem hooks como `.site-header`, `.hero`, `.roles-grid`, `.events-timeline`, `.artifacts`, `.cta-section` e `#scrum-framework`. |
| 3 | Revisar PR de HTML5 | Avaliar clareza, semantica, conteudo e ausencia de classes/ids no HTML. | Aluno 2 | PR da branch HTML | A fazer | PR revisado com comentario objetivo e aprovacao ou solicitacao de ajuste. |
| 4 | Revisar PR de CSS3 | Avaliar responsividade, organizacao, seletores planejados e aderencia ao tema visual. | Aluno 1 | PR da branch CSS | A fazer | PR revisado com comentario objetivo e aprovacao ou solicitacao de ajuste. |
| 5 | Integrar entregas da Sprint 1 | Realizar merge dos PRs aprovados na `main`. | Aluno 1 e Aluno 2 | `main` | A fazer | `main` contem HTML e CSS como arquivos separados, ainda sem integracao funcional completa. |

---

## Sprint 2 - Integracao e Validacao

Objetivo: conectar os artefatos da Sprint 1, validar a entrega e demonstrar a pagina final.

| # | Tarefa | Descricao | Responsavel | Branch | Status | Criterios de Aceitacao |
|---|--------|-----------|-------------|--------|--------|------------------------|
| 6 | Criar branch de integracao | Criar `feature/integracao-html-css-validacao` a partir da `main` apos os merges da Sprint 1. | Aluno 1 | `feature/integracao-html-css-validacao` | A fazer | Branch criada a partir da `main` atualizada com HTML e CSS. |
| 7 | Integrar CSS ao HTML | Adicionar `<link rel="stylesheet" href="assets/css/styles.css">` e aplicar classes/ids planejados no HTML. | Aluno 1 e Aluno 2 | `feature/integracao-html-css-validacao` | A fazer | HTML passa a usar os hooks definidos no CSS e a pagina carrega os estilos corretamente. |
| 8 | Validar integracao e responsividade | Testar a landing page em navegador, conferir ancoras, carregamento do CSS e responsividade em celular, tablet e desktop. | Aluno 1 | `feature/integracao-html-css-validacao` | A fazer | Validacao registrada em `VALIDACAO.md`, incluindo resultados e observacoes. |
| 9 | Revisar entrega integrada | Conferir se a pagina comunica Scrum, papeis, eventos, artefatos, beneficios e chamada final. | Aluno 2 | PR da branch de integracao | A fazer | PR revisado com foco em qualidade visual, conteudo e funcionamento. |
| 10 | Demonstrar Sprint Review | Apresentar fluxo Git, arquivos criados, PRs, integracao e landing page funcionando. | Aluno 1 e Aluno 2 | `main` | A fazer | Entrega demonstrada e evidencias registradas no backlog. |

---

## Evidencias de Git e GitHub

| Pessoa | Tarefa relacionada | Link ou hash do commit | Link do Pull Request | PR revisado por | Merge realizado? |
|--------|--------------------|------------------------|----------------------|-----------------|------------------|
| Aluno 1 | Criar HTML5 puro |                        |                      | Aluno 2            |                  |
| Aluno 2 | Criar CSS3 responsivo |                        |                      | Aluno 1 |                  |
| Aluno 1 e Aluno 2 | Integrar HTML + CSS |                        |                      | Aluno 2            |                  |
| Aluno 1 | Validar integracao |                        |                      | Aluno 1 |                  |

---

## Sprint Review

**Link do repositorio publico:**  

**Como executar ou acessar a landing page:**  

**Principais entregas demonstradas:**

- Branch HTML5 com `index.html` puro.
- Branch CSS3 com stylesheet responsivo separado.
- Branch de integracao com HTML conectado ao CSS.
- Validacao da responsividade e do conteudo.

**Itens incompletos ou fora do escopo:**

- Nao ha JavaScript nesta atividade.
- A pagina e estatica e focada na pratica de Scrum + Git.

---

## Observacoes / Bloqueios

- A separacao entre HTML sem hooks e CSS com seletores planejados foi intencional para criar uma atividade real de integracao na Sprint 2.
- A comunicacao entre responsaveis deve ser reforcada antes da integracao para alinhar nomes de classes, ids e estrutura esperada.
