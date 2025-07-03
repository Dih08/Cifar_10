# Projeto CIFAR-10 - Classificação de Imagens com CNN 🧠📷

Este projeto tem como objetivo construir e treinar uma rede neural convolucional (CNN) para classificar imagens do conjunto de dados CIFAR-10. O CIFAR-10 contém 60.000 imagens coloridas de 32x32 pixels, divididas em 10 classes: avião, automóvel, pássaro, gato, cervo, cachorro, sapo, cavalo, navio e caminhão.

## 🔧 Tecnologias Utilizadas
- Python
- PyTorch
- NumPy
- Matplotlib

## 📁 Estrutura do Projeto
- `cifar10_model.py`: Arquitetura da CNN
- `train.py`: Script de treinamento
- `evaluate.py`: Avaliação do modelo
- `utils.py`: Funções auxiliares
- `README.md`: Este documento

## 🧠 Arquitetura da Rede
- Camadas convolucionais com ReLU e MaxPooling
- Camadas densas com Dropout
- Softmax na saída para classificação multiclasse

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências com `pip install -r requirements.txt`
3. Execute o treinamento com `python train.py`
4. Avalie o modelo com `python evaluate.py`

## 📊 Resultados
- Acurácia no conjunto de teste: **76.63%**
- Gráfico de desempenho incluído em `grafico_acuracia.png`

## 📌 Referência
Krizhevsky, A. (2009). *Learning Multiple Layers of Features from Tiny Images*. University of Toronto.

---

Este README é inspirado em projetos como o [Projeto-Cifar-10 de Mauricio Souza](https://github.com/MAURICIOASSOUZA/Projeto-Cifar-10), que também utiliza CNNs com técnicas como Batch Normalization, Dropout e Early Stopping para evitar overfitting.

Se quiser, posso te ajudar a montar o código completo ou melhorar a arquitetura para alcançar uma acurácia ainda maior. Quer seguir por esse caminho?
