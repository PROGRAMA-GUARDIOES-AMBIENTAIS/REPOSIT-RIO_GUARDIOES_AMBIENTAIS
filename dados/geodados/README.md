# dados — geodados

> diretório de dados geográficos do programa (vetoriais, raster, modelos 3d).

## finalidade

armazenar **dados geográficos** brutos e processados, utilizados em análises espaciais e produção de mapas.

## formatos aceitos

### vetoriais
- `.geojson` — geojson;
- `.kml`, `.kmz` — google earth;
- `.gpx` — gps;
- `.shp` — shapefile (componentes auxiliares no `.gitignore`);
- `.gml` — geography markup language;
- `.gpkg` — geopackage.

### raster
- `.tif`, `.tiff` — geotiff;
- `.ecw` — compressed wavelet;
- `.jp2` — jpeg 2000;
- `.sid` — mr sid.

### modelos 3d
- `.las`, `.laz` — nuvem de pontos;
- `.ply` — modelo 3d;
- `.obj` — modelo 3d;
- `.gltf`, `.glb` — modelo web.

## nomenclatura

```
AAAA-MM-DD_local_tipo_descricao.ext
```

## metadados obrigatórios

para cada arquivo geográfico, registrar:

- **fonte**;
- **data**;
- **sistema de referência** (sirgas 2000 preferencial);
- **projeção**;
- **escala / resolução**;
- **responsável**;
- **licença**;
- **descrição** do conteúdo.

## cuidados

- arquivos grandes devem ser gerenciados com **git-lfs** ou fora do repositório;
- documentar **transformações** aplicadas;
- preferir formatos **abertos** (geojson, geopackage, geotiff).

---

> **documento em construção.**
