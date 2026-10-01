Nome: João Pedro Ramos Soares
RA: a086e378f0dabc4351

## Problema da empresa
basicamente a empresa quer que calcule o valor do produto ja com o desconto aplicado. Nesse caso está sendo testado quanto fica um produto de 200 reais com 10% de desconto

## Arquivos
-servidor.py: recebe a chamada RPC e executa o cálculo.
-cliente.py: solicita o cálculo ao servidor e mostra a resposta.

## Resultado do teste
No servidor:
PS C:\Users\Dev Inntegra\Desktop\Prova> python servidor.py
Servidor RPC aguardando solicitações...
127.0.0.1 - - [30/Sep/2026 22:41:03] "POST / HTTP/1.1" 200 -

No cliente:
PS C:\Users\Dev Inntegra\Desktop\Prova> python cliente.py
Preço final: 180.0


## Explicação
1. Em qual programa o cálculo foi executado?
   R: No servidor.py
2. Qual programa inciou a solicitação?
   R: O cliente.py
3.  O que aconteceria com o cliente se o servidor estivesse desligado?
   R: O programa cliente.py não conseguiria conectar e alcançar a função e retornaria erro de conexão.
