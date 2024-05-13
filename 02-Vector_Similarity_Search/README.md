# Vector Similarity Search with Redis

[Always-on demo by Anton](https://antonum-redis-vss-streamlit-streamlit-app-p4z5th.streamlit.app/)

![Redis](https://redis.com/wp-content/themes/wpx/assets/images/logo-redis.svg?auto=webp&quality=85,75&width=120)


Este notebook irá gerar embeddings para o VectorDB (Redis) usando um modelo pré-treinado gratuito: `sentence-transformers/all-MiniLM-L6-v2`

Este modelo é da [HuggingFace](https://huggingface.co/) ! Deem uma olhada nos Sentence Transformers. Quando eu quero overkill, uso outro da HF também:
```
VSS_INDEX_TYPE = "HNSW"
VSS_DATA_TYPE = "FLOAT32"
VSS_DISTANCE = "COSINE"
VSS_DIMENSION = 768
VSS_MODEL = "sentence-transformers/all-mpnet-base-v2"
```
