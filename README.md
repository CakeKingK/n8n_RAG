# n8n_RAG

RAG workspace sample (n8n)


# spec

- AI Agent model: gpt-5.4-mini
- Vector DB: pinecone
- Embedding model: OpenAI text-embedding-3-small

# TODO

- set credential
  AI Agent, Google Drive, Pinecone 등 노드별 인증정보 새로 입력 필요

- edit System Message of AI Agent
  default 소설 내용 요약으로 세팅, 필요 시 범용 문서 등으로 시스템 프롬프트 변경

- change extraction node
  default pdf 대상, 필요 시 binary 등 다른 형태로 변환하거나 별도 노드 추가 필요
