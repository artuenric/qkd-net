# QKD Net
Este repositório contém códigos para simulações de redes que utilizam a **Distribuição Quântica de Chaves (QKD)** para atender requisições de criptografia.

## Informações básicas
A linguagem utilizada é o Python. As redes são construídas com auxílio da biblioteca [networkx](https://networkx.org/), contendo topologias da China e Vienna, além de outras topologias genéricas. Os protocolos QKD utilizados são: BB84, E91, B92. As simulações levam em consideração a topologias da rede, fidelidade dos canais, atributos dos requests, número de qubits e pares EPR disponíveis.

## Instrução de instalação
1. Clonar o repositório
2. Instalar as dependências
   A instalação das dependências pode ser feita de duas formas:
   Opção 1: Por meio do arquivo ``requiriments.txt``.
   ````

## Diretórios
- ``components/``: arquivos referentes ao funcionamento das simulações.
- ``components/qkd/``: arquivos dedicados ao funcionamento dos protocolos.
