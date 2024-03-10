# local-llama
Simple script to run llama2 LLM locally on CPU using this docker container as a base https://github.com/aborroy/llama2-docker-multiarch

## Installation
- install [Docker](https://www.docker.com/)
- run this command to integrate shell script 
```shell
sudo curl -o /usr/local/bin/llama https://raw.githubusercontent.com/Fabricio872/local-llama/main/llama
```
- set permission 
```shell
sudo chown $USER /usr/local/bin/llama && chmod +x /usr/local/bin/llama
```
## Usage
> Note that first run will take longer and will require internet connection to download docker container
```shell
llama "hello llama"
```
