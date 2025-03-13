# database_design_ex1
Aula de DATABASE DESIGN fiz o seguinte exercício passado pela professora

Desenhe o D.E.R. do Modelo Conceitual que represente a seguinte situação:

- Identificar as entidades
- Estabelecer os relacionamentos
- Identificar os atributos de cada entidade e/ou dos relacionamentos, bem como o atributo identificador
- Anotar as cardinalidades dos relacionamentos

1. A empresa Delta tem um nome, é identificada pelo CNPJ e exerce um tipo de atividade. A empresa divide-se em departamentos.
    
    Cada departamento possui um código que o identifica, nome e funcionário responsável (Chefe). Os chefes de departamento podem assumir a chefia no próprio departamento em que estão lotados ou em outro departamento e para a empresa, é importante saber a data em que foi assumida cada chefia.
    
    Os funcionários da empresa estão sempre lotados em um departamento e cada funcionário é identificado por um número, possui um nome, sexo, telefone, dependentes, data de alocação no departamento e cargo.
    
    Os funcionários são alocados em um ou mais projetos e a data de alocação em cada projeto deve ser mantida.
    
    Um projeto é identificado por um código, possui nome, horas previstas e horas gastas.
    
    A cada seis meses é feita uma avaliação de cada funcionário por projeto, de onde se obtém um conceito; a empresa mantém um histórico dos conceitos obtidos, visando analisá-los na época de promoções.
