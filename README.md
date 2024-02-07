# FundamentosArquiteturaSoftware

 - Fundamentos de Arquitetura de Software, é um curso do Eduardo Pires.

# O que é arquitetura

 - Arquitetura é a organização fundamental de um sustema incorporada em seus componentes, relacionamentos com o ambiente e os princípios que conduzem seu design e evolução.[ISO/IEEE 42010-2011].
 
 - Exemplo Tradicional:
    - Como: Waterfall.
    - O que: Aplicação Monoliticas.
    - Onde: Servidores fisicos.

 - Exemplo Atual:
    - Como: Metodos Ageis.
    - O que: Aplicação em camadas(N-TiersApps).
    - Onde: Servidores Virtuais.

 - Exemplo Emergindo:
    - Como: DevOps.
    - O que: Microserviços & API.
    - Onde: Containers(Docker), Hybrid Cloud(Nuvem Hibrida).

 - Exemplo do Futuro:
    - Como: NoOps (sem operação, só desenvolvimento)
    - O que: Serverless services(não precisa de um app, cria funções que roda em nuvem, essas funções se integra uma com a outra.)
    - Onde: Serverless Computing, public cloud(ter um aplicação totalmente em nuvem)

 - Como conceituar a arquitetura?
 - Como deginir a arquitetura?
 - Como gerir uma governança de arquitetura?

 - TOGAF: um documento complexo que se aprofunda para responder essas questoes. 

# O arquiteto

 - Um especialista em soluções para desenvolvimento. Possui uma visão madura e aguçada.

    - Arquiteto Corporativo.
    - Arquiteto Negocio.
    - Arquiteto Software.
    - Arquiteto Soluções.

# Arquiteto Corporativo. 

 - Objetivo: Garantir a estrategia do negocio com soluções em TI.

 - Artefatos: Estratégia de TI, mapas de capacidade, estratégias de integração, análise as-is/to be, analise de gap.

 - Conceito chave: Alinhamento entre TI e negócios.

 ### The Zachman Framework

 - Oque, Como, Onde, Quem, Quando, Porque.

 - Escopo, Modelo de negocio, Sistema(logica), Tecnologia, detalhes da representações, e como funciona a corporação.
 
# Arquiteto de Negócios

 - Objetivo: Modelagem do negócio da organização entendendo os processos atuais e sugerindo melhorias.

 - Artefatos: Mapa de processo, casos de uso e modelos informacionais.

 - Conceito chave: Entender o funcionamento da organização.

# Arquiteto de Soluções

 - Objetivo: Projetos de soluções em TI baseado nos requisitos do negócio, utilizando as capacidades de TI existentes na organização.

 - Artefatos: Diagrama de aplicações, mapas de sistema, interfaces de serviços, interfaces de serviçõs técnicos

 - Conceito chave: Suportar a estratégia do negócio.

# Arquiteto de Software

 - Objetivo: Projetar aplicações utilizando conceitos de arquitetura e boas práticas de desenvolvimento.

 - Artefatos: Frameworks, arquiteturas / modelos de referência, análise de cenários / desafios técnicos.

 - Conceito chave: Qualidade, Flexibilidade, Performance, Reuso, Testabiblidade, Escalabilidade e Segurança.

# Outros perfis de arquitetos

 - Objetivo: Projetar aplicações utilizando conceitos de arquitetura e boas práticas de desenvolvimento

 - Artefatos: Frameworks, arquiteturas / modelos de referência, análise de cenários/ desafios técnicos.

 - Conceito chave: Qualidade, Flexibiblidade, Performace, reuso, testabilidade, escalabilidade e segurança.

# Perfil do Arquiteto de Software

 - O principal requisito técnico de um arquiteto de software é o profundo conhecimento em programação e componentização. Conhecimentos adquitidos através de experiências sólidas em projetos.

 - Dominar amplamente alguma plataforma de desenvolvimento, frameworks, ferramentas e modelagem técnica.

 - Conhecer abordagens de arquitetura e padrões para soluções de porblemas.

 - Conhecer técnicas de design de código e qualidade para permitir uma fácil manutenção e testabilbidade.

