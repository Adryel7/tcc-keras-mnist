# Keras 3: Democratizando o Deep Learning 🧠

Este repositório contém os artefatos práticos e teóricos do meu Trabalho de Conclusão de Curso (TCC) em Engenharia da Computação.

O projeto explora a biblioteca **Keras 3** como uma API multi-backend de alto nível, demonstrando sua eficácia através da implementação de uma Rede Neural (MLP) aplicada ao dataset **MNIST**.

## 📂 Estrutura do Repositório

* **`docs/`**: Contém o artigo científico completo em PDF, detalhando a fundamentação teórica sobre Deep Learning, a evolução do Keras e a análise dos resultados.
* **`notebooks/`**: Contém o experimento prático (`experimento_mnist.ipynb`). O código abrange desde o pré-processamento e data augmentation até o treinamento e avaliação.

## 📊 Resultados Alcançados

O experimento demonstrou a eficiência da simplificação proposta pelo Keras, alcançando métricas competitivas com baixa complexidade de código:

| Métrica | Resultado |
| :--- | :--- |
| **Acurácia Global** | **97.31%** |
| **Arquitetura** | MLP (Dense Layers) |
| **Otimizador** | Adam |
| **Backend** | TensorFlow (via Keras 3) |

## 🚀 Como Executar o Projeto

Você pode visualizar e executar este projeto de duas formas: na nuvem ou localmente.

### Opção 1: Google Colab (Recomendado)
A maneira mais rápida de testar sem instalar nada. O ambiente já conta com GPU configurada.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1M3-VpCAZIu1rjcRALogRUz6fwBtqVWgf?usp=sharing)


### Opção 2: Execução Local

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/tcc-keras-mnist.git](https://github.com/SEU_USUARIO/tcc-keras-mnist.git)
   cd tcc-keras-mnist
   
2. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt

3. **Abra o Notebook::**
   ```bash
   jupyter notebook notebooks/experimento_mnist.ipynb

   ## 🎨 Teste Prático com Imagem Própria

O notebook inclui uma seção dedicada para validação do modelo com dados externos (sua própria caligrafia). Para garantir que o pré-processamento funcione corretamente, siga as instruções abaixo:

1. **Crie a imagem:**
   - Utilize qualquer editor de imagens (Paint, Photoshop, GIMP, etc).
   - Configure o arquivo com **fundo branco**.
   - Desenhe um número (0 a 9) utilizando um pincel ou lápis na cor **preta**.
   - *Dica:* Evite traços excessivamente finos para facilitar a detecção dos recursos pelo modelo.

2. **Salve o arquivo:**
   - Salve a imagem com nome `numberimg` em formato `.png`

3. **Carregue no ambiente:**
   - **No Google Colab:** Faça o upload do arquivo na aba de arquivos (ícone de pasta na lateral esquerda) na pasta `data/`.
   - **Localmente:** Mova o arquivo de imagem para a mesma pasta `data/` onde o notebook está localizado (`notebooks/data`).

4. **Execute a predição:**
   - Rode a célula de teste prático no final do notebook.
   - O algoritmo aplicará automaticamente o tratamento de imagem necessário (redimensionamento para 28x28 pixels e inversão de cores para o padrão MNIST) e exibirá a classificação prevista pela IA.

---
*Desenvolvido como requisito para obtenção do grau de Engenheiro da Computação.*

## 👨‍💻 Autores

Este projeto foi desenvolvido em conjunto por:

* **Adryel Almeida**
  * [LinkedIn](https://www.linkedin.com/in/adryel-almeida-052365321/) | [GitHub](https://github.com/Adryel7)
  
* **Felipe S. de Lima**
  * [LinkedIn](https://www.linkedin.com/in/felipe-salles-6007ba176/)
* **Lucas C. Junker**
  * [LinkedIn](https://www.linkedin.com/in/lucas-junker-978748148/)
