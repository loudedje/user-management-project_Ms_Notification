# MS Notification

## Descrição
Este é o repositório para o projeto MS Notification, que faz parte do desafio durante meu estágio na Compass UOL. O MS Notification tem como objetivo lidar com notificações e eventos no sistema, sendo uma parte integrante da arquitetura de microsserviços, juntamente com MS User.

## Pré-requisitos
- Java 17
- Maven
- RabbitMQ
- MYSQL

## Configuração

### RabbitMQ
- Certifique-se de ter o RabbitMQ instalado e em execução.
- Configure as propriedades do RabbitMQ no arquivo `application.yml`.

## Como Executar
1. Clone o repositório: `git clone https://github.com/loudedje/ms-notification.git`
2. Navegue até o diretório do projeto: `cd ms-notification`
3. Execute o projeto: `mvn spring-boot:run`

O aplicativo estará disponível em `http://localhost:8083` por padrão.

## Endpoints

### Notificações
- `POST /v1/notifications`: Envia uma nova notificação.

## Dependências
- MS User: https://github.com/loudedje/user-management-project_Ms_User.git
