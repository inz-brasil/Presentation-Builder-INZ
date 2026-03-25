# 🟣 Presentation Builder Pack — by INZ

<div align="center">

**O motor definitivo com 5 skills de Design e Copy para agentes de IA**

Transforma qualquer IDE com agente de IA em uma agência produtora de Apresentações completas e irretocáveis.

[![Skills](https://img.shields.io/badge/skills-5-blueviolet)]()
[![Workflow](https://img.shields.io/badge/workflow-1-orange)]()
[![License](https://img.shields.io/badge/license-free-green)]()
[![Platform](https://img.shields.io/badge/platform-any%20AI%20agent-blue)]()

Criado por **INZ** · [Instagram @inzbrasil](https://instagram.com/inzbrasil)

</div>

---

## O que é isso?

Um pack gratuito com **5 skills prontas + 1 workflow** que ensina o seu agente de IA (Antigravity, Claude Code, Cursor, Copilot, Windsurf, etc.) a trabalhar como uma agência formadora de apresentações. Instale no seu projeto, acione o workflow e o agente atuará simultaneamente como diretor de arte, redator e programador do zero, entregando desde PDFs imutáveis até Web Apps interativos.

Funciona com qualquer agente que leia Markdown: Antigravity, Claude Code, Cursor, Windsurf, Copilot.

---

## Skills incluídas

### Estratégia e Copywriting
| Skill | O que faz |
|-------|-----------|
| `copywriting` | Escreve textos humanizados, filtrados de jargões de IA (Em Resumo, Neste Slide) visando conversão e fluidez no design. |
| `seo-fundamentals` | Caso opte por gerar uma apresentação em Web (HTML/React), aplica as tags, meta descriptions e semântica pro Google ranquear. |

### Design e Construção Visual
| Skill | O que faz |
|-------|-----------|
| `ui-ux-pro-max` | Cuida da paleta de cores (contraste premium), espaçamento matemático, respiro em tela e dita a geometria lógica das IAs. |
| `frontend-design` | Converte o pensamento UI/UX em arquiteturas flexíveis no código-fonte, aplicando a estética. |
| `web-artifacts-builder` | Permite o prototipador de artefatos web no background construir componentes modulares lindíssimos. |

---

## Workflow Central

Além das Skills, este pack obedece a uma inteligência estrita em passos:

| Workflow | O que faz |
|----------|-----------|
| `presentation-builder` | O grande Maestro. Freia a IA e a força a cumprir 5 passos: (1) Briefing e Paletas, (2) Redação Humana, (3) Arte Código, (4) Pente-Fino e (5) Publicação Versionada. |

---

## Organização automática

Todo conteúdo e documento produzido usando este ecossistema obedecerá a regra `RULES.md` de versionamento rigoroso e zero bagunça:

```
Apresentacoes/
└── Meu_Projeto_Exemplo/
    ├── src/
    │   ├── App.tsx
    │   ├── index.css
    │   └── assets/
    └── build/
        ├── Meu_Projeto_Exemplo_v1.pdf
        └── Meu_Projeto_Exemplo_v2.pdf
```

Zero confusão de versões ou overwrites de arquivos do passado.

---

## Como instalar

### Antigravity / Gemini CLI

A mais simples. Copia e funciona:

```
seu-projeto/
└── .agent/
    ├── workflows/    ← Mova `presentation-builder.md` aqui
    └── skills/       ← Mova toda a pasta de skills aqui
```

**Passo a passo:**
1. Copie todo o pacote `skills/` para o diretório `seu-projeto/.agent/skills/`.
2. Pegue o arquivo mestre em `workflow/` e largue em `seu-projeto/.agent/workflows/`.
3. Anexe ou cole o conteúdo do `RULES.md` aos System Prompts ou simplesmente os cite. Use a call `@[/presentation-builder]` no terminal de chat, a integração é plug-and-play.

---

### Claude Code

No Claude Code, skills viram comandos:

```
seu-projeto/
├── .claude/
│   └── commands/     ← Cada SKILL.md vira um command
└── CLAUDE.md         ← Rules combinadas aqui
```

**Passo a passo:**
1. Crie a pasta oculta `.claude/commands/` na raiz do projeto.
2. Para cada skill original, direcione o `SKILL.md` para `.claude/commands/nome-da-skill.md`.
3. Crie `CLAUDE.md` na raiz fundindo o que estiver escrito aí com a íntegra de `RULES.md`. Chame o arquivo mestre de workflow na conversa livremente.

---

### Cursor

```
seu-projeto/
├── .cursor/
│   └── rules/        ← Rules organizadas aqui
├── .cursorrules       ← Conteúdo do RULES.md copiado aqui
└── skills/            ← Pasta skills colocada na root do projeto
```

**Passo a passo:**
1. Crie o imbatível arquivo `.cursorrules` (arquivo de leitura matriz do AI do Cursor) jogando lá dentro o texto das nossas regras rígidas (`RULES.md`).
2. Mantenha as pastas das skills visíveis. Pressione Cmd/Ctrl+L para o Chat, puxe usando a menção dupla (`@`) no arquivo do workflow, e ele absorverá.

---

### Windsurf (Codeium)

```
seu-projeto/
├── .windsurfrules     ← Conteúdo de RULES.md 
└── .windsurf/
    └── skills/        ← Toda a esteira de skills aqui
```

1. Crie `RULES.md` -> `.windsurfrules`.
2. Instale e vincule a pasta `skills/` visível ao engine.

---

### GitHub Copilot

```
seu-projeto/
├── .github/
│   ├── copilot-instructions.md  ← Cole RULES.md aqui
│   └── skills/                  ← Skills da esteira soltas aqui
```

1. Crie `.github/copilot-instructions.md` com a nossa injeção de comportamento de regras.
2. Empurre `skills/` e `workflow/` para reposição de conhecimento visual.

---

### Qualquer outro agente (Universal)

A esteira funciona organicamente com qualquer LLM que suporte RAG ou documentação anexada (ChatGPT, Claude Web):

1. **Upload:** Jogue a árvore completa de pastas para o projeto ou para a base de arquivos da IA.
2. **System Prompt / Regras Custom:** Pegue o `RULES.md` e defina essas diretrizes como Lei incondicional para aquele chat ou Workspace.
3. Peça no chat explicitamente: *"Inicie o workflow presentation-builder"*.

---

## Como usar

Depois que todas as pastas e a regra-base estiverem apontadas, acione o motor pedindo naturalmente, ex:

| Você diz | O agente faz |
|----------|-------------|
| "inicie o presentation-builder pra minha aula" | O Agente vira diretor de arte, aciona a SKILL de Design e UX, e inicia o painel visual pedindo arquivos da aula, logs (Etapa 1). |
| "vou querer em webapp interativo e exportado pra Mobile" | Ativa as regras puras de SEO e Frontend, trancando a redação e já criando os blocos base CSS (Passo 2 e 3). |
| "ta legal, finaliza pra mim" | O bot lê a própria tela, confere contraste WCAG, avalia texto por texto em caça a Emojis e exporta versão imutável em `build/` (Passo 4 e 5). |

O segredo de tudo está fundamentado no arquivo **RULES.md**. Ignorar as RULES fará o LLM pular direto para a criação do texto como um robô chato. **Sempre instale as rules junto com as skills.**

---

## Estrutura do pack

```
PRESENTATION BUILDER PACK/
├── README.md
├── RULES.md                      ← Mapa operacional e freios (identidade do agente)
├── workflow/
│   └── presentation-builder.md   ← Esteira mandatória rigorosa de 5 Passos
└── skills/
    ├── copywriting/SKILL.md
    ├── frontend-design/SKILL.md
    ├── seo-fundamentals/SKILL.md
    ├── ui-ux-pro-max/SKILL.md
    └── web-artifacts-builder/SKILL.md
```

---

## Créditos e Licença

Criado por **INZ** · [@inzbrasil](https://instagram.com/inzbrasil)

Livre para uso pessoal e comercial. Compartilhe a vontade, só mantenha os créditos.
