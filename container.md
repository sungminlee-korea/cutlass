### 컨테이너 빌드
```
docker run -d -t --name cutlass_study -v $(pwd):/workspace --gpus all cuda_dafault:v1.0
```
### 컨테이너 실행
```
vscode 연결 or
docker exec -it cut_container /bin/bash
```
