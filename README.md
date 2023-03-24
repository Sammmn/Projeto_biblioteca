# Projeto_banco_de_dados
Projeto da disciplina de banco de dados, trabalho feito no Colégio Estadual Góes Calmon.


Projeto de gerenciamento para a biblioteca (Empréstimo de livros): 


Problema: A biblioteca do nosso colégio, não utiliza nenhum sistema digital e organizado para gerenciar o empréstimo de livros para alunos, o que causa mais trabalho para a funcionária responsável por este empréstimo e abre portas para possíveis furtos.

Hipótese de solução: A criação de um sistema digital para o melhor gerenciamento dos empréstimos, para isso seriam necessários os dados de cada aluno (nome, cpf, telefone, número da matrícula e a turma) bem como a data que este empréstimo foi realizado e o prazo para a devolução do livro, também seria necessário saber qual livro o aluno pegou, para que não haja uma devolução incorreta.

Entidades:

Aluno(atributos): id_aluno, id_escola, nome, CPF, matricula, telefone, turma.

Livro: id_livro, id_editora, título, edição, autor, editora, data_publicacao.

Responsável (bibliotecária): nome, CPF, telefone.

Empréstimo: data, ID_livro, tel_bibliotecaria, ID_aluno, data_limite.

Livro_autor: id_livro, id_autor.

Autor: id_autor, nome.

Editora: id_editora, id_endereco, nome, CNPJ.

Endereço: id_endereco, logradouro, rua, bairro, CEP.

Escola: id_escola, id_endereco, nome.
