# growth-insight-skill

Uma **skill de Claude / Claude Code** que condensa as edições da newsletter
**[Growth Insight](https://growthinsight.com.br)** (de Felipe Collins & Felipe Witt) em uma
**base de conhecimento acionável** de growth e marketing — frameworks, modelos, playbooks e
princípios, organizados por tema e prontos para virar decisão.

## O que é
Um "fundo de conhecimento" que Claude carrega sempre que a tarefa exige **repertório estratégico,
teórico, analítico ou de planejamento** em growth/marketing. Cada edição foi destilada em pontos
acionáveis, com link para o artigo original.

## Atribuição
Este repositório é uma **destilação com atribuição**, não uma republicação. O conteúdo intelectual
(frameworks, teses, exemplos) pertence a **Felipe Collins e Felipe Witt / Growth Insight**. Cada
item de referência linka a edição-fonte; para o texto integral, assine e leia em
**https://growthinsight.com.br**. Edições premium/paywall não são reproduzidas (marcadas como lacuna
em [`sources.md`](sources.md)).

## Instalação
Clone dentro da pasta de skills do seu Claude Code:

```bash
git clone https://github.com/guilhermecalligaris-design/growth-insight-skill \
  ~/.claude/skills/growth-insight
```

A skill fica disponível como `growth-insight` e é acionada automaticamente em tarefas de estratégia,
GTM, branding, copywriting, canais, moats, IA no marketing, gestão e carreira.

## Estrutura
```
SKILL.md              # gatilho + roteador + princípios de uso
sources.md            # as 131 URLs com status de condensação
references/
  INDEX.md            # mapa edição → arquivo
  frameworks.md       # catálogo de frameworks nomeados (consulta rápida)
  estrategia.md  growth.md  gtm.md  branding.md  copywriting.md
  b2b.md  canais-taticas.md  ia-marketing.md  gestao-carreira.md  tendencias.md
```

## Status
Construção em lotes — veja o progresso em [`sources.md`](sources.md).
