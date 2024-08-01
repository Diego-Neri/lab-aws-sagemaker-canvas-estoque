# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, aprendi a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). 

## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)


# Avaliação de Métricas do Modelo

## 1. MAE (Mean Absolute Error)

- **Valor**: 19.198
- **Descrição**: MAE é a média das diferenças absolutas entre as previsões do modelo e os valores reais. É uma métrica de erro que mostra, em média, o tamanho do erro em termos absolutos.
- **Interpretação**: O MAE de 19.198 indica que, em média, as previsões do modelo estão erradas por cerca de 19.198 unidades em relação aos valores reais. A aceitação desse valor depende do contexto do seu problema e da escala dos seus dados. Se os valores reais são muito grandes, esse erro pode ser considerado pequeno; se são pequenos, o erro pode ser considerado grande.

## 2. MSE (Mean Squared Error)

- **Valor**: 715.859
- **Descrição**: MSE é a média dos quadrados das diferenças entre as previsões e os valores reais. Penaliza erros maiores mais severamente do que o MAE devido ao quadrado dos erros.
- **Interpretação**: O MSE de 715.859 indica que, em média, o quadrado do erro de previsão é esse valor. Como o MSE penaliza grandes erros mais fortemente, um valor relativamente alto pode sugerir que há alguns erros muito grandes em suas previsões.

## 3. RMSE (Root Mean Squared Error)

- **Valor**: 26.756
- **Descrição**: RMSE é a raiz quadrada do MSE. Representa o erro médio em unidades do mesmo tipo das variáveis preditivas, o que facilita a interpretação.
- **Interpretação**: O RMSE de 26.756 é a média das magnitudes dos erros de previsão e está em mesma unidade dos dados. Assim como o MAE, você deve considerar a escala dos seus dados para determinar se esse valor é aceitável.

## 4. R² (Coeficiente de Determinação)

- **Valor**: 0.172
- **Descrição**: R² mede a proporção da variabilidade dos dados que é explicada pelo modelo. Um R² de 1 indica que o modelo explica toda a variabilidade dos dados, e um R² de 0 indica que o modelo não explica nenhuma variabilidade além do que seria esperado por acaso.
- **Interpretação**: Um R² de 0.172 é relativamente baixo, sugerindo que apenas 17.2% da variabilidade nos dados é explicada pelo modelo. Isso indica que o modelo pode não estar capturando bem a relação entre as variáveis independentes e a variável dependente, e talvez haja espaço para melhorias.

## Avaliação Geral

Com base nas métricas fornecidas:

- **MAE e RMSE**: Se o erro é grande ou pequeno depende do contexto específico do seu problema. Comparar com uma linha de base ou com modelos alternativos pode fornecer mais insights sobre se esses valores são aceitáveis.
- **MSE**: Um valor alto sugere que existem alguns erros muito grandes nas previsões, o que pode ser problemático.
- **R²**: Um valor baixo sugere que o modelo não está explicando bem a variabilidade dos dados. Isso pode indicar que o modelo é inadequado ou que há características dos dados não capturadas pelo modelo atual.


## 📬 Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

Email: diegoneri500@gmail.com

LinkedIn: 

