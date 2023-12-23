# Resumo para prova de AWS Practitioner

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
computação em nuvem: <a href="www.youtube.com/embed/a9__D53WsUs?si=6rqLthy1FOVwZwIU">O que é? AWS | Amazon Web Services</a>

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

## <a href="https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">Seis vantagens da computação em nuvem</a>

<p>• <strong><a href="https://www.youtube.com/watch?v=Xsej_qwTD1k&ab_channel=GuilhermeTeles">Troque despesas fixas por despesas variáveis</a></strong> — Em vez de ter que investir pesadamente em data
centers e servidores antes de saber como usá-los, você pode pagar somente quando consumir
recursos de computação e pagar somente pelo quanto consumir.</p>

<p>• <strong>Beneficie-se de enormes economias de escala </strong> — Ao usar a computação em nuvem, você pode
obter um custo variável menor do que o obtido sozinho. Como o uso de centenas de milhares de
clientes é agregado na nuvem, provedores como esse AWS podem obter maiores economias de
escala, o que se traduz em preços de pagamento as-you-go mais baixos.</p>

<p>• <strong>Pare de adivinhar a capacidade</strong> — elimine a adivinhação sobre suas necessidades de capacidade
de infraestrutura. Quando você toma uma decisão de capacidade antes de implantar um aplicativo,
geralmente acaba usando recursos ociosos caros ou lidando com capacidade limitada. Com a
computação em nuvem, esses problemas desaparecem. Você pode acessar a capacidade que
precisar e aumentar e reduzir a capacidade conforme necessário com apenas alguns minutos de
antecedência.</p>

<p>• <strong>Aumente a velocidade e a agilidade</strong> — Em um ambiente de computação em nuvem, os novos
recursos de TI estão a apenas um clique de distância, o que significa que você reduz o tempo de
disponibilização desses recursos para seus desenvolvedores de semanas para apenas alguns
minutos. Isso resulta em um aumento drástico na agilidade da organização, já que o custo e o
tempo necessários para experimentar e desenvolver são significativamente menores.</p>

<p>• <strong>Pare de gastar dinheiro administrando e mantendo data centers</strong> — concentre-se em projetos que
diferenciam sua empresa, não na infraestrutura. A computação em nuvem permite que você se
concentre em seus próprios clientes, e não no trabalho pesado de empilhar, empilhar e alimentar
servidores.</p>

<p>• <strong>Torne-se global em minutos</strong> — implante facilmente seu aplicativo em várias regiões ao redor do
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

<p>Os três principais tipos de computação em nuvem são <a href="https://aws.amazon.com/pt/types-of-cloud-computing/" target="_blank">infraestrutura como serviço, plataforma como serviço e software como serviço.</a> Cada tipo de computação em nuvem oferece diferentes níveis de controle, flexibilidade e gerenciamento para que você possa selecionar o conjunto certo de serviços para as suas necessidades.</p>

### Infraestrutura como serviço (IaaS)
<p>O IaaS contém os componentes básicos da IT na nuvem. Normalmente, o IaaS oferece acesso a recursos de rede, computadores (virtuais ou em hardware dedicado) e espaço de armazenamento de dados. O IaaS oferece o mais alto nível de flexibilidade e controle de gerenciamento sobre os recursos de TI. Ele é o tipo de computação mais semelhante aos recursos existentes de TI, já conhecidos por vários departamentos e desenvolvedores de TI.</p>
<p><strong>Definição:</strong> IaaS fornece aos usuários a infraestrutura básica de computação, como máquinas virtuais, servidores, armazenamento e redes.</p>
<p><strong>Responsabilidades do Usuário:</strong> Os usuários são responsáveis por gerenciar o sistema operacional, aplicativos, dados e middleware. Eles têm controle total sobre a configuração e manutenção do ambiente.</p>

### Plataforma como serviço (PaaS)
<p>Com o PaaS, você não precisa mais gerenciar a infraestrutura subjacente (geralmente, hardware e sistemas operacionais) e pode manter o foco na implantação e no gerenciamento de aplicativos. Dessa forma, você fica mais eficiente, pois não precisa se preocupar com aquisição de recursos, planejamento de capacidade, manutenção de software, correções ou qualquer outro tipo de trabalho genérico repetitivo necessário para a execução dos aplicativos.</p>
<p><strong>Definição:</strong> PaaS oferece uma plataforma de desenvolvimento que inclui ferramentas e serviços para facilitar o desenvolvimento, teste e implementação de aplicativos.</p>
<p><strong>Responsabilidades do Usuário:</strong> Os usuários gerenciam apenas os aplicativos e os dados. A infraestrutura, o sistema operacional e as atualizações de middleware são gerenciados pelo provedor de serviços em nuvem.</p>

### Software como serviço (SaaS)
<p>O SaaS oferece um produto completo, executado e gerenciado pelo provedor de serviços. Na maioria dos casos, quando as pessoas mencionam SaaS, estão falando de aplicativos de usuários finais (como e-mail baseado na web). Com uma oferta de SaaS, você não precisa pensar sobre a manutenção do serviço ou o gerenciamento da infraestrutura subjacente. Você só precisa se preocupar sobre como utilizará esse software específico.</p>
<p><strong>Definição:</strong> SaaS fornece aplicativos prontos para uso acessados através da internet. Os usuários não precisam se preocupar com a infraestrutura subjacente ou a manutenção do software.</p>
<p><strong>Responsabilidades do Usuário:</strong> Os usuários gerenciam apenas seus dados e configurações específicas do aplicativo. Todas as outras preocupações, como atualizações de software e hardware, são tratadas pelo provedor.</p>

### Resumo Comparativo:
<p><strong>IaaS:</strong> Fornece infraestrutura básica, controle total do ambiente, responsabilidades de gerenciamento significativas para o usuário.</p>
<p><strong>PaaS:</strong> Oferece uma plataforma de desenvolvimento, gerenciamento de aplicativos e dados, com menos preocupações em relação à infraestrutura.</p>
<p><strong>SaaS:</strong> Fornece aplicativos prontos para uso, com o usuário responsável principalmente pelos dados e configurações específicas do aplicativo.</p>


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

>[nota]<em>O termo "TI legada" refere-se a sistemas, tecnologias ou aplicações de Tecnologia da Informação (TI) que foram desenvolvidos e implementados em uma organização em um momento anterior. Esses sistemas muitas vezes têm uma arquitetura mais antiga, foram projetados para atender a requisitos específicos da época e podem não ser tão flexíveis, interoperáveis ou fáceis de manter quanto soluções mais modernas.</em>

### Infraestrutura
<p>A implantação de recursos no local, usando ferramentas de virtualização e gerenciamento de recursos, às vezes é chamada de nuvem privada. A implantação local não oferece muitos dos
benefícios da computação em nuvem, mas às vezes é procurada por sua capacidade de fornecer recursos dedicados. Na maioria dos casos, esse modelo de implantação é o mesmo da <a href="https://aws.amazon.com/pt/hybrid/services/#Use_case.3A_Cloud_services_on-premises" target="_blank">infraestrutura</a> de TI legada, ao mesmo tempo em que usa tecnologias de gerenciamento e virtualização de aplicativos para tentar aumentar a utilização de recursos.</p>

<p>Implantação On-Promises </p>

<ul>
<li>Implante recursos usando ferramentas de virtualização e gerenciamento de recursos.</li>
<li>Aumente a utilização de recursos usando tecnologias de virtualização e gerenciamento de aplicações.</li>
</ul>

>[nota] <p><em>"On-premises" refere-se a software, hardware ou infraestrutura que está localizado fisicamente nas instalações da própria organização ou empresa, em oposição a estar hospedado em servidores remotos ou na nuvem. Quando algo é descrito como sendo "on-premises", significa que está localizado e operado dentro das instalações físicas da empresa ou organização.</p>
><p>Por exemplo, um software on-premises seria instalado e executado nos servidores da empresa, em vez de ser acessado e operado remotamente a partir de servidores em nuvem. Da mesma forma, hardware on-premises seria aquele que está fisicamente presente no local da organização, como servidores, roteadores, e outros dispositivos de rede.</p>
><p>A escolha entre soluções on-premises e soluções em nuvem depende das necessidades, recursos e preferências específicos de uma organização. Cada abordagem tem suas próprias vantagens e desvantagens em termos de custo, segurança, manutenção e escalabilidade.</em></p>

### Conceito de flexibilidade e Disponibilidade


  <p>Flexibilidade:<em> flexibilidade pode se referir à capacidade de sistemas, software ou infraestrutura se ajustarem facilmente a mudanças nos requisitos de negócios, escalabilidade, integração com outras tecnologias, entre outros.</em></p>

  <p>Disponibilidade:<em> refere-se à capacidade de um sistema, serviço ou recurso estar acessível e operacional quando necessário, sem interrupções ou falhas.</em></p>
 
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

<p>Com o Amazon EC2, você paga apenas pelo tempo de computação que usar. O <a href="https://aws.amazon.com/pt/ec2/pricing/" target="_blank">Amazon EC2 oferece diversas opções de preço</a> para diferentes casos de uso. Por exemplo, se o seu caso de uso tolerar interrupções, você poderá economizar com as instâncias spot. Você também pode economizar assumindo um compromisso antecipadamente e bloqueando um nível mínimo de uso com instâncias reservadas.</p>

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

### Teste de conhecimento

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

## Dimensionamento

<p>O dimensionamento significa começar apenas com os recursos necessários e projetar a arquitetura para responder automaticamente às alterações de demanda, fazendo aumentos ou reduções de quantidade. Como resultado, você paga apenas pelos recursos que usa. Você não precisa se preocupar com a falta de capacidade de computação para atender às necessidades dos clientes.</p>

## Amazon EC2 Auto Scaling
<p>Se você já tentou acessar um site que não carregava e atingiu o tempo limite algumas vezes, ele pode ter recebido mais solicitações do que conseguia atender. Essa situação é semelhante a esperar em uma longa fila em uma cafeteria quando há apenas um barista disponível para registrar os pedidos dos clientes. <br>
O <a href="https://aws.amazon.com/pt/ec2/autoscaling/" target="_blank">Amazon EC2 Auto Scaling</a> permite que você adicione ou remova automaticamente instâncias do Amazon EC2 em resposta à alteração da demanda da aplicação. Ao fazer auto scaling das instâncias, aumentando ou reduzindo a quantidade conforme a necessidade, você tem maior percepção de disponibilidade de aplicações.</p>
<p>No Amazon EC2 Auto Scaling, há duas abordagens disponíveis: scaling dinâmico e scaling preditivo.</p>

<ul>
    <li>O scaling dinâmico responde às alterações na demanda.</li>
    <li>O scaling preditivo programa automaticamente o número correto de instâncias do Amazon EC2 com base na demanda prevista.</li>
</ul>

> [!NOTA]
> Para dimensionar mais rapidamente, você pode combinar o scaling dinâmico e preditivo.

### Exemplo: Amazon EC2 Auto Scaling
<p>Já que na nuvem a capacidade computacional é um recurso programático, você pode adotar uma abordagem mais flexível para o problema de scaling. Ao adicionar o Amazon EC2 Auto Scaling a uma aplicação, você poderá adicionar novas instâncias à aplicação quando for necessário e terminá-las quando não for mais necessário. <br>
Suponha que você esteja se preparando para iniciar uma aplicação em instâncias do Amazon EC2. Ao configurar o tamanho do seu grupo do Auto Scaling, você pode definir o número mínimo de instâncias do Amazon EC2 como sendo um. Isso significa que, em qualquer momento, precisa haver pelo menos uma instância do Amazon EC2 em execução.</p>

<picture>
    <source media="(min-width: 320px)" srcset="https://explore.skillbuilder.aws/files/a/w/aws_prod1_docebosaas_com/1702911600/ohN5DMbTigjSTqI61m3SGQ/tincan/938093_1698984874_o_1he9k000612o1s7k1td9nt7mebb_zip/assets/wnTEwLoRYpZb_4BJ_RwJfS7GUeUFgRe6x.png">
</picture>

<p>Ao criar um grupo do Auto Scaling, você pode definir o número mínimo de instâncias do Amazon EC2. A capacidade mínima é o número de instâncias do Amazon EC2 que são iniciadas imediatamente após a criação do grupo do Auto Scaling. Neste exemplo, o grupo do Auto Scaling tem uma capacidade mínima de uma instância do Amazon EC2.</p>

<p>Em seguida, você pode definir a capacidade desejada como duas instâncias do Amazon EC2, mesmo que a aplicação precise de um mínimo de uma única instância do Amazon EC2 para que seja executada.</p>

> ![NOTA]
> Se você não especificar o número desejado de instâncias do Amazon EC2 em um grupo do Auto Scaling, a capacidade desejada se tornará a capacidade mínima regular.

<p>A terceira configuração que você pode definir em um grupo do Auto Scaling é a capacidade máxima. Por exemplo, você pode configurar o grupo do Auto Scaling para aumentar a quantidade em resposta à demanda elevada, mas apenas para um máximo de quatro instâncias do Amazon EC2. <br>
Como o Amazon EC2 Auto Scaling usa instâncias do Amazon EC2, você vai pagar apenas pelas instâncias que usar, e somente quando elas forem usadas. Você agora tem uma arquitetura econômica que proporciona a melhor experiência do cliente e ao mesmo tempo reduz custos.</p>

