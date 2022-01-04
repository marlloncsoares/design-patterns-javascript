# JavaScript Builder
O padrão Builder permite que um cliente construa um objeto complexo especificando apenas o tipo e o conteúdo. Os detalhes da construção são totalmente ocultados do cliente.

# Usando o Builder

A motivação mais comum para usar o Builder é simplificar o código do cliente que cria objetos complexos. O cliente ainda pode direcionar as etapas executadas pelo Construtor sem saber como o trabalho real é realizado. Os construtores freqüentemente encapsulam a construção de objetos compostos (outro padrão de projeto GoF) porque os procedimentos envolvidos são frequentemente repetitivos e complexos.

Normalmente, é a última etapa que retorna o objeto recém-criado, o que torna mais fácil para um Construtor participar de interfaces fluentes nas quais várias chamadas de método, separadas por operadores de ponto, são encadeadas (nota: interfaces fluentes são implementação do Padrão de Encadeamento como apresentado na seção de padrões modernos).