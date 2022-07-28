# Code Review Checklist

## Código

- O código funciona? 
- Funciona da maneira esperada para cada diferente tipo de usuário (administrador proSeleta, cliente, candidato)?
- Ele desempenha o papel esperado?
- A lógica está correta para o objetivo principal e também para as exceções?
- O código é facilmente entendido?
- Existe algum código redundante ou duplicado?
- O código é o mais modular possível?
- Algum código de log ou debug pode ser removido?
- Foi removido todo código comentado?

## Segurança

- Todos os inputs foram validados?
- Tipo
- Maxlenght
- Formato
- Foram testados campos obrigatórios, digitos verificadores, datas válidas, domínios de tabela, valores de fronteira, valores nulos, valores padrão (default) e de tipos diferentes?
- Os parâmetros inválidos foram tratados?
- Todos os dados foram atualizados corretamente?
- Todas as operações de atualização permitidas foram testadas?

## Documentação

- O código possui documentação? Nos principais métodos e lógicas complexas?
- Todas as variáveis foram definidas com nomes significativos, consistentes e claros?

## Performance

- As consultas foram otimizadas pensando-se em melhoria de performance?
- Informações que podem ser armazenadas em cache estão sendo cacheadas?
- Processamentos redundantes ou lentos foram otimizados?
- Foi evitado o uso de construções IF-ELSE para diminuir a complexidade da execução?

## Banco de Dados

- Nome da tabela está correto.
- Estrutura da tabela está correta:
- Descrição dos campos.
- Tipo.
- Restrições e valores default.
- Charset.
- Charset do banco de dados.

## Relatórios

- O relatório foi testado com mais de uma página?
- Foram testadas todas as quebras do relatório?
- Os totais do relatório estão corretos?

## Testes de Navegadores

- Microsoft Internet Explorer 9.0
- Chrome 35.0
- Firefox version 35

## Referências

[https://github.com/Coderockr/Standards/blob/master/Checklist.md]

[http://www.diegobrocanelli.com.br/code-review/melhore-qualidade-codigo-da-sua-equipe-com-code-review/]
