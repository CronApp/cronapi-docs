Registrar um retorno de chamada
===============================

Registra um URL de retorno de chamada com o serviço para uso com solicitações de reconhecimento assíncronas subsequentes.

Parãmetros
~~~~~~~~~~

O método Registrar um retorno de chamada aceita os seguintes parãmetros para a sua execução:

username

    Nome do usuário.

password

    A senha.

endPoint

    O novo endPoint da API.

headers

    Nome do cabeçalho que será usado na requisição HTTP.

callbackUrl

    Um URL HTTP ou HTTPS para o qual as notificações de retorno de chamada devem ser enviadas.

secret

    Uma string especificada pelo usuário que o serviço usa para gerar a assinatura HMAC-SHA1 enviada.

.. include:: registerCallback-ext.rst
