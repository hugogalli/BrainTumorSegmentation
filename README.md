# Detecção de Tumores Cerebrais usando Detectron2 - Hugo Galli
CONTEUDO: https://colab.research.google.com/drive/1H_TR5lKN2Gzsd40aQXmNXz3AONOMS4se?usp=sharing


Este repositório contém um notebook Jupyter (arquivo .ipynb) que implementa um modelo de detecção de tumores cerebrais utilizando o framework de deep learning Detectron2. O Detectron2 é uma biblioteca de código aberto desenvolvida pelo Facebook AI Research, que fornece uma base poderosa para treinar e implementar modelos de detecção de objetos baseados em deep learning.

O modelo utilizado neste notebook é baseado na arquitetura Faster R-CNN com o ResNet-50 como backbone, que é uma das arquiteturas mais populares em visão computacional para detecção de objetos em tempo real. Essa arquitetura permite que o modelo seja treinado em um grande conjunto de dados e seja capaz de detectar tumores cerebrais em imagens de ressonância magnética (MRI) com alta precisão.

O dataset utilizado para treinar e testar o modelo é o https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection, que consiste em uma coleção de imagens de ressonância magnética (MRI) de tumores cerebrais, juntamente com suas segmentações manuais. O conjunto de dados contém imagens de tumores cerebrais tanto benignos quanto malignos, com diferentes tamanhos e formas, tornando-o uma boa escolha para treinar um modelo robusto de detecção de tumores cerebrais.

Além disso, o notebook Jupyter contém um processo completo de treinamento do modelo e uma avaliação de sua precisão usando métricas comuns de avaliação de desempenho, como precisão, recall e F1-score. O modelo treinado neste notebook pode ser usado para detectar automaticamente tumores cerebrais em imagens de ressonância magnética, o que pode ser útil para auxiliar médicos e especialistas em radiologia na detecção precoce e no tratamento de pacientes com tumores cerebrais.

# Instalação
Antes de executar os comandos praticos do notebook, é necessário ter todas as dependências instaladas. Você pode instalá-las executando os primeiros comandos


# Uso
Para executar o notebook, inicie o servidor Jupyter e abra o arquivo brain-tumor-detection.ipynb. Em seguida, execute as células na ordem em que aparecem.

O notebook possui várias seções, incluindo a importação e visualização dos dados, treinamento do modelo e avaliação dos resultados.

# Contribuindo
Se você deseja contribuir com este projeto, sinta-se à vontade para abrir uma Issue ou enviar um Pull Request.

# Exemplo de resultado da pesquisa
![](https://github.com/hugogalli/BrainTumorSegmentation/blob/main/result_ex.gif)
