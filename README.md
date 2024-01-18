# QKD Net
Este repositório armazena códigos desenvolvidos em Python para simular redes que utilizam de **Distribuição Quântica de Chaves (QKD)** para para aplicações com criptografia clássica.

## Informações básicas
As redes são construídas com auxílio da biblioteca ``networkx``, contendo topologias da China e Vienna, além de algumas topologias genéricas. Os protocolos QKD utilizados são: BB84, E91, B92. As simulações levam em consideração a topologias da rede, fidelidade dos canais, atributos dos requests, número de qubits e pares EPR disponíveis.

## Diretórios
- ``components/``: arquivos referentes ao funcionamento das simulações.
- ``components/qkd/``: arquivos dedicados ao funcionamento dos protocolos.
