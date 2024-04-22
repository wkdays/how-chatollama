#用脚本安装chatollama及运行
1.install ollama in docker
```bash
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
