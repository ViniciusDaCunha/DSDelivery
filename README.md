# DSDelivery

Modelo conceitual:
![modelo-conceitual](https://github.com/ViniciusDaCunha/DSDelivery/assets/99222396/9e6f8b7a-a068-47f5-a4d5-a5cd2de9ef63)

O DSDelivery é um projeto de sistema de delivery que permite que os clientes possam realizar pedidos de forma fácil e rápida, bem como acompanhar o status de seus pedidos.

Objetivos
O objetivo do projeto é criar um sistema de delivery que seja fácil de usar, seguro e escalável. Para isso, serão seguidos os seguintes passos:

Checklist
Realizar o setup inicial do projeto
Configurar as dependências necessárias
Configurar os arquivos .properties
Configurar a segurança do sistema
Definir o modelo de domínio
Definir as entidades e relacionamentos
Realizar o mapeamento objeto-relacional
Criar um seed com dados de teste
Criar os endpoints necessários
Validar perfil dev
Configurar a base de dados Postgres local
Testar todos os endpoints
Preparar o projeto para implantação
Configurar o arquivo system.properties
Criar um profile prod e commitar o código
Implantar o projeto no Heroku
Criar um app e provisionar Postgres
Criar a base de dados remota
Executar os comandos necessários no Heroku CLI
Dependências
Para este projeto, serão utilizadas as seguintes dependências:

Web: Para criar endpoints e controladores.
JPA: Para realizar o mapeamento objeto-relacional.
H2: Para criar um banco de dados em memória para testes.
Security: Para garantir a segurança do sistema.
Arquivos .properties
Os arquivos .properties serão utilizados para configurar o sistema de acordo com o ambiente em que ele está sendo executado. Serão criados arquivos para os ambientes de desenvolvimento, teste e produção.

Configuração de segurança
A segurança do sistema será garantida pelo Spring Security. Será criado um login e senha para acessar o sistema, bem como será definido o papel de cada usuário.

Modelo de domínio
O modelo de domínio será definido de acordo com as necessidades do sistema. Serão definidas as entidades e os relacionamentos necessários para o funcionamento do sistema.

Entidades e relacionamentos
As entidades e relacionamentos serão criados de acordo com o modelo de domínio definido. Serão utilizadas as anotações JPA para realizar o mapeamento objeto-relacional.

Mapeamento objeto-relacional
O mapeamento objeto-relacional será realizado com o uso do Hibernate, que é uma implementação da especificação JPA.

Seed
Será criado um seed com dados de teste para facilitar o desenvolvimento e testes do sistema.

Criar endpoints
Serão criados os seguintes endpoints:

[GET] /products: Retorna todos os produtos disponíveis para compra.
[GET] /orders: Retorna todos os pedidos realizados.
[POST] /orders: Cria um novo pedido.
[PUT] /orders/{id}/delivered: Atualiza o status de um pedido para entregue.

Para executar este projeto, você precisará ter o ambiente de desenvolvimento Java instalado em seu computador.

Em seguida, siga os seguintes passos:

Clone o repositório do projeto para o seu computador usando o seguinte comando:

bash
Copy code
git clone https://github.com/seu-usuario/DSDelivery.git
Abra o projeto em sua IDE de preferência (recomendamos o IntelliJ IDEA).

Configure o arquivo application.properties com as suas credenciais de banco de dados.

Execute o comando mvn spring-boot:run na linha de comando para iniciar o servidor.

Acesse a URL http://localhost:8080 no seu navegador para ver a página inicial do sistema.
