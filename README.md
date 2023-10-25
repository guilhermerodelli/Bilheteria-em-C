# Bilheteria-em-C

Status: desenvolvimento 💻

Linguagem: linguagem C

Projeto de faculdade, no qual o objetivo seria criar uma bilheteria online,
gerendo código de ingresso para cada visitante e fazendo a validação do mesmo.

Maior dificuldade foi com o "scanF", quando pedimos para o usuario digitar seu nome o scanf não le entradas de texto com espaço em branco,
exemplo um "nome espaço e sobrenome", a função só le o primeiro nome.
E para isso usamos a função "fgets" que le a linha inteira, por exemplo "nome espaço e o sobrenome".