## Direcionamento de tráfego com o Elastic Load Balancing (ELB)

<p>O <a href="https://aws.amazon.com/pt/elasticloadbalancing/" target="_blank">Elastic Load Balancing</a> é o serviço da AWS que distribui automaticamente o tráfego de entrada de aplicações entre vários recursos, como instâncias do Amazon EC2. <br>
Um balanceador de carga atua como um ponto único de contato para todo o tráfego na web de entrada para o grupo do Auto Scaling. Isso significa que, à medida que você adiciona ou remove instâncias do Amazon EC2 em resposta à quantidade de tráfego de entrada, essas solicitações são direcionadas para o balanceador de carga primeiro. Em seguida, as solicitações se espalham por vários recursos que lidarão com elas. Por exemplo, se você tiver várias instâncias do Amazon EC2, o Elastic Load Balancing distribuirá a carga de trabalho entre elas para que nenhuma instância tenha que carregar a maior parte.</p>
<p>Embora o Elastic Load Balancing e o Amazon EC2 Auto Scaling sejam serviços separados, eles trabalham juntos para que as aplicações executadas no Amazon EC2 tenham alto desempenho e disponibilidade.</p>

<picture>
    <source media="(min-width: 320px)" srcset="https://www.google.com/url?sa=i&url=https%3A%2F%2Faws.amazon.com%2Fko%2Fblogs%2Fkorea%2Fcategory%2Felastic-load-balancing%2F&psig=AOvVaw24j4ESUY7GASyerNi_dKd-&ust=1702992868485000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCMDDmoCNmYMDFQAAAAAdAAAAABAI">
</picture>

# Sistema de mensagens e enfileiramento

## Aplicações monolíticas e microsserviços

<p>As aplicações são formadas por vários componentes. Os componentes se comunicam entre si para transmitir dados, atender solicitações e manter o aplicativo em execução <br>
Suponha que você tenha uma aplicação com componentes com acoplamento forte. Esses componentes podem ser bancos de dados, servidores, interface do usuário, lógica de negócios e assim por diante. Esse tipo de arquitetura pode ser considerado uma aplicação monolítica. <br>
Nessa abordagem sobre a arquitetura da aplicação, se um único componente falhar, vai ocorrer falha de outros componentes e possivelmente de toda a aplicação.</p>

>![NOTA] Para manter a disponibilidade da aplicação quando um único componente falha, você pode projetar essa aplicação com uma abordagem de microsserviços.

<p>Em uma abordagem de microsserviços, os componentes da aplicação têm um acoplamento fraco. Neste caso, se um único componente falhar, os outros componentes continuarão funcionando porque estarão em comunicação uns com os outros. O acoplamento fraco evita a falha completa do aplicativo.</p>
<p>Ao projetar aplicações na AWS, você pode adotar uma abordagem de microsserviços com serviços e componentes que cumprem funções diferentes. Dois serviços facilitam a integração de aplicativos: Amazon Simple Notification Service (Amazon SNS) e Amazon Simple Queue Service (Amazon SQS).</p>

### Amazon Simple Notification Service (Amazon SNS)
<p>O <a href="https://aws.amazon.com/pt/sns/" target="_blank">Amazon Simple Notification Service (Amazon SNS)</a> é um serviço de publicação/assinatura. Usando tópicos do Amazon SNS, um editor publica mensagens para assinantes. Isso é semelhante à cafeteria: o operador de caixa entrega os pedidos ao barista que, por sua vez, prepara as bebidas.<br>
No Amazon SNS, os assinantes podem ser servidores da web, endereços de e-mail, funções do AWS Lambda ou várias outras opções.</p>

>![Resumo]
>Embora esses exemplos da cafeteria envolvam assinantes que são pessoas, no Amazon SNS, os assinantes podem ser servidores da web, endereços de e-mail, funções do AWS Lambda ou várias outras opções.


### Amazon Simple Queue Service (Amazon SQS)
<p>O Amazon Simple Queue Service (Amazon SQS) é um serviço de enfileiramento de mensagens. <br>
Use o Amazon SQS para enviar, armazenar e receber mensagens entre componentes de software, sem perder mensagens nem precisar que outros serviços estejam disponíveis. No Amazon SQS, uma aplicação envia mensagens para uma fila. Um usuário ou serviço recupera uma mensagem da fila, processa-a e a apaga da fila.</p>

>![Resumo]
>Para aplicações e microsserviços desacoplados, o Amazon SQS permite enviar, armazenar e recuperar mensagens entre componentes.
>Essa abordagem desacoplada permite que os componentes separados funcionem de modo mais eficiente e independente.

#### Teste de conhecimento
<p>Qual serviço da AWS é a melhor opção para publicar mensagens para assinantes?</p>
<ul>
    <li>Amazon Simple Queue Service (Amazon SQS)</li>
    <li>Amazon EC2 Auto Scaling</li>
    <li>&check;Amazon Simple Notification Service (Amazon SNS)</li>
    <li>Elastic Load Balancing</li>
</ul>

# Computação sem servidor

<p>No início , você conheceu o Amazon EC2, um serviço que permite executar servidores virtuais na nuvem. Para executar aplicações no Amazon EC2, faça o seguinte:</p>
<ul>
    <li>Provisione as instâncias (servidores virtuais).</li>
    <li>Faça upload do código.</li>
    <li>Continue gerenciando as instâncias enquanto a aplicação está em execução.</li>
</ul>

<p>O termo “sem servidor” significa que o código é executado em servidores, sem que você precise provisionar ou gerenciar esses servidores. Com a computação sem servidor, você pode se concentrar na inovação de novos produtos e recursos em vez de manter servidores.<br>
Outro benefício da computação sem servidor é a flexibilidade de dimensionar aplicações sem servidor automaticamente. A computação sem servidor pode ajustar a capacidade de aplicativos modificando as unidades de consumo, como taxa de transferência e memória.</p>
<p>Um serviço da AWS para computação sem servidor é o AWS Lambda.</p>

## AWS Lambda
<p>O <a href="https://aws.amazon.com/pt/lambda/" target="_blank">AWS Lambda</a> é um serviço que permite a execução de códigos sem a necessidade de provisionar ou gerenciar servidores. </p>

<p>Ao usar o AWS Lambda, você paga apenas pelo tempo de computação consumido. As cobranças se aplicam ao tempo em que o código fica em execução. Você pode executar códigos para praticamente qualquer tipo de aplicativo ou serviço de back-end sem a necessidade de qualquer gerenciamento.</p>

<p>Por exemplo, uma função simples do Lambda é o redimensionamento automático de imagens com o upload feito na nuvem AWS. Nesse caso, a função é acionada ao fazer upload de uma nova imagem.</p>

#### Como o AWS Lambda funciona

<ul>
    <li>Você faz upload do código para o Lambda.</li>
    <li>Você configura o código para ser acionado pelos eventos de uma origem como serviços da AWS, aplicações móveis ou endpoints HTTP.</li>
    <li>O Lambda executa o código somente quando acionado.</li>
    <li>Você paga apenas pelo tempo de computação que usar. No exemplo anterior de redimensionamento de imagens, você pagaria apenas pelo tempo de computação usado ao fazer upload de novas imagens. Fazer upload das imagens aciona o Lambda a executar o código da função de redimensionamento de imagem.</li>
</ul>

# Contêineres

<p>Os contêineres são uma maneira comum de empacotar códigos, configurações e dependências da aplicação em um único objeto. Você também pode usar contêineres para processos e fluxos de trabalho nos quais há requisitos essenciais de segurança, confiabilidade e dimensionamento.</p>

## Amazon Elastic Container Service (Amazon ECS)
<p>O <a href="https://aws.amazon.com/pt/ecs/" target="_blank"> Amazon Elastic Container Service (Amazon ECS)</a> é um sistema de gerenciamento de contêineres altamente dimensionável e de alto desempenho que permite executar e dimensionar aplicações em contêineres na AWS. </p>
<p>O Amazon ECS é compatível com os contêineres do Docker. O <a href="https://www.docker.com/" target="_blank"> Docker</a> é uma plataforma de software que permite criar, testar e implantar aplicações rapidamente. A AWS é compatível com c Docker Community Edition de código aberto e do Docker Enterprise Edition baseado em assinatura. Com o Amazon ECS, você pode usar chamadas de API para iniciar e interromper aplicativos ativados pelo Docker.</p>

## Amazon Elastic Kubernetes Service (Amazon EKS)
<p>O <a href="https://aws.amazon.com/pt/eks/" target="_blank">Amazon Elastic Kubernetes Service (Amazon EKS)</a> é um serviço totalmente gerenciado que você pode usar para executar o Kubernetes na AWS. </p>

<p>O <a href="https://kubernetes.io/" target="_blank">Kubernetes</a> é um software de código aberto que permite implantar e gerenciar aplicações em contêineres em grande escala. Uma grande comunidade de voluntários mantém o Kubernetes, e a AWS trabalha ativamente em conjunto com essa comunidade Kubernetes. Conforme novos recursos e funcionalidades são lançados para aplicativos Kubernetes, você pode facilmente aplicar essas atualizações aos aplicativos gerenciados pelo Amazon EKS.</p>

## AWS Fargate
<p>O <a href="https://aws.amazon.com/pt/fargate/" target="_blank">AWS Fargate</a> é um mecanismo de computação sem servidor para contêineres. Ele funciona com o Amazon ECS e o Amazon EKS. </p>

<p>Com o AWS Fargate, você não precisa provisionar nem gerenciar servidores. O AWS Fargate gerencia sua infraestrutura de servidor para você. Você pode se concentrar em inovar e desenvolver seus aplicativos, pagando apenas pelos recursos necessários para executar os contêineres.</p>

>[nota] Para saber mais sobre outros serviços e soluções, acesse <a href="https://aws.amazon.com/pt/products/compute/">Computação na AWS.</a>


##### Recursos adicionais

<p>Para saber mais sobre os conceitos que foram explorados, consulte estes recursos.</p>
<ul>
    <li><a href="https://aws.amazon.com/pt/products/compute/>Computação na AWS">Computação na AWS </a></li>
    <li><a href="https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/compute-services.html">Serviços computacionais da aws</a></li>
    <li><a href="https://aws.amazon.com/pt/getting-started/decision-guides/serverless-or-kubernetes-on-aws-how-to-choose/">Dipe dive da categoria: sem servidor</a></li>
    <li><a href="https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ec2-reserved-instances.html">Instãncias reservadas do Amazon EC2</a></li>    
    <li><a href="https://docs.aws.amazon.com/pt_br/savingsplans/latest/userguide/sp-applying.html">Como os Savings Plans se aplicam ao uso</a></li>    
</ul>

#### Teste seu conhecimento 

<p>Você deseja usar uma instância do Amazon EC2 para uma carga de trabalho de processamento em lote. Qual seria o melhor tipo de instância do Amazon EC2 a ser usado?</p>

<ul>
    <li>Uso geral</li>
    <li>Otimizada para memória</li>
    <li>&check;Otimizada para computação</li>
    <li>Otimizada para armazenamento</li>
</ul>

<p>Quais são as opções de duração do contrato para instâncias reservadas do Amazon EC2? (Selecione DUAS opções.)</p>

<ul>
    <li>&check;1 ano</li>
    <li>2 anos</li>
    <li>&check;3 anos</li>
    <li>4 anos</li>
    <li>5 anos</li>
</ul>

<p>Você tem uma carga de trabalho que será executada por um total de seis meses e consegue suportar interrupções. Qual seria a opção de compra mais econômica do Amazon EC2?</p>
<ul>
    <li>Instância reservada</li>
    <li>&check;Instância spot</li>
    <li>Instância dedicada</li>
    <li>Instância sob demanda</li>
</ul>

<p>Qual processo é um exemplo do Elastic Load Balancing?</p>

<ul>
    <li>&check;Garantir que nenhuma instância única do Amazon EC2 tenha que suportar a carga de trabalho completa sozinha</li>
    <li>Remover instâncias desnecessárias do Amazon EC2 quando a demanda está baixa</li>
    <li>Adicionar uma segunda instância do Amazon EC2 durante a venda popular de uma loja on-line</li>
    <li>Ajustar automaticamente o número de instâncias do Amazon EC2 para atender à demanda</li>
</ul>

>[nota] O Elastic Load Balancing é o serviço da AWS que distribui automaticamente o tráfego de entrada de aplicações entre vários recursos, como instâncias do Amazon EC2. Isso ajuda a garantir que nenhum recurso único seja usado em excesso.
>As outras respostas são exemplos de Auto Scaling.

<p>Você deseja implantar e gerenciar aplicativos em contêineres. Qual serviço você deve usar?</p>

<ul>
    <li>AWS Lambda</li>
    <li>Amazon Simple Notification Service (Amazon SNS)</li>
    <li>Amazon Simple Queue Service (Amazon SQS)</li>
    <li>&check;Amazon Elastic Kubernetes Service (Amazon EKS)</li>
</ul>

