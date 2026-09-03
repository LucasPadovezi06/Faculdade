Pet shop
Diagrama de classes
 
Abstração: representada pela classe abstrata Serviço, que contém características e comportamento comum aos diferentes serviços que tem em um petshop.
Herança: as classes Banho, Tosa e Consulta herdam da classe Servico.
Polimorfismo: o método executar() pode apresentar comportamentos diferentes nas classes Banho, Tosa e Consulta.
Encapsulamento: os atributos das classes são privados, sendo acessados e manipulados através de métodos públicos.



Diagrama de objetos
 
Mensagens entre os objetos:
- joao.adicionarPet(fabito)
João (objeto da classe Cliente) chama o método adicionarPet(), passando o Fabito (objeto da classe Pet) como parâmetro.

- agendamento01.confirmar()
O objeto agendamento01 chama seu próprio método confirmar(), que muda o estado do agendamento (ex.: de "pendente" para "confirmado").
