#conversao-temperatura 

# Criar imagem Docker
docker image build -t conversao-temperatura:v1 .

# Criar imagem Docker
docker container run -d -p 8080:8080 --name conversao-temperatura conversao-temperatura:v1