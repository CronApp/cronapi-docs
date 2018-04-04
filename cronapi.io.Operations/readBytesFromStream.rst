Ler arquivo por tamanho de bytes
================================

Função para ler um arquivo por bytes, cada leitura é guardada na variável atribuída em "Retorno", e os comandos são executados em cada leitura. Exemplo: um arquivo com 4096 bytes com tamanho de leitura de 1024 bytes será lido quatro vezes.

Parâmetros
~~~~~~~~~~

O método Ler arquivo por tamanho de bytes aceita os seguintes parãmetros para a sua execução:

Arquivo aberto para leitura

     Retorno da função "Abrir arquivo para leitura"

Tamanho

     Tamanho dos bytes a ler por vez, caso nulo, o valor padrão será 1024 bytes

Comandos

     Comandos para serem executados a cada leitura

.. include:: readBytesFromStream-ext.rst