# Requisitos Pessoais "Soft Skills"

 - Liderança.
 - Comunicação(Auto confiança).
 - Proatividade(prever alguns acontecimentos).
 - Mindset Empreendedor.
 - Humildade.
 - Tomar boas decisões.
 - Estar aberto para críticas e sugestões.
 - Ser um profundo pesquisador.
 - Ser didático.
 - Saber delegar tarefas.
 - Saber questionar.
 - Saber conduzir discussões.
 - Saber conversar com diferentes níveis hierárquicos.
 - Estar sempre aberto ás novas tecnologias(leitura, ventos, foruns).
 - Esta sempre atualizado com o mercado.
 - Maturidade e equilíbrio emocianl.
 - Ter pensamento estratégico.
 - Reconhecer e assumir os próprios erros e de sua equipe.

# Mitos(Mentiras)

 - Arquiteto não programa apenas lidera.
 - Todo senior é um arquiteto. 
 - Precisa de muito tempo.
 - Basta só estudar as técnicas(precisa saber quando usar)
 - Trabalha isolado.
 - Não pode ser questionado.
 - É um gerente técnico(nem sempre).
 - Ele e uma pessoa graduada em Arquitetura de Software.
 - Está sempre na liderança(nem sempre).

# Orientação a Objetos - Pilares

 ### Pilares

 - Estado
 - Comportamento
 - Encapsulamento
 - Abstração
 - Polimordismo
 - Herança

 - É essencial possuir um claro conhecimento dos princípios da orientação a objetos para poder aplicar as melhores práticas de design de código, padrões e abordagens de arquitetura.

 - Na orientação a objetos devemos sempre buscar o baixo acoplamento e a alta coesão entre os objetos.

   ### Acoplamento(ruim): 
   
    - Uma dependência direta entre um objeto e outro. Quando um objeto muda o outro muda por conseqûencia.
    - Exemplo: instanciar objeto dentro do outro, herança mal feita.

   ### Coesao(boa):

    - Obejtos executando uma única responsabilidade livres de uma dependência direta com um outro objeto.
    - Obbjetos independente.

# Orientação a Objetos - Estado e Comportamento.

 - Classe: é uma representação de dados de algo do mundo real.
 - Objeto: Uma instancia da classe, na memória com valores.

 - Estado: É representado pelas propriedades da classe.
 - Comportamento: É representado pelos métodos da classe.

# Orientação a Objetos - Herança

 - Antes de por uma herança, se pergunta se a classe é um "nome da herança", exemplo: "a classe funcionario é uma classe pessoa", se fazer sentido, pode por pessoa como herança de funcionario, mesmo assim tem que ver se valer apena.

 - exemplo que não faz sentido: "a classe funcionario é um classe livro", dessa forma não deve ter livro como herança, os atributos e métodos não vão fazer sentido para a classe funcionario. 

# Orientação a Objetos - Abstração (a super classe).

 -   Oferece um conjunto de estado e comportamento, que abstrai uma certa especialização.

 - Classe abstrata e os metodos abstrato!!

 - Não precisa implementar os metodos na classe pai, pode ser implementado no filho que vai herdar.

 - metodos e propriedades que vc sabe que vai ser usado, como classe abstrata Eletrodomestico, como se fosse uma classe pai que define o tipo da classe(foi o que eu entendi).

 - A classe abstrata só pode ser herdada e nunca instanciada.

# Orientação a Objetos - Polimorfismo

 - siginificado: muitos comportamentos.

 - override: sobrescrever a classe base.

 - base(): siginifica que a classe herdada ja obriga a ter essa propriedade.

 - Tipo virtual: não te obriga a sobrescerver os métodos, mas da a possibilidade.

 - Tipo abstract : te obriga a sobreescrever os métodos.

 - Status privado: só pode ser chamado esse método na classe.

# Encapsulamento

 - Esconder certos métodos de outras classes usando o status de privados,
 para expor outro usando status publico, que ultiliza os privados.

 - O que define o encapsulamento são os Modificador de acesso(status), quando é privado é porque está encapsulado.

  - Public: Não é restrito.
  - Protect: Só pode ser ultilizado quem herda ele.
  - Internal: O acesso é limitado apenas pelo assemble, assemble é uma dll, vira dll quando compila um projeto, limitado por projeto.
  - protect Internal:  sao classes limitada por assemble, e classees que deriva(que herda) daquela classe, não sao para classe apenas para metodo.
  - private: o acesso é limitado apenas pela classe, classe privada nao pode ser chamada.
  - private protected: herança ou se estão no mesmo assemble, não sao para classe apenas para metodo.
  
  - classe sealed: não pode ser herdada nem extender, só instancia.
  - classe privada:
  - class internal:
  - classe abstract: nao pode instanciar apenas herdar, meotod deve ser sobreescrito.

- 


