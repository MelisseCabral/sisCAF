# sisCAF
Prótotipo criado para o HackDay Sobral (05/05/2018)
> *.*

Histórico de Revisões

  **Data**     **Versão**   **Descrição**                             **Autor**
  ------------ ------------ ----------------------------------------- -----------
  25/03/2018   0.1          Definições de layout.                     
  26/03/2018   0.2          Adição do framework Firebase.             
  28/03/2018   0.3          Terminada autenticação.                   
  30/03/2018   0.4          Terminada, alteração de conta.            
  01/04/2018   0.5          Implementação de contato.                 
  04/04/2018   0.6          Implementação de interface de apostador   

Conteúdo

Introdução
==========

<p>Esse projeto está focado no usuário que necessita de uma interface
amigável de apostas de seu time favorito, quase que corriqueiramente.
Promovendo por meio da simplicidade de layout e descomplexidade na
aposta, facilidade até mesmo ao mais inexperiente usuário.<p/>

<p>Assim como, a utilização pelo usuário mais experiente, tornando possível
sem o entendimento de sintaxe de programação, por meio de uma
programação cognitiva, nativa do cotidiano de quem aposta, apenas
contendo blocos lógicos básicos de axiomas lógicos como, se, repita até,
aposte, saia do jogo, etc.<p/>

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

1.  Requisitos Funcionais
    =====================

 
Login
-----

> Consiste em uma tela de e de um sistema de autenticação, que compara a
> chave inserida, com a salva no servidor.

Cadastro
--------

> Permite a criação de um usuário, ou seja de um novo campo na tabela
> *users* do banco de dados.

Remoção de Conta
----------------

> Solicitado usuário sua senha, prosseguida de uma tela de autenticação
> por senha para que haja confirmação da real intenção.

Alteração de Conta
------------------

> Modificação de parâmetros da conta, como nome de usuário, email, e
> senha. Verificando sempre se há no sistema alguém com os respectivos
> nomes de usuários e email, não podendo fazer e reportando erro em caso
> de tentativa de duplicidade de parâmetros.

Contato
-------

> Tela que permite o envio de mensagem reportando, erro, problema,
> solução ou elogio ao email da empresa.

1.  Requisitos Não Funcionais
    =========================

    1.  Conexão com o banco de dados.
        -----------------------------

> O tipo de banco de dados utilizado para a aplicação foi o No-SQL, que
> apresenta melhor desempenho quando comparado a outros modelos de banco
> de dados. Está hospedado em uma plataforma que oferece além de
> desempenho, segurança de altíssima disponibilidade em nível global.

 Autenticação
-------------

> Devido ao uso da plataforma Firebase tornou-se possível uma abstração
> da autenticação, processo dificultoso sem ela, no que se mostra o
> salvamento da seção.
