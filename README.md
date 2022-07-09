# inteligencia-artificial-regressao-linear
Regressão linear

# Tarefa

1. Regressão linear
* Refaça o exemplo de regressão linear usando o modelo de regressão linear implementado pelo scikit (linear_model). Indique qual o erro quadrático médio.
* Refaça o item (a), dividindo o arquivo de exemplos em treinamento (70%) e teste (30%). Indique qual o erro quadrático médio.
* Comente os resultados obtidos.
 
2. Considere a base de dados multi.csv. Ela contém dados com 4 features (X1,X2,X3 e X4) e um atributos alvo (X5).
* Plote os gráficos para X1 x X5, X2 x X5, X3 x X5 e X4 x X5, e determine qual par de atributos (Xi,X5) possui uma relação linear.
* Utilizando os atributos que possuem uma relação linear com X5, utilize a regressão linear para determinar os coeficientes da equação correspondentes. Utilize o modelo de regressão linear do scikit e todo o conjunto de dados no treinamento.
* Divida os dados em conjuntos de  treinamento (75%) e teste (25%).

# Instalar dependencias, jupyter notebook e todas as configurações necessarias para executar o projeto. 
Antes, sera necessario ter instalado o python3 e o pip(que vem dentro da instalação do python3)

Execute o comando dentro da pasta do projeto.

pip install -r requirements.txt


# Configuração Google colab para local runtime 

Setup instructions
In order to allow Colaboratory to connect to your locally running Jupyter server, you'll need to perform the following steps.

Step 1: Install Jupyter
Install Jupyter on your local machine.

Step 2: Install and enable the jupyter_http_over_ws jupyter extension (one-time)
The jupyter_http_over_ws extension is authored by the Colaboratory team and available on GitHub.

pip install jupyter_http_over_ws

jupyter serverextension enable --py jupyter_http_over_ws

Step 3: Start server and authenticate
New notebook servers are started normally, though you will need to set a flag to explicitly trust WebSocket connections from the Colaboratory frontend.

jupyter notebook --NotebookApp.allow_origin='https://colab.research.google.com' --port=8888 --NotebookApp.port_retries=0
    
Once the server has started, it will print a message with the initial backend URL used for authentication. Make a copy of this URL as you'll need to provide this in the next step.

Step 4: Connect to the local runtime
In Colaboratory, click the "Connect" button and select "Connect to local runtime...". Enter the URL from the previous step in the dialog that appears and click the "Connect" button. After this, you should now be connected to your local runtime.

# Utilize o github como repositorio e para controle de versão do notebook diretamente no front end do google colab
![Capturar](https://user-images.githubusercontent.com/21993550/178114681-d810653b-ca8f-4e9d-a80b-978f3c3e8689.PNG)
