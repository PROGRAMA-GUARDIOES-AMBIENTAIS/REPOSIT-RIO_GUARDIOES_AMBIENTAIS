# dados — coordenadas

> diretório de coordenadas geográficas coletadas em campo.

## finalidade

armazenar **coordenadas geográficas** obtidas com gnss, receptores diversos, drones ou extraídas de fontes oficiais.

## formatos aceitos

- `.csv` — utf-8, separador vírgula ou ponto-e-vírgula;
- `.txt` — texto estruturado;
- `.kml` / `.kmz` — google earth;
- `.gpx` — gps exchange;
- `.geojson` — geojson;
- `.shp` — shapefile (componentes auxiliares no `.gitignore` por padrão, gerenciados externamente).

## nomenclatura

```
AAAA-MM-DD_local_ponto_NNN.csv
```

exemplo: `2026-07-31_garanhuns_aterro_001.csv`.

## sistema de referência

- preferir **sirgas 2000** (oficial brasil);
- informar **sistema de referência** em cada arquivo;
- registrar **projeção** quando aplicável (utm, geográfica);
- anotar **precisão** do equipamento.

## metadados obrigatórios

cada conjunto de coordenadas deve registrar:

- fonte (quem coletou, quando);
- sistema de referência;
- projeção;
- precisão;
- equipamento utilizado;
- descrição dos pontos;
- licença de uso.

## cuidados

- **não versionar** shapefiles grandes (`.shp`, `.shx`, `.dbf`) — usar `.gitignore` ou git-lfs;
- preferir formatos **abertos** (geojson, kml, gpx, csv);
- documentar **transformações** aplicadas (datum, projeção).

---

> **documento em construção.**
