# Mapa de Áreas de Risco do DF – Demonstrativo Social 2026

Mapa interativo das 23 áreas de risco do Distrito Federal publicadas na **Portaria SSP/DF nº 63, de 14 de setembro de 2026** (DODF nº 172, de 16/09/2026), que torna público o Demonstrativo Social 2026 previsto na Lei nº 5.861/2017.

- `index.html`: a aplicação (Leaflet + MapLibre, mapa base OpenFreeMap/OpenStreetMap, satélite Esri).
- `data/areas.json`: os dados do quadro do Art. 1º. A página lê este arquivo a cada acesso; edite-o para atualizar o mapa.
- `docs/portaria-63-2026.pdf`: a Portaria, anexada para consulta.
- `data/areas-2025.json`: o Demonstrativo 2025 (Portaria nº 69/2025), pareado com 2026 por região e endereço, para a comparação.
- `data/ras.geojson`: limites das regiões administrativas (IPEDF) com a população do Censo 2022 (IBGE, elaboração IPEDF).
- `data/zee-erosao.geojson` e `data/drenagem.geojson`: risco de perda de solo por erosão (ZEE-DF) e trechos de drenagem, do catálogo do IPEDF.
- `data/setores.geojson` (opcional): polígonos oficiais dos setores de risco, quando a Defesa Civil os publicar.

## Formas de visualização
Pontos (classe, tipo e população), Zonas indicativas (área proporcional às residências), Regiões (pessoas afetadas por RA, absoluto e por 10 mil habitantes), Matriz de ameaças (áreas × tipos Cobrade) e 2025 × 2026 (o que mudou entre os Demonstrativos). O botão Camadas acrescenta as camadas oficiais de contexto.

Iconografia própria, organizada pelos grupos da Classificação e Codificação Brasileira de Desastres (Cobrade) e pela divisão entre riscos hidrológicos e geológicos usada pelo Cemaden.

Nas áreas 16 e 18, os números seguem a Portaria; o popup traz uma ressalva sobre a divergência com outra versão dos dados.

## Autoria
Wagner de Jesus Martins, Fernanda Machiner, Maria Eduarda Silva, Jeferson Martins de Castro.

Mapa base: dados © colaboradores do OpenStreetMap (ODbL), estilo OpenFreeMap / OpenMapTiles. Este mapa não substitui o texto oficial.
