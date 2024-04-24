# lab-natty-or-not_DIO

## Desafio de projeto da DIO [Natural ou Fake Natty? Como Vencer na Era das IAs Generativas!](https://web.dio.me/project/natural-ou-fake-natty-como-vencer-na-era-das-ias-generativas/learning/95e52735-b8ac-4657-bd4b-0a9cf3c1a5db?back=/track/coding-future-vivo-python-ai-backend-developer&tab=undefined&moduleId=undefined)

[Link para o repositório da DIO](https://github.com/digitalinnovationone/lab-natty-or-not)

---

# Explorando IAs Generativas para Criar Conteúdo Criativo

## 📒 Descrição
Este projeto tem como objetivo explorar o potencial das Inteligências Artificiais Generativas (IAGs) para criar conteúdos criativos e realistas, como imagens, textos, áudios, vídeos e suas combinações. Foram Utilizados diversas técnicas e modelos de IAGs para gerar conteúdo inovador e surpreendente.

## 🤖 Tecnologias Utilizadas
* Redes Neurais Recorrentes (RNNs)
  As RNNs são projetadas para processar dados sequenciais, onde a ordem dos elementos na sequência é importante, como texto, áudio e séries temporais.
  Uma característica chave das RNNs é que elas mantêm estados ocultos que são atualizados a cada passo de tempo, permitindo que a rede mantenha informações de contexto sobre a sequência até o momento atual.
  No entanto, as RNNs tradicionais têm dificuldade em capturar dependências de longo prazo em sequências devido ao problema de desvanecimento ou explosão do gradiente.  
  1. OpenAI GPT: Embora a versão completa do GPT (Generative Pre-trained Transformer) da OpenAI seja paga, eles oferecem uma versão menor chamada GPT-3.5 que pode ser usada gratuitamente para fins não comerciais. O GPT-3.5 é baseado em arquiteturas de RNNs e pode ser usado para gerar texto de forma criativa.
  2. NVIDIA Deep Learning Examples: A NVIDIA disponibiliza exemplos de aprendizado profundo em seu repositório GitHub, que incluem modelos de RNNs pré-treinados para várias tarefas. Esses modelos podem ser baixados e usados gratuitamente.
* Transformers
  Os Transformers são uma arquitetura de rede neural baseada em mecanismos de atenção que foram introduzidos pela primeira vez no modelo "Attention is All You Need" em 2017.
  Os Transformers eliminam a necessidade de recorrência ao usar mecanismos de atenção para capturar as dependências entre elementos na sequência. Isso permite que eles capturem relações de longo alcance de forma mais eficaz.
  Os modelos de Transformer consistem em múltiplas camadas de auto-atendimento (self-attention) e camadas de feedforward, o que os torna altamente paralelizáveis e eficientes para treinamento em grandes conjuntos de dados.
  1. Hugging Face Inference API: A Hugging Face também oferece uma API de inferência que permite acessar modelos de Transformers pré-treinados diretamente na nuvem, sem a necessidade de configurar um ambiente local. Você pode usar essa API gratuitamente para fazer inferências com modelos de Transformers em tempo real.
* Outras técnicas de IAs Generativas
  Autoregressive Models: são modelos generativos que modelam a distribuição conjunta de uma sequência de dados como o produto de distribuições condicionais ao longo da sequência. Eles geram dados de forma iterativa, amostrando uma dimensão de cada vez, condicionada aos valores anteriores.
  1. PixelCNN: Uma arquitetura de modelo autoregressivo para geração de imagens, implementada no TensorFlow e no PyTorch.
  2. WaveNet: Um modelo autoregressivo desenvolvido pelo DeepMind para geração de áudio, implementado no TensorFlow.
