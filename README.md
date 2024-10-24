# Predição de Colesterol Usando Regressão Linear
Este projeto utiliza técnicas de regressão linear para prever os níveis de colesterol com base em informações de saúde dos indivíduos. Utilizamos diversas características, como grupo sanguíneo, nível de atividade física, idade, peso, altura e se a pessoa é fumante ou não.

## Tecnologias Utilizadas
  Python: Linguagem de programação principal.
  Pandas: Manipulação de dados.
  Scikit-learn: Para a criação do modelo de regressão linear e o pipeline de pré-processamento.
  Gradio: Para criar uma interface gráfica amigável que permite aos usuários realizarem previsões com base em suas informações pessoais.
  Matplotlib & Seaborn: Utilizadas para visualização de dados.
  Pingouin & Scipy: Para testes estatísticos de normalidade e homocedasticidade.
## Requisitos
  Certifique-se de ter as seguintes dependências instaladas:
    pip install pandas scikit-learn gradio matplotlib seaborn pingouin scipy statsmodels
## Funcionalidades
### O modelo de regressão linear utiliza as seguintes variáveis como entrada:

  Grupo Sanguíneo: 'O', 'A', 'B', 'AB'
  Fumante: Sim ou Não (input do tipo checkbox)
  Nível de Atividade Física: 'Baixo', 'Moderado', 'Alto'
  Idade: Um valor numérico (20 a 80)
  Altura: Um valor numérico (40 a 160)
  Peso: Um valor numérico (150 a 200)
  
###Com base nesses dados, o modelo faz uma predição do nível de colesterol.

## Avaliação do Modelo
Após a criação do modelo, foram calculadas várias métricas para avaliar o desempenho, como R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), além de testes de normalidade e homocedasticidade.

Normalidade dos Resíduos: Testada com Shapiro-Wilk, Kolmogorov-Smirnov e outros.
Homocedasticidade: Verificada utilizando o teste de Goldfeld-Quandt.

Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