>[nota] O Amazon EKS é um serviço totalmente gerenciado do Kubernetes. O Kubernetes é um software de código aberto que permite implantar e gerenciar aplicações em contêineres em grande escala.
> <li>As outras respostas estão incorretas porque:</li>
> <li>O AWS Lambda é um serviço que permite executar código sem provisionar nem gerenciar servidores.</li>
> <li>O Amazon Simple Queue Service (Amazon SQS) é um serviço que permite enviar, armazenar e receber mensagens entre componentes de software por uma fila.</li>
> <li>O Amazon Simple Notification Service (Amazon SNS) é um serviço de publicação/assinatura. Usando tópicos do Amazon SNS, um editor publica mensagens para assinantes.</li>


# Infrestutura Global e Confiabilidade
## Objetivos de aprendizado

<ul>
    <li>Resumir os benefícios da infraestrutura global da AWS.</li>
    <li>Descrever o conceito básico de Zonas de Disponibilidade.</li>
    <li>Descrever os benefícios do Amazon CloudFront e dos locais de borda.</li>
    <li>Comparar métodos diferentes de provisão de serviços da AWS.</li>
</ul>


## Seleção de uma Região

<p>Ao determinar a Região certa para seus serviços, dados e aplicações, considere os quatro fatores de negócios a seguir.</p>

### Conformidade com governança de dados e requisitos legais

<p>Dependendo da sua empresa e localização, talvez seja necessário executar seus dados em áreas específicas. Por exemplo, se sua empresa exige que todos os dados residam dentro dos limites do Reino Unido, você deve escolher a Região Londres. <br>
Nem todas as empresas têm regulamentações de dados relacionadas a determinados locais, portanto, você pode precisar se concentrar nos outros três fatores.</p>

### Proximidade com os clientes
<p>Ao selecionar uma Região próxima aos clientes, você entrega o conteúdo a eles com mais rapidez. Por exemplo, sua empresa está sediada em Washington, DC, e muitos de seus clientes residem em Singapura. Você pode considerar executar sua infraestrutura na Região Norte da Virgínia por estar perto da sede da empresa e executar os aplicativos a partir da Região Singapura.</p>

### Serviçõs disponiveis em uma região
<p>Às vezes, a Região mais próxima pode não ter todos os recursos que você deseja oferecer aos clientes. A AWS inova frequentemente ao criar novos serviços e expandir recursos em serviços existentes. No entanto, disponibilizar novos serviços em todo o mundo às vezes exige que a AWS desenvolva o hardware físico de cada Região por vez. <br>
Suponha que seus desenvolvedores queiram criar uma aplicação que use o Amazon Braket (plataforma de computação quântica da AWS). Neste curso, o Amazon Braket ainda não está disponível em todas as Regiões AWS em todo o mundo, por isso, os desenvolvedores precisariam executá-lo em uma das Regiões que já o oferece.</p>

### Preços

<p>Suponha que você pretenda executar aplicações nos Estados Unidos e no Brasil. Com a estrutura tributária do Brasil, pode custar 50% mais caro executar a mesma carga de trabalho na Região São Paulo em comparação com a Região Oregon. Você aprenderá com detalhes que vários fatores determinam o preço, mas, por enquanto, saiba que o custo dos serviços pode variar entre as regiões.</p>

## Zonas de disponibilidade
<p>Uma Zona de Disponibilidade é um único data center ou um grupo de data centers em uma Região. As Zonas de Disponibilidade estão localizadas a dezenas de quilômetros de distância umas das outras. A proximidade é suficiente para haver baixa latência (tempo entre o momento em que o conteúdo foi solicitado e recebido) entre as Zonas de Disponibilidade. No entanto, se ocorrer um desastre em uma parte da Região, eles estarão distantes o suficiente para reduzir a chance de várias Zonas de Disponibilidade serem afetadas.</p>

#### Teste de conhecimento

<p>Qual das afirmações a seguir melhor descreve as Zonas de Disponibilidade?</p>

<ul>
    <li>Uma área geográfica que contém recursos da AWS</li>
    <li>&check;Um único data center ou grupo de data centers em uma Região</li>
    <li>Um data center usado por um serviço AWS para executar operações específicas do serviço</li>
    <li>Um serviço que você pode usar para executar a infraestrutura da AWS em seu próprio data center on-premises em uma abordagem híbrida.</li>
</ul>

#### Saiba mais:
<ul>
    <li><a href="https://aws.amazon.com/pt/about-aws/global-infrastructure/">Infraestrutura global da AWS</a></li>
    <li><a href="https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/">Regiões e Zonas de Disponibilidade</a></li>
</ul>

## Locais de borda

<p>Um <a href="https://aws.amazon.com/pt/products/networking/edge-networking/" target="blank">local de borda</a>é um site que o Amazon CloudFront usa para armazenar cópias em cache do conteúdo mais próximo dos clientes para uma entrega mais rápida.</p>

#### Origem
<p>Suponha que os dados da sua empresa estejam armazenados no Brasil e que você tenha clientes que residem na china.Para entregar conteúdo e esses clientes, você não precisa mover todo o conteúdo para uma das regiões chinesas</p>

#### Local de borda

<p>Em vez de exigir que seus clientes obtenham os dados no brasil, você pode armazenar localmente em cache uma cópia em um local de borda próximo dos seus clientes na China</p>

#### Cliente
<p>Quando um cliente na china solicita um de seus arquivos, o Amazon CloudFront recupera o arquivo por meio do cache no local de borda e entrega o arquivo ao cliente.O arquivo é entregue ao cliente mais rapido porque em vez da fonte original no Brasil.</p>

## Maneiras de interagir com os serviços da AWS
#### Console de gerenciamento da AWS 
<p>O <a href="https://aws.amazon.com/pt/console/" target="_blank">console de gerenciamento da AWS</a> é uma interface baseada na web para acessar e gerenciar os serviços da AWS. Você pode acessar rapidamente os serviços usados recentemente e pesquisar outros serviços por nome, palavra-chave ou acrônimo. O console inclui assistentes e fluxos de trabalho automatizados que podem simplificar o processo de conclusão de tarefas. <br> Você também pode usar o AWS Console Mobile Application para executar tarefas como monitoramento de recursos, visualização de alarmes e acesso a informações de cobrança. Várias identidades podem permanecer em sessão no AWS Console Mobile Application ao mesmo tempo.</p>

#### AWS Command Line Interface (AWS CLI)
<p>Para economizar tempo ao fazer solicitações de API, você pode usar o <a href="https://aws.amazon.com/pt/cli/" target="_blank">AWS Command Line Interface (AWS CLI)</a>. O AWS CLI permite que você controle vários serviços AWS diretamente a partir da linha de comando em uma ferramenta. O AWS CLI está disponível para usuários no Windows, macOS e Linux. <br> Usando a AWS CLI, você pode automatizar as ações que seus serviços e aplicações executam por meio de scripts. Por exemplo, você pode usar comandos para iniciar uma instância do Amazon EC2, conectar uma instância do Amazon EC2 a um grupo específico do Auto Scaling e muito mais. </p>

#### Kits de Desenvolvimento de Software (SDKs)
<p>Outra opção para acessar e gerenciar serviços da AWS são os <a href="https://aws.amazon.com/pt/developer/tools/" target="_blank">Kits de Desenvolvimento de Software (SDKs)</a>. Os SDKs facilitam o uso dos serviços AWS por uma API projetada para sua linguagem de programação ou plataforma. Os SDKs permitem que você use serviços da AWS com suas aplicações ou crie aplicações totalmente novas que serão executados na AWS. <br> Para ajudar você a começar a usar SDKs, a AWS disponibiliza a documentação e um código de exemplo para cada linguagem de programação compatível. As linguagens de programação compatíveis são C++, Java, .NET e muito mais.</p>

## AWS Elastic Beanstalk
<P>Com o <a href="https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/Welcome.html" target="_blank">AWS Elastic Beanstalk</a>, você envia definições de código e configuração, e o Elastic Beanstalk implanta os recursos necessários para executar as seguintes tarefas:</P>
<ul>
    <li>Ajustar capacidade</li>
    <li>Balancear carga</li>
    <li>Auto scaling</li>
    <li>Monitorar o health da aplicação</li>
</ul>

## AWS CloudFormation

<p>Com o <a href="https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/Welcome.html">AWS CloudFormation</a>, você pode considerar sua infraestrutura como código. Isso significa que você pode criar um ambiente escrevendo linhas de código em vez de usar o console de gerenciamento da AWS para provisionar recursos individualmente.</p>
<p>O AWS CloudFormation provisiona os recursos de maneira segura e repetível, permitindo que você crie frequentemente a infraestrutura e as aplicações sem precisar executar ações manuais. Ele determina quais são as operações mais adequadas para gerenciar sua pilha e reverte as alterações automaticamente se detecta erros.</p>

## AWS Outposts
<p>O <a href="https://aws.amazon.com/pt/outposts/" targert="_blank">AWS Outposts</a> é uma família de soluções totalmente gerenciadas que fornecem infraestrutura e serviços da AWS para praticamente qualquer local da borda ou on-premises para uma experiência híbrida verdadeiramente consistente. As soluções do Outposts permitem que os clientes estendam e executem serviços da AWS nativos on-premises e estão disponíveis em uma variedade de formatos, de servidores Outposts 1U e 2U a racks Outposts 42U e várias implantações de rack.</p>
<p>Com o AWS Outposts, você pode executar alguns produtos da AWS localmente e se conectar a uma ampla gama de serviços disponíveis na região local da AWS. Execute aplicações e workloads on-premises usando serviços, ferramentas e APIs familiares da AWS. O Outposts é compatível com workloads e dispositivos que exigem acesso de baixa latência a sistemas on-premises, processamento de dados local, residência de dados e migração de aplicações com interdependências do sistema local. </p>

#### Recursos adicionais

<ul>
    <li><a href="https://aws.amazon.com/pt/about-aws/global-infrastructure/">Infraestrutura global</a></li>
    <li><a href="https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/">Mapa interativo da infraestrutura global da AWS</a></li>    
    <li><a href="Regiões e zonas de disponibilidade">Regiões de Zonas de Disponibilidade</a></li>
    <li><a href="https://aws.amazon.com/pt/developer/tools/">Ferramentas de criação na AWS </a></li>    
</ul>

### Questionario
<p>Qual declaração é VERDADEIRA para a infraestrutura global da AWS?</p>
<ul>
    <li>Uma Região consiste em uma única Zona de Disponibilidade.</li>
    <li>Uma Zona de Disponibilidade consiste em duas ou mais Regiões.</li>
    <li>&check;Uma Região consiste em três ou mais Zonas de Disponibilidade.</li>
    <li>Uma Zona de Disponibilidade consiste em uma única Região.</li>
</ul>

<p>Quais fatores devem ser considerados ao selecionar uma Região? (Selecione DUAS opções.)</p>
<ul>
    <li>&check;Conformidade com governança de dados e requisitos legais</li>
    <li>&check;Proximidade com os clientes</li>
    <li>Acesso a suporte técnico 24 horas por dia</li>
    <li>Capacidade de atribuir permissões personalizadas a diferentes usuários</li>
    <li>Acesso à AWS Command Line Interface (AWS CLI)</li>
</ul>

<p>Qual declaração descreve melhor o Amazon CloudFront?</p>
<ul>
    <li>Um serviço que permite executar a infraestrutura em uma abordagem de nuvem híbrida</li>
    <li>Um mecanismo de computação sem servidor para contêineres</li>
    <li>Um serviço que permite enviar e receber mensagens entre componentes de software por uma fila</li>
    <li>&check;Um serviço global de entrega de conteúdo</li>
</ul>

>[nota] O Amazon CloudFront é um serviço de entrega de conteúdo. Ele usa uma rede de locais de borda para armazenar conteúdo em cache e entregar conteúdo para clientes em todo o mundo. Quando o conteúdo é armazenado em cache, ele é mantido localmente como uma cópia. Esse conteúdo pode ser arquivos de vídeo, fotos, páginas da web e assim por diante.

<p>Qual site o Amazon CloudFront usa para armazenar cópias de conteúdo em cache para entregá-los mais rapidamente aos usuários em qualquer local?</p>
<ul>
    <li>Região</li>
    <li>Zona de Disponibilidade</li>
    <li>Origem</li>
    <li>&check;Local de borda</li>
</ul>

<p>Qual ação você pode executar com o AWS Outposts?</p>
<ul>
    <li>Automatizar ações para serviços e aplicações da AWS por meio de scripts.</li>
    <li>Acessar assistentes e fluxos de trabalho automatizados para executar tarefas nos serviços da AWS.</li>
    <li>Desenvolver aplicações da AWS em linguagens de programação compatíveis.</li>
    <li>&check;Estender a infraestrutura e os serviços da AWS para diferentes locais, incluindo um data center on-premises.</li>
</ul>

# Redes

### Introdução ao Módulo

 <ul>
        <li>Descrever os conceitos básicos de redes.</li>
        <li>Descrever a diferença entre recursos de redes públicas e privadas.</li>
        <li>Explicar como um gateway privado virtual funciona usando um cenário real.</li>
        <li>Explicar como uma rede privada virtual (VPN) funciona usando um cenário real.</li>
        <li>Descrever o benefício do AWS Direct Connect.</li>
        <li>Descrever o benefício das implantações híbridas.</li>
        <li>Descrever as camadas de segurança usadas em uma estratégia de TI.</li>
        <li>Descrever os serviços que os clientes usam para interagir com a rede global da AWS.</li>
