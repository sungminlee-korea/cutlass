# 도커 빌드
```
docker build -f dockerfile -t cut_docker:v1.0 .
```
# 도커실행 (w/ args)
```
docker run -d -t --name cut_container -v $(pwd):/workspace --gpus all cut_docker:v1.0
```
```
vscode 연결 or
docker exec -it cut_container /bin/bash
```
