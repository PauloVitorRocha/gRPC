Clonar o repositorio, baixar os seguintes requisitos:
![Screenshot from 2022-02-10 18-44-29](https://user-images.githubusercontent.com/37215459/153501602-85e4d4ce-1d9c-4c4c-b8c1-d20fb8bddc15.png)

e após isso rodar o seguinte comando dentro da pasta helloworld:
```
python -m grpc_tools.protoc -I.. --python_out=. --grpc_python_out=. ../helloworld.proto
```
[This code's documentation lives on the grpc.io site.](https://grpc.io/docs/languages/python/quickstart)
