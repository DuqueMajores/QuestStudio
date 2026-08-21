# QuestStudio

Aplicação front-end de estudo por questões.

Recursos:
- Cadernos, matérias e questões com relacionamento.
- Métricas de acertos, erros e desempenho.
- Busca instantânea por palavras/frases com resultados em cascata.
- Modo Professor com justificativa e avaliação local de 0–100%.
- Área de Revisão e Questões Feitas.
- Gerenciamento de conteúdo.
- Importação +All no formato `Caderno: matéria 1; matéria 2;`.
- Cadastro/edição de questões com explicação manual.
- Persistência no `localStorage`.

Observação técnica: a avaliação do Modo Professor neste protótipo é uma heurística local, não uma chamada real a um modelo de IA. Para produção, substitua `gradeJustification()` por uma API de IA no backend, mantendo a chave fora do navegador.
