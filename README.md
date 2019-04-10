# api-java
Exemplo de uma API Java utilizando Maven com Springboot.


# Refer�ncia
https://medium.com/assertqualityassurance/como-construir-e-testar-uma-api-em-java-utilizando-o-postman-baae69d8b8aa


# Escopo
Durante um apocalipse zumbi os sobreviventes precisam realizar algumas intera��es e esta API tem como objetivo facilit�-las.


## A API dever� contar com as seguintes funcionalidades:

1- Cadastro de sobreviventes informando o nome, data de nascimento, sexo, invent�rio atual (item e quantidade) e localiza��o atual (latitude e longitude).

2- Um sobrevivente poder� reportar se outro est� infectado e caso julgue necess�rio, remover o report. Ao acumular tr�s reports o sistema dever� marcar aquela pessoa como infectada, aplicando uma s�rie de restri��es explicadas em outros requisitos.

3- Um sobrevivente poder� atualizar sua localiza��o. N�o � necess�rio gravar a localiza��o anterior.

4- Dois sobreviventes poder�o trocar itens entre si, contanto que:
	a) Nenhum esteja infectado.
	b) O valor da troca seja igual para os dois lados (vide a tabela de refer�ncias dos itens).
	c) Ambos sobreviventes tenham recursos 0necess�rios para realizar a troca.
	d) Todos os itens existem na tabela de refer�ncias de itens.

5- Os sobreviventes poder�o consultar a porcentagem de sobreviventes infectada e n�o infectada.

6- Os sobreviventes poder�o consultar a quantidade de itens e valor deles perdida nos invent�rios dos sobreviventes infectados.


## Refer�ncias

### Itens:
- �gua        R$ 4,00
- Comida      R$ 3,00
- Medicamento R$ 2,00
- Muni��o     R$ 1,00