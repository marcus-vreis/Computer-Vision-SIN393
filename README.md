# Computer-Vision-k-nn

## Overview


Este projeto utiliza diversas bibliotecas de Python para realizar tarefas relacionadas à manipulação de imagens, aprendizado de máquina e análise de dados. As principais funcionalidades incluem:

- **Pré-processamento de imagens:** Transformações e filtragens usando `skimage`.
- **Extração de características:** Ferramentas para análise e seleção de propriedades relevantes.
- **Classificação:** Teste e validação de algoritmos como K-Nearest Neighbors (K-NN) e Support Vector Machine (SVM).
- **Métricas de Avaliação:** Acurácia, Precisão, Recall e F1-Score.

O foco principal do repositório é aplicar e avaliar os algoritmos K-NN e SVM em uma base de dados MPEG7 modificada.



## Executando Notebook

Passo a passo para abrir o código usando o Anaconda, certifique-se que possua o ambiente Python instalado.

1. Crie um ambiente virtual (opcional):

    Para garantir um ambiente isolado, recomenda-se criar um ambiente virtual. Utilize o seguinte comando para criar um ambiente virtual usando o Conda:

    ```bash
        conda create --name nome_do_seu_ambiente python=3.8
    ```

2. Ative o ambiente virtual:

    Ative o ambiente virtual recém-criado com o seguinte comando:

    ```bash
        conda activate nome_do_seu_ambiente
    ```

3. Instale o Jupyter Notebook:

    Instale o Jupyter Notebook no ambiente virtual com o seguinte comando:

    ```bash
        conda install jupyter
    ```

4. Instale as Bibliotecas Necessárias:

    Use o comando abaixo para instalar as Dependências:

    ```bash
        conda install numpy pandas matplotlib seaborn scikit-learn
    ```
5. Certifique-se que esta tudo atualizado:

    Certifique-se de que tudo está atualizado executando o seguinte comando:

    ```bash
        conda update --all
    ```

6. Inicie o Jupyter Notebook:

    Depois de instalado, inicie o Jupyter Notebook com o comando:
    
    ```bash
        jupyter notebook
    ```
   
7. Observação: O arquivo .ipynb e a base de dados mpeg7_mod devem estar no mesmo diretório, caso não, o ds_path do arquivo jupyter deve ser modificado.


## Participantes
Brenno Alves Silva - 7000

Marcus Vinicius Diniz dos Reis - 8151