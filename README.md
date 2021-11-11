## 手順

公式の方法だと上手くいかなかったので

1. docker build -t vscode-generator-code .
1. docker run -itd -v $(pwd):/usr/src/app vscode-generator-code
1. docker ps
1. docker attach < CONTAINER ID >
1. yo code
