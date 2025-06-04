# Projeto Utilizando Huggingfaces

Este projeto tem como objetivo demonstrar o uso de modelos da biblioteca [Hugging Face Transformers](https://huggingface.co/) para tarefas de classificação de texto, utilizando como base de dados artigos da Folha UOL.

## Proposta

- Utilizar um modelo pré-treinado do Hugging Face para classificação de texto.
- Comparar os resultados obtidos com abordagens anteriores utilizando GloVe.
- Baseado no tutorial: [Building a Text Classification Model using DistilBERT](https://medium.com/@prakashram1327/building-a-text-classification-model-using-distilbert-703c1409696c).

## Estrutura do Projeto

- `ECOM09A_2024_1_Atividade_2_Etapa_4_COMPLETO.ipynb`: Notebook principal contendo todo o fluxo de preparação de dados, treinamento e avaliação do modelo.

## Principais Funcionalidades

- Download e leitura de base de dados de artigos.
- Instalação e utilização das bibliotecas `datasets` e `transformers`.
- Carregamento de modelos pré-treinados (ex: DistilBERT) do Hugging Face para classificação de textos.
- Pipeline completo: pré-processamento, tokenização, treinamento e avaliação.
- Comparação de resultados com abordagens tradicionais.

## Como Executar

1. **Clone este repositório**:
    ```bash
    git clone https://github.com/Eduelvs/Projeto-Utilizando-Huggingfaces.git
    ```
2. **Abra o notebook principal**:  
   `ECOM09A_2024_1_Atividade_2_Etapa_4_COMPLETO.ipynb` em Google Colab.

3. **Instale as dependências** (no Colab, já existe suporte para muitos pacotes):
    ```python
    !pip install -q datasets transformers[torch]
    ```

4. **Execute as células em ordem** para realizar o download dos dados, treinar o modelo e avaliar os resultados.

## Observações

- Para acesso a alguns modelos do Hugging Face, talvez seja necessário um token de autenticação (veja avisos no notebook).
- O projeto utiliza artigos da Folha UOL como base de dados para classificação.

## Referências

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Dataset de Modelos para Text Classification](https://huggingface.co/models?pipeline_tag=text-classification)
- [Tutorial Base](https://medium.com/@prakashram1327/building-a-text-classification-model-using-distilbert-703c1409696c)

---

*Projeto criado para fins didáticos na disciplina ECOM09A - 2024/1*
