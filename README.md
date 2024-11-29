# desafio-DIO-oficina
 Segundo desafio de projeto da DIO - Narrativa Oficina Mecânica.

### Considerações Finais ###
>. Clientes levam para conserto ou para passarem por revisões periódicas.  

Neste ponto, compreendo que é possível agendar mais de um tipo de serviço, por isso criei uma tabela de agendamentos, também para organizar horários de clientes.
***
>. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche 
uma OS com data de entrega.  

Na minha compreensão, não é possível ter tanta certeza se um mecânico pode fazer parte de mais de uma equipe ou se pode realizar mais de um serviço, então assumi que a oficina tem vários funcionários e que cada um faz parte de uma só equipe e que realiza atividades limitadas, já que foi especificado que na tabela de mecânicos existe o atributo "Especialidade".  
***
>. A partir da OS, calcula-se o valor de cada serviço, 
tabela de referência de mão-de-obra.  

Aqui presumi duas tabelas diferentes pois serviço e mão-de-obra tem definições diferentes e o que gera a ordem de serviço é o serviço. Usei como referência o exemplo do cenário de helpdesk, em que a solicitação gera a ordem de serviço.  
***
>. A mesma equipe avalia e executa os serviços  

Não achei que essa linha deveria gerar um relacionamento ou entidade.
***
> . Uma OS pode ser composta de vários serviços e um mesmo 
serviço pode estar contido em mais de uma OS.  
. Uma OS pode ter vários tipos de peça e uma pode estar 
presente em mais de uma OS.  

Usei como exemplo o atributo "local" na tabela relacionamento de estoque & produto do e-commerce. Na minha concepção, fez mais sentido colocar o "valor" na tabela gerada pelo relacionamento e outro valor geral na OS de serviço. Acredito que seja possível refletir esse valor geral da OS através de uma operação, porém ainda não me foi apresentado esse elemento no curso.
***

### Conclusão ###
Achei um cenário muito interessante de modelar e gostei bastante do meu resultado final. Tive mais facilidade e fiquei mais satisfeita com esse desafio do que o de e-commerce, que também gostei muito.  
Algumas tabelas e relacionamentos me geraram algumas dúvidas mas acredito que para uma iniciante em banco de dados, fui capaz de refletir e refinar da melhor forma possível o que foi pedido.