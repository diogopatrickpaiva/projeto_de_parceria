# Predição da Demanda por Bicicletas

Este projeto utiliza técnicas de aprendizado de máquina e análise de dados para prever a demanda por bicicletas em uma cidade, com base em um conjunto de dados históricos de aluguel de bicicletas. O objetivo é criar um modelo preditivo que auxilie na tomada de decisões relacionadas à logística e ao planejamento de disponibilização de bicicletas.

## 1. Coleta de Dados

Os dados utilizados neste projeto foram extraídos de um dataset público que contém informações sobre o aluguel de bicicletas ao longo do tempo, incluindo variáveis como condições climáticas, feriados, e demanda registrada. Essas informações foram processadas e analisadas para entender melhor os padrões de demanda.

## 2. Modelagem

Para modelar a demanda por bicicletas, foi utilizado um modelo de Regressão Linear, que é uma técnica estatística para prever o valor de uma variável dependente com base em uma ou mais variáveis independentes. O modelo foi treinado com 70% dos dados disponíveis e testado com os 30% restantes para avaliar sua performance.

### Etapas de Modelagem:
- **Exploração dos Dados:** Análise inicial para entender a correlação entre as variáveis e a demanda por bicicletas.
- **Treinamento do Modelo:** Utilização dos dados de treino para ajustar o modelo de Regressão Linear.
- **Avaliação do Modelo:** O modelo foi avaliado utilizando uma matriz de correlação e gráficos de valores reais vs previstos.

## 3. Visualização de Dados

As visualizações de dados foram uma parte crucial deste projeto, pois permitiram identificar padrões e anomalias nos dados. As principais visualizações incluem:

- **Matriz de Correlação:** Para identificar a relação entre diferentes variáveis.
- **Distribuição da Demanda de Bicicletas:** Para entender a frequência da demanda ao longo do tempo.
- **Gráfico de Valores Reais vs Previstos:** Para avaliar a precisão do modelo preditivo.

## 4. Conclusões

O modelo de Regressão Linear se mostrou eficaz para prever a demanda por bicicletas, com uma acurácia de aproximadamente 96%. No entanto, o modelo apresentou maior variabilidade na previsão de valores altos, sugerindo que ajustes adicionais ou a consideração de modelos mais complexos poderiam melhorar a precisão.

## 5. Como Usar

Para reproduzir os resultados deste projeto:

1. Clone este repositório.
2. Execute o script `data_processing.py` para processar os dados.
3. Treine o modelo executando `train_model.py`.
4. Gere as visualizações com `generate_visualizations.py`.
5. Avalie os resultados através dos gráficos e do relatório gerado.

## 6. Contribuições

Contribuições são bem-vindas! Se você deseja melhorar o modelo ou adicionar novas funcionalidades, sinta-se à vontade para abrir um pull request.

## 7. Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

Este README fornece uma visão geral clara do projeto, explica o processo e as ferramentas utilizadas, e dá instruções sobre como utilizar o código.
