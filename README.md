# verba with flox :)

here's a quick demo repo with a `/.flox` folder
containing a flox environment.

It contains:
- a running ollama daemon
- a weaviate vector db
- verba, a UI service for RAG workflows
- a "models" service to pull pre-trained models from the internet into ollama

This repo also has a few sample markdown documents from the [Flox blog](https://flox.dev/blog).
These are for loading into verba, so that it can chunk and embed vectors for you to perform
RAG.

This env was created by pulling a template from [FloxHub](https://hub.flox.dev):
```bash
flox pull --copy flox/verba
```
