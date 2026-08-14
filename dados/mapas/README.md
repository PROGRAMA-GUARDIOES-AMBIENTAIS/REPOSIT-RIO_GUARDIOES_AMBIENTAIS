# dados — mapas

> diretório de mapas produzidos ou utilizados pelo programa.

## finalidade

armazenar **mapas temáticos**, **cartas**, **imagens de satélite**, **mosaicos** e **modelos** produzidos em campo ou em gabinete.

## formatos aceitos

- `.png`, `.jpg`, `.webp` — mapas exportados (visualização);
- `.pdf` — mapas vetoriais;
- `.tif` / `.tiff` — imagens georreferenciadas (grandes, gerenciar com cautela);
- `.geojson`, `.kml`, `.kmz` — mapas vetoriais abertos;
- `.qgz` — projetos qgis (geralmente não versionar — usar `.gitignore`);
- `.qml` — estilos de camada qgis (versionar).

## nomenclatura

```
AAAA-MM-DD_local_tipo_descricao.png
```

exemplos:

- `2026-07-31_garanhuns_localizacao.png`;
- `2026-07-31_garanhuns_uso_solo.png`;
- `2026-07-31_garanhuns_aterro_ortofoto.tif`.

## metadados obrigatórios

cada mapa deve registrar:

- título;
- autor;
- data de produção;
- sistema de referência;
- projeção;
- escala / resolução;
- fontes de dados;
- licença.

## produção

ferramentas utilizadas:

- qgis;
- google earth engine;
- software de drone (pix4d, dronesmadeeasy, etc.);
- inkscape / gimp para edição final;
- arcgis (quando aplicável).

---

> **documento em construção.**
