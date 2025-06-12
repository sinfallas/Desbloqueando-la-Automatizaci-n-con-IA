# N8n

Basado en: [llm-lab](https://github.com/tecno-consultores/llm-lab)

Para ejecutar N8N con todas las recomendacion en AMD64/ARM64 (Postgres, Redis):

```bash
docker compose -f docker-compose.yml --env-file env.example --profile n8n --profile openwebui up -d
```

Para acceder a N8N vaya a: http://localhost:5678


Para acceder a Open WebUI vaya a: http://localhost:8080


Servicios recomendados:

Vector DB:
* [Pinecone](https://www.pinecone.io/)
* [Chroma](https://github.com/chroma-core/chroma)
* [Qdrant](https://github.com/qdrant/qdrant)

UI:
* [OpenwebUI](https://github.com/open-webui/open-webui)

Memoria:
* [Zep](https://www.getzep.com/)
* [Airtable](https://airtable.com/)

Voz:
* [Elevenlabs](https://elevenlabs.io/)

Modelos:
* [Openrouter](https://openrouter.ai/)

Buscador:
* [Tavily](https://tavily.com/)

Web Scrapping:
* [Jina.AI](https://jina.ai)
* [Browserless](https://www.browserless.io/)
