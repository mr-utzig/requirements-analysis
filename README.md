# Requisitos de Software

## Conceitos

- Requisito.
  - Funcional.
  - Não funcional.

- Regra de Negócio.
- Caso de uso.

## Requisito

- Necessidade a ser atendida.
- Requisito de software: Característica necessária.
- Os rumos do desenvolvimento.

A definição da palavra "requisito" significa uma necessidade a ser atendida, Quando usada no escopo do desenvolvimento de software se torna um requisito de software sendo assim uma característica a ser atendida na produção do software. Quando são definidos os requisitos de um software se esta definindo os rumos que devem ser seguidos no desenvolvimento desse software.

O desenvolvimento ocorre para satisfazer um conjunto de requisitos de software.

### Tipos de requisito de software

#### Funcional

- Algo que o programa de fazer ou executar.
- Um requsito funcional é sempre caracterizável por um verbo no infinitivo
  - buscar, definir, recuperar...
- Exemplo: sistema de matrícula
  - Exibir turmas
  - Editar solicitação de matrícula
  - Avaliar solicitação de matrícula

##### Descrição de requisito funcional

- 5W1H
- O que? Por que? Por quem? Quando? Onde Como?
  - Quando for ser definido um requisito funcional deve-se responder essas 6 perguntas.
  - As 6 perguntas devem estar respondidas no contexto do documento de especificação de requisitos.

##### Exemplo: "Avaliar solicitação de matrícula"

- O que?
  - Buscar inconsistências em uma eventual solicitação de matrícula.
- Por que?
  - Garantir a consistência do processo de matrícula.
- Por quem? (normalmente pensamos em usuários)
  - Um estudante
- Quando? (questão temporal)
  - Durante o processo de matrícula.
- Onde? (questão geográfica)
  - Se for um aluno já cadastrado pode ser feito de qualquer lugar que tenha conexão com a internet (sistema web).
  - Se for um novo aluno ele deverá comparecer em um determinado local para realizar o cadastro e validar as informações por um usuário específico do software.
- Como? (deve ser detalhada, deve considerar restrições... [Regras de negócios])
  - Deve obedecer um conjunto de regras:
    - Carga horária mínima e máxima.
    - Os pré-requisitos de cada disciplina.

#### Não funcional

- Características que o software deve aprensentar mas que não são funcionalidades.
- Pode ser restrição associada a funcionalidades.
- Exemplo: "O programa deve ser implementado em..."
- Exemplo: "Persistência redundante em..."
- Possível organizá-la em categorias: (Pode variar)
  - Inteface.
    - Cores.
    - Posição do logotipo.
    - Menus.
  - Suporte de desenvolvimento.
    - IDE.
    - SGBD.
    - Software para modelagem de UML.
  - Plataforma de execução. (IOS, Windows, Linux...)
  - Robustez, integridade, segurança.
  - Performance... etc.

##### Descrição de requisito não funcional

- Em seção específica.
- Mais simples que requisito funcional.

## Regra de negócio

- Não é requisito de software.
- Chamado tambem de "requisito de domínio"
- Independe do mundo computacional.
- Afeta os requisitos funcionais.

A regra de negócio é alguma coisa que eu devo observar porem não se classifica como requisito de software.
Se refere ao domínio do problema que o software trata.

### Exemplos de regra de negócio

#### Avaliar solicitação de matrícula (Requisito funcional)

- Carga horária (máxima/mínima).
  - A carga tem que ser igual ou superior a mínima e igual ou inferior a máxima. (Regra de negócio)
- Pré-requisito.
  - Para se matricular na cadeira de POO II tem que ter sido aprovado em POO I. (Regra de negócio)
- Choque de horário.
  - Duas disciplinas não podem ter horários total ou parcialmente sobrepostos. (Regra de negócio)

### Descrição de regra de negócio

- 1ª possibilidade: Seção específica.
  - Regras referenciadas pelos requisitos funcionais.
- 2ª possibilidade: No corpo dos requisitos funcionais.

## Caso de uso

- Conceito do desenvolvimento (UML).
- Funcionalidade do software.
- Relacionado aos requisitos funcionais.
  - Caso de uso: pelo menos um requisito funcional.
  - Requisito funcional: pelo menos um caso de uso.
- Correspondência entre caso de uso e requisito funcional.

### Exemplos de caso de uso

#### Avaliar solicitação de matrícula
