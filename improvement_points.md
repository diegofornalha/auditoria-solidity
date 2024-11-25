# Notas de Melhoria

Algumas notas de melhoria sobre como ensinar segurança e auditoria em currículos futuros.

## Análises de Auditoria / Bugs

1. Potencialmente tentar uma nova configuração para fazer análises de auditoria.
   1. Opção A: Introdução aos Bugs -> encontrar na análise
      1. Primeiro, passar por uma lista de bugs
         1. Introduzir nomes dos bugs
         2. Mostrar diagramas deles
         3. Fazer uma demonstração deles no remix
         4. Escrever uma PoC deles no foundry (material clássico de vídeo)
         5. Estudos de caso de exemplos reais do bug
      2. Depois, fazer uma análise da auditoria, e dizer "vamos APENAS procurar por estas classes de bugs"
         1. Encontrar bug durante revisão manual/testes fuzzing/etc
         2. Fazer PoC no foundry
         3. Escrever relatório
   2. Opção B: Encontrar bugs conforme aparecem (a implementação atual, mais ou menos)

Acho que devemos tentar a Opção A. Depois, após cada seção, dar aos alunos uma base de código DIFERENTE para que encontrem os bugs. Idealmente essas bases de código podem se tornar primeiros voos posteriormente.
