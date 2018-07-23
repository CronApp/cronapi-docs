Adicionar Login por redes sociais em sua aplicação
==================================================

O `Social Login <https://en.wikipedia.org/wiki/Social_login>`_ permite que usuários acessem sua aplicação ou site sem a necessidade de fazer um cadastro prévio, utilizando o login e senha de alguma rede social.

Essa forma de autenticação possui algumas vantagens em relação a forma tradicional de login: Acesso direto pelo usuário sem a necessidade de realizar cadastro, preencher formulários e não precisar lembrar do cadastro para cada site; a validação das informações do usuário possui uma confiabilidade maior, já que foram validadas pela rede social e além disso, sites integrados com redes sociais costumam ter um engajamento maior por parte de seus usuários.


Pré-requisitos
--------------

Antes de começar a seguir os passos do tutorial é preciso ter certeza de que se tem um ambiente minimamente preparado para reproduzir o exemplo. Abaixo estão os requisitos principais.

Requisitos:
~~~~~~~~~~~
1. Projeto do tipo web criado. Caso haja dúvidas de como criar esse tipo de projeto acesse o link (`Criando Projeto Web <Antes de começar a seguir os passos do tutorial é preciso ter certeza de que se tem um ambiente minimamente preparado para reproduzir o exemplo. Abaixo estão os requisitos principais. Requisitos: Projeto do tipo web criado. Caso haja dúvidas de como criar esse tipo de projeto acesse o link (Criando Projeto Web).>`_).

Visão geral: exemplo
--------------------
Nesse tutorial iremos aprender a configurar login social em sua aplicação ou site desenvolvido pelo CronApp, permitindo que o usuário da seu sistema logue utilizando uma das suas redes sociais (Figura 1).

.. image:: https://docs.cronapp.io/download/attachments/30278695/1-login.JPG?version=1&modificationDate=1521659072556&api=v2

Obter ID e chave secreta da rede social
---------------------------------------
Para que sua aplicação ou site possa utilizar o Social Login, é necessário adquirir um ID e chave secreta para o seu sistema diretamente no site da rede social, na área destinada a desenvolvedores. Isso permitirá a troca de informações entre sua aplicação e a rede social. 

Abaixo seguem os links para os tutoriais que ensina o processo de aquisição do ID e chave secreta em diferente redes sociais. Os passos mostrados nesses tutoriais podem ser alterados ou atualizados nos sites das respectivas redes sociais, nesse caso, essas informações deverão ser encontradas na área de desenvolvimento da rede social.

    * `Google <https://docs.cronapp.io/display/CRON2/Obter+ID+e+Chave+secreta+para+permitir+o+login+social+de+contas+Google>`_
    * `Facebook <https://docs.cronapp.io/display/CRON2/Obter+ID+e+Chave+secreta+para+permitir+o+login+social+de+contas+facebook>`_
    * `GitHub <https://docs.cronapp.io/display/CRON2/Obter+ID+e+Chave+secreta+para+permitir+o+login+social+de+contas+GitHub>`_
    * `Linkedin <https://docs.cronapp.io/display/CRON2/Obter+ID+e+Chave+secreta+para+permitir+o+login+social+de+contas+Linkedin>`_

    .. note::
        ** Usuários do CronApppp:** Não é necessário obter ID ou chave secreta para permitir que usuários loguem em seu sistema utilizando o cadastro do CronApp, basta que seu sistema possua permissão para realizar o login social (Figura 5) e esteja ativo o login pelo CronApp (Figura 4).