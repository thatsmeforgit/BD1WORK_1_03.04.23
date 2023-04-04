# MODELO DE NEGÓCIO - ALUGUEL DE ESPAÇOS COWORKING

### O que é Coworking?
> **Coworking** é uma estação de trabalho de acordo com suas necessidades e recebe também ***serviços*** e ***facilidades*** como *recepção*, *internet*, *estrutura física*, como *auditório*, *sala de reuniões* e *estacionamento*. Tudo depende do que você precisa, há ***planos no mercado*** por ***hora***, por ***mês*** e até, ***anuais***.

### *Serviços Oferecidos pelo Coworking*
> * **Salas Privativas**
> Você vai encontrar vários que oferecem salas privativas. Elas podem ser úteis caso você necessite de um ambiente reservado para atender seus clientes ou para pequenas empresas, que precisem de espaço para abrigar de três a cinco funcionários.
> * **Estacionamento**
> Com sorte, você pode encontrar um *coworking* bem perto da sua casa. Mas se não for o caso, há vários que oferecem estacionamento próprio, que pode ser útil para a visita do seu cliente, também.
> * **Internet**
> É quase chover no molhado, dizer que você precisa verificar se a Internet oferecida é de qualidade. A maior parte dos *coworkings* têm esse cuidado, mas se você trabalha com arquivos pesados, como vídeos, por exemplo, não custa checar.
> * **Escritório Virtual**
> A maior parte dos *coworkings* oferece o serviço de escritório virtual. Com ele, você vai ter o gerenciamento de ligações, correspondência e recados, endereço físico e fiscal.
> * **Estações Compartilhadas**
> Especialmente se a sua empresa é apenas você, a grande mesa compartilhada será uma grande experiência para interação com os demais profissionais do escritório.
> * **Recepção**
> Nada como ser recebido com um sorriso. Sem precisar contratar ninguém, no coworking você e seus clientes serão bem recebidos. Na recepção, também, serão gerenciadas suas correspondências e ligações.
> * **Estrutura Física**
> Com tantas ofertas no mercado, procure um *coworking* cuja estrutura física combine com o jeito da sua empresa. Verifique se o ambiente é acolhedor, confortável e se é organizado como você gostaria para lhe atender e aos seus clientes.
> * **Salas de Reunião**
> As reuniões presenciais ou virtuais são uma realidade em todo o tipo de atividade. Para isso, verifique se há um espaço reservado, com mesas, cadeiras e monitor para projeção de apresentações. Você e seus clientes ficarão muito mais à vontade se houver esse cuidado com o resguardo de informações e que favoreçam o clima de confiança.
> * **Auditório**
> Este é um espaço muito bacana para a promoção de palestras, workshops de aperfeiçoamento e formação, tanto dos usuários do *coworking*, como para sua equipe ou convidados. Você pode compartilhar formações com seus colegas de escritório e oferecê-las aos seus colaboradores – tudo sem sair do mesmo ambiente! Muitos auditórios de *coworkings* também podem ser alugados para empresas de fora.
> * **Espaço de Convivência**
> Muitas vezes, as melhores ideias surgem de uma conversa descompromissada entre um cafezinho e outro. As áreas de convivência são espaços comuns, compartilhados por todos os usuários do *coworking*. É um local para ficar à vontade, bater um papo e, até, fazer um happy-hour com os colegas na sexta-feira.
> * **Impressora**
> É bom que o coworking ofereça boas impressoras para serem compartilhadas.

## MODELAGEM DE BANCO DE DADOS PARA COWORKING 
**Proposta de modelagem** 
> Crie um modelo para um ***Coworking*** que guarde todos os dados de seus clientes/usuários aonde eles devem passar por um cadastro de Pessoa Física ou CNPJ se for empresa, resultando assim e duas entidades, **cadastro_PessoaFisica** e **cadastro_CNPJ****. Será preciso também que o seu modelo armazene dados de todos os ambientes com uma entidade **ambientePrivado**, como salas de desenvolvimento de trabalho baseada em modelos de negócios que vão possuir uma entidade Contrato que se relaciona com a entidade de faturamento referente ao pagemento desses ambientes que vão ser alugados e **ambienteCompartilhado** como Salas de Reunião, cada ambiente deve possuir seu próprio **identificador** e também deve ser informado a **disponibilidade** do ambiente, pois só poderá utilizar dos ambientes, com ***horários marcados*** (ambientes compartilhados). Para ambientes que possuem dispositivos deve ser criada uma entidade relacionada a serviço denominada **ServicoDispositivos** como impressoras, deve ser pensado em guardar os dados desses dispositivos ofertados como serviço, por exemplo cada impressora deve possuir também seu **identificador** pois elas serão relacionadas a cada ambiente da empresa além de que os ambientes privativos alugados pelos clientes podem assumir uma determinada função ou **modelo de negócio** que utilizam ou ***disponibilizam diferentes tipos de dispositivos*** desta forma deve ser pensado em uma entidade **ModeloNegocio** lembrando de fazer o relacionamento pensando na cardinalidade e também no sentido de cada relacionamento entre as entidades. *Use a criatividade para a criação de entidades e suas características de acordo com a proposta do modelo.*

> Written with [StackEdit](https://stackedit.io/).
