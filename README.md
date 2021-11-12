## 手順

公式の方法だと上手くいかなかったので

と思ったら、これも上手くいかないー。chownが効いてないなぜ

vsceも上手くいかない。原因不明

1. docker build -t vscode-generator-code .
1. docker run -itd -v $(pwd):/usr/src/app vscode-generator-code
1. docker ps
1. docker exec -it < CONTAINER ID > /bin/sh
1. yo code
