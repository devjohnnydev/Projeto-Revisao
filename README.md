# Revisão de Semestre · HTML, CSS e JavaScript DOM

**Escola SENAI Morvan Figueiredo** · Curso Técnico em Desenvolvimento de Sistemas
Prof. Johnny Braga de Oliveira

Atividade de revisão contextualizada: os alunos (Morvan Dev Studio) constroem a landing page da startup fictícia **EcoBike SP**, praticando HTML semântico, CSS moderno, functions e manipulação do DOM.

## O que tem no site
| Seção | Conteúdo |
|---|---|
| Contexto | Briefing do cliente (e-mail da CEO) e papel do aluno |
| Missões | 18 requisitos com checklist salvo no navegador |
| Código base | `index.html`, `style.css`, `script.js` com TODOs (copiar/baixar) |
| Quiz | 35 questões (HTML, CSS, JS, DOM) com explicação, filtro e embaralhar |
| Qual a saída? | 18 trechos de código: o aluno prevê o console e depois executa |
| Lab de Functions | 10 funções com testes automáticos (`return` comparado ao esperado) |
| Lab de DOM | 8 desafios com prévia ao vivo e verificador que clica nos botões |
| Avaliação | Rubrica de 10 pontos + bônus, passo a passo do GitHub Pages |
| Meu progresso | Medidores e relatório copiável para o aluno entregar |

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `revisao-ds`) e envie **o conteúdo desta pasta** (`index.html`, `css/`, `js/`, `favicon.ico`).
2. *Settings → Pages → Deploy from a branch → main / (root) → Save*.
3. Endereço: `https://SEU-USUARIO.github.io/revisao-ds/`

Não há build nem dependências: é HTML, CSS e JS puros. O progresso do aluno fica no `localStorage` do navegador dele.

## Como editar o conteúdo
Tudo está em `js/dados.js`:
- `QUIZ` — `{ id, cat, q, code?, lang?, opts, ans, exp }` (`ans` é o índice da opção certa)
- `SAIDAS` — `{ titulo, nivel, code, esperado, dica }` (uma linha de `esperado` por `console.log`)
- `FUNCOES` — `{ id, nome, titulo, enunciado, starter, testes: [[args], esperado], dica }`
- `DOM_DESAFIOS` — `{ id, titulo, enunciado, html, css?, starter, verificar(doc) }`
- `MISSOES` e `STARTER` — checklist e arquivos base do projeto

> O gabarito fica na pasta `gabarito-professor/`, **fora** do site. Não publique essa pasta.
