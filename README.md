Universidade Federal do Ceará<br> Engenharia da Computação
==========================================================



Documento de Requisitos<br> PosGRAD V.0.6
-----------------------------------------



Histórico de Revisões
---------------------

  |**Data**    | **Versão** |  **Descrição**                           |  **Autor** |
  |------------|------------| -----------------------------------------|------------|
  |            | 0.1        |                                          |            |
  |            | 0.2        |                                          |            |
  |            | 0.3        |                                          |            |
  |            | 0.4        |                                          |            |
  |            | 0.5        |                                          |            |
  |            | 0.6        |                                          |            |
  
  <br>

Introdução
==========

<p>Esse projeto está focado no usuário que necessita de uma interface
amigável. Promovendo por meio da simplicidade de layout e descomplexidade no
uso, facilidade até mesmo ao mais inexperiente usuário.<p/>

Visão Geral
-----------

<p>Este documento está organizado em várias
seções com conteúdo específico. A **seção 2** mostra uma visão geral do
escopo do projeto. A **seção 3** descreve os requisitos funcionais da
aplicação. A **seção 4** descreve os requisitos não-funcionais. A
**seção 5** apresenta os diagramas dos casos de uso. A **seção 6**
descreve os casos de uso da aplicação. A **seção 7** mostra o modelo
navegacional da aplicação.<p/>


Descrição Geral do Sistema
==========================

   Requisitos Funcionais:
   ----------------------

 
### Login

<p>Consiste em uma tela de e de um sistema de autenticação, que compara a
chave inserida, com a salva no servidor.<p/>

### Cadastro

<p>Permite a criação de um usuário, ou seja de um novo campo na tabela
*users* do banco de dados.<p/>

### Remoção de Conta

<p>Solicitado usuário sua senha, prosseguida de uma tela de autenticação
por senha para que haja confirmação da real intenção.<p/>

### Alteração de Conta

Modificação de parâmetros da conta, como nome de usuário, email, e
senha. Verificando sempre se há no sistema alguém com os respectivos
nomes de usuários e email, não podendo fazer e reportando erro em caso
de tentativa de duplicidade de parâmetros.

### Contato

Tela que permite o envio de mensagem reportando, erro, problema,
solução ou elogio ao email da empresa.

  Requisitos Não Funcionais:
  --------------------------
<br>

### Conexão com o banco de dados

O tipo de banco de dados utilizado para a aplicação foi o No-SQL, que
apresenta melhor desempenho quando comparado a outros modelos de banco
de dados. Está hospedado em uma plataforma que oferece além de
desempenho, segurança de altíssima disponibilidade em nível global.

### Autenticação

  Devido ao uso da plataforma Firebase tornou-se possível uma abstração
da autenticação, processo dificultoso sem ela, no que se mostra o
salvamento da seção.
