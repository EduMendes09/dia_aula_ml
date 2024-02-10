# dia_aula_ml
Teste aula de ML IA900 Dio

1. Criar um Recurso do Azure Machine Learning:
1.1. Acesse o Portal do Azure.

1.2. Clique em "Criar um recurso" e pesquise por "Machine Learning".

1.3. Escolha "Serviço de Machine Learning" e siga as instruções para criar um novo recurso.

2. Criar e Treinar um Modelo no Azure ML:
2.1. Acesse o Azure Machine Learning Studio.

2.2. Crie um novo experimento e importe seus dados.

2.3. Escolha um algoritmo, treine o modelo e avalie seu desempenho.

2.4. Publique o modelo treinado como um serviço web.

3. Configurar Pontos de Extremidade (Endpoints) no Azure ML:
3.1. No Azure Machine Learning Studio, vá para o modelo treinado.

3.2. Na guia "Modelo", clique em "Implantar".

3.3. Siga as instruções para implantar o modelo como um serviço web.

3.4. Durante o processo de implantação, você configurará os pontos de extremidade (endpoints). Escolha se deseja um ponto de extremidade de Pontuação Real (Real-time endpoint) ou de Lote (Batch endpoint).

4. Consumir o Ponto de Extremidade:
4.1. Uma vez implantado, você receberá um ponto de extremidade (URL) para seu serviço web.

4.2. Use essa URL para fazer solicitações HTTP para realizar previsões em tempo real.

4.3. Se você configurou um ponto de extremidade de Lote, envie um conjunto de dados para a URL do ponto de extremidade de Lote e aguarde os resultados.
