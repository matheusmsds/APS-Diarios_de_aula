# Instruções da aula de hoje
Terminar de fazer as HU e revisar
Entrega de até dia 22/04 Prototipação e "Checagem LD, HU, P"

# História
Como usuário logado (professor/aluno)
Quero realizar o pagamento online  
Para regularizar minha situação remotamente e ser desbloqueado de  
imediato.  

# Cenários

1. Dado que possuo uma pendência, Quando realizo o  
pagamento remoto, Então o sistema deve  
processar meu pagamento e desbloquear minha conta para novos  
empréstimos automaticamente.  

2. Dado que o usuário com multa em atraso  
Quero realizar pagamentos via PIX ou Cartão no sistema online  
Para regularizar minha situação  remotamente e ser desbloqueado de  
imediato.  

3. Dado que um exemplar seja devolvido em más condições (Danificado)  
Quando o operador registrar a devolução  
Então o sistema deve gerar uma cobrança de reparo/indenização e encaminhar o exemplar para avaliação do acervo.  

4. Dado que o usuário comunique a perda de um exemplar  
Quando o operador registrar a ocorrência de perda no sistema  
Então o exemplar deve ficar indisponível e o usuário deve ser bloqueado para novas movimentações até o pagamento da multa.  

5. Dado que há multa 
Quando o usuário(professor/aluno) possui uma multa
Então deve mostrar no sistema que há uma multa pendente.

6. Dado que não há multa 
Quando o usuário(professor/aluno) verificar sua situação.
Então o sistema deve mostrar no sistema que não há nenhuma multa pendente.

7. Dado que não há internet para o pagamento
Quando o usuário(professor/aluno) não possui acesso a internet
O sistema deve permitir o registro de um pagamento em dinheiro ou cartão presencialmente e desbloquear o usuário.

# História 2 - Regras do Sistema/Operador

Histórias :
Como administrador do sistema ...
1. Quero registrar danos físicos em livros, para que eles sejam
retirados de circulação até avaliação.  
2. Quero aplicar multas automáticas  calculadas à taxa de R$ 1,00
por dia útil de atraso, ignorando o recesso escolar na pausa.  
3. Quero registrar perdas vinculadas a usuários, para bloquear
novas retiradas enquanto pendente. 
4. Quero conferir as multas ativas no sistema, sejam elas de danos ou de atrasos.

