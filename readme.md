# Projeto de Pesquisa em Sistemas de Recomendação de Vagas com Deep Learning

## **Descrição do Projeto**
Este projeto de pesquisa é focado no desenvolvimento de **sistemas de recomendação de vagas de emprego** utilizando técnicas avançadas de **Deep Learning**. O objetivo principal é criar soluções que analisem dados textuais de descrições de vagas e perfis de candidatos para fornecer recomendações personalizadas e eficazes.

(No momento o projeto utiliza uma base de dados em inglês)
---

## **Objetivos**

1. **Representação de Dados Textuais**:
   - Explorar modelos como **BERT** e **BERTimbau** para gerar representações numéricas (embeddings) de descrições de vagas e perfis de candidatos.
   - Implementar técnicas para calcular a similaridade entre embeddings, utilizando métricas como:
     - Similaridade do cosseno
     - Distância Euclidiana

2. **Construção de Sistemas de Recomendação de Vagas**:
   - Desenvolver modelos de recomendação de vagas baseados em aprendizado de máquina (Machine Learning) e aprendizado profundo (Deep Learning).
   - Investigar abordagens híbridas de recomendação, combinando:
     - Filtragem colaborativa
     - Sistemas baseados em conteúdo
   - Testar diferentes modelos híbridos sugeridos na literatura acadêmica.

3. **Incorporação de Aprendizado por Reforço**:
   - Explorar como Reinforcement Learning pode ser utilizado para otimizar sistemas de recomendação dinâmicos, adaptando-se às mudanças no comportamento do usuário e nas características das vagas.

---

## **Próximos Passos**

1. **Modelos de Recomendação**:
   - Implementar e testar modelos básicos de recomendação utilizando bibliotecas como TensorFlow e PyTorch.
   - Comparar abordagens híbridas utilizando datasets reais relacionados a vagas de emprego.

2. **Exploração de Aprendizado por Reforço**:
   - Criar um modelo básico que utiliza Reinforcement Learning para decisões de recomendação.
   - Testar a abordagem em cenários simulados para avaliar seu impacto em métricas de recomendação específicas do contexto de vagas.

---

## **Ferramentas e Tecnologias Utilizadas**
- **Python**: Linguagem principal para implementação.
- **Bibliotecas**:
  - `Transformers` (Hugging Face): Modelos como BERT e BERTimbau.
  - `scikit-learn`: Cálculo de similaridade e métricas de avaliação.
  - `TensorFlow` e `PyTorch`: Implementação de redes neurais e modelos de recomendação.
  - `pandas` e `numpy`: Manipulação de dados.
  - `matplotlib` e `seaborn`: Visualização de resultados.
- **Datasets**:
  - Conjuntos de dados textuais e de recomendação relacionados a vagas de emprego (ex.: `LinkedIn`, `Glassdoor`).


## **Referências**
1. **Modelos pré-treinados**:
   - [BERTimbau (Hugging Face)](https://huggingface.co/neuralmind/bert-base-portuguese-cased)
2. **Técnicas de recomendação híbrida**:
   - [Artigo ScienceDirect](https://www.sciencedirect.com/topics/computer-science/hybrid-recommendation)
   - [Exemplo no Kaggle](https://www.kaggle.com/code/iambideniz/hybrid-recommender-system)
3. **Aprendizado por Reforço**:
   - Estudos de Reynold Navarro Mazo.

---

## **Contato**
Se tiver dúvidas ou sugestões, entre em contato:
- Nome: André Penchel
- E-mail: [penchel.andre@gmail.com]
