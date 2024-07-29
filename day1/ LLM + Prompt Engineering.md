### Running LLM on Macbook

#### Download
```text
https://github.com/ollama/ollama 접속
macOS 버전 다운로드 후 설치
Reference: https://github.com/ollama/ollama/blob/main/README.md
```

#### Quick start
```text
ollama run llama3
```

### Rest API
```bash
curl http://localhost:11434/api/chat -d '{
  "model": "llama3",
  "messages": [
    { "role": "user", "content": "why is the sky blue?" }
  ]
}'
```

