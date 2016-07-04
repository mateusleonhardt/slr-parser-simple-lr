# SLR Parser
- Is a type of LR parser with small parse tables and a relatively simple parser generator algorithm. As with other types of LR(1) parser, an SLR parser is quite efficient at finding the single correct bottom-up parse in a single left-to-right scan over the input stream, without guesswork or backtracking. The parser is mechanically generated from a formal grammar for the language.

----------------------------------------------------------------------------------------------------

To run the program, open the slr.html file in a browser of your choice.

----------------------------------------------------------------------------------------------------

The application comes with a grammar and a set of pre-filled production, but nothing prevents the information is changed and other sets of production can be tested.
The productions set entry already contains increased grammar (S '-> S) and each new set of productions added, it is automatically numbered (required step for the next steps).

The 'Gerar Tabela Sintática' button, firstly, creates the tables FIRST / FOLLOW and CLOSURE table with the definitions of the canonical items, ie all structures and information necessary to fill the Syntactical Table LR.

The syntactic table created is based on the previous steps, containing the states ACTION and GOTO.

Finally, there is the sentence recognition option. We have already used a pre-filled example, but any other sentence can be recognized, just change the value of the field 'Sentença a ser reconhecida' The 'Reconhecer entrada' button makes the recognition of this award showing the steps, the stack, the input tape and the action taken.


----------------------------------------------------------------------------------------------------

Developed by: 
- Fernando Wendland
- Gabriel Bittencourt
- Mateus Leonahrdt
