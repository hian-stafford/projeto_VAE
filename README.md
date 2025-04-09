# Variational Autoencoder (VAE) com PyTorch – Geração de Dígitos Manuscritos

Este projeto implementa um **Autoencoder Variacional (VAE)** utilizando a biblioteca **PyTorch**, com foco na geração e reconstrução de imagens da base **MNIST** (dígitos manuscritos). É um exemplo didático e prático de aplicação de modelos generativos baseados em aprendizado profundo.

---

## ✨ O que este projeto faz?

- Treina um **VAE simples** para comprimir e reconstruir imagens de dígitos (0 a 9).
- Aprende uma **representação latente (vetores z)** para o espaço de imagens.
- Permite **gerar novas imagens realistas** a partir de vetores amostrados aleatoriamente.
- Visualiza os resultados com uso de `matplotlib`.

---

## 🧠 Por que usar um VAE?

O VAE é um tipo de autoencoder **probabilístico**, capaz de:
- Aprender **representações compactas e estruturadas** de dados complexos.
- Realizar **geração de dados sintéticos**, útil em diversos cenários.
- Possibilitar **interpolação e exploração do espaço latente** de forma controlada.

---

## 🚀 Tecnologias e ferramentas utilizadas

| Ferramenta | Utilidade |
|-----------|-----------|
| [PyTorch](https://pytorch.org) | Framework principal de deep learning usado para criar e treinar o modelo. |
| `torchvision.datasets.MNIST` | Utilizada para carregar facilmente o conjunto de dados de treino. |
| `matplotlib` | Geração de gráficos e imagens de saída do modelo. |
| CPU ou CUDA | Suporte para execução tanto em máquinas sem GPU quanto com GPU Nvidia. |

---

## 📚 Dataset utilizado

- **MNIST**: conjunto de 60.000 imagens de treino e 10.000 de teste, com dígitos manuscritos de 0 a 9.
- Dimensões: 28x28 pixels, escala de cinza.

---

## 💡 Possíveis aplicações reais

- **Geração de imagens realistas** (ex: rostos, roupas, arte).
- **Compressão de dados com controle probabilístico**.
- **Análise de anomalias** (comparando reconstruções).
- **Interpolação e transferência de estilo** em domínios visuais.
- **Pré-processamento e representação de dados** em tarefas downstream.
    - Classificar que número está na imagem (0 a 9)
    - Detectar se uma imagem é anômala ou corrompida
    - Agrupar imagens semelhantes
    - Reduzir dimensionalidade para visualização
    - (Todas essas são tarefas downstream, porque usam o que o VAE aprendeu como base.)

---

## 🛠️ Habilidades aplicadas

- Implementação de modelos generativos com **PyTorch**.
- Construção de arquiteturas com `nn.Module`.
- Aplicação de **função de perda com KL divergence**.
- Uso de técnicas de **reparametrização** para treinamento com backpropagation.
- Manipulação de imagens com `torchvision`.
- Geração e visualização de dados sintéticos.

---

## 📷 Exemplos de saída

Abaixo, uma amostra de imagens **geradas pelo modelo VAE** após o treinamento com MNIST:

![output](https://github.com/user-attachments/assets/0ec4d76b-fd32-4ccc-b3e0-cc496051c3c1)

---

## 👤 Autor

**Hian Stafford**  
📧 [hian.correa@gmail.com](mailto:hian.correa@gmail.com)

---
