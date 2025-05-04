# ollama-embedding

# 🧠 Gerar de Embeddings com Ollama

Este projeto demonstra como gerar vetores de embeddings utilizando o [Ollama](https://ollama.com) rodando localmente, por meio de um notebook Jupyter.

## 🚀 O que este projeto faz

- Conecta à API local do Ollama
- Envia um texto simples
- Gera o vetor de embedding usando o modelo `nomic-embed-text`
- Exibe o tamanho e os primeiros valores do vetor

---

## 🧱 Pré-requisitos

- Python 3.8+
- Jupyter Notebook
- Ollama instalado localmente: [Instruções de instalação](https://ollama.com)
- Modelo de embeddings baixado: [nomic-embed-text](https://ollama.com/library/nomic-embed-text)

```bash
ollama pull nomic-embed-text
```
## Dependências

```bash
pip install requests
```
