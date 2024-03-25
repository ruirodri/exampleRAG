# Código e Links na apresentação do Rui Rodrigues no TDC Summit - 03/2024

- Meu LinkedIn: https://www.linkedin.com/in/rui-ml-rodrigues/
- Hugging face: https://huggingface.co/
- Ollama: https://ollama.com/
- LM Studio: https://lmstudio.ai/
- Chat with RTX: https://www.nvidia.com/pt-br/ai-on-rtx/chat-with-rtx-generative-ai/ 

Este é um exemplo de aplicação preparada para conversar com um LLM local (um Mistral, no caso) rodando sob Ollama, e que vai utilizar uma abordagem de Retrieval Augmented Generation (RAG) para adicionar conteúdos em documentos de texto como contexto para a geração de respostas do LLM.

- Testado com Python 3.10.12
- Sugiro a criação de um ambiente virtual Python antes te baixar as dependências (que estão no arquivo requirements.txt, na raiz do projeto). O volume de dependências baixadas é grande e está evoluindo com muita rapidez, então tê-las na biblioteca padrão do seu Python não é uma estratégia muito boa.

Baseado no artigo que pode ser encontrado no link abaixo:
https://duyhuynh.substack.com/p/build-your-own-rag-and-run-it-locally
