# Identificador de moda com TensorFlow e Fashion MNIST

Este projeto foi desenvolvido como parte do curso rápido Building a Brain da [NVIDIA Deep Learning Institute](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+T-FX-01+V1)
O objetivo foi treinar uma rede neural simples para identificar itens de moda (sapatos, camisetas, bolsas etc.) usando o dataset Fashion MNIST.

## Principais etapas do fluxo de trabalho

1. Carregar e explorar os dados – importação do conjunto Fashion MNIST, visualização das classes e distribuição.
2. Pré-processamento – normalização dos valores dos pixels, transformação das saídas em categorias, divisão em treino/teste.
3. Construção do modelo
4. Compilação e treinamento
5. Avaliação e previsões – checagem da acurácia no conjunto de teste, e visualização de previsões corretas e incorretas.
   
## Tecnologias Utilizadas

- **TensorFlow** — framework principal para aprendizado de máquina
- **Keras (API Sequential)** — construção e treinamento do modelo
- **NumPy** — manipulação de dados
- **Matplotlib** — visualização dos resultados
- **Fashion MNIST** — dataset de imagens de roupas em escala de cinza
