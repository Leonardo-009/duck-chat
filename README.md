<div align="center">
    <img src="https://github.com/Leonardo-009/duck-chat/assets/88870830/981c096d-f7e2-4fe9-925c-02d19091f1d2">
</div>

# Descrição
Sistema de batepapo online onde é possível criar salas e interagir com outros usuários ao vivo através de websockets.<br>

# Rodando a aplicação
O projeto tem o docker implementado, para dar um build na aplicação é necessário ter o Docker e o docker-compose instalados em sua maquina.<br> 
Basta rodar os seguinte comando:
<br>
>$ `docker-compose up --build`
<br>

# Visualizando o site
Depois de rodar o sistema, ele estará disponível no <a target="_blank" href="http:127.0.0.1:8000"> localhost </a>

![image](https://github.com/Leonardo-009/duck-chat/assets/88870830/8072d3a5-7ab1-4e47-b20c-77a1c4a3265d)<br>
![image](https://github.com/Leonardo-009/duck-chat/assets/88870830/93a94f0f-a9cb-4800-a59f-7c5f1d602067)<br>

# Visualizando o banco de dados
O banco de dados é o PostgreSQL e fica disponível na porta 5432, é necessário algum gerenciador para poder visualizar os dados.<br>

Usuário: postgres<br>
Senha: postgres

<br>

# Tecnologias utilizadas
#### Back-End:
 - Python
 - Flask
 - Flask-Socketio

#### Front-End:
 - HTML5
 - JavaScript
 - JQuery
 - Requisições AJAX
 - SocketIO.js
 - CSS3
 - Bootstrap

#### Banco de Dados:
 -  PostgreSQL
