# ENEM Serafim de Carvalho — Análise 2026

Dashboard de desempenho do 1º dia do ENEM 2026 (CEPI Serafim de Carvalho, Jataí-GO).
Resultados em **acertos brutos** (gabarito preliminar), sem nota TRI.

## Estrutura
- `index.html` — aplicação completa (HTML + CSS + JS), versão 2 (layout moderno, mobile-first). Dados e regras de correção preservados; totais por estudante conferidos contra a versão anterior.
- `assets/logo-serafim.png` — brasão da escola (adicionar manualmente; ver `assets/LEIA-ME.txt`).
- `docs/DIAGNOSTICO_E_PLANO.md` — diagnóstico técnico e plano de evolução (aguardando aprovação).

## ⚠️ Antes de publicar
O `index.html` contém **nomes e respostas reais de estudantes**. Em GitHub Pages público,
qualquer pessoa poderia ler esses dados. **Não publique em repositório/página pública**
até que a etapa de privacidade (seção 5 do diagnóstico) seja aplicada.
Use repositório **privado** para guardar o código enquanto isso.

## Mudanças da versão 2
- Respostas em branco aparecem em **cinza** na grade do estudante e contam como erro (também na aba Questões, com coluna "Em branco").
- Navegação lateral no computador e barra inferior no celular; cartões, gráficos e tabelas responsivos.
- Estudante selecionado por identificador (não muda ao trocar filtros); clique no nome na tabela abre a análise individual.
- Tabela com cabeçalho fixo, ordenação por clique e destaque ▲/▼ acima/abaixo da média; menor resultado nos indicadores; ordenação de questões por menor taxa.

## Publicar no GitHub Pages
Settings → Pages → Branch `main` / pasta `/ (root)`. Lembre-se de adicionar `assets/logo-serafim.png`.
