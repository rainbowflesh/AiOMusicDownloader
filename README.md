# AiOMusicDownloader

A music downloader fork from `573462273/QQFlacMusicDownloader`, implement with python and fully functional.

## Usage

### In python environment

```shell
pip3 install -r requirements.txt
python MainServer.py --port 9876
```

### Docker

```shell
docker build -t dockerimage .

docker run -p 127.0.0.1:9876:9876 -v path/to/download_folder -it dockerimage:latest
```

#### docker-compose

Possible no longer available, skip this.
