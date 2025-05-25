# PCG1NO---ACO
PCG1NO - Implementação de Algoritmos para Solução de Problemas Cotidianos
🛠️ Instruções de Uso
📦 Pré-requisitos
Para executar este projeto, você precisará ter instalado os seguintes itens:

Python 3.10 ou superior (Recomendado)

Conta no Google Colab (opcional, mas recomendado para facilitar a execução)

As seguintes bibliotecas Python:

Biblioteca  	Instalação
OSMnx         pip install osmnx
NetworkX	    pip install networkx
NumPy	        pip install numpy
Pandas	      pip install pandas
Matplotlib  	pip install matplotlib
ipyleaflet  	pip install ipyleaflet

⚠️ Observação: Algumas bibliotecas podem requerer permissões ou dependências adicionais no seu ambiente local. Recomenda-se fortemente executar no Google Colab, onde todas as dependências são facilmente configuráveis.

🚀 Executando o Projeto
✔️ Via Google Colab (Recomendado)

Execute as células na ordem, certificando-se de instalar as bibliotecas quando solicitado.

O notebook irá:

Gerar o grafo do bairro José Menino (Santos - SP) com dados do OpenStreetMap.

Definir os pontos de entrega e o centro de distribuição.

Executar o Algoritmo de Colônia de Formigas (ACO) para gerar a rota otimizada.

Exibir a rota em um mapa interativo, destacando os trajetos de ida (vermelho) e volta (azul).

✔️ Execução Local
Clone este repositório:
git clone https://github.com/MathSGarcia/PCG1NO---ACO.git

Acesse a pasta do projeto:
cd PCG1NO---ACO

Instale as dependências:
pip install -r requirements.txt
Caso não exista o arquivo requirements.txt, você pode instalar manualmente conforme a tabela de pré-requisitos.

Execute o arquivo .ipynb com o Jupyter Notebook ou Google Colab instalado localmente.

🗺️ Personalização
É possível alterar os pontos de entrega modificando as coordenadas geográficas diretamente no notebook, na seção correspondente à definição dos nós.

📊 Saída Esperada
Mapa interativo exibindo a rota otimizada com o algoritmo ACO.

Informações como:

Distância total da rota de ida.

Distância total da rota de volta.

Sequência dos nós visitados.

🐞 Possíveis Problemas
Caso o mapa não carregue corretamente no Google Colab, certifique-se de ativar o suporte a widgets. Siga as instruções exibidas no topo do notebook.

Problemas de conexão com o OpenStreetMap podem ocorrer se houver falha na internet.
