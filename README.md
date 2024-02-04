# indicium
repositori para o processo seletivo
Para executar é necessario ter o python 3 e o pip instalados.Tendo eles deve-se baixar as bibliotecas com:
  pip install pandas matplotlib numpy seaborn scikit-learn joblib.

Após isso é necessario baixar o pkl e importa-lo no ambiente:
 
  loaded_transform_and_predict = joblib.load('caminho/model_and_transform.pkl')

Por fim basta chamar o metodo:
 
  loaded_transform_and_predict(dados)

Dentro do metodo estão as transformações necessarias e o modelo treinado

