# Cadastro_de_pessoa
# Boas vindas ao repositório do projeto People Registry!!

# Descrição do projeto
Neste projeto eu fui responsável por criar uma API REST responsável por gerenciar informações de pessoas e seus endereços utilizando Java com Spring-boot e Hibernate.

# Instalação do projeto localmente
Após cada um dos passos, haverá um exemplo do comando a ser digitado para fazer o que está sendo pedido
Realize o clone do projeto no diretório de sua preferência:
git clone  github.com/Eder84Carlos/Cadastro_de_pessoa.git

Acesse o diretório do projeto e depois utilize o comando mvn install para instalar todas as dependências necessárias:
cd people-registry
  mvn install
  
  Após empacote o código compilado com o comando mvn package :
  mvn package
 
# Comandos para usar o Docker
Para criar e iniciar os contêineres:
Obs.: Com o comando abaixo o docker fica rodando no terminal.
docker-compose up

Para criar e iniciar os contêineres em stand-by:
docker-compose up -d

Para realizar apenas a etapa de construção das imagens que serão utilizadas:
docker-compose build

Para paralisar e remover todos os contêineres e seus componentes como rede, imagem e volume:
docker-compose down

# Usando o Spring-boot sem o Docker
Rodar o Spring-Boot com o comando:
mvn spring-boot:run

# Realização dos tes
Para realizar todos os testes da aplicação você pode utilizar o seguinte comando:
mvn clean test

Para realizar somente um teste específico, você deve utilizar o comando:
mvn test -Dtest=O_nome_do_teste_vai_aqui

# Documentação
Para acessar os documentos pelo swagger rode o comando mvn spring-boot:run ou docker-compose up e acesse o projeto via navegador, no caminho http://localhost:8080/swagger-ui/index.html ou pelo caminho http:/ /localhost:8080/v3/api-docs .



