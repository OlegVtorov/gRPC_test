пример работы с gRPC
=
установка либ
-
python -m pip install grpcio  
python -m pip install grpcio-tools

создание кода по proto файлу
-
python -m grpc_tools.protoc --python_out=. --grpc_python_out=. --pyi_out=. --proto_path=. ./venv/protos/*.proto  
Важно: при работе в виртуальном окружении прописывать именно эту команду, во всех гайдах этот момент упускается  

