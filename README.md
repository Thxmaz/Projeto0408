# BANCO DE DADOS
CREATE DATABASE skoolla;

USE DATABASE skoolla;

# Cria Tabela Aluno
CREATE TABLE aluno (
	codAluno INT AUTO_INCREMENT,
	nome VARCHAR(100),
	rg VARCHAR(10),
	ra VARCHAR(10),
	endereco VARCHAR(50),
	cidade VARCHAR(50),
	email VARCHAR(100),
	telefone VARCHAR(30),
	PRIMARY KEY (codAluno)
);

# Cria Tabela Funcionário
CREATE TABLE funcionario (
	codFunc INT AUTO_INCREMENT,
	nome VARCHAR(100),
	rg VARCHAR(10),
	cpf VARCHAR(10),
	endereco VARCHAR(50),
	cidade VARCHAR(50),
	email VARCHAR(100),
	telefone VARCHAR(30),
	PRIMARY KEY (codFunc)
);

# Cria Tabela Professor
CREATE TABLE professor (
	codProf INT AUTO_INCREMENT,
	nome VARCHAR(100),
	rg VARCHAR(10),
	cpf VARCHAR(10),
	endereco VARCHAR(50),
	cidade VARCHAR(50),
	email VARCHAR(100),
	telefone VARCHAR(30),
	PRIMARY KEY (codProf)
);
