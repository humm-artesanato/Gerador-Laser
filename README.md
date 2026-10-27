# Gerador de caixas a laser

Página única (HTML + JavaScript, sem servidor) que gera SVG de caixas para corte a laser em MDF de 3 mm, com visualização 3D.

## Tipos de caixa
- **Caixas basculantes**: dobradiça lateral (estilo MakerCase) e dobradiça traseira (estilo IntegratedHingeBox do boxes.py).
- **Caixa fechada**: formato cubo e formato cunha (rampa).
- Divisórias internas, largura dos dentes, medidas internas ou externas, chapa de 380 × 300 mm (pode ser ultrapassada) e três modos de corte (peças separadas, agrupado, linha comum).

## Como usar
Abra o `index.html` no navegador, ou publique no GitHub Pages:
1. Crie um repositório e envie estes arquivos.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. A página ficará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

A visualização 3D carrega o Three.js (r128) do cdnjs, então precisa de internet.

## Créditos e licença
A dobradiça traseira é um port para JavaScript da lógica do `IntegratedHingeBox` e das arestas `ChestHinge` do projeto
[boxes.py](https://github.com/florianfesti/boxes) (Florian Festi), licenciado sob **GPLv3**.
Por isso este projeto também é distribuído sob a **GNU GPL v3** (arquivo `LICENSE`).
