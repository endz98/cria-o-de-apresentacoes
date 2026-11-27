---
name: criacao-de-apresentacoes
description: Cria apresentações padronizadas da Voluto Vinhos direto no Figma via MCP, com as cores, fontes, logo, layouts e áreas de imagem da marca. Use sempre que o usuário pedir uma "apresentação", "slides", "deck", "proposta comercial", "pitch", "apresentação de campanha", "relatório para cliente/diretoria" ou qualquer material em formato de slides, mesmo que não diga "apresentação" explicitamente (ex.: "monta o material da reunião da Black Friday", "prepara uns slides pros parceiros").
---

# Criação de Apresentações — Voluto Vinhos

## Divisão de responsabilidades

- **Esta Skill define o padrão:** identidade visual, tipos de slide, grid e onde imagens e elementos gráficos entram.
- **O prompt do usuário define o conteúdo:** tema, objetivo, público, quantidade de slides, textos, dados e qualquer briefing específico.
- **Ajustes vêm depois**, pelo chat ou feitos à mão pelo usuário no Figma. Antes de editar um deck existente, leia o estado atual no Figma para não desfazer alterações manuais.

Quando o prompt pedir algo que contrarie a Skill (ex.: outra cor), o prompt vence, porque é a decisão mais recente do usuário.

## Arquivos da Skill

| Arquivo / pasta | Conteúdo | Quando ler |
|---|---|---|
| `guias/identidade-visual.md` | Cores, fontes, hierarquia tipográfica, tom de voz, logo | **Sempre**, antes de criar |
| `guias/estrutura-de-slides.md` | Sequência do deck, grid e catálogo de layouts com áreas de imagem | Ao montar o roteiro e cada slide |
| `guias/fluxo-figma.md` | Como trabalhar no Figma via MCP, nomes e placeholders | Antes da primeira chamada ao Figma |
| `referencias/` | Prints de estilo (o `LEIA-ME.md` diz o que aproveitar de cada um) | Ao definir o visual, abra as imagens |
| `elementos-graficos/` | Logo e futuros elementos da marca | Ao montar capa e fechamento |
| `imagens/` | Fotos (adicionadas aos poucos pelo usuário) | Se houver arquivos, use; senão, placeholder |
| `modelos/briefing.md` | Checklist do que um pedido precisa ter | Quando faltar informação no prompt |

## Fluxo

1. **Ler o pedido.** Extraia objetivo, público, número de slides e conteúdo. Se faltar algo essencial (objetivo ou conteúdo principal), pergunte de forma breve. O resto, assuma e avise o que assumiu.
2. **Ler `identidade-visual.md` e `estrutura-de-slides.md`** e abrir as imagens de `referencias/`. As referências mostram **estilo e layout**, não as cores ou fontes: o visual final usa sempre a paleta e as fontes da Voluto.
3. **Propor o roteiro antes de desenhar.** Uma lista com número, layout escolhido (código do catálogo, ex.: `L03`), título e resumo do conteúdo de cada slide. Espere o OK do usuário. Refazer no Figma custa caro, refazer uma lista não.
4. **Montar no Figma** seguindo `fluxo-figma.md`. Onde entrar foto ou elemento gráfico, crie o **placeholder padronizado** descrito lá, que o usuário troca depois manualmente.
5. **Revisar.** Screenshot de cada slide: alinhamento ao grid, contraste, texto cortado, hierarquia, consistência entre slides. Corrija (até 3 rodadas).
6. **Entregar.** Link da página no Figma e um resumo curto: o que foi criado, o que foi assumido, a lista de placeholders de imagem a preencher e qualquer `[CONFIRMAR]` pendente.

## Princípios

- **Minimalista e informativo.** Muito espaço livre, um ponto de destaque por slide, poucas cores por slide (fundo + texto + no máximo um acento).
- **Texto médio, nunca extenso.** Tópicos curtos são bem-vindos. Se o conteúdo não couber com folga, divida em dois slides.
- **Consistência.** Mesmas margens, grid, estilos de texto e posição do logo/rodapé em todo o deck.
- **Nada de inventar.** Preços, datas, números e nomes de vinhos vêm do prompt. Se faltar, escreva `[CONFIRMAR]` no lugar.
