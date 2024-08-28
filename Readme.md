## Docker setup
```sh
docker build -t san360/phi3medium .
docker push san360/phi3medium
docker run -p 11434:11434 san360/phi3medium
´´´

Tested with data set from https://huggingface.co/datasets/TypicaAI/pii-masking-60k_fr