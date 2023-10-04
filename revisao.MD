1. Um plano de execução S de n transações é serializável se  equivalente ao plano de execução serial das mesmas n transações
  - Um plano serial intercalável é considereado um plano serializável
  - Se ele gerar um valor diferente quando comparado aos outros planos seriais ele não pode ser serializável "Problema da atualização perdida"
2. Problemas de Conflito
  - Leitura e escrita de um mesmo item em transações diferentes são conflitantes
  - Equivalência por conflito são quando as ordens de leitura e escrita em dois planos são conflitantes entre suas operações porém ocorrem numa mesma ordem dentro dos planos então eles geram dados equivalentes.
  - Dois planos são considerados conflito serializáveis se forem equivalentes por conflito a um plano serial
