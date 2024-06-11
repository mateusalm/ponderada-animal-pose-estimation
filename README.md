### Análise dos Resultados

#### Distribuição das Categorias

A análise do dataset ANIMAL-POSE revelou a seguinte distribuição de imagens por categoria:

| Categoria | Quantidade de Imagens |
|-----------|------------------------|
| Dog       | 1771                   |
| Sheep     | 1078                   |
| Horse     | 960                    |
| Cow       | 842                    |
| Cat       | 1466                   |

A categoria "cow" possui um total de 842 imagens, representando uma parte significativa, mas não dominante, do dataset.

#### Processamento de Imagens da Categoria "Cow"

Para as 842 imagens da categoria "cow", foi aplicado um pipeline de processamento de imagem que inclui:
1. **Rotação**: Rotação da imagem em 45 graus.
2. **Ajuste de Brilho**: Aumento do brilho da imagem.
3. **Normalização**: Normalização dos valores de pixel para o intervalo [0, 1].
4. **Adição de Ruído**: Adição de ruído gaussiano.
5. **Recorte**: Recorte central da imagem.

### Conclusões

#### Principais Aprendizados

- **Importância do Processamento de Imagem**: Técnicas como rotação, ajuste de brilho, normalização, adição de ruído e recorte são cruciais para melhorar a qualidade dos dados de entrada em modelos de visão computacional.
- **Diversidade de Dados**: A distribuição desigual das categorias no dataset destaca a importância de balancear os dados para treinar modelos mais robustos.

#### Limitações

- **Quantidade de Imagens**: A quantidade limitada de imagens da categoria "cow" pode não ser suficiente para treinar modelos robustos de aprendizado de máquina.
- **Introdução de Artefatos**: Algumas técnicas de processamento, como a adição de ruído, podem introduzir artefatos que podem impactar negativamente a performance de modelos subsequentes.

#### Sugestões para Trabalhos Futuros

- **Aumento do Dataset**: Coletar mais imagens, especialmente para categorias com menos representatividade, para aumentar a diversidade e o equilíbrio do dataset.
- **Exploração de Novas Técnicas**: Explorar outras técnicas de data augmentation, como transformações geométricas avançadas e filtros de imagem.
- **Comparação de Modelos**: Implementar e comparar a performance de diferentes modelos de aprendizado de máquina utilizando o dataset processado, para identificar as melhores abordagens para cada tipo de dado.
