GPT-Mini Image 1

GPT-Mini Image 1 é o gerador de imagens oficial da família GPT-Mini, projetado para criar imagens realistas em resolução 4K. É baseado no código do DALL·E PyTorch, mas foi adaptado e otimizado para integrar-se à família GPT-Mini como um modelo independente de geração de imagens.

Principais características

Geração de imagens ultra-realistas em 4K (3840x3840).

Baseado em arquitetura Transformer e VAE (Variational Autoencoder).

Suporta geração de imagens a partir de prompts de texto.

Código totalmente aberto e personalizável para integração com outros projetos da família GPT-Mini.

Treinamento simplificado com datasets customizáveis, podendo evoluir para uso em datasets reais de imagens.


Estrutura do modelo

1. GPTMiniImageVAE: VAE responsável pelo encoding e decoding das imagens.


2. GPTMiniImage1: Modelo Transformer que traduz prompts de texto em imagens.


3. GPTMiniImageDataset: Dataset fictício para treinamento inicial, que pode ser substituído por datasets reais de imagens.



Treinamento

Otimizador: Adam

Função de perda: MSE (Mean Squared Error)

Batch size e número de épocas configuráveis para ajustar desempenho vs memória.



---

📌 Observação: O GPT-Mini Image 1 ainda é um modelo independente. Para integrar com os outros modelos da família GPT-Mini, é necessário adaptar o código de integração manualmente.
