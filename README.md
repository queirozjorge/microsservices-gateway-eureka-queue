# Microsserviços com Gateway, Eureka e mensageria com RabbitMQ 

Microsserviços desenvolvidos juntamente com a evolução de um respectivo curso na Alura.
Para rodá-los é necessário clonar este monorepo para sua máquina local, carregar os projetos numa ide e baixar as dependências com auxílio do maven.
É obigatório subir uma instância do RabbitMQ no docker para o correto funcionamento da mensageria.
Com o docker instalado na máquina e devidamente funcional, copie e cole o código abaixo em um prompt de comando:
  - docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.10-management
    
Também se faz necessário a instalação do banco de dados MySQL.
Após isso, primeiro recomenda-se subir o gateway e o eureka-server, na sequência os 3 microsserviços.
