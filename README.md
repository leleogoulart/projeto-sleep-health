# projeto-sleep-health

Análise sobre saúde do sono e estilo de vida, na qual o objetivo foi entender quais são os principais pontos que influenciam os pacientes a ter sintomas que prejudique o sono, como insonia ou apneia do sono, e o que influencia a não ter nenhum sintoma.

💡 Comparação dos modelos

A Árvore de Decisão apresentou ótimo desempenho geral, com 86% de acurácia e alta sensibilidade para identificar apneia do sono (95% de recall). Contudo, demonstrou instabilidade devido ao alto índice de falsos positivos, confundindo frequentemente pacientes saudáveis ou com insônia..

E com o Random Forest, percebe-se que solucionou a instabilidade do modelo anterior ao mitigar os erros individuais da árvore simples. Essa abordagem elevou a acurácia geral para 90% e, mais importante, atingindo um equilíbrio de 84% de precisão e recall para a classe de Insônia, tornando o sistema muito mais confiável para suporte a diagnósticos clínicos.

Conclusão e Insights de Negócio

Com base na análise exploratória dos dados e no comportamento dos modelos preditivos, conclui-se que os distúrbios do sono são casados por uma sinergia de estilo de vida e indicadores físicos: 
1. O Peso como Fator de Risco Principal: O IMC como "Sobrepeso" e "Obeso" demonstrou ser o gatilho mais forte para o desenvolvimento de Apneia do Sono.
2. O Combo do Estresse vs. Atividade Física: A Insônia mostrou-se altamente correlacionada a rotinas com alto nível de estresse combinadas com baixíssima atividade física (poucos passos diários).
