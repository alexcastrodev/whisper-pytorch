# Transcript

## Install

```bash
docker build -t whisper .
```

## Run Auto detect language

```bash
docker run --rm -v "$PWD:/app" whisper whisper audio.mp3
```


## English

```bash
docker run --rm -v "$PWD:/app" whisper whisper --language English audio.mp3
```