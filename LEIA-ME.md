# Botões 3D do M30

A base `m30-3d-base.svg` foi refeita com `Fontes/m30-oficial-frente-Photoroom.png`, e a desconexão `m30-3d-desconectado.svg` usa `Fontes/m30-oficial-desconnected.png`. As duas fontes têm 1500 × 1500 px e foram colocadas no mesmo enquadramento de **650 × 354 px** dos SVGs anteriores. Os arquivos dos botões não foram alterados. As prévias atualizadas estão em `Previas`.

Cada arquivo SVG mede **650 × 354 px**. A imagem de base já contém os botões fotografados; as camadas abaixo acrescentam o relevo e a indicação de pressão sem deslocá-los.

Para cada peça no GamePad Viewer, use **Width = 650**, **Height = 354**, **Top = 0**, **Left = 0**:

- **Neutral State Image URL:** `m30-3d-neutro-NOME.svg`
- **Pressed State Image URL:** `m30-3d-pressionado-NOME.svg`

`NOME` pode ser `A`, `B`, `C`, `X`, `Y`, `Z`, `DU`, `DD`, `DL`, `DR`, `L`, `R`, `START`, `STAR`, `SELECT` ou `HOME`. Os quatro códigos `D` representam o direcional: cima, baixo, esquerda e direita.

Os SVGs `m30-3d-base.svg` e `m30-3d-desconectado.svg` vão nos estados conectado e desconectado da base. Publique os arquivos em URLs HTTPS diretas antes de preencher os campos. O mapeamento físico dos botões deve ser conferido com o M30 conectado no modo que você usa.
