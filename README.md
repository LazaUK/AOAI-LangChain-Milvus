# AOAI-LangChain-Milvus
Document-based QnA, powered by Azure OpenAI, LangChain and Milvus.



In this repo I'll demo how to utilise Whisper models offline or consume them through an Azure endpoint (either from [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/overview) or [Azure AI Speech](https://learn.microsoft.com/en-GB/azure/ai-services/speech-service/overview) resources).

Each option from the table of contents below is wrapped into a functional Web interface, powered by [Gradio](https://www.gradio.app/) platform.

## Table of contents:
- [Step 1 - Start standalone Milvus instance with Docker](https://github.com/LazaUK/)


## Step 1 - Start standalone Milvus instance with Docker

1. Download the latest version of [docker-compose.yml](https://github.com/milvus-io/milvus/releases/download/v2.3.2/milvus-standalone-docker-compose.yml) YAML file;
2. Start the Milvus Docker instance with the Docker Compose command:
```
docker-compose up -d
```
3. You should get confirmation that the network has been setup and 3 constainers started:
   ![screenshot_1.3_docker](images/aoai_milvus_step1.3.png)
5. 