</ul>

## Amazon Virtual Private Cloud (Amazon VPC)

<p>magine os milhões de clientes que usam os serviços AWS. Imagine também os milhões de recursos que esses clientes criaram, como as instâncias do Amazon EC2. Sem limites para todos esses recursos, o tráfego de rede fluiria entre eles sem restrições.</p>

<p>Um serviço de rede que você pode usar para definir limites para seus recursos AWS é o <a href="https://aws.amazon.com/pt/vpc/" target="_blank"> Amazon Virtual Private Cloud (Amazon VPC)</a>.</p>

<p>O Amazon VPC permite que você provisione uma seção isolada da nuvem AWS. Nessa seção isolada, você pode executar os recursos em uma rede virtual que definir. Em uma Virtual Private Cloud (VPC), você pode organizar seus recursos em sub-redes. Uma <strong>sub-rede</strong> é uma seção de uma VPC que pode conter recursos como instâncias do Amazon EC2.</p>

## Gateway de internet

<p>Para permitir que o tráfego público da internet acesse sua VPC, é preciso anexar um <strong>gateway de internet</strong> à VPC.</p>

<p>
<figure>
<img width="980" alt="U98VX8q8oGj1lgLY_cQWnrSlZAhp3-TiT" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/8caafb21-104b-43b0-88e6-29ce32967d5d">
<div style="text-align: left;">
<small><em>Ícone do gateway de internet anexado a uma VPC que contém três instâncias do EC2. Uma seta conecta o cliente ao gateway na internet<br><div style="text-align: center;"> indicando que a solicitação do cliente obteve acesso à VPC.</em></small></div>
 </figure></p>


<p>Um gateway da internet é uma conexão entre uma VPC e a internet. Você pode pensar em um gateway da internet como sendo semelhante a uma porta que os clientes usam para entrar na cafeteria. Sem um gateway da internet, ninguém pode acessar os recursos em sua VPC.</p>

<h3>E se você tiver uma VPC apenas com recursos privados?</h3>

## Gateway privado virtual

<p>ara acessar recursos privados em uma VPC, use um gateway privado virtual.</p>
<p>Veja um exemplo de como um gateway privado virtual funciona. Você pode pensar na internet como o caminho entre sua casa e a cafeteria. Suponha que você está viajando com um guarda-costas para proteção. Você ainda usa o mesmo caminho que outros clientes, mas com uma camada extra de proteção.</p>

<p>O guarda-costas é como uma conexão de rede privada virtual (VPN) que criptografa (ou protege) seu tráfego de internet de todas as outras solicitações ao redor.</p>
<p>O gateway privado virtual é o componente que permite que o tráfego protegido da internet ingresse na VPC. Mesmo que sua conexão com a cafeteria tenha proteção extra, os engarrafamentos são possíveis porque você usa o mesmo caminho que outros clientes.</p>

<p><figure>
<img width="980" alt="GVVnz3UVA2zeRO_k_6XoEmx4Atan-vguA" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/c18bcbf9-b47e-4d70-9b82-a36d8e05b1d9">
</figure></p>

<p>Um gateway privado virtual permite estabelecer uma conexão VPN (rede privada virtual) entre a VPC e uma rede privada, como um data center on-premises ou uma rede corporativa interna. Um gateway privado virtual permitirá o tráfego na VPC somente se ele for proveniente de uma rede aprovada.</p>

## AWS Direct Connect

<p>O <a href="https://aws.amazon.com/pt/directconnect/" target="_blank">AWS Direct Connect</a> é um serviço que permite estabelecer uma conexão privada dedicada entre seu data center e uma VPC.</p>

<p>Suponha que haja um prédio com um corredor que o liga diretamente à cafeteria. Somente os moradores do prédio podem passar por esse corredor.</p>

<p>Esse corredor privado estabelece o mesmo tipo de conexão dedicada que o AWS Direct Connect. Os moradores conseguem entrar na cafeteria sem precisar usar a estrada pública compartilhada com outros clientes. </p>

<figure>
<img width="980" alt="dGcj_FD522Xi0IOA_Oe6TnlWoopXumQBZ" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/fdc67ea4-1f8b-44c4-bef1-3cda2e67d796">
<p><small><em>Um data center corporativo roteia tráfego de rede para uma localização do AWS Direct Connect. Em seguida, esse tráfego é roteado para uma VPC por meio de um gateway privado virtual. Todo o tráfego de rede entre o data center corporativo e a VPC passa por essa conexão privada dedicada.</em></small></p>
</figure>

<p>A conexão privada do AWS Direct Connect ajuda a reduzir os custos de rede e a aumentar a quantidade de largura de banda que pode trafegar pela rede.</p>


## Sub-redes e listas de controle de acesso à rede

Para saber mais sobre a função das sub-redes em uma VPC, veja o exemplo da cafeteria a seguir.

Primeiro, os clientes fazem os pedidos ao operador de caixa. O operador de caixa, em seguida, passa os pedidos para o barista. Esse processo permite que a fila prossiga sem problemas à medida que mais clientes entram. 

Suponha que alguns clientes tentem pular a fila do caixa e fazer os pedidos diretamente ao barista. Isso interrompe o fluxo de tráfego e faz com que os clientes acessem uma parte da cafeteria que é restrita a eles.

<img width="980" alt="0Nx_XXGFi6rkyf35_Itp7yAAZE80GMzEV" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/e80a5e6d-e392-44da-b882-83c3351eca4a">

<p>Para corrigir isso, os proprietários da cafeteria dividem a área do balcão colocando o operador de caixa e o barista em estações de trabalho separadas. A estação de trabalho do operador de caixa é voltada para o público e projetada para receber clientes. A área do barista é privada. O barista ainda pode receber pedidos do operador de caixa, mas não diretamente dos clientes.</p>

<img width="980" alt="0Nx_XXGFi6rkyf35_Itp7yAAZE80GMzEV" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/d2e122ff-8749-4fb9-b035-5127c21f8c2b">
<p><em>Um caixa, um barista e três clientes na fila. O ícone do primeiro cliente da fila tem uma seta apontando para o caixa, mostrando que o cliente entrega o pedido ao caixa. Em seguida, o ícone do caixa tem uma seta apontando para o ícone do barista, mostrando que o caixa encaminha o pedido do cliente ao barista. O último cliente da fila tenta fazer o pedido diretamente ao barista, mas é impedido de fazê-lo.</em></p>

<p>Isso é semelhante à forma como você pode usar os serviços de redes da AWS para isolar recursos e determinar exatamente como o tráfego de rede flui.</p>

<p>Na cafeteria, você pode pensar na área do balcão como uma VPC. A área do balcão divide-se em duas áreas separadas para a estação de trabalho do operador de caixa e para a estação de trabalho do barista. Em uma VPC, sub-redes são áreas separadas usadas para agrupar recursos</p>

## sub-redes

<p>Uma sub-rede é uma seção de uma VPC na qual você pode agrupar recursos com base em necessidades operacionais ou de segurança. As sub-redes podem ser públicas ou privadas</p>

<p align="center">
    <img width="300" alt="Hjj3x2_gHkWR2qfn_sChGBbygF3F2Ydkl" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/b1dffb96-e6df-45ad-bc59-0da6240883b5">
</p>


<p>Sub-redes públicas contêm recursos que precisam ser acessíveis ao público, como o site de uma loja on-line.</p>
<p>As sub-redes privadas contêm recursos que devem ser acessíveis apenas pela sua rede privada, como um banco de dados que contém informações pessoais dos clientes e históricos de pedidos.</p>
<p>Em uma VPC, as sub-redes podem se comunicar entre si. Por exemplo, um aplicativo que envolve instâncias do Amazon EC2 em uma sub-rede pública que se comunicam com bancos de dados localizados em uma sub-rede privada.</p>

## Trafego de rede em uma VPC

<p>Quando um cliente solicita dados de um aplicativo hospedado na nuvem AWS, essa solicitação é enviada como um pacote. Um pacote é uma unidade de dados enviada pela internet ou por uma rede.</p>

<p>Ele entra em uma VPC por um gateway de internet. Antes de um pacote poder entrar em uma sub-rede ou sair de uma sub-rede, ele verifica se há permissões. Essas permissões indicam quem enviou o pacote e como ele tenta se comunicar com os recursos em uma sub-rede.</p>

<p>O componente da VPC que verifica as permissões de pacotes das sub-redes é uma <a href="https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-network-acls.html" target="_blank">lista de controle de acesso (ACL)</a> de rede.</p>

## ACLs de rede

<p>Uma ACL de rede é um firewall virtual que controla o tráfego de entrada e saída no nível de sub-rede.</p>

<p>Por exemplo, saia da cafeteria e imagine que você está em um aeroporto. No aeroporto, os viajantes estão tentando entrar em outro país. Você pode pensar nos viajantes como pacotes e no oficial de controle de passaportes como uma ACL de rede. O oficial de controle de passaportes verifica as credenciais dos viajantes quando entram e saem do país. Se um viajante estiver em uma lista aprovada, ele poderá passar. No entanto, se ele não estiver na lista aprovada ou estiver explicitamente em uma lista de viajantes proibidos, ele não poderá entrar.</p>

<p align="center">
  <img width="320" alt="1GNhfNCCHhhKV1AH_2EJFiOIG7TfIZq2Y" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/08247029-dc81-4e16-b3a3-3d464d5da109">
</p>

<p>Cada conta AWS tem uma ACL de rede-padrão. Ao configurar sua VPC, você pode usar a ACL de rede comum da sua conta ou criar ACLs de rede personalizadas.</p>

<p>Por padrão, a ACL-padrão de rede da conta permite todo o tráfego de entrada e saída, mas você pode adicionar suas regras. Para ACLs de rede personalizadas, todo o tráfego de entrada e saída é negado até que você adicione regras para especificar qual tráfego permitir. Além disso, todas as ACLs de rede têm uma regra de negação explícita. Essa regra garante que, se um pacote não corresponder a nenhuma das outras regras na lista, ele será negado.</p>

## Filtragem de pacotes stateless

<p>As ACLs de rede executam a filtragem de pacotes stateless. Elas não se lembram de nada e verificam os pacotes que atravessam a fronteira da sub-rede em todos os sentidos: entrada e saída.</p>
<p>Lembre-se do exemplo anterior de um viajante que quer entrar em outro país. Isso se parece com o envio de uma solicitação de uma instância do Amazon EC2 para a internet.</p>
<p>Quando a resposta de pacote da solicitação volta para a sub-rede, a ACL de rede não se lembra da solicitação anterior. A ACL de rede verifica a resposta do pacote em relação à lista de regras para determinar se permite ou nega.</p>

<p align="center">
 <img width="840" alt="Bbzv_ITcdhxUAI0w_dOvIexppHYQObzwv" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/b1b0cbdf-26ea-40c5-a59d-08b53af9f368">
</p>

<p>Depois que um pacote entra em uma sub-rede, é necessário verificar as permissões dele nos recursos da sub-rede, como as instâncias do Amazon EC2.</p>

<p>O componente de VPC que verifica as permissões de pacote para uma instância do Amazon EC2 é um <a href="https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-security-groups.html">grupo de segurança.</a></p>

## Grupos de Segurança

<p>Um grupo de segurança é um firewall virtual que controla o tráfego de entrada e saída de uma instância do Amazon EC2.</p>

<p align="center">
<img width="300" alt="L0WTTAvTJDOoV89e_6tYbYV-wpC1UbpRk" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/b2597e7a-be43-4ad4-95b7-608ebe925564">
</p>

<p>Por padrão, um grupo de segurança nega todo o tráfego de entrada e permite todo o tráfego de saída. Você pode adicionar regras personalizadas para configurar o tráfego que será permitido</p>

<p>Neste exemplo, suponha que você esteja em um prédio com um porteiro que recebe as visitas no lobby. Você pode pensar nas visitas como pacotes e no porteiro como um grupo de segurança. À medida que as visitas chegam, o porteiro verifica uma lista para garantir que eles podem entrar no edifício. No entanto, o porteiro não verifica a lista novamente quando as visitas saem do edifício</p>

<p>Se você tiver várias instâncias do Amazon EC2 na mesma VPC, poderá associá-las ao mesmo grupo de segurança ou usar grupos de segurança diferentes para cada instância.</p>

## Filtragem de pacotes stateful

<p>Os grupos de segurança fazem a filtragem de pacotes stateful. Eles se lembram de decisões anteriores tomadas para pacotes recebidos.</p>

<p>Considere o mesmo exemplo de envio de uma solicitação de uma instância do Amazon EC2 para a internet. </p>

<p>Quando a resposta de pacote da solicitação retorna para a instância, o grupo de segurança lembra-se da solicitação anterior. O grupo de segurança permite que a resposta prossiga, independentemente das regras do grupo de segurança de entrada.</p>

<p align="center">
<img width="840" alt="state" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/e28e8905-e912-416e-b55e-835f03e39623">
</p>

<p>Com as ACLs de rede e os grupos de segurança, você pode configurar regras personalizadas para o tráfego na sua VPC. Conforme você sabe mais sobre a segurança e a rede da AWS, entenda as diferenças entre ACLs de rede e grupos de segurança.</p>

