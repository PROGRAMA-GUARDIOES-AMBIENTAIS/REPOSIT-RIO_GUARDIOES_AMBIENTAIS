# dados — tabelas

> diretório de tabelas e dados tabulares do programa.

## finalidade

armazenar **planilhas** e **tabelas estruturadas** com dados de visitas, diagnósticos, indicadores e levantamentos.

## formatos aceitos

- `.csv` — utf-8, separador vírgula ou ponto-e-vírgula;
- `.tsv` — tab-separated;
- `.xlsx` — excel moderno (até 2007+);
- `.ods` — formato aberto libreoffice;
- `.json` — dados estruturados;
- `.parquet` — colunar (análise de dados).

## nomenclatura

```
AAAA-MM-DD_local_tipo_descricao.csv
```

exemplos:

- `2026-07-31_garanhuns_aterro_indicadores.csv`;
- `2026-07-31_garanhuns_entrevistas.csv`.

## estrutura mínima

cada tabela deve conter:

- **cabeçalho** descritivo;
- **dicionário de dados** (em arquivo `.md` irmão ou em comentário no início do arquivo);
- **unidades** quando numérico;
- **fonte** dos dados;
- **data** de produção;
- **responsável**.

## cuidados

- arquivos `.xlsx` grandes podem ser substituídos por `.csv`;
- **não versionar** arquivos com macros ou fórmulas proprietárias sem alternativa aberta;
- documentar **codificação** (utf-8 com ou sem bom).

---

> **documento em construção.**
