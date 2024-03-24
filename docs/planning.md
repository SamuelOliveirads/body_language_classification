### Planejamento do Projeto de Classificação de Ações

#### Introdução
O objetivo deste projeto é desenvolver um sistema capaz de classificar diferentes ações realizadas por pessoas, utilizando como entrada imagens ou vídeos, que podem ser capturados ao vivo através de uma webcam ou fornecidos como arquivos pré-gravados.

#### Output (Saída)
O sistema será capaz de classificar até 20 diferentes ações (ou poses), como correr, saltar, sentar, acenar, etc. A classificação será feita em tempo real ou em vídeos pré-gravados, fornecendo uma etiqueta correspondente à ação identificada na imagem ou sequência de imagens.

#### Input (Entrada)
O sistema aceitará como entrada:
- Imagens estáticas
- Fluxo de vídeo ao vivo (por exemplo, de uma webcam)

Essas entradas serão processadas para identificar ações realizadas pelas pessoas presentes nas imagens ou vídeos.

#### Processo
O processo envolvido na construção e operação do sistema pode ser dividido em várias etapas chave:

1. **Coleta de Dados**: Coletar um conjunto de dados diversificado que contenha imagens ou vídeos das ações que desejamos classificar. Este conjunto de dados deve incluir exemplos variados para cada ação, capturados sob diferentes condições de iluminação, fundos e perspectivas.

2. **Pré-processamento de Dados**: Utilizar a biblioteca MediaPipe para detectar as juntas e poses das pessoas nas imagens ou vídeos. Converter essas detecções em dados tabulares que representem as características das poses.

4. **Divisão dos Dados**: Dividir o conjunto de dados em conjuntos de treinamento, validação e teste para permitir o treinamento eficaz do modelo e a avaliação do seu desempenho.

5. **Seleção e Treinamento do Modelo**: Escolher um modelo classificador adequado. Treinar o modelo no conjunto de dados preparado, ajustando os hiperparâmetros para otimizar o desempenho.

6. **Avaliação do Modelo**: Utilizar o conjunto de teste para avaliar o desempenho do modelo classificador, utilizando métricas apropriadas como precisão, recall, e F1-score. Realizar ajustes e otimizações conforme necessário.

7. **Otimização e Escala**: Após os testes iniciais, otimizar o sistema para melhorar a eficiência e a precisão. Avaliar a possibilidade de escalar o sistema para suportar a classificação de mais ações ou para ser implementado em diferentes plataformas.

8. **Documentação e Lançamento**: Documentar todo o processo de desenvolvimento, incluindo a coleta de dados, o processo de treinamento, a seleção de modelos e a implementação. Preparar materiais de suporte para facilitar a adoção e utilização do sistema.