<p align="center">
  <img width="840" alt="vNa6k_zqfuKfAn2__3urHJnnrLbfcZk4e" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/523c2ab4-672e-4c0e-bde0-0432c5705482">
  <br>
<em><small>Um pacote viaja pela internet de um cliente para o gateway de internet e para a VPC. Em seguida, o pacote passa pela lista de controle de acesso à rede e acessa a sub-rede pública, na qual estão localizadas duas instâncias do EC2.</small></em>
</p>

### Recapitulação de componente da VPC

<ul>
  <li><strong>Sub-rede privada:</strong> Isola bancos de dados contendo informações pessoais dos clientes.</li>
  <li><strong>Gateway privado virtual:</strong> Cria uma conexão VPN entre a VPC e a rede corporativa interna.</li>
  <li><strong>Sub-rede pública:</strong> É compatível com o site voltado para o cliente.</li>
  <li><strong>AWS Direct Connect:</strong> Estabelece uma conexão dedicada entre o data center on-premises e a VPC.</li>
</ul>

### Teste de conhecimento

Qual declaração descreve melhor a lista de controle de acesso de rede-padrão de uma conta AWS?

<ul>
  <li>Ela é stateless e nega todo o tráfego de entrada e saída.</li>
  <li>Ela é stateful e permite todo o tráfego de entrada e saída.</li>
  <li>&check;Ela é stateless e permite todo o tráfego de entrada e saída.</li>
  <li>Ela é stateful e nega todo o tráfego de entrada e saída.</li>
</ul>

A resposta correta é Ela é stateless e permite todo o tráfego de entrada e saída.



As ACLs de rede (listas de controle de acesso de rede) fazem a filtragem de pacotes stateless. Elas não se lembram de nada e verificam os pacotes que atravessam a fronteira da sub-rede nos dois sentidos: entrada e saída.



Cada conta AWS tem uma ACL de rede-padrão. Ao configurar a VPC, você pode usar a ACL de rede-padrão da conta ou criar ACLs de rede personalizadas.



Por padrão, a ACL de rede-padrão da conta permite todo o tráfego de entrada e saída, mas você pode modificá-la adicionando suas regras. Para ACLs de rede personalizadas, todo o tráfego de entrada e saída é negado até que você adicione regras para especificar qual tráfego deve ser permitido. Além disso, todas as ACLs de rede têm uma regra de negação explícita. Essa regra garante que, se um pacote não corresponder a nenhuma das outras regras na lista, ele será negado.


## Redes globais

### Sistema de nomes de domínio (DNS)

Suponha que a AnyCompany tenha um site hospedado na nuvem AWS. Os clientes digitam o endereço da web no navegador e podem acessar o site. Isso acontece devido à resolução do sistema de nomes de domínio (DNS). Na resolução de DNS, o resolvedor DNS do cliente se comunica com um servidor DNS.

Pense no DNS como a lista telefônica da internet. A resolução de DNS é o processo de conversão de um nome de domínio para um endereço IP. 

![Qqrcp-f22LyvBJQy_C9XUGu7bQqfnD46J](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/898313cb-2fa0-42d0-8177-b65da4546a1a)
<small><em>Um cliente se conecta a um resolvedor de DNS procurando um domínio. O resolvedor encaminha a solicitação para o servidor DNS, que retorna o endereço IP para o resolvedor.</em></small>

Por exemplo, suponha que você deseja acessar o site da AnyCompany. 

<ol>
  <li>
    Quando você digita o nome de domínio no navegador, essa solicitação é enviada a um resolvedor de DNS do cliente.
  </li>
  <li>
    O resolvedor de DNS do cliente solicita ao servidor DNS da empresa o endereço IP que corresponde ao site da AnyCompany.
  </li>
  <li>
    O servidor DNS da empresa responde com o endereço IP para o site da AnyCompany, 192.0.2.0.
  </li>
</ol>

### Amazon Route 53

O <a href="https://aws.amazon.com/pt/route53/">Amazon Route 53</a> é um serviço da web de DNS. Oferece aos desenvolvedores e empresas uma maneira confiável de rotear os usuários finais para aplicativos da internet hospedados na AWS. 

O Amazon Route 53 conecta solicitações de usuários à infraestrutura em execução na AWS (como instâncias do Amazon EC2 e balanceadores de carga). Ele pode direcionar os usuários para a infraestrutura fora da AWS.

Outro recurso do Route 53 é a capacidade de gerenciar os registros DNS para nomes de domínio. Você pode registrar novos nomes de domínio diretamente no Route 53. Você também pode transferir registros DNS para nomes de domínio existentes gerenciados por outras empresas de registro de domínio. Isso permite que você gerencie todos os seus nomes de domínio em um único local.

No módulo anterior, você conheceu o Amazon CloudFront, um serviço de entrega de conteúdo. O exemplo a seguir descreve como o Route 53 e o Amazon CloudFront trabalham juntos para entregar conteúdo aos clientes.

### como o Amazon Route 53 e o Amazon CloudFront entregam conteúdo

<img width="840" alt="84fDqozgQugxVdRS_alwFaBM8JjKKCXFD" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/57850c6a-d88f-490a-8fa6-7e5468b550a5">

Suponha que a aplicação da AnyCompany esteja em execução em várias instâncias do Amazon EC2. Essas instâncias estão em um grupo do Auto Scaling que é anexado a um Application Load Balancer. 

<ol>
  <li>
    Um cliente solicita dados da aplicação acessando o site da AnyCompany.
  </li>
  <li>
    O Amazon Route 53 usa a resolução de DNS para identificar o endereço IP correspondente da AnyCompany.com, 192.0.2.0. Essas informações são enviadas de volta para o cliente.
  </li>
  <li>
    A solicitação do cliente é enviada para o local de borda mais próximo por intermédio do Amazon CloudFront.
  </li>
  <li>
    O Amazon CloudFront se conecta ao Application Load Balancer, que envia o pacote de entrada para uma instância do Amazon EC2.
  </li>
</ol>

#### Teste de conhecimento 

Qual declaração melhor descreve a resolução de DNS?

<ol>
  <li>
    Iniciar recursos em uma rede virtual definida por você
  </li>
  <li>
    Armazenar cópias locais de conteúdo em locais de borda em todo o mundo
  </li>
  <li>
    Conectar uma VPC à Internet
  </li>
  <li>
    &check;Converter um nome de domínio em um endereço IP
  </li>
</ol>

A resposta correta é Converter um nome de domínio em um endereço IP.

Por exemplo, para acessar o site da AnyCompany, digite o nome de domínio no seu PC e essa solicitação será enviada para um servidor DNS. Em seguida, o servidor DNS solicita ao servidor web o endereço IP que corresponde ao site da AnyCompany. O servidor da web responde com o endereço IP do site da AnyCompany, 192.0.2.0.


### Recursos adicionais

<ul>
  <li><a href="https://aws.amazon.com/pt/products/networking/" target="_blank">Redes e entrega de conteúdo na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/vpc/" target="_blank">Amazon Virtual Private Cloud</a></li>
  <li><a href="https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/what-is-amazon-vpc.html" target="_blank">O que é o Amazon VPC?</a></li>
  <li><a href="https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/how-it-works.html" target="_blank">Como o Amazon VPC funciona</a></li>
</ul>

#### teste de conhecimento 2

Sua empresa tem um aplicativo que usa instâncias do Amazon EC2 para executar o site voltado para o cliente e instâncias de banco de dados do Amazon RDS para armazenar informações pessoais dos clientes. Como o desenvolvedor deve configurar a VPC de acordo com as práticas recomendadas?

<ul>
  <li>Colocar as instâncias do Amazon EC2 em uma sub-rede privada e as instâncias de bancos de dados do Amazon RDS em uma sub-rede pública.</li>
  <li>&check; Colocar as instâncias do Amazon EC2 em uma sub-rede pública e as instâncias de bancos de dados do Amazon RDS em uma sub-rede privada.</li>
  <li>Colocar as instâncias do Amazon EC2 e as instâncias de bancos de dados do Amazon RDS em uma sub-rede pública.</li>
  <li>Colocar as instâncias do Amazon EC2 e as instâncias de bancos de dados do Amazon RDS em uma sub-rede privada.</li>
</ul>

A resposta correta é Colocar as instâncias do Amazon EC2 em uma sub-rede pública e as instâncias de bancos de dados do Amazon RDS em uma sub-rede privada.



Uma sub-rede é uma seção de uma VPC na qual você pode agrupar recursos com base em necessidades operacionais ou de segurança. As sub-redes podem ser públicas ou privadas.



As sub-redes públicas têm recursos que precisam ser acessíveis pelo público, como o site de uma loja on-line.



As sub-redes privadas têm recursos que devem ser acessíveis apenas pela sua rede privada, como um banco de dados contendo informações pessoais dos clientes e históricos de pedidos.

Qual componente pode ser usado para estabelecer uma conexão privada dedicada entre o data center da sua empresa e a AWS?

<ul>
  <li>Sub-rede privada</li>
  <li>DNS</li>
  <li>&check; AWS Direct Connect</li>
  <li>Gateway privado virtual</li>
</ul>

Qual declaração descreve melhor os grupos de segurança?

<ul>
  <li>&check; Eles são stateful e negam todo o tráfego de entrada por padrão.</li>
  <li>Eles são stateful e permitem todo o tráfego de entrada por padrão.</li>
  <li>Eles são stateless e negam todo o tráfego de entrada por padrão.</li>
  <li>Eles são stateless e permitem todo o tráfego de entrada por padrão.</li>
</ul>

A resposta correta é Grupos de segurança são stateful e negam todo o tráfego de entrada por padrão.



Grupos de segurança são stateful. Isso significa que eles usam padrões e fluxos de tráfego anteriores ao avaliar novas solicitações para uma instância.



Por padrão, os grupos de segurança negam todo o tráfego de entrada, mas você pode adicionar regras personalizadas para atender às suas necessidades operacionais e de segurança.

Qual componente é usado para conectar uma VPC à internet?

<ul>
  <li>Sub-rede pública</li>
  <li>Local de borda</li>
  <li>Grupo de segurança</li>
  <li>&check; Gateway de internet</li>
</ul>

Qual serviço é usado para gerenciar os registros de DNS para nomes de domínio?

<ul>
  <li>Amazon Virtual Private Cloud</li>
  <li>AWS Direct Connect</li>
  <li>Amazon CloudFront</li>
  <li>&check; Amazon Route 53</li>
</ul>
A resposta correta é Amazon Route 53.

# Amazon Route 53

O Amazon Route 53 é um serviço da web de DNS. Ele oferece aos desenvolvedores e empresas uma maneira confiável de direcionar os usuários finais para aplicações da internet hospedados na AWS.



Outro recurso do Route 53 é a capacidade de gerenciar os registros DNS para nomes de domínio. Você pode transferir registros DNS para nomes de domínio existentes gerenciados por outras empresas de registro de domínio. Você também pode registrar novos nomes de domínio diretamente no Route 53.


# Armazenamento e Banco de Dados

Objetivos de aprendizado

<ul>
  <li>Resumir o conceito básico de armazenamento e bancos de dados.</li>
  <li>Descrever os benefícios do Amazon Elastic Block Store (Amazon EBS).</li>
  <li>Descrever os benefícios do Amazon Simple Storage Service (Amazon S3).</li>
  <li>Descrever os benefícios do Amazon Elastic File System (Amazon EFS).</li>
  <li>Resumir várias soluções de armazenamento.</li>
  <li>Descrever os benefícios do Amazon Relational Database Service (Amazon RDS).</li>
  <li>Descrever os benefícios do Amazon DynamoDB.</li>
  <li>Resumir vários serviços de banco de dados.</li>
</ul>

## Armazenamentos de instâncias

Os volumes de armazenamento a nível de bloco se comportam como discos rígidos físicos.

Um <a href="https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/InstanceStorage.html">armazenamento de instância</a> é um meio temporário de armazenamento a nível de bloco para uma instância do Amazon EC2. Um armazenamento de instância é o armazenamento em disco fisicamente anexo ao computador host para uma instância do EC2 e, portanto, tem a mesma vida útil da instância. Quando a instância for terminada, você perderá todos os dados no armazenamento de instância.

Para ver um exemplo de como os armazenamentos de instância funciona, selecione os botões de seta para exibir cada etapa.


<div>
  <img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/663b579b-5cd9-4295-a4c8-eb7e24373ee6" alt="passo1" width="25%" style="float: left; margin-right: 10px;">
  <p>Uma instância do Amazon EC2 com um armazenamento de instância anexo em execução.</p>
</div>


<div>
  <img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/1c697975-19c8-46ef-a78c-e6f3a2624c3e" alt="passo2" width="25%" style="float: left; margin-right: 10px;">
  <p>A instância é interrompida ou encerrada.</p>
</div>

<div>
  <img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/74b37318-b905-4ba2-b045-6babc7534f1b" alt="passo3" width="25%" style="float: left; margin-right: 10px;">
  <p>Todos os dados no armazenamento de instância anexo são apagados.</p>
</div>

#### Resumo


