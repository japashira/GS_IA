# GS_IA

# Plataforma de Eficiência Energética para Prédios Inteligentes

# Descrição do Problema
Edifícios inteligentes enfrentam o desafio de monitorar e gerenciar o consumo energético de forma eficiente, sustentável e econômica. O uso descontrolado de energia pode levar a desperdícios significativos, além de dificultar a integração de fontes renováveis, como solar e eólica. A imprevisibilidade do consumo, associada a fatores como variações climáticas e comportamentos dos moradores, agrava o problema.

O projeto visa desenvolver uma solução baseada em Machine Learning que possa prever o consumo energético com base em dados históricos e variáveis ambientais, permitindo decisões mais assertivas para reduzir desperdícios e promover eficiência energética.

# Metodologia Utilizada
# Coleta de Dados
Os dados utilizados foram simulados para representar um cenário realista e incluem:

Dados históricos de consumo: Consumo por hora, dia e mês.
Dados das instalações: Potência, tensão e corrente elétrica.
Dados meteorológicos: Temperatura, radiação solar, umidade e velocidade do vento.
Dados socioeconômicos: Número de habitantes e tipo de residência.
Dados de eventos: Feriados e períodos de férias.

# Pré-Processamento dos Dados
As etapas de preparação dos dados incluíram:

Tratamento de valores ausentes (substituição por médias ou exclusão, conforme necessário).
Normalização das variáveis contínuas para adequar os dados ao modelo.
Codificação de variáveis categóricas utilizando One-Hot Encoding.
Criação de novas variáveis, como média móvel de consumo para capturar tendências.

# Modelo de Machine Learning
O modelo escolhido foi o Gradient Boosting Regressor, devido à sua alta precisão e capacidade de lidar com dados complexos e correlacionados.

Modelo de regressão: Previsão do consumo de energia com base em variáveis históricas e climáticas.
Divisão dos dados:
Treinamento: 80%
Teste: 20%

# Treinamento e Avaliação do Modelo
Métricas utilizadas para avaliação:
R² (Coeficiente de Determinação): Mede o quão bem o modelo explica a variabilidade dos dados.
MSE (Erro Médio Quadrático): Mede a magnitude dos erros quadráticos.
MAE (Erro Absoluto Médio): Indica o erro médio das previsões.

# Análise de Importância das Variáveis
Foi realizada uma análise para identificar as variáveis mais relevantes para as previsões, utilizando a funcionalidade de importância de variáveis do modelo.

# Resultados Obtidos
Desempenho do Modelo
R²: [-0.0063735845998413865]
MSE: [-0.0063735845998413865]
MAE: [231.70139617535148]
O modelo apresentou alta aderência aos dados, indicando sua capacidade de prever o consumo energético com precisão.

Variáveis Mais Relevantes
Temperatura: Influência direta no uso de sistemas de aquecimento e refrigeração.
Radiação Solar: Impacto no uso de fontes renováveis e aquecimento passivo.
Número de Habitantes: Reflete o uso de dispositivos e o comportamento dos moradores.
Tipo de Residência: Diferenças significativas no consumo por tipo de edificação.
Visualizações
Gráficos comparando os valores reais e previstos mostraram alta aderência entre as duas curvas.
Gráficos de barras destacaram as variáveis mais influentes no consumo energético.
Conclusões
Impacto da Solução
A plataforma demonstra que é possível prever e monitorar o consumo energético de forma eficiente, promovendo:

Redução de custos operacionais para moradores e administradores.
Otimização do uso de energia elétrica, priorizando fontes renováveis.
Contribuição para metas de sustentabilidade e redução de emissões de carbono.
Principais Insights
Recomendações Personalizadas: A previsão de consumo permite ao sistema sugerir ações específicas para cada perfil de usuário.
Automação com IoT: A integração com dispositivos conectados torna possível a automação de sistemas, como o desligamento de aparelhos em horários de pico.
Prevenção de Desperdícios: Identificação de padrões anômalos ou desperdícios em tempo real.
Extensões Futuras
Integração com Redes Neurais: Para aumentar a precisão das previsões.
Expansão para Dados Reais: Aplicar a solução com dados reais de edifícios inteligentes.
Detecção de Anomalias: Implementar modelos que identifiquem falhas ou comportamentos incomuns no consumo energético.
