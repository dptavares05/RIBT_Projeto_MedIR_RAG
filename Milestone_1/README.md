# Milestone 1: Indexação, Baseline Lexical e Avaliação Tradicional

## Descrição
Nesta primeira fase do projeto, o objetivo foi estabelecer uma *baseline* para a recuperação de informação utilizando a coleção de dados biomédica BioASQ (Task B)[cite: 20, 21]. 

## Tarefas Realizadas
* Pré-processamento e tokenização do corpus[cite: 21].
* Indexação da coleção utilizando a implementação probabilística BM25[cite: 21].
* Avaliação quantitativa da *baseline* com a ferramenta `pytrec_eval` utilizando as métricas NDCG@5, NDCG@10, MRR@10, MAP e Recall@100[cite: 21].

## Como executar
1. Instalar dependências: `pip install -r requirements.txt`
2. Executar o notebook `milestone1.ipynb`.