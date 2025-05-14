# pearc25-chat
PEARC 25 - Dartmouth Chat resources

Pleae note that these resources will need to be customized for your environment

* [Ollama](ollama.yml) - Kubernetes manifest for deploying Ollama for use by OpenWebUI
* [Valkey](open-webui-valkey.yml) - Kubernetes manifest for deploying Valkey for Websockets for multiple replicas of OpenWebUI
* [OpenWebUI](open-webui.yml) - OpenWebUI Kubernetes manifest
* [SearXNG](searxng.yml) - Kubernetes manifest for web search proxy for OpenWebUI
* [Text Embedding Inference](text-embeddings-inference.yml) - Kubernetes manifest for embeddings model used for document upload
* [Text Generation Inference](text-generation-inference.yml) - Kubernetes manifest for additional models served from TGI
* [Tika](tika.yml) - Kubernetes manifest for document extraction engine
