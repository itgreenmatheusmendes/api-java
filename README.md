# api-java
Exemplo de uma API Java utilizando Maven com Springboot.


# Referência
https://medium.com/assertqualityassurance/como-construir-e-testar-uma-api-em-java-utilizando-o-postman-baae69d8b8aa


# Escopo
Durante um apocalipse zumbi os sobreviventes precisam realizar algumas interações e esta API tem como objetivo facilitá-las.


## A API deverá contar com as seguintes funcionalidades:

1- Cadastro de sobreviventes informando o nome, data de nascimento, sexo, inventário atual (item e quantidade) e localização atual (latitude e longitude).

2- Um sobrevivente poderá reportar se outro está infectado e caso julgue necessário, remover o report. Ao acumular três reports o sistema deverá marcar aquela pessoa como infectada, aplicando uma série de restrições explicadas em outros requisitos.

3- Um sobrevivente poderá atualizar sua localização. Não é necessário gravar a localização anterior.

4- Dois sobreviventes poderão trocar itens entre si, contanto que:
	a) Nenhum esteja infectado.
	b) O valor da troca seja igual para os dois lados (vide a tabela de referências dos itens).
	c) Ambos sobreviventes tenham recursos 0necessários para realizar a troca.
	d) Todos os itens existem na tabela de referências de itens.

5- Os sobreviventes poderão consultar a porcentagem de sobreviventes infectada e não infectada.

6- Os sobreviventes poderão consultar a quantidade de itens e valor deles perdida nos inventários dos sobreviventes infectados.


## Referências

### Itens:
- Água        R$ 4,00
- Comida      R$ 3,00
- Medicamento R$ 2,00
- Munição     R$ 1,00