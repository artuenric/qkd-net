# QKD Net
Este repositório contém códigos para simulações de redes que utilizam a **Distribuição Quântica de Chaves (QKD)** para atender requisições de criptografia.

## Informações básicas
A linguagem utilizada é o Python. As principais redes são baseadas nas topologias reais das redes QKD da China e de Vienna, mas também está disponível além de outras topologias genéricas. Os protocolos QKD utilizados são: BB84, E91, B92. As simulações levam em consideração a topologias da rede, fidelidade dos canais, atributos dos requests, número de qubits e pares EPR disponíveis.

## Instruções de instalação
1. Clonar o repositório

   ````
   $ git clone https://github.com/artuenric/qkd-net.git
   ````
3. Instalar as dependências
   
   As principais ferramentas utilizadas são:
``Numpy``, ``Matplotlib``, ``Networkx``, além do ``Jupyter Notebook``. Para obtê-las, utiliza-se o ``pip``. Isso pode ser feito individualmente, ou por meio do arquivo ``requiriments.txt`` deste repositório com o seguinte comando no terminal:
   ````
   $ pip install -r requirements.txt
   ````
   Este documento contém todas as dependências utilizadas pelo ambiente virtual onde o código foi desenvolvimento.
5. Pronto

   Após clonar o repositório e instalar as dependências, os notebooks e o restante dos códigos já podem ser executados e manipualdos.

## Conteúdo
Os diretórios do repositório estão organizados da seguinte maneira:<br>
- [``components/``](https://github.com/artuenric/qkd-net/tree/0c46fd9d58ff9919eba7d821b81097dcb801f3dc/components): arquivos referentes aos componentes da rede e tudo que abrange o funcionamento das simulações.
- [``components/qkd/``](https://github.com/artuenric/qkd-net/tree/0c46fd9d58ff9919eba7d821b81097dcb801f3dc/components/qkd): arquivos dedicados ao funcionamento dos protocolos.

Além disso, os arquivos em Jupyter Notebook dispostos na raiz contém algumas simulações.
## Ambiente de testes
A ferramenta foi executada e testada na prática nos seguintes ambientes:
1. Windows 11 <br>
   Kernel =  <br>
   Python = <br>
   Módulos Python conforme [requirements.txt](https://github.com/artuenric/qkd-net/blob/0c46fd9d58ff9919eba7d821b81097dcb801f3dc/requirements.txt) <br>

3. Debian GNU/Linux 12.4.0 (bookworm) <br>
   Kernel Version: 6.1.0-17-amd64 <br>
   Python = 3.11.2 <br>
   Módulos Python conforme [requirements.txt](https://github.com/artuenric/qkd-net/blob/0c46fd9d58ff9919eba7d821b81097dcb801f3dc/requirements.txt) <br>
