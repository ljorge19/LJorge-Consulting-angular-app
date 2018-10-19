# Avaliação Final angularjs

Neste documento descreveremos os procedimentos para a elaboração e entrega de um trabalho, que é parte integrante da avaliação final da disciplina. O trabalho está dividido em duas partes:


Parte 1 - Projeto Angular
Descrição da atividade:

    • Tomar como base a aula desenvolvida sobre Angular
    • Baseado no modelo quickstart, definir um projeto chamado angular_XXXXX, sendo XXXXX o número do RM de um dos integrantes do grupo.
    • Neste projeto, considerar como modelo os dados de contato de uma pessoa: CPF, NOME, TELEFONE e EMAIL.
    • O projeto deve ter, pelo menos:
        ◦ Uma página inicial (HomeComponent),
        ◦ Um menu de opções (MenuComponent),
        ◦ Um componente para o formulário e listagem de contatos (CadastroComponent),
        ◦ Um componente para tratar páginas não encontradas (ErroComponent).
    • Se achar necessário, incluir outros componentes da sua escolha.
    • Considerar um serviço (service) para conter a lista de contatos a ser exibida.
    • Quando um contato na lista for selecionado, exibir seus dados no formulário.
    • Desenvolver um filtro capaz de listar os contatos pelo nome.
    • Utilizar um webservice local (componente json-server) para a apresentação e inclusão dos dados.

Apresentação

Dado o cenário acima, usar a imaginação e o conhecimento para elaborar as aplicações. As regras são:

    1. Elaborar uma resenha como descritivo de todos os tópicos desenvolvidos no projeto. Suponha que este projeto será oferecido a alguma empresa, e antes de conhecer o produto, ela precisa conhecer a proposta do produto.  Esta resenha deverá ser entregue junto com os projetos.
    2. O projeto poderá ser incluídos em uma pasta na nuvem (google drive, onedrive, etc) e o link fornecido em um arquivo texto a ser postado no portal da Fiap.
    3. A data da entrega será registrada na área de trabalhos no portal da Fiap.


Parte 2 - Trabalho de pesquisa
Realizar uma pesquisa sobre os temas listados abaixo, e apresentar um documento no formato WORD com os resultados e exemplos de aplicação, justificando-os:
Bower (https://bower.io/): Gerenciador de dependências.
Grunt (https://gruntjs.com/):  Aplicação com o objetivo de automatizar tarefas comuns.
Sass (https://sass-lang.com/): Linguagem baseada em CSS que, após compilada, produz o CSS desejado.

Observações:
    • Este trabalho contemplará 60% da nota final.
    • O trabalho pode ser feito em grupos de até 03 pessoas.
    • Dada a natureza flexível dos trabalhos nas duas partes, trabalhos iguais serão anulados!


```sh
npm install -g json-server
json-server banco.json --port 3005
```
