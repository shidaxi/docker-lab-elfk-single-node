# elfk-single-node-docker-labs


## Requirement

Install Docker Desktop https://www.docker.com/products/docker-desktop/

## Run

`docker-compose up -d`

## Usage

根据 filebeat/filebeat.yaml收集的文件和logstash/pipelines/* 里面的规则，将样例日志写入 logs目录对应的文件，即回自动收到elasticsearch，然后便可以从kibana看见了