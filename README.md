Sistema de cadastro no Tkinter
==============================

Este é um prototipo de um sistema de cadastro de pessoas, usando Tkinter para a interface gráfica e SQLite como banco de dados


Descrição: A aplicação permite as seguintes funcionalidades:
------------------------------------------------------------
  -Criar um novo cadastro de pessoa
  
  -Editar cadastros realizados
  
  -Deletar cadastros por um sistema de busca de CPF
  
  -Vizualizar o historico de atividades feitas pelo programa


Como rodar a aplicação:
------------------------------------------------------------
  -Baixe a paste com os arquivos .py(todos são necessários) e execute o arquivo main na IDE de sua escolha


Requisitos:
------------------------------------------------------------
  -Ter o Python 3.11.9 ou superior instalado


Estrutura do Projeto
------------------------------------------------------------
O projeto é composto por 8 arquivos:

  -main é responsavel pela criação da janela príncipal onde todo o programa se estrutura ao redor
  
  -tela_login cria uma janela onde é feita a entrada de usuário e senha para genrenciamento de acesso
  
  -os arquivos frames_ são responsaiveis pelas janelas onde o usuário pode interagir com as funcionalidades do programa
  
  -funcoes_db é onde tem o backend para executar as interações com o banco de dados
  
  -validor_entry foi armazenado todas as validações de entrada de usuário para serem puxadas por outros programas mais facilmente
  
  -widgets está armazenando botões, labels, entry e combobox, alguns com estilos variáveis para serem reutilizados ao longo do programa
