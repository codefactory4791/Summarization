# summarization

```bash
gcloud auth login

docker build -t summarization .
docker run -v ~/.config:/root/.config -e GOOGLE_CLOUD_PROJECT=call-summarizatiion summarization
```