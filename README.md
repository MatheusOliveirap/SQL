# SQL

create database BancoExSql;
use BancoExSql;


create table tbUsuarios(
id_usuario int primary key, 
usuario varchar (50) not null,
login varchar (50) not null,
senha varchar (50) not null,
email varchar (50) not null
);

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1,  'matheuskk', 'reallogin' '2324' 'matheusoliveira@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'lucas', 'lucassss',  '444' 'lcskkkk@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'paulo', 'paulin', '555' 'pauloreal@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'camila', 'camilala', '666' 'camilala2222@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'pedro', 'pedraotlgd',  '777' 'pedrao@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'thailor', 'thailornekk', '4445345' 'thailorkkk@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'arthur', 'arthurlogin', '2345' 'arthursantos@gmail.com ');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'valdirene', 'valdirenetrindade', '645464' 'valdirene@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'Sidinei', 'sidineilogin222', '6656788' 'sidinei@gmail.com');

insert into tbUsuarios(id_usuario, usuario, login, senha, email)
values(1, 'pablo', 'pablojunior', '538288373' 'pablojunior@gmail.com');


create table tbBolsonaro(
altura int primary key,
nome varchar (50) not null,
idade varchar (50) not null,
peso varchar (50)not null,
partido varchar (50) not null
);

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');

insert into tbBolsonaro(altura, nome, idade, peso, partido)
values(1, '1,70', 'Jair messias Bolsonaro', '70', '90kg', 'PL');


create table tbcmd(
id_usuario int primary key,
usuario varchar (50) not null,
login varchar (50) not null,
senha varchar (50)not null,
comandos varchar (50) not null
);

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');

insert into tbcmd (id_usuario, usuario, login, senha, comandos)
values(1, 'matheus', 'realmatheus', '564772', 'sfc scannow');


create table tbLuta(
modalidade int primary key,
ambiente varchar (50) not null,
rounds varchar (50) not null,
tempos varchar (50)not null,
roupas varchar (50) not null
);

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');

insert into tbLuta(modalidade, ambiente, rounds, tempos, roupas)
values (1, 'jiu-jitsu', 'academia', '12' '3:00' 'bermuda');


create table tbEscola(
id_usuario int primary key,
usuario varchar (50) not null,
login varchar (50) not null,
senha varchar (50)not null,
estudantes varchar (50) not null
);

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha, estudantes)
values (1, 'real', 'matheusreal', 'realll' '2424' 'alunos');

insert into tbEscola(id_usuario, usuario, login, senha)
values (1, 'Eder de Rosso', 'ederrosso', '123456');