As instâncias do Amazon EC2 são servidores virtuais. Caso você execute uma instância a partir de um estado interrompido, ela poderá ser iniciada em outro host, em que o volume de armazenamento de instância usado anteriormente não existe. Portanto, a AWS recomenda armazenamentos de instâncias para casos de uso que envolvam dados temporários que você não precisa a longo prazo.


## Amazon Elastic Block Store (Amazon EBS) 


O <a href="https://aws.amazon.com/pt/ebs/" target="_blank"> Amazon Elastic Block Store (Amazon EBS)</a> é um serviço que fornece volumes de armazenamento a nível de bloco que você pode usar com instâncias do Amazon EC2. Se você interromper ou terminar uma instância do Amazon EC2, todos os dados no volume do EBS anexo permanecerão disponíveis.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/7000f51e-a1fa-497e-bca2-3e0aa90be8ab" alt="passo3" width="25%" style="float: left; margin-right: 10px;">

Para criar um volume do EBS, defina a configuração (como tamanho e tipo do volume) e a provisão. Depois de criado, o volume do EBS pode ser anexado a uma instância do Amazon EC2.

Como os volumes do EBS são para dados que precisam perdurar, é importante fazer backup dos dados. Você pode fazer backups incrementais de volumes do EBS criando snapshots do Amazon EBS.

### Snapshots do Amazon EBS

<div>
  <img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/0dae5a02-9b82-48c9-8be2-a2a306bc265a">
 <p><small><em>Backups incrementais de volumes do EBS criando snapshots do Amazon EBS. No dia 1, dois volumes são salvos em backup. No dia 2, um novo volume é adicionado e salvo em backup. No dia 3, são adicionados mais dois volumes para um total de cinco volumes. Somente os dois novos volume são salvos em backup.</small></em></p>
</div>

<p>Um <a href="https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/EBSSnapshots.html" target="_blank">snapshot do EBS</a> é um backup incremental. Isso significa que o primeiro backup de um volume copia todos os dados. Nos backups subsequentes, somente os blocos de dados que foram alterados desde o snapshot mais recente são salvos. </p>

Os backups incrementais são diferentes dos backups completos, nos quais todos os dados em um volume de armazenamento são copiados cada vez que ocorre um backup. O backup completo inclui dados que não foram alterados desde o backup mais recente.


Teste de conhecimento

Quais das seguintes opções são características do serviço Amazon EBS? (Selecione DUAS opções.)

<ul>
  <li>&check; Ideal para dados que precisam ser retidos</li>
  <li> Ideal para dados temporários que não são mantidos a longo prazo</li>
  <li>&check; Unidades separadas do computador host de uma instância do EC2</li>
  <li> Conectado fisicamente ao computador host da instância do EC2</li>
  <li> Os dados são apagados quando uma instância do EC2 é encerrada</li>
</ul>


## Amazon Simple Storage Service (Amazon S3)

#### Armazenamento de objetos

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/20f68118-b10e-4490-8f98-df20a2e5b410" alt="objeto" width="100%" style="float: left; margin-right: 10px;">

No armazenamento de objetos, cada objeto consiste em dados, metadados e uma chave.

Os dados podem ser uma imagem, vídeo, documento de texto ou qualquer outro tipo de arquivo. Os metadados contêm informações sobre o que são os dados, como eles são usados, o tamanho do objeto e assim por diante. A chave de um objeto é seu identificador exclusivo.


>Lembre-se de que, quando modificar um arquivo no armazenamento de blocos, somente as partes alteradas são atualizadas. Quando um arquivo no armazenamento de objetos é modificado, todo o objeto é atualizado.


### Amazon Simple Storage Service S3

O <a href="https://aws.amazon.com/pt/s3/" target="_blank">Amazon Simple Storage Service (Amazon S3)</a> é um serviço que fornece armazenamento a nível do objeto. O Amazon S3 armazena dados como objetos em buckets.

É possível fazer upload de qualquer tipo de arquivo para o Amazon S3, como imagens, vídeos, arquivos de texto e assim por diante. Por exemplo, você pode usar o Amazon S3 para armazenar arquivos de backup, arquivos de mídia para um site ou documentos arquivados. O Amazon S3 oferece espaço de armazenamento ilimitado. O tamanho máximo de arquivo para um objeto no Amazon S3 é de 5 TB.

Ao fazer upload de um arquivo para o Amazon S3, é possível definir permissões para controlar a visibilidade e o acesso a ele. Você também pode usar o recurso de versionamento do Amazon S3 para rastrear alterações em seus objetos ao longo do tempo.

### Storage classes do Amazon S3

Com o Amazon S3, você paga somente pelo que usar. Você pode escolher dentre diversas <a href="https://aws.amazon.com/pt/s3/storage-classes/" target="_blank">storage classes</a> aquela que melhor se ajusta às suas necessidades de negócios e de custo. Ao selecionar uma storage class do Amazon S3, considere estes dois fatores:

<ul>
<li>Com que frequência você planeja recuperar seus dados</li>
<li>Seus dados precisam estar muito ou pouco disponíveis</li>
</ul>

Para saber mais sobre as storage classes do Amazon S3, expanda casa uma das oito categorias a seguir.


### S3 Standard

<ul>
<li>Projetado para dados acessados com frequência</li>
<li>Armazena dados em um mínimo de três Zonas de Disponibilidade</li>
</ul>

O Amazon S3 Standard fornece alta disponibilidade para objetos. Isso o torna uma boa escolha para diversos casos de uso, como sites, distribuição de conteúdo e data analytics. O Amazon S3 Standard tem um custo mais alto do que outras storage classes destinadas a dados acessados com pouca frequência e armazenamento de arquivamento.

### S3 Standard – Infrequent Access (S3 Standard-IA)

<ul>
<li>Ideal para dados com pouca frequência de acesso</li>
<li>Semelhante ao Amazon S3 Standard, mas com um preço de armazenamento mais baixo e um preço de recuperação mais alto</li>
</ul>

O Amazon S3 Standard-IA é ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade para quando necessário. O Amazon S3 Standard e o Amazon S3 Standard-IA armazenam dados no mínimo em três Zonas de Disponibilidade. O Amazon S3 Standard-IA tem o mesmo nível de disponibilidade da Amazon S3 Standard, mas com um preço de armazenamento mais baixo e um preço de recuperação mais alto.

### S3 One Zone-Infrequent Access (S3 One Zone – IA)

<ul>
  <li>Armazena dados em uma única Zona de Disponibilidade</li>
  <li>Tem um preço de armazenamento menor do que o Amazon S3 Standard-IA</li>
</ul>

Comparado com o S3 Standard e o S3 Standard-IA, que armazenam dados em um mínimo de três Zonas de Disponibilidade, o S3 One Zone – IA armazena em uma única Zona de Disponibilidade. Isso o torna uma boa storage class nas seguintes condições:

<ul>
  <li>o ideal é economizar custos com armazenamento.</li>
  <li>Você pode reproduzir facilmente seus dados em caso de falha na Zona de Disponibilidade.</li>
</ul>

### S3 Intelligent-Tiering

<ul>
  <li>Ideal para dados com padrões de acesso desconhecidos ou em alteração</li>
  <li>Requer uma pequena taxa mensal de monitoramento e automação por objeto</li>
</ul>

Na storage class S3 Intelligent-Tiering, o Amazon S3 monitora os padrões de acesso dos objetos. Se você não acessou um objeto por 30 dias consecutivos, o Amazon S3 o move automaticamente para o nível de acesso pouco frequente S3 Standard – IA. Se você acessar um objeto no nível de acesso pouco frequente, o Amazon S3 o move automaticamente para o nível de acesso frequente S3 Standard.


### S3 Glacier Instant Retrieval

<ul>
  <li>Funciona bem para dados arquivados que requerem acesso imediato</li>
  <li>Pode recuperar objetos em alguns milissegundos</li>
</ul>

Ao decidir entre as opções de armazenamento de arquivamento, considere a rapidez com que deve recuperar os objetos arquivados. Você pode recuperar objetos armazenados na storage class do S3 Glacier Instant Retrieval em milissegundos, com o mesmo desempenho que o S3 Standard.

### S3 Glacier Flexible Retrieval

<ul>
  <li>Armazenamento de baixo custo projetado para arquivamento de dados</li>
  <li>Capaz de recuperar objetos em poucos minutos a horas</li>
</ul>

O S3 Glacier Flexible Retrieval é uma storage class de baixo custo, ideal para o arquivamento de dados. Por exemplo, você pode usar essa storage class para armazenar registros de clientes arquivados ou arquivos de fotos e vídeos mais antigos. Você pode recuperar seus dados do S3 Glacier Flexible Retrieval de 1 minuto a 12 horas.

### S3 Glacier Deep Archive

<ul>
  <li>Storage class de objetos de menor custo, ideal para arquivamento</li>
  <li>Capaz de recuperar objetos em 12 horas</li>
</ul>

O S3 Deep Archive dá suporte a retenção de longo prazo e preservação digital de dados acessados uma ou duas vezes por ano. Essa storage class é o armazenamento de menor custo na nuvem AWS, com recuperação de dados de 12 a 48 horas. Todos os objetos dessa storage class são replicados e armazenados em pelo menos três Zonas de Disponibilidade geograficamente dispersas.

### S3 Outposts

<ul>
  <li>Cria buckets do S3 no Amazon S3 Outposts</li>
  <li>Torna mais fácil recuperar, armazenar e acessar dados no AWS Outposts</li>
</ul>

O Amazon S3 Outposts oferece armazenamento de objetos para seu ambiente on-premises do AWS Outposts. O Amazon S3 Outposts foi projetado para armazenar dados de maneira durável e redundante em vários dispositivos e servidores em seus Outposts. Por manter os dados próximos às aplicações on-premises, ele funciona bem para cargas de trabalho que exigem um alto desempenho e a permanência dos dados no local.

#### Teste de conhecimento

Você quer armazenar dados que são acessados com pouca frequência, mas devem estar imediatamente disponíveis quando necessário. Qual storage class do Amazon S3 você deve usar?

<ul>
  <li>S3 Intelligent-Tiering</li>
  <li>S3 Glacier Deep Archive</li>
  <li>&check; S3 Standard-IA</li>
  <li>S3 Glacier Flexible Retrieval</li>
</ul>

A resposta correta é S3 Standard-IA.

A storage class S3 Standard-IA é ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade quando necessário. O S3 Standard e o S3 Standard – IA armazenam dados em um mínimo de três Zonas de Disponibilidade. O S3 Standard-IA tem o mesmo nível de disponibilidade que o S3 Standard, mas a um preço de armazenamento mais baixo.

As outras respostas estão incorretas porque:

na storage class S3 Intelligent-Tiering, o Amazon S3 monitora os padrões de acesso dos objetos. Se você não acessou um objeto por 30 dias consecutivos, o Amazon S3 o move automaticamente para o nível de acesso pouco frequente S3 Standard-IA. Se você acessar um objeto no nível de acesso pouco frequente, o S3 vai movê-lo automaticamente para o nível de acesso frequente S3 Standard.


O S3 Glacier Flexible Retrieval e o S3 Glacier Deep Archive são storage classes de baixo custo ideais para arquivamento de dados. Eles não seriam a melhor escolha para esse cenário, pois alta disponibilidade é necessária. É possível recuperar objetos armazenados na storage class S3 Glacier Flexible Retrieval de alguns minutos a algumas horas. Em comparação, é possível recuperar objetos armazenados na storage class S3 Glacier Deep Archive em até 12 horas.


### Amazon Elastic File System (Amazon EFS)

#### Armazenamento de arquivos

No armazenamento de arquivos, vários clientes (como usuários, aplicações, servidores e assim por diante) podem acessar os dados armazenados em pastas de arquivos compartilhadas. Nessa abordagem, um servidor de armazenamento usa armazenamento em bloco com um sistema de arquivos local para organizar os arquivos. Os clientes acessam dados por meio de caminhos de arquivo.

Comparado ao armazenamento em blocos e ao armazenamento de objetos, o armazenamento de arquivos é ideal para casos de uso em que um grande número de serviços e recursos precisam acessar os mesmos dados ao mesmo tempo.

O Amazon <a href="https://aws.amazon.com/pt/efs/">Elastic File System (Amazon EFS)</a> é um sistema de arquivos dimensionável usado com os AWS Cloud Services e recursos on-premises. À medida que você adiciona e remove arquivos, o Amazon EFS expande e retrai automaticamente. Ele pode dimensionar sob demanda para petabytes sem interromper os aplicativos. 

#### Comparação entre o Amazon EBS e o Amazon Elastic File System

Um volume do Amazon EBS armazena dados em uma única Zona de Disponibilidade. 

Para anexar uma instância do Amazon EC2 a um volume do EBS, tanto a instância do Amazon EC2 quanto o volume do EBS precisam residir na mesma Zona de Disponibilidade.

O Amazon Elastic File System é um serviço regional. Ele armazena dados em várias Zonas de Disponibilidade e entre elas. 

O armazenamento duplicado permite que você acesse dados simultaneamente de todas as Zonas de Disponibilidade na Região em que um sistema de arquivos está localizado. Além disso, os servidores on-premises podem acessar o Amazon Elastic File System usando o AWS Direct Connect.


