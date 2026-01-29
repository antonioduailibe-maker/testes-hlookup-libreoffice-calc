# Testes de Regressão para PROCH (HLOOKUP) no LibreOffice Calc

Este repositório contém testes simples de regressão para a função PROCH (HLOOKUP) no LibreOffice Calc, criados com o objetivo de ampliar a cobertura de testes já existentes.

## Casos de teste incluídos

- **Busca horizontal com valor encontrado**  
  Verifica o funcionamento correto da função quando o valor procurado existe na tabela.

- **Busca horizontal com valor inexistente**  
  Verifica o retorno do erro `#N/D` quando o valor procurado não é encontrado.

- **Erro de sintaxe com valor inválido**  
  Verifica o retorno do erro `#NOME?` quando a função PROCH recebe um valor inválido, como `.101`.

Os testes seguem o mesmo padrão de estrutura utilizado em contribuições anteriores para a função PROCV, utilizando arquivos `.ods` e `.csv` para validação do comportamento esperado.
