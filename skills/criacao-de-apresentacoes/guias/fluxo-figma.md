# Fluxo no Figma (via MCP)

Só comece a trabalhar no Figma quando o usuário pedir e depois que ele aprovar o roteiro.

## Arquivo de destino
- O link do arquivo Figma vem **no prompt**. Se não vier, peça antes de criar ou ofereça criar um arquivo novo.
- Cada apresentação ganha uma **página nova** chamada `AAAA-MM-DD – Nome da apresentação`. Confira antes se ela já existe, para não duplicar.
- Não altere nem apague páginas ou elementos que já existiam, a menos que o usuário peça.

## Passo a passo
1. Abra a sessão no arquivo (`create_session` com o fileKey) e carregue as orientações do Figma MCP antes de escrever.
2. Procure estilos e variáveis da marca no arquivo (cores, estilos de texto). Se existirem, use-os. Se não existirem, use os valores de `identidade-visual.md`.
3. Carregue as fontes (Montserrat e Baskerville Old Face, com Libre Baskerville como alternativa) antes de criar textos.
4. Crie uma **Section** com o nome da apresentação. Dentro dela, um **frame 1920×1080 por slide**, lado a lado, com 120 px entre eles, nomeados `01 – Capa – L01`, `02 – Agenda – L03` etc. (número, conteúdo, layout).
5. Use Auto Layout para blocos de texto, listas e cartões, para manter o espaçamento consistente.
6. Depois de cada 3–4 slides, tire screenshot e revise. No final, revise o deck inteiro lado a lado para checar consistência.
7. Entregue o link da página e a lista de placeholders a preencher.

## Placeholders de imagem e elementos gráficos

Imagens e elementos são colocados manualmente pelo usuário depois. Cada área reservada precisa ser fácil de achar e de substituir:

- **Foto:** retângulo (ou forma com o recorte do layout: curva, arco) com preenchimento **Oliva `#848158` a 35%**, nomeado `IMG – descrição` (ex.: `IMG – garrafas Malbec na mesa`). No centro, um texto pequeno em Montserrat 16 px Creme com a mesma descrição e a proporção ideal (ex.: `FOTO · garrafas Malbec · 4:5`).
  - Para trocar, o usuário seleciona a camada e aplica a foto como preenchimento (*Fill → Image*). O recorte e a posição se mantêm. Avise que o texto-guia deve ser apagado depois.
- **Produto recortado (garrafas sem fundo):** mesmo padrão, nomeado `IMG-PRODUTO – descrição`.
- **Elemento gráfico** (selo, ícone, textura, ornamento): retângulo com contorno tracejado Dourado `#C9A07A` de 2 px, sem preenchimento, nomeado `ELEM – descrição` (ex.: `ELEM – selo Black Friday`).
- **Logo:** se `elementos-graficos/logos/logo-voluto-branca.png` puder ser enviado ao Figma (upload de assets), use o arquivo real. Se não puder, crie `ELEM – logo Voluto branca` no tamanho e posição corretos.
- Se o usuário já tiver colocado fotos em `imagens/` com nome compatível, envie-as e use no lugar do placeholder.

O nome das camadas é o que permite ao usuário (e ao Claude em edições futuras) achar cada área. Mantenha o padrão `IMG – …` / `ELEM – …` sempre.
