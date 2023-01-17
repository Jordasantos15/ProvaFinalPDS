# Projeto
# Jorda Floripe de Oliveira Santos

## Introdução

Nesta etapa é onde será tomada as maior parte das decisões para que os requisitos do cliente sejam atenditos. Dentro dessa etapa deve ser considerados alguns aspectos como: a linguagem que será usada, o sistema operacional, arquitetura do sistema, o sistema gerenciador de banco de dados que será ultilizado, padrão de interface gráfica e entre outros.

## Definições

. O projeto é uma extensão do modelo de análise visando sua implementação num computador

. Novos objetos aparecem, mas não são do domínio do problema

. O resultado é para o programador ver, não o cliente

. Objetos da análise são (geralmente) mantidos e são embutidos numa infra-estrutura técnica

. As atividades de projeto incluem:

. Fase de refinamento da arquitetura (high-level design)

    . Definição de pacotes (módulos), interfaces entre pacotes

    . Decisão sobre uso/criação de bibliotecas e/ou componentes

. Fase de projeto detalhado (low-level design)

    . Atribuição de responsabilidades entre os objetos

    . Construção de diagramas de classes

        . Pode incluir documentação javadoc (ideal)
  
. Construção de diagramas de interação (opcional)

. Levantamento de necessidades de concorrência

. Considerações de tratamento de falhas

. Detalhamento do formato de saída (interface com usuário, relatórios, transações enviadas para outros sistemas, ...)

. Definição do esquema do BD

. Mapeamento de objetos para tabelas se o BD for relacional

# Caso de Uso

Antes de falar sobre exemplos de arquitetura de software e como cada uma funciona, precisamos entender o que é um padrão na arquitetura de software, um padrão arquitetural é uma solução já estudada, testada e documentada de um problema recorrente. O modelo ajuda na tomada de decisões do projeto de software, como qual será sua utilidade e as funções e relacionamento de cada subsistema. É ele que define a estrutura fundamental do programa.

Os modelos arquiteturais foram descritos pela primeira vez por Christopher Alexander, no final da década de 1970. Em dois livros, o autor descreve um método de documentação de padrões, que, apesar de ter sido pensado para a arquitetura, foi adaptado para a área de software e se popularizou na década de 1990. Desde então, os padrões se tornaram indispensáveis no trabalho de arquitetos de software.

Os principais tipos de arquitetura de software são:

Layers (camadas)
Os módulos e componentes do software são organizados em camadas de funcionalidades, que podem ser desconstruídas em diferentes serviços. Este padrão é mais usado em programas de e-commerce.

Client-server (cliente-servidor)
Neste modelo arquitetural, o processamento da informação se divide em módulos e processos distintos. Um deles é responsável pela manutenção da informação e o outro pela obtenção de dados. Este tipo de arquitetura de software é bastante usado em aplicativos de bancos e e-mail.

Model-view-controller (MVC)
O padrão MVC separa o projeto do software em três camadas independentes: o modelo (manipulação da lógica de dados), a visão (a interface do usuário) e o controlador (fluxo de aplicação). Esta separação facilita a manutenção do código, que pode ser reutilizado em outros projetos.

Microservices (microsserviços)
O padrão se baseia em múltiplos serviços e componentes para desenvolver uma estrutura modular. É o modelo preferido dos desenvolvedores e arquitetos de software, por permitir escalabilidade e independência dos módulos, que podem usar diferentes linguagens.

Pipes-and-filters (PF)
Baseada em uma arquitetura linear, o padrão Pipe-and-filter usa os componentes computacionais como filtros, que recebem uma entrada, transformam-na a partir de um ou mais algoritmos e geram uma saída para um canal de comunicação. Alguns exemplos deste tipo de arquitetura de software são o Sheel do Linux e os reprodutores de vídeo em diferentes formatos.

Peer-to-Peer (P2P)
Se você já baixou algum arquivo via torrent, se deparou com este padrão arquiteturall. No Peer-to-Peer, todos os pares são clientes e servidores, ou seja, cada computador é um provedor de serviços independente de um servidor central.

Service-Oriented Architecture (SOA)
O SOA facilita a operação das grandes empresas, pois auxilia na criação do processo de encontrar, definir e gerenciar os serviços disponibilizados. O NuBank e a Amazon são exemplos de corporações que utilizam este modelo arquitetural.

Publish-Subscribe (Pub/Sub)
Principal padrão arquitetural de redes sociais como Instagram e do Spotify, o modelo Publish-Subscribe conecta publicadores (publishers) e assinantes (subscribers). Os publishers enviam mensagens aos subscribers, que são notificados sempre que um novo conteúdo é disponibilizado.


# Conclusão

Seguindo tais etapas, um projeto de desenvolvimento de software certamente terá melhor qualidade, tanto durante o desenvolvimento quanto no produto final. Também será um trabalho mais saudável (mentalmente, fisicamente e financeiramente) para todas as partes: clientes, equipe comercial e a equipe de desenvolvedores.

Um ponto importante a se ressaltar é que não necessariamente o processo listado nesse texto é sólida e linear. Dependendo do projeto, pode haver diferenças das etapas, adicionando ou removendo totalmente elas ou parte delas, além de poder mudar a ordem.

# Referência

https://www.ivoryit.com.br/2022/05/06/processo-de-desenvolvimento-de-software-veja-o-passo-a-passo/ file:///C:/Users/Jorda%20Floripe/Downloads/Aula%2007%20-%20Projeto.pdf https://docente.ifrn.edu.br/nickersonferreira/disciplinas/projeto-de-desenvolvimento-de-software https://felipelirarocha.wordpress.com/2012/04/15/diversos-modelos-de-desenvolvimento-de-software-resumo/ https://www.macoratti.net/17/09/net_slcd1.htm