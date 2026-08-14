# política de segurança

este repositório é **público para leitura** mas pode conter informações sensíveis quando mal utilizado. este documento orienta condutas para preservar a segurança do programa, das pessoas e das instituições.

## 1. dados que **nunca** devem ser commitados

**proibido armazenar** neste repositório:

- senhas, tokens, chaves de api;
- credenciais de acesso a sistemas;
- cpf, rg ou documentos pessoais;
- dados pessoais sensíveis (saúde, religião, orientação política);
- dados privados de terceiros sem consentimento;
- contratos, termos ou documentos sigilosos;
- informações privadas de empresas parceiras.

## 2. boas práticas

- revisar **todo arquivo** antes do commit;
- usar **.gitignore** para impedir inclusão acidental;
- em caso de dúvida, **não commitar** e consultar a coordenação;
- se um segredo for exposto acidentalmente:
  1. **revogar imediatamente** a credencial;
  2. remover do histórico (ex.: `git filter-repo`);
  3. notificar a coordenação.

## 3. imagens e mídias

fotografias devem sempre estar acompanhadas de:

- **autor**;
- **data**;
- **local**;
- **evento**;
- **descrição**;
- **licença**;
- **fonte** (se externa).

> fotografias externas **nunca** devem ser apresentadas como se fossem produzidas pela equipe.

## 4. dados pessoais em atas e relatórios

em documentos institucionais:

- evitar nomes próprios quando desnecessário;
- preferir cargos ou funções ("coordenador", "técnico ambiental");
- quando citar pessoas, obter **autorização prévia**;
- **anonimizar** dados sensíveis em amostras de documentos.

## 5. reporte de vulnerabilidades

caso identifique alguma falha de segurança neste repositório, reporte à coordenação do programa através dos canais institucionais.

## 6. auditoria periódica

- revisar o repositório em busca de credenciais expostas;
- verificar links externos quebrados;
- validar licenças de imagens e dados.

---

> **documento em construção.**
