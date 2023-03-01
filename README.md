# Banco_de_Dados_Resilia

##  - Descrição do Projeto 
A Resilia está analisando lançar um novo sistema de
acompanhamento e precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.
Recebemos uma tarefa de realizar essa modelagem e responder algumas perguntas para contribuir nesse sistema. 


## ⇨ Existem outras entidades além dessas três?
Professor, Disciplinas

## ⇨ Quais são os principais campos e tipos?
São os campos que contém Id, Nome e Cpf que correspondem INT , VARCHAR e CHAR.

## ⇨ Como essas entidades estão relacionadas?
CURSOS < tem > DISCIPLINAS < ministrado > PROFESSOR < leciona > TURMAS < contém > ALUNOS.


## Dbdiagram

![DBdiagram](https://user-images.githubusercontent.com/115565161/222277419-dec667dc-2dda-4483-b6dc-0268a568b884.png)
