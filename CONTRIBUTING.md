# guia de contribuição

obrigado por contribuir com o **programa guardiões ambientais**!

este repositório é uma base documental viva. toda contribuição deve seguir os princípios de **organização, rastreabilidade, transparência e reprodutibilidade**.

## quem pode contribuir

- coordenação do programa;
- guardiões ambientais;
- pesquisadores e extensionistas;
- instituições parceiras;
- colaboradores convidados.

> nomes específicos de responsáveis **não devem ser criados sem validação**. consultar [`docs/01_projeto/governanca.md`](./docs/01_projeto/governanca.md).

## como propor alterações

1. faça um **fork** do repositório;
2. crie uma **branch** descritiva:
   - `docs/ajuste-descricao-aterro`
   - `fix/coordenadas-garanhuns`
   - `feat/template-relatorio-visita`
3. siga a **estrutura de pastas** existente;
4. respeite a **nomenclatura padronizada** (`AAAA-MM-DD_descricao`);
5. preencha o **template de pull request**;
6. aguarde **revisão** antes do merge.

## princípios editoriais

- **não inventar informações.** quando faltar dado: *"documento em construção."*
- sempre **separar**:
  - informação fornecida;
  - informação observada;
  - informação pesquisada;
  - interpretação técnica;
  - recomendação.
- aplicar **ABNT** (NBR 14724, NBR 10520, NBR 6023, NBR 6024, NBR 6027, NBR 6028) quando exigido.
- escrever em **português do Brasil**.
- usar **markdown** preferencialmente.
- preferir **minúsculas** e nomes de arquivo sem espaços.

## padrão de mensagens de commit

utilize prefixos:

- `docs:` — alterações de documentação;
- `feat:` — novas funcionalidades ou seções;
- `fix:` — correções;
- `refactor:` — reorganização sem mudança de conteúdo;
- `chore:` — manutenção (gitignore, templates, workflows).

exemplos:

- `docs: corrige endereço do aterro de garanhuns`
- `feat: adiciona template de visita técnica`
- `fix: ajusta coordenadas utm do parque euclides dourado`

## checklist antes de abrir pull request

- [ ] documento revisado integralmente;
- [ ] fontes verificadas;
- [ ] dados conferidos;
- [ ] imagens identificadas (autor, data, local, licença);
- [ ] referências conferidas (ABNT);
- [ ] nenhuma informação inventada;
- [ ] links verificados;
- [ ] estrutura do repositório respeitada;
- [ ] changelog atualizado (se aplicável).

## segurança

**nunca** armazene no repositório:

- senhas, tokens, chaves de api;
- cpf, dados pessoais sensíveis;
- credenciais de sistemas;
- documentos privados.

> veja [`SECURITY.md`](./SECURITY.md).

## governança

detalhes sobre aprovação, revisão e versionamento: [`docs/01_projeto/governanca.md`](./docs/01_projeto/governanca.md).

---

> **documento em construção.**