### Amazon Relational Database Service (Amazon RDS)

#### Banco de dados relacionais

Em um banco de dados relacional, os dados são armazenados de modo que se relacionem a outros dados. 

Um exemplo de um banco de dados relacional pode ser o sistema de gerenciamento de inventário da cafeteria. Cada registro no banco de dados incluiria dados para um único item, como nome do produto, tamanho, preço e assim por diante.

Bancos de dados relacionais usam linguagem de consulta estruturada (SQL) para armazenar e consultar dados. Essa abordagem permite que os dados sejam armazenados de forma facilmente compreensível, consistente e dimensionável. Por exemplo, os proprietários da cafeteria podem escrever uma consulta SQL para identificar todos os clientes que compravam com mais frequência um café com leite médio.

Exemplo de dados em um banco de dados relacional:

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/6cc3382e-d4e9-4172-95a5-2def4f92af74" alt="bc" style="width: 75%;">
</div>

### Amazon Relational Database Service

O <a href="https://aws.amazon.com/pt/rds/" target="_blank">Amazon Relational Database Service (Amazon RDS)</a> é um serviço que permite executar bancos de dados relacionais na nuvem AWS.

O Amazon RDS é um serviço gerenciado que automatiza tarefas como provisão de hardware, configuração de banco de dados, patch e backups. Com esses recursos, você pode passar menos tempo concluindo tarefas administrativas e mais tempo usando dados para inovar seus aplicativos. Você pode integrar o Amazon RDS a outros serviços para atender às suas necessidades de negócios e operacionais, como usar o AWS Lambda para consultar seu banco de dados de uma aplicação sem servidor.

O Amazon RDS tem inúmeras opções de segurança diferentes. Muitos mecanismos de banco de dados do Amazon RDS oferecem criptografia em repouso (protegendo os dados enquanto estão armazenados) e criptografia em trânsito (protegendo os dados enquanto estão sendo enviados e recebidos).

#### Mecanismos de banco de dados do Amazon RDS

O Amazon RDS está disponível em seis mecanismos de banco de dados, que otimizam memória, desempenho ou entrada/saída (E/S). Os mecanismos de banco de dados compatíveis são:

<ul>
  <li>Amazon Aurora</li>
  <li>PostgreSQL</li>
  <li>MySQL</li>
  <li>MariaDB</li>
  <li>Oracle Database</li>
  <li>Microsoft SQL Server</li>
</ul>

### Amazon Aurora

O <a href="https://aws.amazon.com/pt/rds/aurora/" target="_blank">Amazon Aurora</a> é um banco de dados relacional de nível empresarial. É compatível com os bancos de dados relacionais MySQL e PostgreSQL. É até cinco vezes mais rápido do que os bancos de dados MySQL comuns e até três vezes mais rápido do que os bancos de dados PostgreSQL comuns.

O Amazon Aurora ajuda a reduzir os custos do banco de dados reduzindo operações desnecessárias de entrada/saída (E/S), garantindo que os recursos do banco de dados permaneçam confiáveis e disponíveis. 

Considere o Amazon Aurora se suas cargas de trabalho exigem alta disponibilidade. Ele replica seis cópias de seus dados em três Zonas de Disponibilidade e faz backup contínuo de seus dados para o Amazon S3.

## Bancos de dados não relacionais

Em um banco de dados não relacional, você cria tabelas. Uma tabela é um lugar em que você pode armazenar e consultar dados.

Bancos de dados não relacionais também são chamados de “bancos de dados NoSQL” porque usam estruturas diferentes de linhas e colunas para organizar dados. Um tipo de abordagem estrutural para bancos de dados não relacionais é o uso de pares de chave-valor. Com pares de chave-valor, os dados são organizados em itens (chaves) e cada item tem um atributo (valores). Pode-se pensar em atributos como sendo diferentes características de seus dados.

Em um banco de dados de chave-valor, você pode adicionar ou remover atributos de itens na tabela a qualquer momento. Além disso, nem todos os itens na tabela precisam ter os mesmos atributos. 

Exemplo de dados em um banco de dados não relacional:

![bc2](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/810fd5b7-baaf-4f20-9913-411c53b6903b)

### Amazon DynamoDB

O <a href="https://aws.amazon.com/pt/dynamodb/" target="_blank">Amazon DynamoDB</a> é um serviço de banco de dados de chave-valor. Ele oferece um desempenho de um dígito de milissegundo em qualquer scaling.

#### sem servidor

O DynamoDB é sem servidor, o que significa que você não precisa provisionar, aplicar patches ou gerenciar servidores. 

Você também não precisa instalar, manter ou operar o software.

#### Auto scaling

À medida que o tamanho do banco de dados expande ou retrai, o DynamoDB é dimensionado automaticamente para se ajustar às alterações na capacidade e, ao mesmo tempo, manter o desempenho consistente. 

Isso o torna uma escolha adequada para casos de uso que exigem alto desempenho durante o scaling.

#### Teste de conhecimento

Quais são os cenários em que você deve usar o Amazon Relational Database Service (Amazon RDS)? (Selecione DUAS opções.)

<ul>
  <li>Ao executar um banco de dados sem servidor</li>
  <li>&check; Ao usar SQL para organizar dados</li>
  <li>Ao armazenar dados em um banco de dados de chave-valor</li>
  <li>Ao dimensionar para 10 trilhões de solicitações por dia</li>
  <li>&check; Ao armazenar dados em um banco de dados do Amazon Aurora</li>
</ul>

As outras três respostas são cenários nos quais você deve usar o Amazon DynamoDB.


### Amazon Redshift

O <a href="https://aws.amazon.com/pt/redshift/" target="_blank">Amazon Redshift</a> é um serviço de data warehouse que você pode usar para análise de Big Data. Ele oferece a capacidade de coletar dados de muitas fontes além de ajudar a entender relações e tendências em todos os seus dados.

### AWS Database Migration Service (AWS DMS)

O <a href="https://aws.amazon.com/pt/dms/" target="_blank">AWS Database Migration Service (AWS DMS)</a> permite migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados.

Com o AWS DMS, você move dados entre bancos de dados de origem e de destino. <a href="https://aws.amazon.com/pt/dms/resources/" target="_blank">Os bancos de dados de origem e de destino</a> podem ser do mesmo tipo ou de tipos diferentes. Durante a migração, o banco de dados de origem permanece operacional, reduzindo o tempo de inatividade em qualquer aplicativo que dependa do banco de dados. 

Por exemplo, suponha que você tenha um banco de dados MySQL armazenado on-premises em uma instância do Amazon EC2 ou no Amazon RDS. Pense no banco de dados MySQL como seu banco de dados de origem. Usando o AWS DMS, você pode migrar seus dados para um banco de dados de destino, por exemplo, um banco de dados do Amazon Aurora.

#### Outros casos de uso do AWS DMS

<strong>Desenvolvimento e teste de migrações de banco de dados</strong><br>
Os desenvolvedores conseguem testar as aplicações com os dados de produção sem afetar os usuários de produção

<strong>Consolidação de banco de dados</strong><br>
Combinação de vários bancos de dados em um único banco de dados

<strong>Replicação contínua</strong><br>
Envio de cópias contínuas dos dados para outras fontes de destino em vez de fazer uma migração única

### Serviços de banco de dados adicionais

#### Amazon DocumentDB

O <a href="https://aws.amazon.com/pt/documentdb/" target="_blank">Amazon DocumentDB</a> é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB. (MongoDB é um programa de banco de dados de documentos.)

#### Amazon Neptune

O <a href="https://aws.amazon.com/pt/neptune/" terget="_blank">Amazon Neptune</a> é um serviço de banco de dados de grafo. 

Você pode usar o Amazon Neptune para criar e executar aplicações que funcionam com conjuntos de dados altamente conectados, como mecanismos de recomendação, detecção de fraude e grafos de conhecimento.

#### Amazon Quantum Ledger Database (Amazon QLDB)

O <a href="https://aws.amazon.com/pt/qldb/" target="_blank">Amazon Quantum Ledger Database (Amazon QLDB)</a> é um serviço de banco de dados ledger. 

Você pode usar o Amazon QLDB para ver um histórico completo de todas as alterações feitas nos dados da aplicação.

#### Amazon Managed Blockchain

O <a href="https://aws.amazon.com/pt/managed-blockchain/" target="_blank">Amazon Managed Blockchain</a> é um serviço para criar e gerenciar redes de blockchain com frameworks de código aberto. 

O Blockchain é um sistema de registro distribuído que permite que várias partes executem transações e compartilhem dados sem uma autoridade central.

#### Amazon ElastiCache

O <a href="https://aws.amazon.com/pt/elasticache/" target="_blank">Amazon ElastiCache</a> é um serviço que adiciona camadas de cache sobre bancos de dados para ajudar a melhorar os tempos de leitura de solicitações comuns. 

Ele é compatível com dois tipos de armazenamentos de dados: Redis e Memcached.

#### Amazon DynamoDB Accelerator

O <a href="https://aws.amazon.com/pt/dynamodb/dax/" target="_blank">Amazon DynamoDB Accelerator (DAX)</a> é um cache em memória do DynamoDB. 

Ele ajuda a melhorar os tempos de resposta de milissegundos para microssegundos.

#### Recursos adicionais

<ul>
  <li><a href="https://aws.amazon.com/pt/storage/">Armazenamento na nuvem na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/storage/">Blog de armazenamento na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/getting-started/hands-on/">Tutoriais práticos: armazenamento</a></li>
  <li><a href="https://aws.amazon.com/pt/solutions/case-studies/storage/">Histórias de clientes da AWS: armazenamento</a></li>
  <li><a href="https://aws.amazon.com/pt/dms/">AWS Database Migration Service</a></li>
  <li><a href="https://aws.amazon.com/pt/products/databases/">Bancos de dados na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/database/">Blog de bancos de dados da AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/solutions/case-studies/databases/">Histórias de clientes da AWS: bancos de dados</a></li>
</ul>

Quais storage classes do Amazon S3 são otimizadas para dados de arquivamento? (Selecione DUAS opções.)

<ul>
  <li>Amazon S3 Standard</li>
  <li>&check; Amazon S3 Glacier Flexible Retrieval</li>
  <li>Amazon S3 Intelligent-Tiering</li>
  <li>Amazon S3 Standard-IA</li>
  <li>&check; Amazon S3 Glacier Deep Archive</li>
</ul>

As duas opções corretas são:

Amazon S3 Glacier Flexible Retrieval
Amazon S3 Glacier Deep Archive
Objetos armazenados na storage class Amazon S3 Glacier Flexible Retrieval podem ser recuperados de poucos minutos a algumas horas. Em comparação, os objetos armazenados na storage class Amazon S3 Glacier Deep Archive podem ser recuperados em 12 horas.

As outras respostas estão incorretas porque:

O Amazon S3 Standard é a storage class ideal para dados acessados com frequência, não dados de arquivamento.
O Amazon S3 Intelligent-Tiering monitora padrões de acesso de objetos e os move automaticamente entre as storage classes Amazon S3 Standard e Amazon S3 Standard-IA. Ele não foi projetado para dados de arquivamento.
O Amazon S3 Standard-IA é ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade para quando necessário.

<a href="https://aws.amazon.com/pt/s3/storage-classes/">Storage classes do Amazon S3/</a>

Qual(ais) afirmação(ões) é(são) VERDADEIRA(S) sobre os volumes do Amazon EBS e sistemas de arquivos do Amazon Elastic File System?

<ul>
  <li>&check; Os volumes do EBS armazenam dados em uma única Zona de Disponibilidade. Os sistemas de arquivos do Amazon EFS armazenam dados em várias Zonas de Disponibilidade.</li>
  <li>Os volumes do EBS armazenam dados em várias Zonas de Disponibilidade. Os sistemas de arquivos do Amazon EFS armazenam dados em uma única Zona de Disponibilidade.</li>
  <li>Os volumes do EBS e os sistemas de arquivos do Amazon EFS armazenam dados em uma única Zona de Disponibilidade.</li>
  <li>Os volumes do EBS e os sistemas de arquivos do Amazon Elastic File System armazenam dados em várias Zonas de Disponibilidade.</li>
</ul>

A resposta correta é: Os volumes do EBS armazenam dados em uma única Zona de Disponibilidade. Os sistemas de arquivos do Amazon Elastic File System armazenam dados em várias Zonas de Disponibilidade.

Um volume do EBS precisa estar localizado na mesma Zona de Disponibilidade que a instância do Amazon EC2 à qual ele está associado.

Os dados em um sistema de arquivos do Amazon Elastic File System podem ser acessados simultaneamente de todas as Zonas de Disponibilidade na Região em que o sistema de arquivos está localizado.

<a href="https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ebs-volumes.html" target="_blank">Volumes do Amazon EBS</a>
<a href="https://docs.aws.amazon.com/pt_br/efs/latest/ug/how-it-works.html" target="_blank">Amazon Elastic File System: como funciona</a>


Você quer armazenar dados em um serviço de armazenamento de objetos. Qual serviço da AWS é o melhor para esse tipo de armazenamento?

<ul>
  <li>Amazon Managed Blockchain</li>
  <li>Amazon Elastic File System (Amazon EFS)</li>
  <li>Amazon Elastic Block Store (Amazon EBS)</li>
  <li>&check; Amazon Simple Storage Service (Amazon S3)</li>
