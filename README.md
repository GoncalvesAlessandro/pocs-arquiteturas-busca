# Trabalho de Conclusão: Arquiteturas Modernas em Sistemas de Busca

Este repositório contém as Provas de Conceito (POCs) e os códigos-fonte desenvolvidos para o Trabalho de Conclusão de Curso (TCC) do curso de Sistemas de Informação. 

## 📌 Objetivo do Projeto
O objetivo desta pesquisa é realizar uma análise comparativa entre diferentes arquiteturas de Recuperação da Informação, avaliando a qualidade dos resultados, custo computacional e adequação em diferentes cenários. 

As arquiteturas analisadas são:
1. **Busca Booleana** (Correspondência Exata com operadores lógicos)
2. **Ranqueamento Estatístico** (BM25)
3. **Busca Vetorial / Semântica** (Embeddings)

## 🗄️ Conjuntos de Dados (Datasets)
Para garantir a conformidade com a LGPD e permitir análises qualitativas e quantitativas, foram utilizados dois conjuntos de dados públicos:
* **Constituição Federal do Brasil (~4.000 documentos):** Foco na avaliação qualitativa e compreensão de intenção/semântica devido à complexidade da linguagem jurídica.
* **Wikipedia em Português (50.000 artigos):** Foco na avaliação quantitativa, medição de latência, tempo de indexação e escalabilidade.

## 🚀 Como executar
Os scripts foram desenvolvidos em linguagem Python utilizando o ambiente Google Colab. Para reproduzir os testes, basta aceder aos notebooks `.ipynb` disponíveis neste repositório.
