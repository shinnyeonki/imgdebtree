# 우분투 의존성 확인시 image 로 볼 수 있는 스크립트 파일
```shell
cd <project_clone_folder>
sudo chmod +x imgdebtree

mv imgdebtree /usr/local/bin
#없으면
mv imgdebtree /usr/bin
``` 


gcc 의존성 확인
```shell
imgdebtree gcc
```
