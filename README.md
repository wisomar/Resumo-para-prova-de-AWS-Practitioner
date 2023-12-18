# Resumo para prova de AWS Practitioner

# Sumário
- [Introdução](#Introdução) <br>
- [O que é computação em nuvem?](#O-que-é-computação-em-nuvem?) <br>
    - [Seis vantagens da computação em nuvem](#Seis-vantagens-da-computação-em-nuvem)<br>
    - [Tipos de computação em nuvem](#Tipos-de-computação-em-nuvem) <br>
      -  [Infraestrutura como serviço (IaaS)](#Infraestrutura-como-serviço-(IaaS)) <br>
      -  [Plataforma como serviço (PaaS)](#Plataforma-como-serviço-(PaaS)) <br>
      -  [Software como serviço (SaaS)](#Software-como-serviço-(SaaS)) <br>
    -  [Modelos de implantação de computação em nuvem](#Modelos-de-implantação-de-computação-em-nuvem) <br>
       - [Nuvem](#Nuvem) <br>
       - [Abordagem híbrida](#Abordagem-híbrida) <br>
       - [Infraestrutura](#Infraestrutura)  <br>
    - [implantação da computação em nuvem](#Modelos-de-implantação-da-computação-em-nuvem)
        - [Troque despesas iniciais por despesas Variáveis](#Troque-despesas-iniciais-por-despesas-Variáveis)
        - [Pare de gastar dinheiro para executar data centers](#Pare-de-gastar-dinheiro-para-executar-data-centers)
        - [Pare de tentar adivinhar a capacidade](#Pare-de-tentar-adivinhar-a-capacidade)
        - [Beneficie-se de grandes economias de escala](#Beneficie-se-de-grandes-economias-de-escala)
        - [Aumentar a velocidade e a agilidade](#Aumentar-a-velocidade-e-a-agilidade)
        - [Ter alcance global em minutos](#Ter-alcance-global-em-minutos)
- [Infraestrutura global](#Infraestrutura-global) <br>
- [Segurança e conformidade](#Segurança-e-conformidade) <br>
    -  [Segurança](#Segurança) <br>
       - [Benefícios da AWS segurança](#Benefícios-da-AWS-segurança)
    - [Conformidade](#Conformidade)
- [Computação](#Computação)
    - [Amazon Elastic Compute Cloud (Amazon EC2)](#Amazon-Elastic-Compute-Cloud (Amazon EC2))
        - [Tipos de instâncias do Amazon EC2](#Tipos-de-instâncias-do-Amazon-EC2)
        - [Instâncias de uso geral](#Instacias-de-uso-geral)
        - [Instâncias otimizadas para computação](#Instâncias-otimizadas-para-computação)
        - [Instâncias otimizadas para memória](#Instâncias-otimizadas-para-memória)
        - [Instâncias de computação acelerada](#Instâncias-de-computação-acelerada)
        - [Instâncias otimizadas para armazenamento](#Instâncias-otimizadas-para-armazenamento)
    - [Definição de preços do Amazon EC2](#Definição-de-preços-do-Amazon-EC2)
        - [Sob demanda](#Sob-demanda)
        - [Instâncias reservadas](#Instâncias-reservadas)
        - [Savings Plans da instâncias do EC2](#Savings-Plans-da-instâncias-do-EC2)
        - [Instâncias spot](#Instâncias-spot)
        - [Hosts dedicados](#Hosts-dedicados)



 

# Introdução

Em 2006, a Amazon Web Services (AWS) começou a oferecer serviços de infraestrutura de TI para
empresas como serviços web — agora comumente conhecidos como computação em nuvem. Um
dos principais benefícios da computação em nuvem é a oportunidade de substituir as despesas
iniciais de infraestrutura de capital por baixos custos variáveis que se adaptam à sua empresa. Com
a nuvem, as empresas não precisam mais planejar e adquirir servidores e outras infraestruturas de
TI com semanas ou meses de antecedência. Em vez disso, eles podem ativar instantaneamente
centenas ou milhares de servidores em minutos e fornecer resultados mais rapidamente.
Atualmente, AWS fornece uma plataforma de infraestrutura altamente confiável, escalável e de baixo
custo na nuvem que alimenta centenas de milhares de empresas em 190 países ao redor do mundo.

Este vídeo explora como milhões de clientes usam AWS para tirar proveito da eficiência da
computação em nuvem: <a href="www.youtube.com/embed/a9__D53WsUs?si=6rqLthy1FOVwZwIU" target="_blank">O que é? AWS | Amazon Web Services</a>

# <a href="https://aws.amazon.com/pt/getting-started/cloud-essentials/" target="_blank">O que é computação em nuvem?</a>

<p>A computação em nuvem é a entrega sob demanda de poder computacional, banco de dados,
armazenamento, aplicativos e outros recursos de TI por meio de uma plataforma de serviços
em nuvem via Internet com pay-as-you-go preços. Se você estiver executando aplicativos que
compartilham fotos com milhões de usuários móveis ou dando suporte às operações críticas da sua
empresa, uma plataforma de serviços em nuvem fornece acesso rápido a recursos de TI flexíveis
e de baixo custo. Com a computação em nuvem, você não precisa fazer grandes investimentos
iniciais em hardware e gastar muito tempo com o trabalho pesado de gerenciar esse hardware. Em
vez disso, você pode provisionar exatamente o tipo e o tamanho certos de recursos de computação
necessários para impulsionar sua mais nova ideia brilhante ou operar seu departamento de TI. Você
pode acessar quantos recursos precisar, quase instantaneamente, e pagar apenas pelo que usar.</p>

<p>A computação em nuvem fornece uma maneira simples de acessar servidores, armazenamento,
bancos de dados e um amplo conjunto de serviços de aplicativos pela Internet. Uma plataforma de
serviços em nuvem, como a Amazon Web Services, possui e mantém o hardware conectado à rede
necessário para esses serviços de aplicativos, enquanto você provisiona e usa o que precisa por
meio de um aplicativo web.</p>

## Seis vantagens da computação em nuvem

<p>• Troque despesas fixas por despesas variáveis — Em vez de ter que investir pesadamente em data
centers e servidores antes de saber como usá-los, você pode pagar somente quando consumir
recursos de computação e pagar somente pelo quanto consumir.</p>

<p>• Beneficie-se de enormes economias de escala — Ao usar a computação em nuvem, você pode
obter um custo variável menor do que o obtido sozinho. Como o uso de centenas de milhares de
clientes é agregado na nuvem, provedores como esse AWS podem obter maiores economias de
escala, o que se traduz em preços de pagamento as-you-go mais baixos.</p>

<p>• Pare de adivinhar a capacidade — elimine a adivinhação sobre suas necessidades de capacidade
de infraestrutura. Quando você toma uma decisão de capacidade antes de implantar um aplicativo,
geralmente acaba usando recursos ociosos caros ou lidando com capacidade limitada. Com a
computação em nuvem, esses problemas desaparecem. Você pode acessar a capacidade que
precisar e aumentar e reduzir a capacidade conforme necessário com apenas alguns minutos de
antecedência.</p>

<p>• Aumente a velocidade e a agilidade — Em um ambiente de computação em nuvem, os novos
recursos de TI estão a apenas um clique de distância, o que significa que você reduz o tempo de
disponibilização desses recursos para seus desenvolvedores de semanas para apenas alguns
minutos. Isso resulta em um aumento drástico na agilidade da organização, já que o custo e o
tempo necessários para experimentar e desenvolver são significativamente menores.</p>

<p>• Pare de gastar dinheiro administrando e mantendo data centers — concentre-se em projetos que
diferenciam sua empresa, não na infraestrutura. A computação em nuvem permite que você se
concentre em seus próprios clientes, e não no trabalho pesado de empilhar, empilhar e alimentar
servidores.</p>

<p>• Torne-se global em minutos — implante facilmente seu aplicativo em várias regiões ao redor do
mundo com apenas alguns cliques. Isso significa que você pode fornecer menor latência e uma
melhor experiência para seus clientes a um custo mínimo.
</p>

## Tipos de computação em nuvem

<p>A computação em nuvem fornece aos desenvolvedores e departamentos de TI a capacidade
de se concentrar no que é mais importante e evitar trabalhos indiferenciados, como compras,
manutenção e planejamento de capacidade. À medida que a popularidade da computação em
nuvem cresceu, surgiram vários modelos e estratégias de implantação diferentes para ajudar a
atender às necessidades específicas de diferentes usuários. Cada tipo oferece diferentes níveis de
controle, flexibilidade e gerenciamento.</p>

<p>Os três principais tipos de computação em nuvem são infraestrutura como serviço, plataforma como serviço e software como serviço. Cada tipo de computação em nuvem oferece diferentes níveis de controle, flexibilidade e gerenciamento para que você possa selecionar o conjunto certo de serviços para as suas necessidades.</p>

### Infraestrutura como serviço (IaaS)
<p>O IaaS contém os componentes básicos da IT na nuvem. Normalmente, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço de armazenamento de dados. O IaaS oferece o mais alto nível de flexibilidade e controle de gerenciamento sobre os recursos de TI. Ele é o tipo de computação mais semelhante aos recursos existentes de TI, já conhecidos por vários departamentos e desenvolvedores de TI.</p>

### Plataforma como serviço (PaaS)
<p>Com o PaaS, você não precisa mais gerenciar a infraestrutura subjacente (geralmente, hardware e sistemas operacionais) e pode manter o foco na implantação e no gerenciamento de aplicativos. Dessa forma, você fica mais eficiente, pois não precisa se preocupar com aquisição de recursos, planejamento de capacidade, manutenção de software, correções ou qualquer outro tipo de trabalho genérico repetitivo necessário para a execução dos aplicativos.</p>

### Software como serviço (SaaS)
<p>O SaaS oferece um produto completo, executado e gerenciado pelo provedor de serviços. Na maioria dos casos, quando as pessoas mencionam SaaS, estão falando de aplicativos de usuários finais (como e-mail baseado na web). Com uma oferta de SaaS, você não precisa pensar sobre a manutenção do serviço ou o gerenciamento da infraestrutura subjacente. Você só precisa se preocupar sobre como utilizará esse software específico.</p>

## Modelos de implantação de computação em nuvem
### Nuvem
<p>Um aplicativo baseado em nuvem é totalmente implantado na nuvem e todas as partes do aplicativo são executadas na nuvem. Os aplicativos na nuvem foram criados na nuvem ou migrados de uma infraestrutura existente para aproveitar os <a href="https://aws.amazon.com/pt/what-is-cloud-computing/" target="_blank">benefícios da computação em nuvem</a>.</p>

<p>Os aplicativos baseados em nuvem podem ser criados em partes de infraestrutura de baixo nível ou podem usar serviços de nível superior que fornecem abstração dos requisitos de gerenciamento, arquitetura e escalabilidade da infraestrutura principal.</p>

<p> Implantação baseada na nuvem</p>
<ul>
<li>Execute todas as partes da aplicação na nuvem</li>
<li>Migre aplicações para a nuvem</li> 
<li>Proteje e crie novas aplicações na nuvem</li>
</ul>

<p>Em um modelo de implantação baseada na nuvem, você pode migrar aplicações para a nuvem ou projetar e criar novas aplicações na nuvem. Você pode criar essas aplicações em uma infraestrutura de baixo nível que precise do gerenciamento de sua equipe de TI. Você também pode criá-los usando serviços de nível superior que reduzem os requisitos de gerenciamento, arquitetura e scaling da infraestrutura principal.</p>
<p>Por exemplo, uma empresa poderia criar uma aplicação que consiste em servidores virtuais, bancos de dados e componentes de redes totalmente baseados na nuvem.</p>

### Abordagem híbrida
<p>Uma implantação <a href="https://aws.amazon.com/pt/hybrid/" target="_blank">híbrida</a> é uma maneira de conectar infraestrutura e aplicativos entre recursos
na nuvem e recursos existentes que não se encontram na nuvem. O método mais comum de implantação híbrida é entre a nuvem e a infraestrutura local existente para estender e expandir a
infraestrutura de uma organização na nuvem e, ao mesmo tempo, conectar os recursos da nuvem ao sistema interno.</p>

<ul><li>Conecte recursos baseados na nuvem à infraestrutura on-premises.</li>
<li>Integre recursos baseados na nuvem com aplicações de TI legadas.</li></ul>

<p>Em uma implantação híbrida, os recursos baseados na nuvem ficam conectados à infraestrutura on-premises. Você pode adotar essa abordagem em várias situações. Por exemplo, você tem aplicações legadas que são melhor mantidas on-premises ou as regulamentações governamentais exigem que sua empresa mantenha determinados registros on-premises.</p>

<p>Suponha que uma empresa queira usar serviços de nuvem que podem automatizar o processamento e a análise de dados em batch. No entanto, a empresa tem vários aplicativos legados que são mais adequados no local e que não serão migrados para a nuvem. Com uma implantação híbrida, a empresa conseguiria manter os aplicativos legados no local enquanto se beneficiaria dos serviços de dados e análises executados na nuvem.</p>


### Infraestrutura
<p>A implantação de recursos no local, usando ferramentas de virtualização e gerenciamento de recursos, às vezes é chamada de nuvem privada. A implantação local não oferece muitos dos
benefícios da computação em nuvem, mas às vezes é procurada por sua capacidade de fornecer recursos dedicados. Na maioria dos casos, esse modelo de implantação é o mesmo da <a href="https://aws.amazon.com/pt/hybrid/services/#Use_case.3A_Cloud_services_on-premises" target="_blank">infraestrutura</a> de TI legada, ao mesmo tempo em que usa tecnologias de gerenciamento e virtualização de aplicativos para tentar aumentar a utilização de recursos.</p>

<p>Implantação On-Promises </p>
<li>Implante recursos usando ferramentas de virtualização e gerenciamento de recursos.</li>
<li>Aumente a utilização de recursos usando tecnologias de virtualização e gerenciamento de aplicações.</li>

## Beneficios da computação em nuvem

<p>Considere por que uma empresa adota determinada abordagem de computação em nuvem para atender às necessidades de negócios.</p>

### Troque despesas iniciais por despesas Variáveis

<p>Ao adotar uma abordagem de computação em nuvem com o benefício de despesas variáveis, as empresas podem implementar soluções inovadoras enquanto economizam custos.</p>

### Pare de gastar dinheiro para executar data centers

<p>A computação em data centers costuma exigir que você gaste mais dinheiro e tempo gerenciando a infraestrutura e os servidores.</p> 
<p>Um benefício da computação em nuvem é poder se concentrar menos nessas tarefas e mais nas aplicações e clientes.</p>

### Pare de tentar adivinhar a capacidade

<p>Com a computação em nuvem, você não precisa prever a capacidade de infraestrutura necessária antes de implantar uma aplicação.
Por exemplo, você pode iniciar instâncias do Amazon EC2 quando necessário e pagar apenas pelo tempo de computação que usar. Em vez de pagar por recursos não usados ou ter que lidar com capacidade limitada, você pode acessar apenas a capacidade necessária. Você também pode aumentar ou reduzir a capacidade em resposta à demanda.</p>

### Beneficie-se de grandes economias de escala

<p>O uso da computação em nuvem permite obter um custo variável menor ao que você conseguiria por conta própria.</p>
<p>Como o uso de centenas de milhares de clientes pode ser agregado na nuvem, provedores como a AWS podem alcançar enormes economias de escala. A economia de escala se transforma em pagamento conforme o uso com preços mais baixos. </p>

### Aumentar a velocidade e a agilidade
<p>A flexibilidade da computação em nuvem facilita o desenvolvimento e a implantação de aplicações.</p>
<p>Essa flexibilidade permite mais tempo para experimentar e inovar. Ao fazer a computação em data centers, pode levar semanas para obter os novos recursos de que você precisa. Em comparação, a computação em nuvem permite que você acesse novos recursos em poucos minutos.</p>

### Ter alcance global em minutos
<p>A presença global da nuvem AWS permite que você implante aplicações para clientes em todo o mundo rapidamente, ao mesmo tempo que oferece baixa latência. Isso significa que, mesmo se você estiver em uma parte do mundo diferente de seus clientes, eles poderão acessar os seus aplicativos com atrasos mínimos.</p>

# Infraestrutura global
<p>A Nuvem AWS <a href="https://aws.amazon.com/pt/about-aws/global-infrastructure/" target="_blank">infraestrutura</a> é construída em torno Regiões da AWS de zonas de disponibilidade.
A Região da AWS é um local físico no mundo em que temos várias zonas de disponibilidade. As zonas de disponibilidade consistem em um ou mais data centers discretos, cada um com
energia, rede e conectividade redundantes, alojados em instalações separadas. Essas zonas de disponibilidade oferecem a capacidade de operar aplicativos e bancos de dados de produção
que são mais altamente disponíveis, tolerantes a falhas e escaláveis do que seria possível em um único data center</p>

# Segurança e conformidade
## Segurança
<p>A <a href="https://aws.amazon.com/pt/security/" target="_blank">segurança na nuvem</a> AWS é a maior prioridade. À medida que as organizações adotam a escalabilidade e a flexibilidade da nuvem, a AWS as ajuda a transformar segurança, identidade e conformidade em importantes facilitadores de negócios. A AWS incorpora a segurança no núcleo de nossa infraestrutura de nuvem e oferece serviços básicos para ajudar as organizações a atender aos
seus requisitos exclusivos de segurança na nuvem.</p>
<p>Como um cliente da AWS, você se beneficiará de um datacenter e uma arquitetura de rede criados para atender os requisitos da maioria das organizações com exigências de segurança. A segurança na nuvem é muito parecida com a segurança em seus data centers locais, mas sem os custos de manutenção de instalações e hardware. Na nuvem, você não precisa gerenciar servidores físicos ou dispositivos de armazenamento. Em vez disso, você usa ferramentas de segurança baseadas em software para monitorar e proteger o fluxo de informações que entram e saem dos seus recursos de nuvem.</p>
<p>Uma vantagem disso Nuvem AWS é que ele permite que você escale e inove, mantendo um ambiente seguro e pagando somente pelos serviços que você usa. Isso significa que você pode ter a segurança de que precisa a um custo menor do que em um ambiente local.</p>
<p>Como AWS cliente, você herda todas as melhores práticas de AWS políticas, arquitetura e processos operacionais criados para satisfazer os requisitos de nossos clientes mais sensíveis à segurança. Obtenha a flexibilidade e a agilidade de que você precisa nos controles de segurança.</p>
<p>Nuvem AWS permite um modelo de responsabilidade compartilhada. Enquanto AWS gerencia a segurança da nuvem, você é responsável pela segurança na nuvem. <a href="https://www.youtube.com/watch?v=_2HFqANE4gw&ab_channel=AmazonWebServices" target="_blank">Isso significa que você mantém o controle da segurança </a> que escolhe implementar para proteger seu próprio conteúdo, plataforma, aplicativos, sistemas e redes da mesma forma que faria em um data center local.
AWS fornece orientação e experiência por meio de recursos on-line, pessoal e parceiros.</p>
<p>AWS fornece recomendações sobre problemas atuais, além de você ter a oportunidade de trabalhar com eles AWS quando encontrar problemas de segurança.
Você tem acesso a centenas de ferramentas e recursos para ajudá-lo a atingir seus objetivos de segurança. AWS fornece ferramentas e recursos específicos de segurança em segurança de rede, gerenciamento de configuração, controle de acesso e criptografia de dados.</p>
<p>Por fim, os AWS ambientes são auditados continuamente, com certificações de órgãos de credenciamento em todas as regiões e setores. No AWS ambiente, você pode aproveitar as ferramentas automatizadas para inventário de ativos e relatórios de acesso privilegiado.</p>

### Benefícios da AWS segurança
<p>• Mantenha seus dados seguros — A AWS infraestrutura implementa proteções sólidas para ajudar a proteger sua privacidade. Todos os dados são armazenados em AWS data centers altamente seguros.</p>
<p>• Atenda aos requisitos de conformidade — AWS gerencia dezenas de programas de conformidade em sua infraestrutura. Isso significa que segmentos de sua conformidade já foram concluídos.</p>
<p>• Economize dinheiro: — Corte custos usando AWS data centers. Mantenha o mais alto padrão de segurança sem precisar gerenciar suas próprias instalações</p>
<p>• Dimensione rapidamente — a segurança aumenta com seu Nuvem AWS uso. Não importa o tamanho da sua empresa, a AWS infraestrutura foi projetada para manter seus dados seguros.</p>

## Conformidade
<p>A <a href="https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-risk-and-compliance/welcome.html" target="_blank">conformidade com a nuvem da AWS </a>ajuda você a entender os controles robustos em vigor AWS para segurança e proteção de dados na nuvem. A conformidade é uma responsabilidade compartilhada entre o cliente AWS e você pode visitar o <a href="https://aws.amazon.com/pt/compliance/shared-responsibility-model/" target="_blank">Modelo de Responsabilidade Compartilhada</a> para saber mais. Os clientes podem se sentir confiantes em operar e desenvolver com base nos controles de segurança AWS usados em sua infraestrutura.</p>

# Computação

## Amazon Elastic Compute Cloud (Amazon EC2)

<p>O <a href="https://aws.amazon.com/pt/ec2/" target="_blank">Amazon Elastic Compute Cloud (Amazon EC2)</a> fornece capacidade computacional segura e redimensionável na nuvem como instâncias do Amazon EC2.</p>

<p>Imagine que você é responsável pela arquitetura dos recursos de sua empresa e precisa dar suporte a novos sites. Com os recursos on-premises tradicionais, você precisa fazer o seguinte:</p>

<ul>
<li> Gastar dinheiro antecipadamente para comprar o hardware.</li>
<li> Aguardar até que os servidores sejam entregues para você.</li>
<li> Instalar os servidores em seu data center físico.</li>
<li> Fazer todas as configurações necessárias.</li>
</ul>
  
<p>Em comparação, com uma instância do Amazon EC2, você pode usar um servidor virtual para executar aplicações na nuvem AWS.</p>

<ul>
<li>Você pode provisionar e iniciar uma instância do Amazon EC2 em minutos.</li>
<li>Você pode parar de usar a instância quando terminar de executar uma carga de trabalho.</li>
<li>Você paga apenas pelo tempo de computação em que uma instância está em execução, não quando ela é interrompida ou terminada.</li>
<li>Você pode economizar custos pagando apenas pela capacidade do servidor necessária ou desejada.</li>
</ul>

## Tipos de instâncias do Amazon EC2

<a href="https://aws.amazon.com/pt/ec2/instance-types/" target="_blank">Os tipos de instâncias do Amazon EC2</a> são otimizados para tarefas diferentes. Ao selecionar um tipo de instância, considere as necessidades específicas de suas cargas de trabalho e suas aplicações. Isso pode incluir requisitos para recursos de computação, memória ou armazenamento.

### Instancias de uso geral

<p>As instâncias de uso geral equilibram os recursos de computação, memória e rede. Você pode usá-las para diversas cargas de trabalho, como:</p>

<ul>
   <li>servidores de aplicações</li>
   <li>servidores de jogos</li>
   <li>servidores de back-end para aplicações empresariais</li>
   <li>bancos de dados pequenos e médios</li>
</ul>
<p>Suponha que uma aplicação precise de recursos de computação, de memória e de rede no mesmo nível. Você pode executar esse aplicativo em uma instância de uso geral porque ele não precisa de otimização em nenhuma área de recurso único.</p>

### Instâncias otimizadas para computação 
<p>As instâncias otimizadas para computação são ideais para aplicações de computação que usam processadores de alto desempenho. Assim como as instâncias de uso geral, você pode usar as instâncias otimizadas para computação para cargas de trabalho, como servidores da web, de aplicações e de jogos.</p>

<p>No entanto, a diferença é que as aplicações otimizadas para computação são ideais para servidores web de alto desempenho, servidores de aplicações de computação intensiva e servidores de jogos dedicados. Você também pode usar instâncias otimizadas para computação para cargas de trabalho de processamento em lote, com o processamento de muitas transações em um único grupo.</p>

### Instâncias otimizadas para memória
<p>As instâncias otimizadas para memória têm desempenho rápido para cargas de trabalho que processam grandes conjuntos de dados na memória. Na computação, a memória é uma área de armazenamento temporário. Ela contém todos os dados e instruções de que uma unidade central de processamento (CPU) precisa para conseguir realizar ações. Antes que um programa de computador ou aplicativo possa ser executado, ele é carregado do armazenamento para a memória. Esse processo de pré-carregamento dá à CPU acesso direto ao programa de computador.</p>

<p>Suponha que uma carga de trabalho exige o pré-carregamento de muitos dados antes de executar uma aplicação. Esse cenário pode ser de um banco de dados de alto desempenho ou uma carga de trabalho que envolva a execução de processamento em tempo real de uma grande quantidade de dados não estruturados. Nesses tipos de casos de uso, considere usar uma instância otimizada para memória. As instâncias otimizadas para memória permitem que você execute cargas de trabalho com altas necessidades de memória e tenha um ótimo desempenho.</p>

### Instâncias de computação acelerada
<P>As instâncias de computação acelerada usam aceleradoras de hardware, ou coprocessadores, para executar algumas funções de maneira mais eficiente do que é possível em um software executado em CPUs. Exemplos dessas funções são cálculos de números com vírgula flutuante, processamento de gráficos e correspondência de padrões de dados.</P>

<p>Na computação, uma aceleradora de hardware é um componente que agiliza o processamento de dados. As instâncias de computação acelerada são ideais para cargas de trabalho, como aplicativos gráficos e streaming de jogos e de aplicativos.</p>

### Instâncias otimizadas para armazenamento 
<p>As instâncias otimizadas para armazenamento são projetadas para cargas de trabalho que exigem alto acesso sequencial de leitura e gravação a grandes conjuntos de dados no armazenamento local. Exemplos de cargas de trabalho adequadas para as instâncias otimizadas para armazenamento são sistemas de arquivos distribuídos, aplicações de data warehouse e sistemas de processamento de transação on-line (OLTP) de alta frequência.</p>

<p>Na computação, o termo operações de entrada/saída por segundo (IOPS) é uma métrica que mensura o desempenho de um dispositivo de armazenamento. Ela indica quantas operações diferentes de entrada ou saída um dispositivo pode executar em um segundo. As instâncias otimizadas para armazenamento foram projetadas para fornecer dezenas de milhares de IOPS aleatórias e de baixa latência para aplicativos. </p>

<p>Imagine as operações de entrada como dados colocados em um sistema, como registros inseridos em um banco de dados. Uma operação de saída são dados gerados por um servidor. Um exemplo de saída pode ser a análise realizada nos registros em um banco de dados. Se você tiver um aplicativo com alto requisito de IOPS, uma instância otimizada para armazenamento poderá fornecer melhor desempenho em relação a outros tipos de instâncias não otimizados para esse tipo de caso de uso.</p>

#### Teste de conhecimento:

<p>Qual tipo de instância do Amazon EC2 é adequado para aplicações de data warehousing?</p>

<ul>
    <li>Otimizada para memória</li>
    <li>&check;Otimizada para armazenamento</li>
    <li>Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 equilibra os recursos de computação, memória e rede?</p>

<ul>
    <li>Otimizada para memória</li>
    <li>Otimizada para armazenamento</li>
    <li>&check;Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 é ideal para bancos de dados de alto desempenho?</p>

<ul>
    <li>&check;Otimizada para memória</li>
    <li>Otimizada para armazenamento</li>
    <li>Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 oferece processadores de alto desempenho?</p>

 <ul>
     <li>Otimizada para memória</li>
     <li>Otimizada para armazenamento</li>
     <li>Uso geral</li>
     <li>&check;Otimizada para computação</li>
 </ul>   

## Definição de preços do Amazon EC2

<p>Com o Amazon EC2, você paga apenas pelo tempo de computação que usar. O Amazon EC2 oferece diversas opções de preço para diferentes casos de uso. Por exemplo, se o seu caso de uso tolerar interrupções, você poderá economizar com as instâncias spot. Você também pode economizar assumindo um compromisso antecipadamente e bloqueando um nível mínimo de uso com instâncias reservadas.</p>

### Sob demanda

<p>Instâncias sob demanda são ideais para cargas de trabalho irregulares de curto prazo que não podem ser interrompidas. Custos antecipados ou contratos mínimos não se aplicam. As instâncias são executadas continuamente até que sejam interrompidas, e você paga apenas pelo tempo de computação usado.</p>
<p>Exemplos de casos de uso para instâncias sob demanda são desenvolvimento e teste de aplicações e execução de aplicações com padrões de uso imprevisíveis. As instâncias sob demanda não são recomendadas para cargas de trabalho que duram um ano ou mais, porque essas cargas de trabalho podem ser mais econômicas usando instâncias reservadas.</p>

### Instâncias reservadas

<p>As instâncias reservadas são um desconto de cobrança aplicado ao uso de instâncias sob demanda na sua conta. Há dois tipos disponíveis de instância reservada:</p>

<ul>
    <li>Standard Reserved Instances</li>    
    <li>Instâncias reservadas conversíveis</li> 
</ul>

<p>Você pode comprar Standard Reserved Instances e instâncias reservadas conversíveis por um período de vigência de 1 ou 3 anos. Você terá maior economia de custos com a opção de três anos.</p>

<p>Standard Reserved Instances: essa opção será adequada se você souber o tipo e o tamanho da instância do EC2 de que precisa para suas aplicações com estado pronto e em qual Região da AWS planeja executá-las. As instâncias reservadas exigem que você declare as seguintes qualificações:</p>

<ul>
    <li>Tipo e tamanho da instância: Por exemplo, m5.xlarge</li>
    <li>Descrição da plataforma (sistema operacional): Por exemplo, Microsoft Windows Server ou Red Hat Enterprise Linux</li>
    <li>Tenancy: Tenancy-padrão ou dedicado</li>
</ul>

<p>Você tem a opção de especificar uma Zona de Disponibilidade para as instâncias reservadas do EC2. Se você usar essa especificação, vai obter a reserva de capacidade do EC2. Isso garante que a quantidade desejada de instâncias do EC2 estará disponível quando você precisar delas.</p>

<p>Instâncias reservadas conversíveis: se você precisar executar suas instâncias do EC2 em diferentes Zonas de Disponibilidade ou diferentes tipos de instância, as instâncias reservadas conversíveis poderão ser adequadas para você. Observação: você negocia com um desconto maior quando precisa de flexibilidade para executar suas instâncias do EC2.</p>

<p>No final de um período de vigência de instância reservada, você pode continuar usando a instância do Amazon EC2 sem interrupção. No entanto, são cobrados os preços de instâncias sob demanda até que um dos procedimentos a seguir seja feito:</p>

<ul>
    <li>Terminar a instância.</li>
    <li>Adquirir uma nova instância reservada que corresponda aos atributos da instância (tamanho e família de instância, Região, plataforma e tenancy).</li>
</ul>

### Saving Plans da Instância do EC2

<p>A AWS oferece Savings Plans para alguns serviços computacionais, incluindo o Amazon EC2. Os Savings Plans reduzem o custo da instância do EC2 quando você assume um compromisso de gasto por hora com uma família de instância e uma Região por um período de um ou três anos. Esse compromisso com o período de vigência resulta em uma economia de 72% em comparação com as taxas sob demanda. Qualquer uso até o compromisso é cobrado de acordo com o preço de Savings Plans com desconto (por exemplo, USD 10 por hora). Qualquer uso além do compromisso é cobrado de acordo com as taxas normais de instâncias sob demanda.</p>
<p>Os Savings Plans de instância do EC2 serão uma boa opção se você precisar de flexibilidade no uso do Amazon EC2 durante o período de vigência do compromisso. Você tem o benefício de reduzir o custo de execução de qualquer instância do EC2 em uma família na Região escolhida (por exemplo, uso de M5 no Norte da Virgínia), independentemente da Zona de Disponibilidade, tamanho da instância, sistema operacional ou tenancy. A economia com os Savings Plans da instância do EC2 é semelhante à economia das Standard Reserved Instances.</p>
<p>Ao contrário das instâncias reservadas, no entanto, você não precisa especificar antecipadamente qual tipo e tamanho da instância do EC2 (por exemplo, m5.xlarge), sistema operacional e tenancy para receber o desconto. Além disso, você não precisa se comprometer com um determinado número de instâncias do EC2 durante um período de vigência de um ou três anos. Além disso, os Savings Plans da instância do EC2 não incluem uma opção de reserva de capacidade do EC2.</p>
<p>
Posteriormente neste curso, você conhecerá o AWS Cost Explorer, que pode ser usado para visualizar, entender e gerenciar seus custos e uso da AWS ao longo do tempo. Se você está considerando as opções dos Savings Plans, use o AWS Cost Explorer para analisar seu uso do Amazon EC2 nos últimos 7, 30 ou 60 dias. O AWS Cost Explorer também dá recomendações personalizadas para Savings Plans. Essas recomendações calculam o quanto você pode economizar mensalmente com o Amazon EC2, com base no uso anterior do Amazon EC2 e no valor do compromisso por hora em um Savings Plan de um ou três anos.</p>

### Instãcias spot

<p>As instâncias spot são ideais para cargas de trabalho com horários de início e término flexíveis ou que toleram interrupções. As instâncias spot usam a capacidade de computação não utilizada do Amazon EC2 e têm até 90% de desconto em relação aos preços das instâncias sob demanda.</p>

<p>Suponha que você tenha um trabalho de processamento em segundo plano que pode ser iniciado e interrompido conforme for necessário (por exemplo, para uma pesquisa de cliente). Você deseja iniciar e interromper o trabalho de processamento sem afetar as operações gerais de seus negócios. Se você fizer uma solicitação spot e a capacidade do Amazon EC2 estiver disponível, a instância spot será iniciada. No entanto, se você fizer uma solicitação spot e a capacidade do Amazon EC2 estiver indisponível, a solicitação não terá sucesso até que a capacidade seja disponibilizada. A capacidade indisponível pode atrasar o início do trabalho de processamento em segundo plano.</p>

<p>As instâncias spot que você iniciar poderão ser interrompidas se não houver mais capacidade disponível ou se a demanda por essas instâncias aumentar. Isso pode não representar problemas para o trabalho de processamento em segundo plano. No entanto, no exemplo anterior de desenvolvimento e teste de aplicativos, é provável que você queira evitar interrupções inesperadas. Portanto, escolha um tipo de instância do EC2 diferente que seja ideal para essas tarefas.</p>

### Hosts Dedicados

<p>Os hosts dedicados são servidores físicos com capacidade de instância do Amazon EC2 totalmente dedicada ao uso do cliente</p>
<p>Você pode usar suas licenças de software por soquete, por núcleo ou por VM para manter a conformidade da licença. Você pode adquirir hosts dedicados sob demanda e reservas de hosts dedicados. De todas as opções do Amazon EC2 que foram abordadas, os hosts dedicados são os mais caros.</p>

###Teste de conhecimento

<p>Qual opção de preço do Amazon EC2 oferece um desconto quando você especifica um número de instâncias do EC2 para executar um sistema operacional, família e tamanho de instância e tenancy específicos em uma Região?</p>

<ul>
    <li>Instâncias reservadas conversíveis</li>
    <li>Savings Plans da instância do EC2</li>
    <li>Instâncias spot</li>
    <li>&check;Standard Reserved Instances</li>
</ul>

<p>Qual opção de preço do Amazon EC2 oferece um desconto quando você assume um compromisso de gasto por hora com uma família de instância e uma Região por um período de vigência de um ou três anos?</p>
<ul>
    <li>Sob demanda</li>
    <li>&check;Savings Plans da instância do EC2</li>
    <li>Instâncias spot</li>
    <li>Instâncias reservadas</li>
</ul>


