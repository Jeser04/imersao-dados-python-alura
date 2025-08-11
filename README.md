# 📊 Dashboard de Análise de Salários na Área de Dados

Este é um projeto de um dashboard interativo construído com Streamlit para visualizar e analisar dados de salários na área de tecnologia e dados.


Você pode acessar e interagir com o dashboard diretamente no link abaixo:

**(https://jeser-imersao-dados-python-alura.streamlit.app/)**

## ✨ Funcionalidades

* **Filtros Interativos:** Permite filtrar os dados por:
    * Ano
    * Nível de Senioridade
    * Tipo de Contrato
    * Tamanho da Empresa
* **Métricas em Destaque (KPIs):** Exibe cartões com informações chave, como:
    * Salário Médio (USD)
    * Salário Máximo (USD)
    * Total de Registros na seleção
    * Cargo mais frequente
* **Visualizações de Dados:** Gráficos gerados com Plotly para análises mais profundas:
    * **Top 10 Cargos:** Gráfico de barras com os maiores salários médios.
    * **Distribuição Salarial:** Histograma mostrando a frequência das faixas salariais.
    * **Trabalho Remoto:** Gráfico de pizza com a proporção de trabalho remoto, híbrido e presencial.
    * **Salário por País:** Mapa (Choropleth) exibindo o salário médio para Cientistas de Dados por país.
* **Tabela de Dados:** Apresenta o dataframe com os dados filtrados para consulta direta.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Python:** Linguagem de programação principal.
* **Streamlit:** Framework para a criação do dashboard web interativo.
* **Pandas:** Biblioteca para manipulação e análise dos dados.
* **Plotly:** Biblioteca para a criação dos gráficos dinâmicos.

## 📦 Instalação e Execução

Para executar este projeto localmente, siga os passos abaixo.

### Pré-requisitos

* [Python 3.8+](https://www.python.org/)
* [pip](https://pip.pypa.io/en/stable/installation/) (gerenciador de pacotes do Python)
* [Git](https://git-scm.com/) (opcional, para clonar o repositório)

### Passos

1.  **Clone o repositório (ou crie os arquivos localmente):**
    ```bash
    # Se você tiver o projeto em um repositório git
    git clone <URL-DO-SEU-REPOSITORIO>
    cd <NOME-DO-SEU-PROJETO>
    ```
    Caso não tenha, apenas crie uma pasta e coloque os arquivos `app.py` e `requirements.txt` dentro dela.

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    # Criar o ambiente virtual
    python -m venv venv

    # Ativar no Windows
    .\venv\Scripts\activate

    # Ativar no macOS/Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    Execute o comando abaixo para instalar as bibliotecas necessárias listadas no arquivo `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute a aplicação Streamlit:**
    Com as dependências instaladas, inicie o dashboard com o seguinte comando:
    ```bash
    streamlit run app.py
    ```
    Após executar o comando, o seu navegador web abrirá automaticamente com o dashboard em execução.
