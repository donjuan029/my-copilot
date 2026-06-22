# 🤖 My Copilot — Dev Stack

> System prompts para GitHub Copilot (Chat) calibrados para a stack de Java/Spring Boot,
> Spring AI, Python e LLMs. Baseado na estrutura do projeto
> [my-first-copilot (DIO)](https://github.com/digitalinnovationone/my-first-copilot) com
> expansão de cobertura, integração nativa e prompts completos para todos os 5 modos.

---

## Stack coberta

| Camada | Tecnologias |
|---|---|
| **Backend** | Java 17+, Spring Boot 3.x, Spring AI, Spring Data JPA, Spring Security |
| **Banco de dados** | PostgreSQL, H2, Hibernate / JPA |
| **Frontend** | React, TypeScript, HTML/CSS |
| **IA / LLM** | Spring AI, Ollama (qwen3), Google Gemini API |
| **Infra / Build** | Maven, Git, GitHub, Docker |

---

## Como usar

### Opção 1 — Integração nativa (recomendada)

Copie o arquivo `.github/copilot-instructions.md` para a raiz do seu projeto.
O GitHub Copilot lerá automaticamente esse arquivo como contexto global.

```
seu-projeto/
└── .github/
    └── copilot-instructions.md   ← copie este arquivo
```

### Opção 2 — Modo sob demanda

Cole o conteúdo do prompt desejado diretamente no GitHub Copilot Chat antes de iniciar
uma sessão de trabalho.

---

## Os 5 modos

| Modo | Arquivo | Quando usar |
|---|---|---|
| **ASK** 🔍 | `prompt/prompt-ask.md` | Entender erros, analisar código, esclarecer conceitos |
| **EDIT** ✏️ | `prompt/prompt-edit.md` | Refatorar, corrigir bugs, melhorar código existente |
| **PLAN** 🗺️ | `prompt/prompt-plan.md` | Planejar features, decisões de arquitetura |
| **AGENT** 🤖 | `prompt/prompt-agent.md` | Implementar tarefas completas de ponta a ponta |
| **STUDY** 📖 | `prompt/prompt-study.md` | Aprender conceitos em profundidade com exemplos reais |

---

## Personalização

Cada prompt tem seções marcadas como `(EDITÁVEL)`. Para adaptar a um projeto específico:

1. **STACK** — ajuste as tecnologias do projeto atual
2. **PERSONALIDADE** (ASK/STUDY) — ajuste tom e nível de detalhe
3. **REGRAS** — adicione ou remova regras conforme as convenções do time

---

## Referência mental rápida

```
Erro / dúvida?          → ASK
Código ruim / bug?      → EDIT
Nova feature?           → PLAN → AGENT
Conceito desconhecido?  → STUDY
```

---

## Créditos

Estrutura de modos inspirada em [digitalinnovationone/my-first-copilot](https://github.com/digitalinnovationone/my-first-copilot).
Prompts expandidos e calibrados para stack Java/Spring/Python/LLM.
