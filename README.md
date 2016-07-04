# SLR Parser

Developed by: 
- Fernando Wendland
- Gabriel Bittencourt
- Mateus Leonahrdt

----------------------------------------------------------------------------------------------------

Para executar o programa, basta abrir a pasta do programa (slr) e dar dois clique no arquivo slr.html

Isso fará com que seja aberto o navegador do seu computador e executado o analisador desenvolvido.

----------------------------------------------------------------------------------------------------

A aplicação já vem com uma gramática e conjunto de produções pré-preenchida. Usamos a mesma dos slides de aula. Porém, as informações podem ser alteradas ou outros conjuntos de produções podem ser testados. A entrada do conjunto de produções já contem a gramática aumentada (S' -> S) e a cada novo conjunto de produções adicionado, o mesmo é numerado automaticamente (passo necessário para as próximas etapas).

O botão 'Gerar Tabela Sintática', primeiramente, cria os FIRST e FOLLOW, CLOSURE, define itens canonicos... enfim, todas as estruturas necessárias para preencher a tabela sintática LR. 

Assim, a tabela sintática criada é baseada nesses passos anteriores, contendo os estados, a AÇÃO (Action) e o DESVIO (goto).

Por fim, existe a opção de reconhecimento de sentença. Já usamos um exemplo pré-preenchido, mesmo dos slides de aula também, mas qualquer outra sentença pode ser reconhecida, basta alterar o campo 'Sentença a ser reconhecida:'. O botão 'Reconhecer Entrada' faz o reconhecimento desta sentença exibindo os passos, a pilha, a fita de entrada e a ação realizada.


----------------------------------------------------------------------------------------------------

Thank you.
