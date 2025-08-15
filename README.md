# Contagem-Inteligente
Algoritmo em Portugol que realiza contagem crescente ou decrescente entre dois valores informados, utilizando estruturas condicionais e de repetição para praticar lógica de programação.

📊 Contagem Inteligente
Este é um projeto simples desenvolvido em Portugol para praticar lógica de programação.
O algoritmo realiza uma contagem crescente ou decrescente de acordo com os valores inseridos pelo usuário.

🚀 Funcionalidade
Solicita ao usuário um valor inicial (INÍCIO).
Solicita um valor final (FIM).
Se o valor inicial for menor que o final, ele conta de forma crescente.
Se o valor inicial for maior que o final, ele conta de forma decrescente.
Exibe cada número separado por .. até atingir o valor final.

🛠 Estrutura do Código
Entrada de dados: Leia(I) e Leia(F) para capturar os valores de início e fim.
Decisão: Estrutura condicional Se...Senao para determinar o sentido da contagem.
Repetição: Estrutura Enquanto para executar a contagem.
Saída: Uso de Escreva e Escreval para mostrar resultados no console.

[UpAlgoritmo "contagemInteligente"

Var
   I, F, cont: Inteiro

Inicio
   Escreval ("CONTAGEM INTELIGENTE")
   Escreval ("--------------------")
   Escreval ("INICIO: ")
   Leia (I)
   Escreval ("FIM: ")
   Leia (F)
   Escreval ("-------------------")
   Escreval ("  C O N T A N D O  ")
   Escreval ("-------------------")
   Se (I < F) entao
      cont <- I
      Enquanto (cont <= F) faca
         Escreva (cont, "..")
         cont <- cont + 1
      FimEnquanto
   Senao
      cont <- I
      Enquanto (cont >= F) faca
         Escreva (cont, "..")
         cont <- cont - 1
      FimEnquanto
   FimSe


Fimalgoritmoloading CONTAGEMINTELIGENTE.ALG…]()
