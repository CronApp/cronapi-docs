Reconhecer o áudio
==================

Envia áudio e retorna resultados de transcrição para um pedido de reconhecimento sem sessão.

Parãmetros
~~~~~~~~~~

O método Reconhecer o áudio aceita os seguintes parãmetros para a sua execução:

username

    Nome do usuário.

password

    A senha.

endPoint

    O novo endPoint da API.

headers

    Nome do cabeçalho que será usado na requisição HTTP.

audio

    O áudio.

options

    reconhece o uso de opções de soquete web.  Saiba mais: https://www.ibm.com/watson/developercloud/speech-to-text/api/v1/#websockets

callback

    a instância onde os resultados serão enviados.

.. include:: recognizeUsingWebSocket-ext.rst
