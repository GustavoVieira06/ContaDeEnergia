
# ContaDeEnergia C#
O sistema consiste em uma aplicação desktop para o cálculo, armazenamento e consulta de faturas de energia elétrica.
O software deve gerenciar dois tipos de perfis, Residencial e Comercial,  cada um com regras de tributação distintas:

Taxa fixa de luz -> 9,25
CPF -> tarifa por KW/h -> R$ 0,40 + IMPOSTO 30% 
CNPJ -> Tarifa por KW/h -> R$ 0,35  + IMPOSTO 18%

Funcionalidades Principais: 
Cadastro: Interface gráfica para registrar clientes (Físicos/Jurídicos)
Persistência: Salvar e carregar os dados automaticamente em arquivos externos (arquivos XML/JSON)
Cálculos Automáticos, retornando o consumo, valor total da fatura (com imposto) e valor liquido (sem imposto)
