# lt_frota
projeto - software product - impacta

# dependencias node
- express
- cors
- dotenv
- nodemon

# query para criação do banco (tem no arquivo .sql tbm)
create database dbCars;

use dbCars;

create table carros (
codigo int primary key auto_increment,
marca varchar(20),
modelo varchar(30),
descricao varchar (100),
valor varchar(10)
);

select * from carros

# troca de senha do user root no mysql em caso de erro de autenticação
ALTER USER 'root'@'localhost' IDENTIFIED WITH 'mysql_native_password' BY 'senha1234';
