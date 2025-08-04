# BANCO DE DADOS
CREATE DATABASE skoolla;

USE DATABASE skoolla;

CREATE TABLE Aluno(
	codAluno INT AUTO_INCREMENT,
	nome VARCHAR(100),
	RG   VARCHAR(10),
	RA   VARCHAR(10),
	Endereco VARCHAR(50),
	Cidade VARCHAR(50),
	Email  VARCHAR(100),
	Telefone VARCHAR(30)
	);
	
CREATE TABLE Funcionario(
	codFuncionario INT AUTO_INCREMENT,
	nome VARCHAR(100),
	RG   VARCHAR(10),
	CPF   VARCHAR(10),
	Endereco VARCHAR(50),
	Cidade VARCHAR(50),
	Email  VARCHAR(100),
	Telefone VARCHAR(30)
	);
	
CREATE TABLE Professor(
	codProfessor INT AUTO_INCREMENT,
	nome VARCHAR(100),
	RG   VARCHAR(10),
	CPF   VARCHAR(10),
	Endereco VARCHAR(50),
	Cidade VARCHAR(50),
	Email  VARCHAR(100),
	Telefone VARCHAR(30)
	);