</ul>

A resposta correta é Amazon Simple Storage Service (Amazon S3).

As outras opções estão incorretas porque:

o Amazon Managed Blockchain é um serviço que você pode usar para criar e gerenciar redes de blockchain com frameworks de código aberto. O Blockchain é um sistema de ledger distribuído que permite que várias partes executem transações e compartilhem dados sem uma autoridade central.

O Amazon Elastic File System (Amazon EFS) é um sistema de arquivos dimensionável usado com os AWS Cloud Services e recursos on-premises. Ele não armazena dados como armazenamento de objetos.

O Amazon Elastic Block Store (Amazon EBS) é um serviço que fornece volumes de armazenamento em nível de bloco que você pode usar com instâncias do Amazon EC2.

<a href="https://aws.amazon.com/s3/" target="_blank">Amazon S3</a>

<a href="https://aws.amazon.com/pt/what-is-cloud-object-storage/" target="_blank">O que é armazenamento de objetos na nuvem?</a>

Qual afirmação melhor descreve o Amazon DynamoDB?

<ul>
  <li>Um serviço que permite executar bancos de dados relacionais na nuvem AWS</li>
  <li>&check; Um serviço de banco de dados de chave-valor sem servidor</li>
  <li>Um serviço que você pode usar para migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados</li>
  <li>Banco de dados relacional de nível empresarial</li>
</ul>

A resposta correta é Um serviço de banco de dados de chave-valor sem servidor.

O Amazon DynamoDB é um serviço de banco de dados de chave-valor. Ele é sem servidor, o que significa que você não precisa provisionar, aplicar patches ou gerenciar servidores.

As outras respostas estão incorretas porque:

um serviço que permite executar bancos de dados relacionais na nuvem AWS é a descrição do Amazon Relational Database Service (Amazon RDS).

Um serviço que você pode usar para migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados é a descrição do AWS Database Migration Service (AWS DMS).

Um banco de dados relacional de nível empresarial é a descrição do Amazon Aurora.

<a href="https://aws.amazon.com/pt/dynamodb/" target="_blank">Amazon DynamoDB</a>

Qual serviço é usado para consultar e analisar dados em um data warehouse?

<ul>
  <li>&check; Amazon Redshift</li>
  <li>Amazon Neptune</li>
  <li>Amazon DocumentDB</li>
  <li>Amazon ElastiCache</li>
</ul>

A resposta correta é Amazon Redshift.

O Amazon Redshift é um serviço de data warehouse que você pode usar para análise de Big Data. Use o Amazon Redshift para coletar dados de muitas origens e entender relações e tendências em todos os dados.

As outras respostas estão incorretas porque:

O Amazon Neptune é um serviço de banco de dados de grafo. Você pode usar o Amazon Neptune para criar e executar aplicações que funcionam com conjuntos de dados altamente conectados, como mecanismos de recomendação, detecção de fraude e grafos de conhecimento.

O Amazon DocumentDB é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB.

O Amazon ElastiCache é um serviço que adiciona camadas de cache sobre os bancos de dados para melhorar os tempos de leitura de solicitações comuns.

<a href="https://aws.amazon.com/pt/redshift/" target="_blank">Amazon Redshift</a>

### AWS Database Migration Service (AWS DMS)

O <a href="https://aws.amazon.com/pt/dms/">AWS Database Migration Service (AWS DMS)</a> permite migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados.

Com o AWS DMS, você move dados entre bancos de dados de origem e de destino. Os <a href="https://aws.amazon.com/pt/dms/resources/">bancos de dados de origem e de destino</a>
podem ser do mesmo tipo ou de tipos diferentes. Durante a migração, o banco de dados de origem permanece operacional, reduzindo o tempo de inatividade em qualquer aplicativo que dependa do banco de dados. 

Por exemplo, suponha que você tenha um banco de dados MySQL armazenado on-premises em uma instância do Amazon EC2 ou no Amazon RDS. Pense no banco de dados MySQL como seu banco de dados de origem. Usando o AWS DMS, você pode migrar seus dados para um banco de dados de destino, por exemplo, um banco de dados do Amazon Aurora.

### Outros casos de uso do AWS DMS

#### Desenvolvimento e teste de migrações de banco de dados

Os desenvolvedores conseguem testar as aplicações com os dados de produção sem afetar os usuários de produção

### Consolidação de banco de dados

Combinação de vários bancos de dados em um único banco de dados

### Replicação contínua

Envio de cópias contínuas dos dados para outras fontes de destino em vez de fazer uma migração única

## Serviços de banco de dados adicionais

### Amazon DocumentDB

O <a href="https://aws.amazon.com/pt/documentdb/"> Amazon DocumentDB</a> é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB. (MongoDB é um programa de banco de dados de documentos.)

### Amazon Neptune

O <a href="https://aws.amazon.com/pt/neptune/">Amazon Neptune</a> é um serviço de banco de dados de grafo. 

Você pode usar o Amazon Neptune para criar e executar aplicações que funcionam com conjuntos de dados altamente conectados, como mecanismos de recomendação, detecção de fraude e grafos de conhecimento.

### Amazon Quantum Ledger Database (Amazon QLDB)

O <a href="https://aws.amazon.com/pt/qldb/">Amazon QLDB</a> é um serviço de banco de dados ledger. 

Você pode usar o Amazon QLDB para ver um histórico completo de todas as alterações feitas nos dados da aplicação.

### Amazon Managed Blockchain

O <a href="https://aws.amazon.com/pt/managed-blockchain/">Amazon Managed Blockchain</a> é um serviço para criar e gerenciar redes de blockchain com frameworks de código aberto. 

O Blockchain é um sistema de registro distribuído que permite que várias partes executem transações e compartilhem dados sem uma autoridade central.

### Amazon ElastiCache

O <a href="https://aws.amazon.com/pt/elasticache/">Amazon ElastiCache</a> é um serviço que adiciona camadas de cache sobre bancos de dados para ajudar a melhorar os tempos de leitura de solicitações comuns. 

Ele é compatível com dois tipos de armazenamentos de dados: Redis e Memcached.

### Amazon DynamoDB Accelerator

O <a href="https://aws.amazon.com/pt/dynamodb/dax/">Amazon DynamoDB Accelerator (DAX)</a> é um cache em memória do DynamoDB. 

Ele ajuda a melhorar os tempos de resposta de milissegundos para microssegundos.

#### Recursos adicionais

<ol>
  <li><a href="https://aws.amazon.com/pt/products/storage/">Armazenamento na nuvem na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/storage/">Blog de armazenamento na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/getting-started/hands-on/">Tutoriais práticos: armazenamento</a></li>
  <li><a href="https://aws.amazon.com/pt/solutions/case-studies/">Histórias de clientes da AWS: armazenamento</a></li>
  <li><a href="https://aws.amazon.com/pt/dms/">AWS Database Migration Service</a></li>
  <li><a href="https://aws.amazon.com/pt/getting-started/decision-guides/databases-on-aws-how-to-choose/">Bancos de dados na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/getting-started/hands-on/">Deep dive na categoria: bancos de dados</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/database/">Blog de bancos de dados da AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/solutions/case-studies/">Histórias de clientes da AWS: bancos de dados</a></li>
</ol>

#### Teste de conhecimento

Quais storage classes do Amazon S3 são otimizadas para dados de arquivamento? (Selecione DUAS opções.)

<ul>
  <li>Amazon S3 Standard</li>
  <li>&#10003; Amazon S3 Glacier Flexible Retrieval</li>
  <li>Amazon S3 Intelligent-Tiering</li>
  <li>Amazon S3 Standard-IA</li>
  <li>&#10003; Amazon S3 Glacier Deep Archive</li>
</ul>

Objetos armazenados na storage class Amazon S3 Glacier Flexible Retrieval podem ser recuperados de poucos minutos a algumas horas. Em comparação, os objetos armazenados na storage class Amazon S3 Glacier Deep Archive podem ser recuperados em 12 horas.

As outras respostas estão incorretas porque:

O Amazon S3 Standard é a storage class ideal para dados acessados com frequência, não dados de arquivamento.

O Amazon S3 Intelligent-Tiering monitora padrões de acesso de objetos e os move automaticamente entre as storage classes Amazon S3 Standard e Amazon S3 Standard-IA. Ele não foi projetado para dados de arquivamento.

O Amazon S3 Standard-IA é ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade para quando necessário.

<a href="https://aws.amazon.com/pt/s3/storage-classes/">Classes de Armazenamento de Objetos</a>

Qual(ais) afirmação(ões) é(são) VERDADEIRA(S) sobre os volumes do Amazon EBS e sistemas de arquivos do Amazon Elastic File System?

<ul>
  <li>&#10003; Os volumes do EBS armazenam dados em uma única Zona de Disponibilidade.</li>
  <li>Os sistemas de arquivos do Amazon EFS armazenam dados em várias Zonas de Disponibilidade.</li>
  <li>Os volumes do EBS e os sistemas de arquivos do Amazon EFS armazenam dados em uma única Zona de Disponibilidade.</li>
  <li>Os volumes do EBS e os sistemas de arquivos do Amazon Elastic File System armazenam dados em várias Zonas de Disponibilidade.</li>
</ul>

Um volume do EBS precisa estar localizado na mesma Zona de Disponibilidade que a instância do Amazon EC2 à qual ele está associado.

Os dados em um sistema de arquivos do Amazon Elastic File System podem ser acessados simultaneamente de todas as Zonas de Disponibilidade na Região em que o sistema de arquivos está localizado.

<a href="https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ebs-volumes.html">Volumes do Amazon Elastic Block Store (EBS)</a>

<a href="https://docs.aws.amazon.com/pt_br/efs/latest/ug/how-it-works.html">Como funciona o Amazon EFS</a>

Você quer armazenar dados em um serviço de armazenamento de objetos. Qual serviço da AWS é o melhor para esse tipo de armazenamento?

<ul>
  <li>Amazon Managed Blockchain</li>
  <li>Amazon Elastic File System (Amazon EFS)</li>
  <li>Amazon Elastic Block Store (Amazon EBS)</li>
  <li>&#10003; Amazon Simple Storage Service (Amazon S3)</li>
</ul>

A resposta correta é Amazon Simple Storage Service (Amazon S3).

As outras opções estão incorretas porque:

o Amazon Managed Blockchain é um serviço que você pode usar para criar e gerenciar redes de blockchain com frameworks de código aberto. O Blockchain é um sistema de ledger distribuído que permite que várias partes executem transações e compartilhem dados sem uma autoridade central.

O Amazon Elastic File System (Amazon EFS) é um sistema de arquivos dimensionável usado com os AWS Cloud Services e recursos on-premises. Ele não armazena dados como armazenamento de objetos.

O Amazon Elastic Block Store (Amazon EBS) é um serviço que fornece volumes de armazenamento em nível de bloco que você pode usar com instâncias do Amazon EC2.

<a href="https://aws.amazon.com/pt/what-is/object-storage/">O que é armazenamento de objetos?</a>

Qual afirmação melhor descreve o Amazon DynamoDB?

<ul>
  <li>Um serviço que permite executar bancos de dados relacionais na nuvem AWS</li>
  <li>&#10003; Um serviço de banco de dados de chave-valor sem servidor</li>
  <li>Um serviço que você pode usar para migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados</li>
  <li>Banco de dados relacional de nível empresarial</li>
</ul>

A resposta correta é Um serviço de banco de dados de chave-valor sem servidor.

O Amazon DynamoDB é um serviço de banco de dados de chave-valor. Ele é sem servidor, o que significa que você não precisa provisionar, aplicar patches ou gerenciar servidores.

As outras respostas estão incorretas porque:

um serviço que permite executar bancos de dados relacionais na nuvem AWS é a descrição do Amazon Relational Database Service (Amazon RDS).

Um serviço que você pode usar para migrar bancos de dados relacionais e não relacionais e outros tipos de armazenamentos de dados é a descrição do AWS Database Migration Service (AWS DMS).

Um banco de dados relacional de nível empresarial é a descrição do Amazon Aurora.

Qual serviço é usado para consultar e analisar dados em um data warehouse?

<ul>
  <li>&#10003; Amazon Redshift</li>
  <li>Amazon Neptune</li>
  <li>Amazon DocumentDB</li>
  <li>Amazon ElastiCache</li>
</ul>

A resposta correta é Amazon Redshift.

O Amazon Redshift é um serviço de data warehouse que você pode usar para análise de Big Data. Use o Amazon Redshift para coletar dados de muitas origens e entender relações e tendências em todos os dados.

As outras respostas estão incorretas porque:

O Amazon Neptune é um serviço de banco de dados de grafo. Você pode usar o Amazon Neptune para criar e executar aplicações que funcionam com conjuntos de dados altamente conectados, como mecanismos de recomendação, detecção de fraude e grafos de conhecimento.

O Amazon DocumentDB é um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB.

O Amazon ElastiCache é um serviço que adiciona camadas de cache sobre os bancos de dados para melhorar os tempos de leitura de solicitações comuns.

# Segurança

## O modelo de responsabilidade compartilhada da AWS



