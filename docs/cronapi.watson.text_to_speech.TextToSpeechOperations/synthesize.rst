Sintetizar áudio.
=================

Sintetiza texto para áudio falado, retornando o fluxo de áudio sintetizado como uma matriz de bytes.

Parãmetros
~~~~~~~~~~

O método Sintetizar áudio. aceita os seguintes parãmetros para a sua execução:

username

    Nome do usuário.

password

    A senha.

endPoint

    O novo endPoint da API.

headers

    Nome do cabeçalho que será usado na requisição HTTP.

text

    O texto a ser sintetizado.

voice

    O objeto Java para a voz a ser usada para a síntese.

audioFormat

    O objeto Java para o formato de áudio solicitado (tipo MIME) do áudio.

customizationId

    O GUID de um modelo de voz personalizado que deve ser usado para a síntese.

.. include:: synthesize-ext.rst
