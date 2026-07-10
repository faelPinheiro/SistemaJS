Sistema de Alunos (HTML + JavaScript)


Sistema de cadastro de alunos rodando direto no navegador, feito com HTML, CSS e JavaScript puro (sem frameworks).


Funcionalidades


Cadastrar aluno (nome, idade e matrícula)

Listar alunos ordenados numericamente pela matrícula

Remover aluno da lista

Validação de campos obrigatórios (não deixa cadastrar com campo vazio)

Validação de matrícula duplicada (não permite duas matrículas iguais)

Mensagens de feedback na tela (sucesso ao cadastrar/remover, erro em validações)

Numeração de exibição sequencial (1, 2, 3...), sem "buracos" ao remover, mantendo a matrícula original de cada aluno intacta


Tecnologias e conceitos utilizados


HTML para estrutura da página

CSS para estilização (formulário em cartão, cores de feedback, layout responsivo simples)

JavaScript puro para toda a lógica:

Manipulação do DOM (document.getElementById, createElement, appendChild)

Arrow functions e métodos de array (filter, some, sort, map)

Eventos (onclick, onchange)

Validação de formulário


Estrutura do projeto


cadastrar() — valida os campos e adiciona um novo aluno à lista

remover(matricula) — remove um aluno pela matrícula

atualizarLista() — reordena e redesenha a lista de alunos na tela

mostrarMensagem(texto, cor) — exibe mensagens de feedback (sucesso ou erro) na página.
