# ExBanco-17-09

create database BancoEx_17_09;
use BancoEx_17_09;

create table tbUsuarios(
id_usuario int primary key,
usuario varchar (50) not null,
login varchar (50) not null unique,
senha varchar (50) not null,
email varchar (50) not null
);

insert into tbUsuario(id_usuario, usuario, login, senha)
values (1, 'Lucas', 'lucasm', '234','lucas@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (2, 'Luis', 'luisp', '123','luis@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (3, 'Laura', 'laurac', '978','laura@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (4, 'Lutencio', 'lutencioq', '346','lutencio@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (5, 'Lara', 'Larad', '453','lara@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (6, 'Heitor', 'heitork', '675','heitor@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (7, 'Carlos', 'ecarlosw', '132','carlos@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (8, 'Otavio', 'otaviov', '157','otavio@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (9, 'Lisa', 'lisaz', '332','lisa@gmail.com');

insert into tbUsuario(id_usuario, usuario, login, senha)
values (10, 'Pedro', 'pedrot', '795','pedro@gmail.com');

create table tbRestaurante(
Nome int primary key,
ende varchar (50) not null,
Delivery varchar (50) not null,
Carda varchar (50) not null,
Mesas varchar (50) not null
);

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (1, 'RuaA', 'sim', 'carne', 'madeira');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (2, 'RuaB', 'não', 'arroz', 'plastico');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (3, 'RuaC', 'talvez', 'feijão', 'metal');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (4, 'RuaD', 'talvezSim', 'macarrão', 'pedra');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (5, 'RuaE', 'talvezNão', 'café', 'agua');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (6, 'RuaF', 'sera', 'carreteiro', 'ar');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (7, 'RuaG', 'seraQsim', 'linguiça', 'pano');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (8, 'RuaH', 'seraQn', 'tofú', 'terra');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (9, 'RuaI', 'achoQs', 'alface', 'calcario');

insert into tbRestaurante(Nome, ende, Delivery, Carda, Mesas)
values (10, 'RuaJ', 'achoQn', 'suco', 'lava');

create table tbLuta(
Tempo int primary key,
Rounde varchar (50) not null,
Modali varchar (50) not null,
Onde varchar (50) not null,
Cores varchar (50) not null
);

insert into tbLuta(Tempo, Rounde, Modali, Onde, Cores)
values (1, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta(Tempo, Rounde, Modali, Onde, Cores)
values (2, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta(Tempo, Rounde, Modali, Onde, Cores)
values (3, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta(Tempo, Rounde, Modali, Onde, Cores)
values (4, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta(Tempo, Rounde, Modali, Onde, Cores)
values (5, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta (Tempo, Rounde, Modali, Onde, Cores)
values (6, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta (Tempo, Rounde, Modali, Onde, Cores)
values (7, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta (Tempo, Rounde, Modali, Onde, Cores)
values (8, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta (Tempo, Rounde, Modali, Onde, Cores)
values (9, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbLuta (Tempo, Rounde, Modali, Onde, Cores)
values (10, 'Eder de Rosso', 'ederrosso', '123456');

create table tbTeclado(
Teclas int primary key,
Tamanho varchar (50) not null,
Nasc varchar (50) not null,
Cor varchar (50) not null,
Tipo varchar (50) not null
);

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (1, 'grande', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (2, 'pequeno', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (3, 'medio', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (4, 'minimio', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (5, 'grandão', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values (6, 'pequeninho', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values(7, 'mediozinho', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values(8, 'large', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values(9, 'largezão', 'ederrosso', '123456');

insert into tbTeclado(Teclas, Tamanho, Nasc, Cor, Tipo)
values(10, 'largezinho', 'ederrosso', '123456');

create table tbEscola(
Nome int primary key,
Onde varchar (50) not null,
Diretor varchar (50) not null,
Cor varchar (50) not null,
Tamanho varchar (50) not null
);

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(1, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(2, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(3, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(4, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(5, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(6, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(7, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(8, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(9, 'Eder de Rosso', 'ederrosso', '123456');

insert into tbEscola(Nome, Onde, Diretor, Cor, Tamanho)
values(10, 'Eder de Rosso', 'ederrosso', '123456');
