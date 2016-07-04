# SLR Parser
- Is a type of LR parser with small parse tables and a relatively simple parser generator algorithm. As with other types of LR(1) parser, an SLR parser is quite efficient at finding the single correct bottom-up parse in a single left-to-right scan over the input stream, without guesswork or backtracking. The parser is mechanically generated from a formal grammar for the language.

----------------------------------------------------------------------------------------------------

To run the program, open the slr.html file in a browser of your choice.

----------------------------------------------------------------------------------------------------

The application comes with a grammar and a set of pre-filled production, but nothing prevents the information is changed and other sets of production can be tested.
The productions set entry already contains increased grammar (S '-> S) and each new set of productions added, it is automatically numbered (required step for the next steps).

The 'Generate Table Syntactic' button, firstly, creates the tables FIRST / FOLLOW and CLOSURE table with the definitions of the canonical items, ie all structures and information necessary to fill the Syntactical Table LR.

Assim, a tabela sintática criada é baseada nesses passos anteriores, contendo os estados, a AÇÃO (Action) e o DESVIO (goto).

Por fim, existe a opção de reconhecimento de sentença. Já usamos um exemplo pré-preenchido, mesmo dos slides de aula também, mas qualquer outra sentença pode ser reconhecida, basta alterar o campo 'Sentença a ser reconhecida:'. O botão 'Reconhecer Entrada' faz o reconhecimento desta sentença exibindo os passos, a pilha, a fita de entrada e a ação realizada.


----------------------------------------------------------------------------------------------------

Developed by: 
- Fernando Wendland
- Gabriel Bittencourt
- Mateus Leonahrdt
