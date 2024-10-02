# Objetivo

- Utilizando o Sagemaker Canvas da AWS, analisar os dados e exibir os resultados.

# Resultado

Com base nos dados do site [DIEESE](https://www.dieese.org.br/cesta/produto) para a cidade de São Paulo:
- Eu baixei o arquivo _.xls_;
- Apaguei os dados anteriores ao plano real;
- Limpei as informações desnecessárias;
- Transformei em _.csv_.

Após, joguei no Sagemaker Canvas, criando um novo modelo e colocando como target o **Valor** para cada mês, e os resultados obtidos no Quick Builder foram os seguintes:
- **Setembro:** R$782.34
- **Outubro:** R$783.35
- **Novembro:** R$784.27
- **Dezembro:** R$785.70

Aqui está as métricas de avaliação de desempenho obtidas com o uso desse modelo:
- **MAE:** 5.857
- **MSE:** 88.156
- **RMSE:** 9.389
- **R²:**  0.997

⚠️ _Eu não segui o padrão da atividade, para manter o padrão que venho seguindo com minhas atividades no Github._

