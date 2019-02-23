# Cloud9 Docker

Docker for [Cloud9 IDE](https://github.com/c9/core).

## Build

```bash
docker build -t cloud9:latest .
```

## Usage

```bash
docker run --rm -d -v $HOME:/wd -p 8008:8008 -e USERNAME=usr -e PASSWORD=123 cloud9:latest
```

Visit `localhost:8008` on your web browser, use username `usr` and password `123` to login.