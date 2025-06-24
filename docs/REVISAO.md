# Revisão técnica de UX de negócio

| **Funcionalidade**                          | **Nível de Confiança** | **Esforço** | **Valor UX** | **Valor de Negócio** | **Observação**                                                                 |
|--------------------------------------------|-------------------------|-------------|---------------|----------------------|--------------------------------------------------------------------------------|
| Calendário de corridas por categoria       | Verde                   | E           | ♥♥♥♥          | $$$                  | Alta demanda dos usuários; valor central para o app                            |
| Notificações antes das corridas            | Amarelo                 | EE          | ♥♥♥           | $$                   | Exige integração com push notifications; pode gerar alto engajamento          |
| Resultados e classificação geral           | Verde                   | EE          | ♥♥♥♥          | $$$                  | Dados de terceiros ou atualização manual programada                            |
| Personalização por piloto/equipe/categoria | Amarelo                 | EE          | ♥♥♥           | $$                   | Envolve lógica de filtro e armazenamento de preferências                       |
| Notícias e resumos pós-corrida             | Vermelho                | EE          | ♥♥             | $                    | Conteúdo precisa ser atualizado com frequência manual ou por API              |
| Comparação de desempenho entre pilotos     | Vermelho                | E           | ♥♥♥           | $                    | Útil para entusiastas, mas complexo de implementar e com retorno menor no MVP |


**Legenda:**

*   **Confiança:** Verde (Alta), Amarelo (Média), Vermelho (Baixa)
*   **Esforço:** E (Baixo), EE (Médio), EEE (Alto)
*   **Valor UX:** ♥ (Baixo), ♥♥ (Médio), ♥♥♥ (Alto)
*   **Valor $ (Negócio):** $ (Baixo), $$ (Médio), $$$ (Alto)