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
computação em nuvem: <a href="https://www.youtube.com/watch?v=8JI9wQ8sUdQ&ab_channel=AmazonWebServicesLatinAmerica">O que é? AWS | Amazon Web Services</a>

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

## <a href="https://aws.amazon.com/pt/security/security-learning/?pg=cloudessentials&cards-top.sort-by=item.additionalFields.sortDate&cards-top.sort-order=desc&awsf.Types=*all">Segurança</a>

<p>A <a href="https://aws.amazon.com/pt/security/" target="_blank">segurança na nuvem</a> AWS é a maior prioridade. À medida que as organizações adotam a escalabilidade e a flexibilidade da nuvem, a AWS as ajuda a transformar segurança, identidade e conformidade em importantes facilitadores de negócios. A AWS incorpora a segurança no núcleo de nossa infraestrutura de nuvem e oferece serviços básicos para ajudar as organizações a atender aos
seus requisitos exclusivos de segurança na nuvem.</p>
<p>Como um cliente da AWS, você se beneficiará de um datacenter e uma arquitetura de rede criados para atender os requisitos da maioria das organizações com exigências de segurança. A segurança na nuvem é muito parecida com a segurança em seus data centers locais, mas sem os custos de manutenção de instalações e hardware. Na nuvem, você não precisa gerenciar servidores físicos ou dispositivos de armazenamento. Em vez disso, você usa ferramentas de segurança baseadas em software para monitorar e proteger o fluxo de informações que entram e saem dos seus recursos de nuvem.</p>
<p>Uma vantagem disso Nuvem AWS é que ele permite que você escale e inove, mantendo um ambiente seguro e pagando somente pelos serviços que você usa. Isso significa que você pode ter a segurança de que precisa a um custo menor do que em um ambiente local.</p>
<p>Como AWS cliente, você herda todas as melhores práticas de AWS políticas, arquitetura e processos operacionais criados para satisfazer os requisitos de nossos clientes mais sensíveis à segurança. Obtenha a flexibilidade e a agilidade de que você precisa nos controles de segurança.</p>
<p>Nuvem AWS permite um modelo de responsabilidade compartilhada. Enquanto AWS gerencia a segurança da nuvem, você é responsável pela segurança na nuvem. <a href="https://www.youtube.com/watch?v=_2HFqANE4gw&ab_channel=AmazonWebServices" target="_blank">Isso significa que você mantém o controle da segurança </a> que escolhe implementar para proteger seu próprio conteúdo, plataforma, aplicativos, sistemas e redes da mesma forma que faria em um data center local.
AWS fornece orientação e experiência por meio de recursos on-line, pessoal e parceiros.</p>
<p>AWS fornece recomendações sobre problemas atuais, além de você ter a oportunidade de trabalhar com eles AWS quando encontrar problemas de <a href="https://www.youtube.com/watch?v=-eewsuGLhLw&ab_channel=AmazonWebServicesLatinAmerica">segurança.</a>
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
<p>As instâncias otimizadas para armazenamento são projetadas para cargas de trabalho que exigem alto acesso sequencial de leitura e gravação a grandes conjuntos de dados no armazenamento local. Exemplos de cargas de trabalho adequadas para as instâncias otimizadas para armazenamento são sistemas de arquivos distribuídos, aplicações de <a href="https://aws.amazon.com/pt/what-is/data-warehouse/" target="_blank">data warehouse</a> e sistemas de processamento de transação on-line (OLTP) de alta frequência.</p>

<p>Na computação, o termo operações de entrada/saída por segundo (IOPS) é uma métrica que mensura o desempenho de um dispositivo de armazenamento. Ela indica quantas operações diferentes de entrada ou saída um dispositivo pode executar em um segundo. As instâncias otimizadas para armazenamento foram projetadas para fornecer dezenas de milhares de IOPS aleatórias e de baixa latência para aplicativos. </p>

<p>Imagine as operações de entrada como dados colocados em um sistema, como registros inseridos em um banco de dados. Uma operação de saída são dados gerados por um servidor. Um exemplo de saída pode ser a análise realizada nos registros em um banco de dados. Se você tiver um aplicativo com alto requisito de IOPS, uma instância otimizada para armazenamento poderá fornecer melhor desempenho em relação a outros tipos de instâncias não otimizados para esse tipo de caso de uso.</p>

#### Teste de conhecimento:

<p>Qual tipo de instância do Amazon EC2 é adequado para aplicações de data warehousing?</p>

<ul>
    <li>Otimizada para memória</li>
    <li>&#10004;Otimizada para armazenamento</li>
    <li>Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 equilibra os recursos de computação, memória e rede?</p>

<ul>
    <li>Otimizada para memória</li>
    <li>Otimizada para armazenamento</li>
    <li>&#10004;Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 é ideal para bancos de dados de alto desempenho?</p>

<ul>
    <li>&#10004;Otimizada para memória</li>
    <li>Otimizada para armazenamento</li>
    <li>Uso geral</li>
    <li>Otimizada para computação</li>
</ul>

<p>Qual tipo de instância do Amazon EC2 oferece processadores de alto desempenho?</p>

 <ul>
     <li>Otimizada para memória</li>
     <li>Otimizada para armazenamento</li>
     <li>Uso geral</li>
     <li>&#10004;Otimizada para computação</li>
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
    <li>&#10004;Standard Reserved Instances</li>
</ul>

<p>Qual opção de preço do Amazon EC2 oferece um desconto quando você assume um compromisso de gasto por hora com uma família de instância e uma Região por um período de vigência de um ou três anos?</p>
<ul>
    <li>Sob demanda</li>
    <li>&#10004;Savings Plans da instância do EC2</li>
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
    <li>&#10004;Amazon Simple Notification Service (Amazon SNS)</li>
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
    <li>&#10004;Otimizada para computação</li>
    <li>Otimizada para armazenamento</li>
</ul>

<p>Quais são as opções de duração do contrato para instâncias reservadas do Amazon EC2? (Selecione DUAS opções.)</p>

<ul>
    <li>&#10004;1 ano</li>
    <li>2 anos</li>
    <li>&#10004;3 anos</li>
    <li>4 anos</li>
    <li>5 anos</li>
</ul>

<p>Você tem uma carga de trabalho que será executada por um total de seis meses e consegue suportar interrupções. Qual seria a opção de compra mais econômica do Amazon EC2?</p>
<ul>
    <li>Instância reservada</li>
    <li>&#10004;Instância spot</li>
    <li>Instância dedicada</li>
    <li>Instância sob demanda</li>
</ul>

<p>Qual processo é um exemplo do Elastic Load Balancing?</p>

<ul>
    <li>&#10004;Garantir que nenhuma instância única do Amazon EC2 tenha que suportar a carga de trabalho completa sozinha</li>
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
    <li>&#10004;Amazon Elastic Kubernetes Service (Amazon EKS)</li>
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
    <li>&#10004;Um único data center ou grupo de data centers em uma Região</li>
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
    <li>&#10004;Uma Região consiste em três ou mais Zonas de Disponibilidade.</li>
    <li>Uma Zona de Disponibilidade consiste em uma única Região.</li>
</ul>

<p>Quais fatores devem ser considerados ao selecionar uma Região? (Selecione DUAS opções.)</p>
<ul>
    <li>&#10004;Conformidade com governança de dados e requisitos legais</li>
    <li>&#10004;Proximidade com os clientes</li>
    <li>Acesso a suporte técnico 24 horas por dia</li>
    <li>Capacidade de atribuir permissões personalizadas a diferentes usuários</li>
    <li>Acesso à AWS Command Line Interface (AWS CLI)</li>
</ul>

<p>Qual declaração descreve melhor o Amazon CloudFront?</p>
<ul>
    <li>Um serviço que permite executar a infraestrutura em uma abordagem de nuvem híbrida</li>
    <li>Um mecanismo de computação sem servidor para contêineres</li>
    <li>Um serviço que permite enviar e receber mensagens entre componentes de software por uma fila</li>
    <li>&#10004;Um serviço global de entrega de conteúdo</li>
</ul>

>[nota] O Amazon CloudFront é um serviço de entrega de conteúdo. Ele usa uma rede de locais de borda para armazenar conteúdo em cache e entregar conteúdo para clientes em todo o mundo. Quando o conteúdo é armazenado em cache, ele é mantido localmente como uma cópia. Esse conteúdo pode ser arquivos de vídeo, fotos, páginas da web e assim por diante.

<p>Qual site o Amazon CloudFront usa para armazenar cópias de conteúdo em cache para entregá-los mais rapidamente aos usuários em qualquer local?</p>
<ul>
    <li>Região</li>
    <li>Zona de Disponibilidade</li>
    <li>Origem</li>
    <li>&#10004;Local de borda</li>
</ul>

<p>Qual ação você pode executar com o AWS Outposts?</p>
<ul>
    <li>Automatizar ações para serviços e aplicações da AWS por meio de scripts.</li>
    <li>Acessar assistentes e fluxos de trabalho automatizados para executar tarefas nos serviços da AWS.</li>
    <li>Desenvolver aplicações da AWS em linguagens de programação compatíveis.</li>
    <li>&#10004;Estender a infraestrutura e os serviços da AWS para diferentes locais, incluindo um data center on-premises.</li>
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
  <li>&#10004;Ela é stateless e permite todo o tráfego de entrada e saída.</li>
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
    &#10004;Converter um nome de domínio em um endereço IP
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
  <li>&#10004; Colocar as instâncias do Amazon EC2 em uma sub-rede pública e as instâncias de bancos de dados do Amazon RDS em uma sub-rede privada.</li>
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
  <li>&#10004; AWS Direct Connect</li>
  <li>Gateway privado virtual</li>
</ul>

Qual declaração descreve melhor os grupos de segurança?

<ul>
  <li>&#10004; Eles são stateful e negam todo o tráfego de entrada por padrão.</li>
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
  <li>&#10004; Gateway de internet</li>
</ul>

Qual serviço é usado para gerenciar os registros de DNS para nomes de domínio?

<ul>
  <li>Amazon Virtual Private Cloud</li>
  <li>AWS Direct Connect</li>
  <li>Amazon CloudFront</li>
  <li>&#10004; Amazon Route 53</li>
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
  <li>&#10004; Ideal para dados que precisam ser retidos</li>
  <li> Ideal para dados temporários que não são mantidos a longo prazo</li>
  <li>&#10004; Unidades separadas do computador host de uma instância do EC2</li>
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
  <li>&#10004; S3 Standard-IA</li>
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
  <li>&#10004; Ao usar SQL para organizar dados</li>
  <li>Ao armazenar dados em um banco de dados de chave-valor</li>
  <li>Ao dimensionar para 10 trilhões de solicitações por dia</li>
  <li>&#10004; Ao armazenar dados em um banco de dados do Amazon Aurora</li>
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
  <li>&#10004; Amazon S3 Glacier Flexible Retrieval</li>
  <li>Amazon S3 Intelligent-Tiering</li>
  <li>Amazon S3 Standard-IA</li>
  <li>&#10004; Amazon S3 Glacier Deep Archive</li>
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
  <li>&#10004; Os volumes do EBS armazenam dados em uma única Zona de Disponibilidade. Os sistemas de arquivos do Amazon EFS armazenam dados em várias Zonas de Disponibilidade.</li>
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
  <li>&#10004; Amazon Simple Storage Service (Amazon S3)</li>
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
  <li>&#10004; Um serviço de banco de dados de chave-valor sem servidor</li>
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
  <li>&#10004; Amazon Redshift</li>
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
  <li>&#10004; Amazon S3 Glacier Flexible Retrieval</li>
  <li>Amazon S3 Intelligent-Tiering</li>
  <li>Amazon S3 Standard-IA</li>
  <li>&#10004;; Amazon S3 Glacier Deep Archive</li>
</ul>

Objetos armazenados na storage class Amazon S3 Glacier Flexible Retrieval podem ser recuperados de poucos minutos a algumas horas. Em comparação, os objetos armazenados na storage class Amazon S3 Glacier Deep Archive podem ser recuperados em 12 horas.

As outras respostas estão incorretas porque:

O Amazon S3 Standard é a storage class ideal para dados acessados com frequência, não dados de arquivamento.

O Amazon S3 Intelligent-Tiering monitora padrões de acesso de objetos e os move automaticamente entre as storage classes Amazon S3 Standard e Amazon S3 Standard-IA. Ele não foi projetado para dados de arquivamento.

O Amazon S3 Standard-IA é ideal para dados acessados com pouca frequência, mas que precisam ter alta disponibilidade para quando necessário.

<a href="https://aws.amazon.com/pt/s3/storage-classes/">Classes de Armazenamento de Objetos</a>

Qual(ais) afirmação(ões) é(são) VERDADEIRA(S) sobre os volumes do Amazon EBS e sistemas de arquivos do Amazon Elastic File System?

<ul>
  <li>&#10004; Os volumes do EBS armazenam dados em uma única Zona de Disponibilidade.</li>
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
  <li>&#10004; Amazon Simple Storage Service (Amazon S3)</li>
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
  <li>&#10004; Um serviço de banco de dados de chave-valor sem servidor</li>
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
  <li>&#10004; Amazon Redshift</li>
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

![modelo](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/bb91b050-9074-4e5d-b98c-5682eeaead0e)

Ao longo deste curso, você aprendeu sobre diversos recursos que podem ser criados na nuvem AWS. Esses recursos são as instâncias do Amazon EC2, os buckets do Amazon S3 e os bancos de dados do Amazon RDS. Quem é responsável por manter esses recursos seguros: você (o cliente) ou AWS?

A resposta é ambos. Isso é porque você não trata seu ambiente AWS como um único objeto. Em vez disso, você trata o ambiente como uma coleção de partes que se combinam. A AWS é responsável por algumas partes do seu ambiente e você (o cliente) é responsável por outras. Esse conceito é conhecido como modelo de <a href="https://aws.amazon.com/pt/compliance/shared-responsibility-model/">Modelo de responsabilidade compartilhada da AWS</a>

O modelo de responsabilidade compartilhada divide-se em responsabilidades do cliente (chamadas de “segurança na nuvem”) e responsabilidades da AWS (chamadas de “segurança da nuvem”).

![modelo1](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/ddfb2789-d092-4129-8910-e80f4be788bc)

Você pode pensar nesse modelo como sendo parecido com a divisão de responsabilidades entre um proprietário e uma construtora. A construtora (AWS) é responsável por edificar sua casa e garantir que ela seja construída com solidez. Como proprietário (o cliente), é sua responsabilidade proteger tudo na casa, garantindo que as portas estejam fechadas e trancadas. 

#### Para saber mais sobre o modelo de responsabilidade compartilhada

### Clientes: Segurança na nuvem

Os clientes são responsáveis pela segurança de tudo o que criam e colocam na nuvem AWS.

Ao usar os serviços da AWS, você, o cliente, mantém controle total sobre seu conteúdo. Você é responsável por gerenciar os requisitos de segurança para seu conteúdo, incluindo qual conteúdo você escolhe armazenar na AWS, quais serviços AWS você usa e quem tem acesso a esse conteúdo. Você também controla como os direitos de acesso são concedidos, gerenciados e revogados.

As etapas de segurança que você executar dependem de fatores como os serviços que usa, a complexidade de seus sistemas e as necessidades operacionais e de segurança específicas de sua empresa. As etapas são seleção, configuração e aplicação de patches nos sistemas operacionais que serão executados nas instâncias do Amazon EC2, configuração de grupos de segurança e gerenciamento de contas de usuário. 

### AWS: Segurança da nuvem

A AWS é responsável pela segurança da nuvem.

A AWS opera, gerencia e controla os componentes em todas as camadas da infraestrutura. Isso inclui áreas como o sistema operacional do host, a camada de virtualização e até mesmo a segurança física do data center no qual o serviço opera. 

A AWS é responsável pela proteção da infraestrutura global que executa todos os serviços oferecidos na nuvem AWS. A infraestrutura inclui Regiões AWS, Zonas de Disponibilidade e locais de borda.

A AWS gerencia a segurança da nuvem, especificamente a infraestrutura física que hospeda seus recursos, que incluem:

<ul>
  <li>Segurança física dos data centers</li>
  <li>Infraestrutura de hardware e software</li>
  <li>Infraestrutura de rede</li>
  <li>Infraestrutura de virtualização</li>
</ul>

Embora você não possa visitar os data centers da AWS para ver essa proteção pessoalmente, a AWS oferece vários relatórios de auditores terceirizados. Esses auditores verificaram a conformidade com diversas normas e regulamentações de segurança da computação.

#### Teste de conhecimento

Quais tarefas são responsabilidades dos clientes? (Selecione DUAS opções.)

<ul>
  <li>Manutenção da infraestrutura de rede</li>
  <li>&#10004; Aplicação de patches em software em instâncias do Amazon EC2</li>
  <li>Implementação de controles de segurança física no data center</li>
  <li>&#10004; Definição de permissões para objetos do Amazon S3</li>
  <li>Manutenção de servidores que executam instâncias do Amazon EC2</li>
</ul>

<a href="https://aws.amazon.com/pt/compliance/shared-responsibility-model/">Modelo de responsabilidade compartilhada da AWS</a>

## Permissões de usuário e acesso

### AWS Identity and Access Management (IAM)

O <a href="https://aws.amazon.com/pt/iam/">AWS Identity and Access Management (IAM)</a> permite que você gerencie o acesso aos serviços e recursos da AWS com segurança.   

O IAM oferece a flexibilidade de configurar o acesso com base nas necessidades operacionais e de segurança específicas da sua empresa. Você pode fazer isso usando uma combinação dos recursos do IAM, que vamos conhecer melhor nesta lição:

<ul>
  <li>Usuários, grupos e perfis do IAM</li>
  <li>Políticas do IAM</li>
  <li>Autenticação multifator</li>
</ul>

Você também conhecerá as práticas recomendadas para cada um desses recursos.

Ao criar uma conta AWS pela primeira vez, você começa com uma identidade conhecida como <a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_root-user.html">usuário-raiz</a>

O usuário-raiz é acessado ao entrar com o endereço de e-mail e a senha usados para criar a conta AWS. Pense no usuário-raiz como sendo parecido com o proprietário da cafeteria: Ele tem acesso completo a todos os serviços e recursos AWS na conta.

![iam](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/c29a03a3-7988-4b62-bb7b-bac508b9d361)

> <strong>Prática recomendada:</strong>

> não use o usuário-raiz para tarefas cotidianas. 

> Em vez disso, use o usuário-raiz para criar seu primeiro usuário do IAM e atribua a ele permissões para criar outros usuários.

>  Em seguida, continue a criar outros usuários do IAM e acesse essas identidades para executar tarefas comuns em toda a AWS. Use o usuário-raiz somente quando precisar executar um número limitado de tarefas disponíveis somente para o usuário-raiz. Exemplos dessas tarefas são a alteração do endereço de e-mail do usuário-raiz e a alteração do plano do AWS Support. Para obter mais informações, consulte “Tasks that require root user credentials” (Tarefas que exigem credenciais de usuário-raiz) no <a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/root-user-tasks.html">AWS Account Management Reference Guide</a> (Guia de referência de gerenciamento da conta AWS).

### Usuários do IAM

Um usuário do IAM é uma identidade que você cria na AWS. Ele representa a pessoa ou o aplicativo que interage com os serviços e recursos AWS. Consiste em um nome e credenciais.

Por padrão, ao criar um novo usuário do IAM na AWS, não há permissões associadas a ele. Para permitir que o usuário do IAM execute ações específicas na AWS, como iniciar uma instância do Amazon EC2 ou criar um bucket do Amazon S3, você deve conceder ao usuário do IAM as permissões necessárias.

> <strong>Prática recomendada:</strong>

> recomendamos que crie usuários individuais do IAM para cada pessoa que precisa acessar a AWS.  

> Mesmo que você tenha vários funcionários que precisem do mesmo nível de acesso, você deve criar usuários individuais do IAM para cada um deles. Isso fornece segurança adicional, permitindo que cada usuário do IAM tenha um conjunto exclusivo de credenciais de segurança.

### Políticas do IAM

Uma política do IAM é um documento que concede ou nega permissões para serviços e recursos AWS.  

As políticas do IAM permitem que você personalize os níveis de acesso dos usuários aos recursos. Por exemplo, você pode permitir que os usuários acessem todos os buckets do Amazon S3 em sua conta AWS ou apenas um bucket específico.

> <strong>Prática recomendada:</strong>

> siga o princípio de segurança de menor privilégio ao conceder permissões. 

> Seguindo esse princípio, você ajuda a impedir que usuários ou perfis tenham mais permissões do que o necessário para executar as tarefas. 

> Por exemplo, se um funcionário precisar acessar apenas um bucket específico, especifique o bucket na política do IAM. Faça isso em vez de conceder ao funcionário acesso a todos os buckets em sua conta AWS.

### Exemplo: política do IAM

Veja um exemplo de como as políticas do IAM funcionam. Suponha que o proprietário da cafeteria tenha criado um usuário do IAM para um operador de caixa recém-contratado. Esse funcionário precisa acessar os recibos mantidos em um bucket do Amazon S3 com o ID: AWSDOC-EXAMPLE-BUCKET.

<img width="400" alt="LbdeJm2B_ER5hQiy_vKf8uGbqJDqmoCNE" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/c50b1615-0ea5-448e-a2a5-4165c52b12e3">

Nesse exemplo, a política do IAM permite uma ação específica no Amazon S3: ListObject. A política também menciona o ID de bucket específico: AWSDOC-EXAMPLE-BUCKET. Quando o proprietário associa essa política ao usuário do IAM do operador de caixa, ele permitirá que ele visualize todos os objetos no bucket AWSDOC-EXAMPLE-BUCKET. 

Se o proprietário quiser que o operador de caixa possa acessar outros serviços e executar outras ações na AWS, o proprietário precisará anexar políticas adicionais para especificar esses serviços e essas ações.

Agora, suponha que a cafeteria tenha contratado mais alguns operadores de caixa. Em vez de atribuir permissões a cada usuário individual do IAM, o proprietário coloca os usuários em um <a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_groups.html">grupo do IAM.</a>

### Grupos do IAM

Um grupo do IAM é um conjunto de usuários do IAM. Quando você atribui uma política do IAM a um grupo, todos os usuários do grupo recebem permissões especificadas pela política.

Veja um exemplo de como isso pode funcionar na cafeteria. Em vez de atribuir permissões aos operadores um de cada vez, o proprietário pode criar o grupo “operadores de caixa” do IAM. O proprietário pode, em seguida, adicionar usuários do IAM ao grupo e anexar permissões no nível do grupo. 

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/04f4f4c6-372a-4674-82c4-74f1d56e4ece" alt="db\srn\" width="50%" style="float: left; margin-right: 10px;">

A atribuição de políticas do IAM no nível de grupo também facilita o ajuste de permissões quando um funcionário é transferido para um trabalho diferente. Por exemplo, se um operador de caixa se tornar um especialista em inventário, o proprietário da cafeteria o removerá do grupo “operadores de caixa” do IAM e o adicionará ao grupo “especialistas em inventário”. Isso garante que os funcionários tenham apenas as permissões necessárias para a função atual.

E se um funcionário da cafeteria não tiver trocado de função permanentemente, mas, em vez disso, revezar em diferentes estações de trabalho ao longo do dia? Esse funcionário pode ter o acesso de que precisa pelos <a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles.html">Perfis do IAM</a>

### Perfis do IAM

Na cafeteria, um funcionário se reveza em diferentes estações de trabalho ao longo do dia. Dependendo do tamanho da equipe da cafeteria, esse funcionário pode desempenhar várias tarefas: trabalhar na caixa registradora, atualizar o sistema de inventário, processar pedidos on-line e assim por diante. 

Quando o funcionário precisa alternar para uma tarefa diferente, ele abre mão do acesso a uma estação de trabalho e ganha acesso à próxima estação. O funcionário pode alternar facilmente entre estações de trabalho, mas, a qualquer momento, ele pode ter acesso a uma única estação de trabalho. Esse mesmo conceito existe na AWS com os perfis do IAM.

Um perfil do IAM é uma identidade que você pode assumir para obter acesso temporário a permissões.  

Antes que um usuário, aplicação ou serviço do IAM possa assumir um perfil do IAM, ele precisa receber permissões para alternar para o perfil. Quando alguém assume uma função do IAM, ele abandona todas as permissões anteriores que tinha em uma função anterior e assume as permissões da nova função. 

> <strong>Prática recomendada:</strong>

> os perfis do IAM são ideais para situações em que o acesso a serviços ou recursos precisa ser concedido temporariamente, em vez de por longo prazo. 

### Autenticação com multifator

Você já entrou em um site que exigia várias informações para verificar sua identidade? Talvez tenha sido necessário digitar sua senha e, em seguida, uma segunda forma de autenticação, como um código aleatório enviado para o telefone. Este é um exemplo de <a href="https://aws.amazon.com/pt/iam/features/mfa/">autenticação multifator (MFA) do IAM</a>

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/96cdb7a1-9590-423e-8b3b-3a189577e164" alt="db\srn\" width="50%" style="float: left; margin-right: 10px;">

Primeiro, um usuário insere a senha e o ID do usuário do IAM para entrar em um site da AWS.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/7010c4e5-1de1-41b4-afbc-32a276b68619" alt="db\srn\" width="40%" style="float: left; margin-right: 10px;">

Em seguida, é solicitado ao usuário que informe a resposta de autenticação de seu dispositivo MFA da AWS. Esse dispositivo pode ser uma chave de segurança de hardware, um dispositivo de hardware ou uma aplicação de MFA em um dispositivo, como um smartphone.

#### Conclusão

Quando o usuário tiver sido autenticado com êxito, ele poderá acessar os serviços ou recursos AWS solicitados.

Você pode ativar o MFA para o usuário-raiz e os usuários do IAM. Como prática recomendada, habilite o MFA para o usuário-raiz e todos os usuários do IAM em sua conta. Ao fazer isso, você pode manter sua conta AWS protegida contra um acesso não autorizado.

## AWS Organizations

Suponha que sua empresa tenha múltiplas contas AWS. Você pode usar o <a href="https://aws.amazon.com/pt/organizations/">AWS Organizations</a> para consolidar e gerenciar múltiplas contas AWS em um local central.

Quando você cria uma organização, o AWS Organizations cria automaticamente uma raiz, que é o contêiner primário para todas as contas da organização. 

No AWS Organizations, você pode controlar de maneira centralizada as permissões para as contas em sua organização usando as <a href="https://docs.aws.amazon.com/pt_br/organizations/latest/userguide/orgs_manage_policies_scps.html">Políticas de controle de serviço (SCPs) - AWS Organizations</a>
. As SCPs permitem que você coloque restrições nos serviços AWS, recursos e ações individuais de API que os usuários e funções em cada conta podem acessar.

>{nota] A cobrança consolidada é outro recurso do AWS Organizations. Você conhecerá melhor a cobrança consolidada em um módulo posterior.

### Unidades organizacionais

No AWS Organizations, você pode agrupar contas em unidades organizacionais (UO) para facilitar o gerenciamento de contas com requisitos de negócios ou segurança semelhantes. Ao aplicar uma política a uma UO, todas as contas na UO herdam automaticamente as permissões especificadas na política.  

Ao organizar contas separadas em UO, você pode isolar mais facilmente cargas de trabalho ou aplicações com requisitos de segurança específicos. Por exemplo, se sua empresa tiver contas que podem acessar apenas os serviços da AWS que atendam a determinados requisitos normativos, você poderá colocar essas contas em uma UO. Em seguida, você pode anexar uma política à UO que bloqueia o acesso a todos os outros serviços da AWS que não atendam aos requisitos normativos.

Para ver um exemplo de como uma empresa pode usar o AWS Organizations, escolha os botões de seta para exibir cada etapa.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/c3a7c78a-c7f2-4865-9694-9fcf4348c603" alt="raiz" width="90%" style="float: left; margin-right: 10px;">

Imagine que sua empresa tenha contas AWS separadas para os departamentos financeiro, de tecnologia da informação (TI), de recursos humanos (RH) e jurídico. Você decide consolidar essas contas em uma única organização para que possa administrá-las a partir de um local central. Ao criar a organização, isso estabelece a raiz.

Ao projetar essa organização, você considera as necessidades normativas, de negócios e de segurança de cada departamento. Você usa essas informações para decidir quais departamentos podem ser agrupados em UOs

![raiz](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/5ac9d1af-22d2-466f-998d-a5a3cf0288e4)

![raizrr](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/91f73958-7e8f-4819-ab71-ed55499bc337)

### Conclusão

Mesmo que tenha colocado essas contas em UOs, você pode continuar concedendo acesso a usuários, grupos e perfis por meio do IAM.

Ao agrupar suas contas em UOs, você pode conceder acesso facilmente aos serviços e recursos de que eles precisam. Você também impede o acesso a qualquer serviço ou recurso desnecessário.

#### Teste de conhecimento

Você está configurando políticas de controle de serviço (SCPs) no AWS Organizations. A quais identidades e recursos as SCPs podem ser aplicadas? (Selecione DUAS opções.)

<ul>
  <li>Usuários do IAM</li>
  <li>Grupos do IAM</li>
  <li>&#10004;; Uma conta de membro individual</li>
  <li>Funções do IAM</li>
  <li>&#10004;; Uma unidade organizacional (UO)</li>
</ul>

Com o AWS Organizations, você pode aplicar políticas de controle de serviço (SCPs) para a raiz da organização, uma conta de membro individual ou uma UO. Uma SCP afeta todos os usuários, grupos e perfis do IAM em uma conta, incluindo o usuário-raiz da conta AWS.

Você pode aplicar políticas do IAM a usuários, grupos ou perfis do IAM. Você não pode aplicar uma política do IAM ao usuário-raiz da conta AWS.

<a href="https://aws.amazon.com/pt/organizations/" target="_blank">AWS Organizations</a>
<a href="https://docs.aws.amazon.com/pt_br/organizations/latest/userguide/orgs_manage_policies_scps.html" target="_blank">Políticas de controle de serviço (SCPs) - AWS Organizations</a>
<a href="https://docs.aws.amazon.com/pt_br/organizations/latest/userguide/orgs_manage_policies_scps_attach.html" target="_blank">Anexar SCPs</a>

### AWS Artifact

Dependendo do setor de sua empresa, talvez seja necessário manter padrões específicos. Uma auditoria ou inspeção assegurará que a empresa cumpriu esses padrões.

O <a href="https://aws.amazon.com/pt/artifact/">AWS Artifact</a> é um serviço que concede acesso sob demanda a relatórios de segurança e conformidade da AWS e a contratos on-line selecionados. O AWS Artifact consiste em duas seções principais: AWS Artifact Agreements e o AWS Artifact Reports.

### AWS Artifact Agreements

Suponha que sua empresa precise assinar um contrato com a AWS em relação ao uso de determinados tipos de informações em todos os serviços da AWS. Você pode fazer isso pelo AWS Artifact Agreements. 

No AWS Artifact Agreements, você pode ver, aceitar e gerenciar contratos para uma conta individual e para todas as suas contas no AWS Organizations. Diferentes tipos de acordos são oferecidos para atender às necessidades dos clientes sujeitos a regulamentações específicas, como a Lei de Portabilidade e Responsabilidade dos Provedores de Saúde dos EUA (HIPAA).
 
### AWS Artifact Reports

Suponha que um membro da equipe de desenvolvimento da sua empresa esteja criando uma aplicação e precise de mais informações sobre a responsabilidade em cumprir determinados padrões regulatórios. Você pode recomendar o acesso a essas informações em AWS Artifact Reports.

O AWS Artifact Reports oferece relatórios de conformidade por auditores terceirizados. Esses auditores testaram e verificaram se a AWS está em conformidade com diversas normas e regulamentações de segurança globais, regionais e específicas do setor. O AWS Artifact Reports se mantém atualizado com os relatórios publicados mais recentes. Você pode fornecer os artefatos de auditoria da AWS aos auditores ou reguladores como evidência dos controles de segurança da AWS. 

O AWS Artifact concede acesso a documentos de segurança e conformidade da AWS, como relatórios de certificações ISO da AWS, relatórios do Payment Card Industry (PCI) e Service Organization Control (SOC).  Para saber mais sobre os relatórios de conformidade disponíveis, visite Programas de conformidade da AWS.

### Centro de conformidade para o cliente

O centro de conformidade para o cliente contém recursos que ajudam você a saber mais sobre a conformidade da AWS. 

No <a href="https://aws.amazon.com/pt/compliance/customer-center/">Centro de conformidade para clientes</a>, você pode ler histórias de conformidade dos clientes para descobrir como as empresas de setores regulamentados resolveram vários desafios de conformidade, governança e auditoria.

Você também pode acessar whitepapers e documentação de conformidade sobre tópicos como:

<ul>
  <li>Respostas da AWS aos principais problemas de conformidade</li>
  <li>Uma visão geral do risco e da conformidade da AWS</li>
  <li>Uma lista de verificação da segurança de auditoria</li>
</ul>

Além disso, o centro de conformidade para o cliente inclui um plano de aprendizagem para auditores. Esse plano de aprendizagem foi elaborado para indivíduos em funções jurídicas, de auditoria e de conformidade que desejam saber mais sobre como suas operações internas podem demonstrar conformidade usando a nuvem AWS.

#### Teste de conhecimento 

Quais tarefas você pode concluir no AWS Artifact? (Selecione DUAS opções.)

<ul>
  <li>&#10004; Acessar relatórios de conformidade da AWS sob demanda.</li>
  <li>Consolidar e gerenciar múltiplas contas AWS em um local central.</li>
  <li>Criar usuários para permitir que pessoas e aplicativos interajam com serviços e recursos AWS.</li>
  <li>Definir permissões para contas configurando as políticas de controle de serviço (SCPs).</li>
  <li>&#10004; Analisar, aceitar e gerenciar seus contratos com a AWS.</li>
</ul>

As outras respostas estão incorretas porque:

Consolidar e gerenciar múltiplas contas AWS em um local central. Essa tarefa pode ser concluída no AWS Organizations.

Criar usuários para permitir que pessoas e aplicações interajam com serviços e recursos da AWS. Essa tarefa pode ser concluída no AWS Identity and Access Management (IAM).

Definir permissões para contas configurando políticas de controle de serviço (SCPs). Essa tarefa pode ser concluída no AWS Organizations.

### Ataques de negação de serviço

Os clientes podem telefonar para a cafeteria para fazer os pedidos. Depois de atender cada chamada, um operador de caixa anota o pedido e o entrega ao barista. 

No entanto, suponha que uma pessoa telefone várias vezes para fazer pedidos, mas nunca retire as bebidas. Isso faz com que o operador de caixa fique indisponível para atender chamadas de outros clientes. A cafeteria pode tentar parar os pedidos falsos bloqueando o número de telefone que a pessoa está usando. 

Nesse cenário, as ações da pessoa passando o trote são semelhantes a um ataque de negação de serviço.

Um ataque de negação de serviço (DoS) é uma tentativa deliberada de tornar um site ou aplicação indisponível para os usuários.

![Sem título](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/fa5a11c0-dc13-44e5-ad6e-a56fba61bd30)

### Ataques distribuídos de negação de serviço

Agora, suponha que a pessoa passando o trote tenha recrutado a ajuda de amigos. 

Essa pessoa e os amigos dela telefonam repetidamente para a cafeteria para fazer pedidos, mesmo que não pretendam retirá-los. Esses pedidos são provenientes de números de telefone diferentes e é impossível que a cafeteria bloqueie todos eles. Além disso, o influxo de chamadas dificultou cada vez mais o atendimento aos clientes. Isso se parece com um ataque distribuído de negação de serviço.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/93985d03-4411-4d1a-9e4a-eb10e0ba1e41" alt="raiz" width="60%" style="float: left; margin-right: 10px;">

Em um ataque distribuído de negação de serviço (DDoS), várias origens são usadas para iniciar um ataque que visa tornar um site ou aplicação indisponível. O ataque pode ser feito por um grupo de invasores, ou até mesmo um único invasor. O único invasor pode usar vários computadores infectados (também conhecidos como “bots”) para enviar tráfego excessivo a um site ou aplicação.

Para ajudar a minimizar o efeito de ataques DoS e DDoS em suas aplicações, você pode usar o <a href="https://aws.amazon.com/pt/shield/">AWS Shield</a>

### AWS Shield

O AWS Shield é um serviço que protege aplicações contra ataques DDoS. O AWS Shield oferece dois níveis de proteção: Standard e Advanced.

### AWS Shield Standard

O AWS Shield Standard protege automaticamente todos os clientes AWS sem nenhum custo. Ele protege seus recursos AWS contra os tipos de ataques DDoS mais comuns e frequentes. 

À medida que o tráfego de rede ingressa nas suas aplicações, o AWS Shield Standard usa diversas técnicas de análise para detectar tráfego mal-intencionado em tempo real e mitigá-lo automaticamente. 

### AWS Shield Advanced

O AWS Shield Advanced é um serviço pago que fornece diagnósticos detalhados de ataques e a capacidade de detectar e mitigar ataques elaborados de DDoS. 

Ele também se integra a outros serviços, como o Amazon CloudFront, o Amazon Route 53 e o Elastic Load Balancing. Além disso, você pode integrar o AWS Shield ao AWS WAF escrevendo regras personalizadas para mitigar ataques complexos de DDoS.

## Serviços de segurança adicionais

### AWS Key Management Service (AWS KMS)

A cafeteria tem muitos itens, como máquinas de café, confeitaria, dinheiro nas caixas registradoras e assim por diante. Você pode pensar nesses itens como dados. Os proprietários da cafeteria querem garantir que todos esses itens estejam protegidos, independentemente de estarem dispostos na sala de armazenamento ou em transporte. 

Da mesma forma, você deve garantir que os dados das suas aplicações estejam protegidos durante o armazenamento (criptografia em repouso) e durante a transmissão (criptografia em trânsito).

O <a href="https://aws.amazon.com/pt/kms/">AWS Key Management Service</a> permite que você execute operações de criptografia usando chaves de criptografia. Uma chave de criptografia é uma cadeia aleatória de dígitos usada para bloquear (criptografar) e desbloquear (descriptografar) dados. Você pode usar o AWS KMS para criar, gerenciar e usar chaves de criptografia. Você também pode controlar o uso de chaves em uma ampla gama de serviços e em suas aplicações.

Com o AWS KMS, você pode escolher os níveis específicos de controle de acesso necessários para suas chaves. Por exemplo, você pode especificar quais usuários e funções do IAM podem gerenciar chaves. Do mesmo modo, você pode desativar temporariamente as chaves para que não sejam mais usadas. Suas chaves nunca saem do AWS KMS e você está sempre no controle delas.

### AWS WAF

O <a href="https://aws.amazon.com/pt/waf/">AWS WAF</a> é um firewall de aplicação web que permite monitorar solicitações de rede que entram em aplicações web. 

O AWS WAF trabalha em conjunto com o Amazon CloudFront e um Application Load Balancer. Lembre-se das listas de controle de acesso de rede que você aprendeu em um módulo anterior. O AWS WAF funciona de forma semelhante para bloquear ou permitir o tráfego. No entanto, ele faz isso usando uma <a href="https://docs.aws.amazon.com/pt_br/waf/latest/developerguide/web-acl.html">lista de controle de acesso (ACL)</a>
da web para proteger seus recursos da AWS. 

Veja um exemplo de como você pode usar o AWS WAF para permitir e bloquear solicitações específicas.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/f77ea60c-1b34-4a77-9d58-304c1af1d548" alt="raiz" width="50%" style="float: left; margin-right: 10px;">

Suponha que a aplicação tenha recebido solicitações de rede mal-intencionadas de vários endereços IP. Você quer impedir que essas solicitações continuem a acessar seu aplicativo, mas também deseja garantir que usuários legítimos ainda possam acessá-lo. Você configura a ACL da web para permitir todas as solicitações, exceto aquelas dos endereços IP que você especificou.

Quando uma solicitação entra no AWS WAF, ele confere a lista de regras configurada na ACL da web. Se uma solicitação não for proveniente de um dos endereços IP bloqueados, ele permitirá o acesso à aplicação.

<img src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/84b3f50c-5ccf-45d0-a2ab-743c6613f125" alt="raiz" width="50%" style="float: left; margin-right: 10px;">

No entanto, se uma solicitação for proveniente de um dos endereços IP bloqueados que você especificou na ACL da web, o AWS WAF vai negar o acesso.

### Amazon Inspector

Suponha que os desenvolvedores da cafeteria estão desenvolvendo e testando um novo aplicativo para pedidos. Eles querem se certificar de que estão projetando o aplicativo de acordo com as práticas recomendadas de segurança. Contudo, eles têm vários outros aplicativos para desenvolver, por isso, não podem passar tempo demais fazendo avaliações manuais. Para fazer avaliações de segurança automatizadas, eles decidem usar o <a href="https://aws.amazon.com/pt/inspector/">AWS Inspector</a>

O Amazon Inspector ajuda a melhorar a segurança e a conformidade das aplicações executando avaliações de segurança automatizadas. Ele verifica os aplicativos quanto a vulnerabilidades de segurança e desvios das práticas recomendadas de segurança, como acesso aberto a instâncias do Amazon EC2 e instalações de versões de software vulneráveis. 

Depois que o Amazon Inspector faz uma avaliação, ele apresenta uma lista de descobertas de segurança. A lista prioriza por nível de gravidade, com uma descrição detalhada de cada problema de segurança e uma recomendação sobre como corrigi-lo. Contudo, a AWS não garante que seguir as recomendações feitas resolverá todos os possíveis problemas de segurança. Sob o modelo de responsabilidade compartilhada, os clientes são responsáveis pela segurança de ferramentas, aplicativos e processos executados nos serviços AWS.

### Amazon GuardDuty

O <a href="https://aws.amazon.com/pt/guardduty/">Amazon GuardDuty</a> é um serviço que realiza detecção inteligente de ameaças para sua infraestrutura e seus recursos AWS. Ele identifica ameaças monitorando continuamente a atividade da rede e o comportamento da conta no seu ambiente AWS.

<img width="840" alt="Txxw3jHbZVvj_mYb_vNMMzBy1e2a2jsnI" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/53865cc2-3681-4d6e-83b6-cdd9a429d94c">

Depois de habilitar o GuardDuty para sua conta AWS, ele começa a monitorar sua atividade de rede e conta. Você não precisa implantar ou gerenciar nenhum outro software de segurança. O GuardDuty analisa continuamente dados de várias fontes da AWS, incluindo logs de fluxo de VPC e logs de DNS. 

Se o GuardDuty detectar ameaças, você poderá analisar as descobertas detalhadas no console de gerenciamento da AWS. As descobertas incluem etapas recomendadas para a correção. Você também pode configurar as funções do AWS Lambda para executar as etapas de correção automaticamente em resposta às descobertas de segurança do GuardDuty.

#### Recursos adicionais

<a href="https://aws.amazon.com/pt/guardduty/" target="_blank">Segurança, identidade e conformidade na AWS</a><br>

<a href="https://d1.awsstatic.com/whitepapers/Security/Introduction_to_AWS_Security_Portuguese.pdf" target="_blank">Introdução à segurança da AWS</a><br>

<a href="https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Overview_Portuguese.pdf" target="_blank">Amazon Web Services: Visão geral de processos de segurança</a><br>

<a href="https://aws.amazon.com/pt/blogs/security/" target="_blank">Blog de segurança da AWS</a><br>

<a href="https://aws.amazon.com/pt/compliance/" target="_blank">Conformidade da AWS</a><br>

<a href="https://aws.amazon.com/pt/compliance/aws-compliance-stories/" target="_blank">Histórias de conformidade da AWS: segurança, identidade e conformidade</a><br>

<a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/best-practices.html" target="_blank">Práticas recomendadas de segurança no IAM</a>

#### Teste de conhecimento 

Qual afirmativa descreve melhor uma política do IAM?

<ul>
    <li>Um processo de autenticação que adiciona uma camada de proteção para sua conta AWS</li>
    <li>&#10004; Um documento que concede ou nega permissões para serviços e recursos AWS</li>
    <li>Uma identidade que você pode assumir para obter acesso temporário a permissões</li>
    <li>A identidade que é estabelecida quando você cria pela primeira vez uma conta AWS</li>
</ul>

A resposta correta é: Um documento que concede ou nega permissões para serviços e recursos AWS.

As políticas do IAM oferecem a flexibilidade de personalizar os níveis de acesso dos usuários aos recursos. Por exemplo, você pode permitir que os usuários acessem todos os buckets do Amazon S3 na conta AWS ou apenas um bucket específico.

As outras respostas estão incorretas porque:

A autenticação multifator (MFA) é um processo de autenticação que adiciona uma camada de proteção para sua conta AWS.

Um perfil do IAM é uma identidade que você pode assumir para obter acesso temporário às permissões.

A identidade do usuário-raiz é a identidade estabelecida quando você cria uma conta AWS pela primeira vez.

<a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/access_policies.html" target="_blank">Políticas e permissões no IAM</a>

Um funcionário precisa de acesso temporário para criar vários buckets do Amazon S3. Qual opção seria a melhor escolha para essa tarefa?

<ul>
    <li>Usuário-raiz da conta AWS</li>
    <li>Grupo do IAM</li>
    <li>&#10004; Função do IAM</li>
    <li>Política de controle de serviço (SCP)</li>
</ul>

A resposta correta é Perfil do IAM.

Um perfil do IAM é uma identidade que você pode assumir para obter acesso temporário a permissões. Quando alguém assume uma função do IAM, ele abandona todas as permissões que tinha em uma função anterior e assume as permissões da nova função. Os perfis do IAM são ideais para situações em que o acesso a serviços ou recursos precisa ser concedido temporariamente em vez de por longo prazo.

As outras respostas estão incorretas porque:

O usuário-raiz da conta AWS é estabelecido quando se cria uma conta AWS pela primeira vez. Como prática recomendada, não use o usuário-raiz para tarefas cotidianas.

Embora você possa associar políticas do IAM a um grupo do IAM, essa não seria a melhor opção para esse cenário porque o funcionário só precisa receber permissões temporárias.

As políticas de controle de serviço (SCPs) permitem que você controle de maneira centralizada as permissões para as contas em sua organização. Uma SCP não é a melhor opção para conceder permissões temporárias a um funcionário individual.

<a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles.html">Perfis do IAM</a>

Qual afirmativa melhor descreve o princípio de menor privilégio?

<ul>
    <li>Adicionar um usuário do IAM em pelo menos um grupo do IAM</li>
    <li>Verificar as permissões de um pacote em relação a uma lista de controle de acesso</li>
    <li>&#10004; Conceder apenas as permissões necessárias para executar tarefas específicas</li>
    <li>Executar um ataque de negação de serviço originado de pelo menos um dispositivo</li>
</ul>

Ao conceder permissões seguindo o princípio de menor privilégio, você impede que usuários ou perfis tenham mais permissões do que o necessário para executar tarefas específicas de trabalho. Por exemplo, os operadores de caixa da cafeteria devem ter acesso a elas. Como prática recomendada, conceda aos usuários e perfis do IAM um conjunto mínimo de permissões, depois conceda outras permissões se necessário.

<a href="https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/best-practices.html">Guia do usuário do IAM: Práticas recomendadas de segurança</a>

Qual serviço ajuda a proteger suas aplicações contra ataques distribuídos de negação de serviço (DDoS)?

<ul>
    <li>Amazon GuardDuty</li>
    <li>Amazon Inspector</li>
    <li>AWS Artifact</li>
    <li>&#10004; AWS Shield</li>
</ul>

À medida que o tráfego de rede ingressa em aplicações, o AWS Shield usa diversas técnicas de análise para detectar ataques DDoS potenciais em tempo real e mitigá-los automaticamente.


As outras respostas estão incorretas porque:

O Amazon GuardDuty é um serviço que realiza detecção inteligente de ameaças para sua infraestrutura e seus recursos da AWS. Ele identifica ameaças monitorando continuamente a atividade da rede e o comportamento da conta no ambiente AWS.

O Amazon Inspector verifica se as aplicações têm vulnerabilidades ou discrepâncias das práticas recomendadas de segurança, como acesso aberto a instâncias do Amazon EC2 e instalações de versões de software vulneráveis.

O AWS Artifact é um serviço que concede acesso sob demanda a relatórios de segurança e conformidade da AWS e contratos on-line selecionados.

<a href="https://aws.amazon.com/pt/shield/">AWS Shield</a>

Qual tarefa o AWS Key Management Service (AWS KMS) pode executar?

<ul>
    <li>Configurar uma autenticação multifator (MFA).</li>
    <li>Atualizar a senha do usuário-raiz da conta AWS.</li>
    <li>&check; Criar chaves de criptografia.</li>
    <li>Atribuir permissões a usuários e grupos.</li>
</ul>

O AWS Key Management Service (AWS KMS) permite que você execute operações de criptografia pelo uso de chaves de criptografia. Uma chave de criptografia é uma cadeia aleatória de dígitos usada para bloquear (criptografar) e desbloquear (descriptografar) dados. Você pode usar o AWS KMS para criar, gerenciar e usar chaves de criptografia. Você também pode controlar o uso de chaves em uma ampla gama de serviços e em suas aplicações.

As outras respostas estão incorretas porque:

Você pode configurar a autenticação multifator (MFA) no AWS Identity and Access Management (IAM).

Você pode atualizar a senha do usuário-raiz da conta AWS no Console de gerenciamento da AWS.

Você pode atribuir permissões a usuários e grupos no AWS Identity and Access Management (IAM).

<a href="https://aws.amazon.com/pt/kms/">AWS Key Management Service</a>

# Monitoramento e Análise

## Amazon CloudWatch

O <a href="https://aws.amazon.com/pt/cloudwatch/">Amazon CloudWatch</a> é um serviço da web que permite monitorar e gerenciar várias métricas e configurar ações de alarme de acordo com os dados dessas métricas.

O CloudWatch usa<a href="https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/working_with_metrics.html">métricas</a> para representar os pontos de dados para seus recursos. Os serviços AWS enviam as métricas ao CloudWatch. Em seguida, o CloudWatch usa essas métricas para criar automaticamente gráficos que mostram como o desempenho mudou ao longo do tempo. 

### Alarmes do CloudWatch

Com o CloudWatch, você pode criar <a href="https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/AlarmThatSendsEmail.html">alarmes</a> que vão executar ações automaticamente se o valor da métrica ultrapassar ou for inferior a um limite predefinido. 

Por exemplo, suponha que os desenvolvedores da sua empresa usem instâncias do Amazon EC2 para fins de desenvolvimento ou teste de aplicações. Se os desenvolvedores ocasionalmente se esquecerem de interromper as instâncias, as instâncias continuarão a ser executadas e incorrerão em cobranças. 

Nesse cenário, você pode criar um alarme do CloudWatch que interrompe automaticamente uma instância do Amazon EC2 quando a porcentagem de utilização da CPU permanecer abaixo de um determinado limite por um período específico. Ao configurar o alarme, você pode especificar se deseja receber uma notificação sempre que esse alarme for acionado.

<img width="700" alt="0ueohXDQwcNsM1XB_rLfuExSsSpuXOVqf" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/00397299-9e57-44f9-b18a-4844970eeb0c">

O recurso de <a href="https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html">painel</a> do CloudWatch permite que você acesse todas as métricas dos seus recursos em um único local. Por exemplo, você pode usar um painel do CloudWatch para monitorar a utilização da CPU de uma instância do Amazon EC2, o número total de solicitações feitas para um bucket do Amazon S3 e muito mais. Você pode até personalizar painéis separados para diferentes fins comerciais, aplicativos ou recursos.

### AWS CloudTrail

O <a href="https://aws.amazon.com/pt/cloudtrail/">AWS CloudTrail</a> registra as chamadas de API realizadas na sua conta. As informações gravadas são identidade do chamador da API, hora da chamada da API, endereço IP de origem do chamador da API e muito mais. Você pode pensar no CloudTrail como uma “trilha” (ou um log de ações) que alguém criou.

Lembre-se de que você pode usar chamadas de API para provisionar, gerenciar e configurar seus recursos da AWS. Com o CloudTrail, você pode visualizar um histórico completo de atividades do usuário e chamadas de API de seus aplicativos e recursos. 

Normalmente, os eventos são atualizados no CloudTrail dentro de 15 minutos após uma chamada de API. Você pode filtrar eventos especificando a hora e a data em que uma chamada de API ocorreu, o usuário que solicitou a ação, o tipo de recurso envolvido na chamada de API e muito mais.

#### Exemplo: evento do AWS CloudTrail

Suponha que o proprietário da cafeteria esteja navegando pela seção AWS Identity and Access Management (IAM) do Console de gerenciamento da AWS. Ele descobre que um novo usuário do IAM chamado Mary foi criado, mas não quem, quando ou qual método foi usado para criar o usuário.

Para responder a essas perguntas, o proprietário navega até o AWS CloudTrail.

![sdgsfjfd](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/76ff76cd-326d-48b8-a668-e0e67f72e498)

Na seção Histórico de eventos do CloudTrail, o proprietário aplica um filtro para exibir somente os eventos da ação da API “CreateUser” no IAM. O proprietário localiza o evento para a chamada de API que criou um usuário do IAM para Mary. Esse registro de evento mostra detalhes completos sobre o que ocorreu: 

em 1º de janeiro de 2020, às 9:00, o usuário do IAM John criou um novo usuário do IAM (Mary) no console de gerenciamento da AWS.

#### CloudTrail Insights

No CloudTrail, você também pode ativar o C<a href="https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/logging-insights-events-with-cloudtrail.html">eventos do Insights - AWS CloudTrail</a>
. Esse recurso opcional permite que o CloudTrail detecte automaticamente atividades de API incomuns em sua conta AWS. 

Por exemplo, o CloudTrail Insights pode detectar que mais instâncias do Amazon EC2 do que o normal foram iniciadas recentemente em sua conta. Em seguida, você pode revisar os detalhes completos do evento para determinar quais ações precisa executar a seguir.

#### Teste de conhecimento

Quais tarefas você pode executar usando o AWS CloudTrail? (Selecione DUAS opções.)

<ul>
    <li>Monitorar sua infraestrutura e seus recursos AWS em tempo real</li>
    <li>&#10004; Rastrear atividades do usuário e solicitações de API em toda a infraestrutura da AWS</li>
    <li>Exibir métricas e gráficos para monitorar o desempenho dos recursos</li>
    <li>Filtrar logs para auxiliar na análise operacional e na solução de problemas</li>
    <li>&#10004; Configurar ações automáticas e alertas em resposta a métricas</li>
</ul>

As outras respostas são tarefas que você pode executar no Amazon CloudWatch.

## AWS Trusted Advisor

O <a href="https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/">Amazon Trusted Advisor</a>  é um serviço da web que inspeciona seu ambiente AWS e faz recomendações em tempo real de acordo com as práticas recomendadas da AWS.

O Trusted Advisor compara as descobertas com as práticas recomendadas da AWS em cinco categorias: otimização de custos, desempenho, segurança, tolerância a falhas e limites de serviço. Para as verificações em cada categoria, o Trusted Advisor oferece uma lista de ações recomendadas e recursos adicionais para saber mais sobre as práticas recomendadas da AWS. 

As orientações feitas pelo AWS Trusted Advisor podem beneficiar sua empresa em todos os estágios da implantação. Por exemplo, você pode usar o AWS Trusted Advisor para ajudar enquanto cria fluxos de trabalho e desenvolve novas aplicações. Ou você pode também usá-lo enquanto faz melhorias contínuas em aplicações e recursos.

![dabgwrN](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/06c5d409-1f50-4b37-a5d3-80124ae8f27d)

Ao acessar o painel do Trusted Advisor no console de gerenciamento da AWS, você pode analisar as verificações concluídas para otimização de custos, desempenho, segurança, tolerância a falhas e limites de serviço.

Para cada categoria:

  <ul>
    <li>A marca de verificação verde indica o número de itens para os quais nenhum problema foi detectado.</li>
    <li>O triângulo laranja representa o número de investigações recomendadas.</li>
    <li>O círculo vermelho representa o número de ações recomendadas.</li>
  </ul>

  #### Recursos adicionais
  
<a href=“https://aws.amazon.com/pt/products/management-and-governance/”>Gerenciamento e governança na AWS</a> 
<a href=“https://aws.amazon.com/pt/cloudops/monitoring-and-observability/”>Monitoramento e observabilidade</a> 
<a href=“https://aws.amazon.com/pt/compliance/”>Configuração, conformidade e auditoria</a> 
<a href=“https://aws.amazon.com/pt/blogs/mt/”>Blog de gerenciamento e governança da AWS</a> 
<a href=“https://d1.awsstatic.com/whitepapers/aws-governance-at-scale.pdf”>Whitepaper: AWS Governance at Scale (Governança da AWS em escala)</a> 



#### Teste de conhecimento

Quais ações você pode executar usando o Amazon CloudWatch? (Selecione DUAS opções.)

<ul>
    <li><span>&#10004;</span> Monitorar a utilização e o desempenho de seus recursos</li>
    <li>Receber orientações em tempo real para melhorar seu ambiente AWS</li>
    <li>Comparar sua infraestrutura com as práticas recomendadas da AWS em cinco categorias</li>
    <li><span>&#10004;</span> Acessar métricas em um único painel</li>
    <li>Detectar automaticamente atividades da conta incomuns</li>
  </ul>

  As duas respostas corretas são:

Monitorar a utilização e o desempenho de recursos

Acessar métricas em um único painel

As outras respostas estão incorretas porque:

Receber recomendações em tempo real para melhorar o ambiente AWS pode ser feito pelo AWS Trusted Advisor.

Comparar a infraestrutura com as práticas recomendadas da AWS em cinco categorias pode ser feito pelo AWS Trusted Advisor.

Detectar automaticamente atividades da conta incomuns pode ser feito pelo AWS CloudTrail.

Qual serviço permite que você reveja a segurança de seus buckets do Amazon S3 verificando permissões de acesso aberto?

  <ul>
    <li>Amazon CloudWatch</li>
    <li>AWS CloudTrail</li>
    <li>&#10004; AWS Trusted Advisor</li>
    <li>Amazon GuardDuty</li>
  </ul>

  A resposta correta é AWS Trusted Advisor.

O AWS Trusted Advisor é um serviço da web que inspeciona o ambiente da AWS e faz recomendações em tempo real de acordo com as práticas recomendadas da AWS. A inspeção inclui verificações de segurança, como buckets do Amazon S3 com permissões de acesso aberto.

As outras respostas estão incorretas porque:

O Amazon CloudWatch é um serviço da web que permite monitorar e gerenciar várias métricas para os recursos que executam aplicações.

O AWS CloudTrail é um serviço da web que permite analisar detalhes das atividades do usuário e das chamadas de API que ocorreram em um ambiente AWS.

O Amazon GuardDuty é um serviço que realiza detecção inteligente de ameaças em um ambiente e recursos da AWS. Ele identifica ameaças monitorando continuamente a atividade da rede e o comportamento da conta no ambiente AWS.

Quais categorias estão inclusas no painel do AWS Trusted Advisor? (Selecione DUAS opções.)

 <ul>
    <li>Amazon CloudWatch</li>
    <li>&#10004; AWS CloudTrail</li>
    <li>AWS Trusted Advisor</li>
    <li>&#10004; Amazon GuardDuty </li>
  </ul>

As duas respostas corretas são:

Desempenho

Tolerância a falhas

O AWS Trusted Advisor inspeciona continuamente o ambiente AWS e faz recomendações de práticas recomendadas em cinco categorias: otimização de custos, desempenho, segurança, tolerância a falhas e limites de serviço.

# Definições de preços e Suporte

## Nível gratuito da AWS

Com o <a href="https://aws.amazon.com/pt/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all">nível gratuito da AWS</a>
, você começa a usar determinados serviços sem ter que se preocupar com o custo durante o período especificado. 

Três tipos de ofertas estão disponíveis: 

 <ul>
        <li>Serviços Sempre Gratuitos</li>
        <li>12 Meses Gratuitos</li>
        <li>Versões de Teste</li>
    </ul>

Verifique quais tipos de recursos estão incluídos em cada oferta de nível gratuito. 

<li>Sempre gratuito</li>

Essas ofertas não expiram e estão disponíveis para todos os clientes AWS.

Por exemplo, o AWS Lambda permite um milhão de solicitações gratuitas e até 3,2 milhões de segundos de tempo de computação por mês. O Amazon DynamoDB libera 25 GB de armazenamento gratuito por mês.

<li>12 meses gratuitos</li>

Essas ofertas são gratuitas por 12 meses após sua data de inscrição inicial na AWS.

Quantidades específicas de armazenamento do Amazon S3 Standard, limites para horas mensais de tempo de computação do Amazon EC2 e quantidades de transferência de dados do Amazon CloudFront para fora são alguns exemplos.  
<li>Versão de teste</li>

As versões de teste gratuitas de curto prazo começam na data em que você ativa determinado serviço. A duração de cada teste pode variar de acordo com o número de dias ou a quantidade de uso do serviço.

Por exemplo, o Amazon Inspector oferece uma versão gratuita de 90 dias. O Amazon Lightsail (um serviço que permite que você execute servidores virtuais privados) oferece 750 horas de uso gratuitas em um período de 30 dias.

#### Teste de conhecimento 

O nível gratuito da AWS inclui ofertas que ficam disponíveis para novos clientes AWS por um determinado período após a data de cadastro da AWS. Qual é a duração deste período?

<ul>
    <li>3 meses</li>
    <li>6 meses</li>
    <li>9 meses</li>
    <li>&#10004; 12 meses</li>
</ul>

A resposta correta é 12 meses.

O nível gratuito da AWS consiste em três ofertas que permitem que os clientes usem os serviços da AWS sem cobranças: sempre gratuito, 12 meses grátis e versão de teste.

Por 12 meses depois de se cadastrar pela primeira vez em uma conta AWS, você pode aproveitar as ofertas da categoria 12 meses gratuitos. Exemplos de ofertas nesta categoria incluem quantidades específicas de armazenamento do Amazon S3 Standard, limites para horas mensais de tempo de computação do Amazon EC2 e quantidades de transferência de dados do Amazon CloudFront para fora.

## Conceitos de definição de preço da AWS

### Como funciona a definição de preço da AWS

A AWS oferece diversos serviços de computação em nuvem com modelos de pagamento conforme o uso. 

Para saber mais sobre como a definição de preço da AWS funciona, expanda cada uma das três categorias a seguir.

#### Pague somente pelo que usar.

Para cada serviço, você paga exatamente a quantidade de recursos que realmente usa, sem exigir contratos de longo prazo ou licenciamento complexo.

#### Pague menos ao fazer reserva.

Alguns serviços oferecem opções de reserva com desconto significativo em comparação com as definições de preços da instância sob demanda.

Por exemplo, suponha que sua empresa use instâncias do Amazon EC2 para uma carga de trabalho que precisa ser executada continuamente. Você pode optar por executar essa carga de trabalho no Amazon EC2 Instance Savings Plans, pois o plano permite uma economia de até 72% em relação à capacidade equivalente da instância sob demanda.

#### Pague menos com descontos baseados em volume, quando usar mais.

Alguns serviços oferecem definição de preço em camadas, portanto, o custo por unidade é incrementalmente menor com o aumento do uso.

Por exemplo, quanto mais espaço de armazenamento do Amazon S3 você usar, menos pagará por GB.

### Calculadora de Preços da AWS

A <a href="https://calculator.aws/#/">Calculadora de Preços da AWS</a> permite explorar os serviços da AWS e gerar uma estimativa de custo de seus casos de uso na AWS. Você pode organizar as suas estimativas da AWS por grupos que definir. Um grupo pode refletir como sua empresa está organizada, por exemplo, realizar estimativas por centro de custo.

Depois de criar uma estimativa, você pode salvá-la e gerar um link para compartilhá-la com outras pessoas.

![8mMbFUZXWcZ0Xsgw_X5vopv9JVIgw0bG3](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/ccd38f14-c1ec-4cf1-bf0a-d8276d2e9af6)

Suponha que sua empresa esteja interessada em usar o Amazon EC2. No entanto, você ainda não tem certeza de qual Região AWS ou tipo de instância seria o mais econômico para seu caso de uso. Na Calculadora de Preços da AWS, você pode inserir detalhes como o tipo de sistema operacional necessário, requisitos de memória e requisitos de entrada/saída (E/S). Usando a Calculadora de Preços da AWS, você pode ver uma comparação estimada de diferentes tipos de instância do EC2 nas Regiões AWS.

### Exemplos de definição de preços da AWS

Esta seção apresenta alguns exemplos de definição de preço dos serviços AWS. 

#### AWS Lambda

Para saber mais sobre a definição de <a href="https://aws.amazon.com/pt/lambda/pricing/">Preços do AWS Lambda</a>.

#### Definição de preço do aws lambda

Para o AWS Lambda, a cobrança é feita com base no número de solicitações das funções e no tempo necessário para serem executadas.

O AWS Lambda permite um milhão de solicitações gratuitas e até 3,2 milhões de segundos de tempo de computação por mês.

Você pode economizar nos custos do AWS Lambda cadastrando-se em um Compute Savings Plan. Um Compute Savings Plan oferece custos de computação mais baixos em troca do compromisso com uma quantidade consistente de uso durante um período de um ou três anos. Este é um exemplo de “reserve e pague menos”. 

#### Exemplo de definição de preço

Se você usou o AWS Lambda em várias Regiões AWS, é possível visualizar as cobranças discriminadas por Região na sua fatura. 

Pegue um exemplo de fatura em que todo o uso do AWS Lambda ocorre na Região Virgínia do Norte. A fatura lista encargos separados para o número de solicitações de funções e sua duração. Havia 680 solicitações para uma função, e a função foi executada por cerca de 255 segundos.

Tanto o número de solicitações quanto a duração total das solicitações neste exemplo estão abaixo dos limites no nível gratuito da AWS, portanto, o proprietário da conta não precisaria pagar por qualquer uso do AWS Lambda neste mês.

<img width="840" alt="I8qP88Qr6GDywD7T_vBX82XA7yd3QXpgS" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/b335e18f-19fd-4b55-9a60-5f8bdf98d55d">

#### Amazon EC2

Para saber mais sobre a definição de <a href="https://aws.amazon.com/pt/ec2/pricing/">Preços do Amazon EC2</a>

#### Definição de preço do EC2

Com o Amazon EC2, você paga apenas pelo tempo de computação que usar enquanto suas instâncias estão em execução.

Para algumas cargas de trabalho, você pode reduzir significativamente os custos do Amazon EC2 usando instâncias spot. Por exemplo, suponha que você esteja executando um trabalho de processamento em lote que pode ser interrompido. O uso de uma instância spot economizaria até 90% dos custos e, ao mesmo tempo, atenderia aos requisitos de disponibilidade de sua carga de trabalho.

Você pode economizar ainda mais no Amazon EC2 considerando o Savings Plans e as instâncias reservadas.

#### Exemplo de definição de preço

Pegue uma instância do Amazon EC2 implantada na Região Virgínia do Norte, por exemplo. As cobranças de serviço incluem detalhes para os seguintes itens:

 <ul>
        <li>Uma instância do Amazon EC2 que está em execução por aproximadamente 107 horas</li>
        <li>Cerca de 11 GB de espaço de armazenamento do Amazon EBS provisionado no mês</li>
        <li>Um Application Load Balancer usado por 268 horas</li>
    </ul>

Neste exemplo, nem todos os valores de uso estão abaixo dos limites no nível gratuito da AWS, portanto, o proprietário da conta não teria que pagar por nenhum uso do Amazon EC2 este mês.

<img width="840" alt="6G6S8fLeZUjahA2d_P8TO97KQwkScisje" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/c5896faa-688a-4166-9983-cbecc47e8341">

#### Amazon S3

Para saber mais sobre a definição de <a href="https://aws.amazon.com/pt/s3/pricing/">Preços do Amazon S3</a>

#### Definição de preço do S3

<ul>
        <li><strong>Armazenamento:</strong> você paga apenas pelo armazenamento usado. A taxa de armazenamento de objetos nos buckets do Amazon S3 é cobrada com base nos tamanhos, storage classes e quanto tempo você armazenou cada objeto durante o mês.</li>
        <li><strong>Solicitações e recuperações de dados:</strong> você paga por solicitações feitas aos seus objetos e buckets do Amazon S3. Por exemplo, suponha que você esteja armazenando arquivos de fotos em buckets do Amazon S3 e hospedando-os em um site. Toda vez que um visitante solicita o site que contém esses arquivos de fotos, isso conta para solicitações que você precisa pagar.</li>
        <li><strong>Transferência de dados:</strong> não há custo para transferir dados entre diferentes buckets do Amazon S3 ou do Amazon S3 para outros serviços dentro da mesma Região AWS. No entanto, você paga pelos dados que transfere para dentro e para fora do Amazon S3, com algumas exceções. Não há custo para os dados transferidos para o Amazon S3 da internet ou para o Amazon CloudFront. Também não há custo para os dados transferidos para uma instância do Amazon EC2 na mesma Região AWS que o bucket do Amazon S3.</li>
        <li><strong>Gerenciamento e replicação:</strong> você paga pelos recursos de gerenciamento de armazenamento que ativou nos buckets do Amazon S3 da sua conta. Esses recursos incluem inventário, análise e marcação de objetos do Amazon S3.</li>
    </ul>

#### Exemplo de definição de preço

Vamos dar uma olhada na conta da AWS que usou o Amazon S3 em duas Regiões: Virgínia do Norte e Ohio. Em cada Região, as cobranças de cada item baseiam-se nos seguintes fatores:

  <ul>
        <li>Número de solicitações para adicionar ou copiar objetos em um bucket (PUT, COPY, POST ou LIST).</li>
        <li>Número de solicitações para recuperar objetos de um bucket (GET).</li>
        <li>Quantidade de espaço de armazenamento usada.</li>
    </ul>
    
 Região Virgínia do Norte tem dois níveis do Amazon S3: Nível 1 e Nível 2. 
 
<ul>
        <li>No Nível 1, havia 185 solicitações para adicionar ou copiar objetos em um bucket. (Não há solicitações para recuperar objetos de um bucket.) 0,159 GB de espaço de armazenamento foi usado.</li>
        <li>No Nível 2, havia 923 solicitações para recuperar objetos de um bucket. (Não havia solicitações para adicionar ou copiar objetos para um bucket.)</li>
    </ul>
A Região de Ohio tem um nível do Amazon S3: Nível 2. Havia quatro solicitações para recuperar objetos de um bucket e 0,000001 GB de espaço de armazenamento foi usado. Não havia solicitações para adicionar ou copiar objetos para um bucket.

Todo o uso do Amazon S3 neste exemplo está abaixo dos limites de nível gratuito da AWS, portanto, o proprietário da conta não teria que pagar por qualquer uso do Amazon S3 neste mês.
    
<img width="840" alt="KaUCTikrYqmoEhU3_GC9mP13u89WV16--" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/78b146f9-03f0-44d5-9e84-a11680148573">

## Painel de cobrança

Use o painel <a href="https://docs.aws.amazon.com/pt_br/awsaccountbilling/latest/aboutv2/billing-what-is.html">Faturamento e Gerenciamento de Custos da AWS</a> para pagar sua fatura da AWS, monitorar seu uso e analisar e controlar seus custos.

 <ul>
        <li>Compare o saldo atual do mês acumulado com o mês anterior e obtenha uma previsão do próximo mês com base no uso atual.</li>
        <li>Visualize os gastos do mês acumulado por serviço.</li>
        <li>Visualize o uso do nível gratuito por serviço.</li>
        <li>Acesse o Cost Explorer e crie orçamentos.</li>
        <li>Adquira e gerencie o Savings Plans.</li>
        <li>Publique o <a href="https://docs.aws.amazon.com/pt_br/cur/latest/userguide/what-is-cur.html">AWS relatório de uso e custo</a></li>
    </ul>

## Cobrança consolidada

Em um módulo anterior, você aprendeu sobre o AWS Organizations, um serviço que permite gerenciar múltiplas contas AWS em um local central. O AWS Organizations também oferece a opção de <a href="https://docs.aws.amazon.com/pt_br/awsaccountbilling/latest/aboutv2/consolidated-billing.html">cobrança consolidada</a>

O recurso de cobrança consolidada do AWS Organizations permite que você receba uma única fatura para todas as contas AWS na sua organização. Ao consolidar, você pode rastrear facilmente os custos combinados de todas as contas vinculadas em sua organização. O número máximo de contas-padrão permitido para uma organização é quatro, mas você pode entrar em contato com o AWS Support para aumentar sua cota, se necessário.

Na sua fatura mensal, você pode ver os encargos discriminados incorridos por cada conta. Isso permite que você tenha maior transparência nas contas da sua organização, mantendo a conveniência de receber uma única fatura mensal.

Outro benefício da cobrança consolidada é a capacidade de compartilhar preços de desconto por volume, Savings Plans e instâncias reservadas nas contas da sua organização. Por exemplo, uma conta pode não ter uso mensal suficiente para se qualificar para preços com desconto. No entanto, quando várias contas são combinadas, o uso agregado pode resultar em um benefício que se aplica a todas as contas na organização.

Para ver um exemplo de cobrança consolidada:

<img width="840" alt="XQIHxinsinArU8bF_lIhutQzs_0HYprXC" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/759e7f8a-9143-4155-bd98-33274448ece8">

Suponha que você seja o líder de negócios que supervisiona a cobrança da sua empresa na AWS. 

Sua empresa tem três contas AWS usadas para departamentos separados. Neste exemplo, a conta 1 deve USD 19,64, a conta 2 deve USD 19,96 e a conta 3 deve USD 20,06. Em vez de pagar a fatura mensal de cada local separadamente, você decide criar uma organização e adicionar as três contas. 

Você gerencia a organização pela conta principal.

<img width="840" alt="OweSR53l2eQuPRUX_XkhkbARL6x-vwwoh" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/18fdfed4-2409-4212-b4ca-74b5e88cba3d">

Continuando o exemplo, todo mês a AWS cobra da sua conta pagadora principal por todas as contas vinculadas em uma fatura consolidada. Com a conta principal, você também pode obter um relatório de custos detalhado para cada conta vinculada. 

A fatura consolidada mensal também inclui os custos de uso da conta incorridos pela conta principal. Nesse caso, a conta principal incorreu em USD 14,14. Esse custo não é um encargo premium por ter uma conta principal. 

A fatura consolidada mostra os custos associados a qualquer ação da conta principal (como armazenar arquivos no Amazon S3 ou executar instâncias do Amazon EC2). O total cobrado na conta pagadora, incluindo a conta principal e as contas de um a três, é de USD 73,80. 

<img width="656" alt="cI6v-Cojs7HqLJtd_Up_BrZZrDs-fStwa" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/38a8eb6b-2bd3-4c96-a20e-c65ad318be75">

Com a cobrança consolidada, também é possível compartilhar descontos por volume entre contas. 

Alguns serviços da AWS, como o Amazon S3, oferecem preços com descontos por volume, resultando em preços mais baixos se você usar cada vez mais o serviço. No Amazon S3, depois que os clientes transferiram 10 TB de dados em um mês, eles pagam um preço de transferência por GB menor para os próximos 40 TB de dados transferidos. 

Neste exemplo, há três contas AWS separadas que transferiram diferentes quantidades de dados no Amazon S3 durante o mês atual: 

 <ul>
        <li>A conta 1 transferiu 2 TB de dados.</li>
        <li>A conta 2 transferiu 5 TB de dados.</li>
        <li>A conta 3 transferiu 7 TB de dados.</li>
    </ul>

Como nenhuma conta única ultrapassou o limite de 10 TB, nenhuma delas é elegível para o preço de transferência mais baixo por GB para os próximos 40 TB de dados transferidos.

<img width="840" alt="Ih5mYKf8KkDxBkCj_HF23i-vUYM2QKEll" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/35d718cf-735f-45e5-8d85-99ed17b3476f">

Agora, suponha que essas três contas separadas sejam reunidas como contas vinculadas em uma única organização da AWS, de acordo com a cobrança consolidada.

Quando o uso do Amazon S3 das três contas vinculadas é combinado (2+5+7), isso resulta em uma quantidade combinada de transferência de dados de 14 TB. Isso excede o limite de 10 TB. 

Com a cobrança consolidada, a AWS combina o uso de todas as contas para determinar quais camadas de definição de preço por volume serão aplicadas, oferecendo um preço geral inferior sempre que possível. Em seguida, a AWS aloca uma parte do desconto por volume geral para cada conta vinculada com base no uso da conta. 

Neste exemplo, a Conta 3 receberia uma parte maior do desconto total por volume porque, com 7 TB, ela transferiu mais dados do que a Conta 1 (com 2 TB) e a Conta 2 (com 5 TB).

## AWS Budgets

No <a href="https://aws.amazon.com/pt/aws-cost-management/aws-budgets/">AWS Budgets</a>, você pode criar orçamentos para planejar o uso do serviço, os custos de serviço e as reservas de instâncias.

As informações do AWS Budgets são atualizadas três vezes por dia. Isso ajuda você a definir com precisão a proximidade entre seu uso e os valores orçados ou limites de nível gratuito da AWS.

No AWS Budgets, você também pode definir alertas personalizados para quando seu uso exceder (ou estiver prestes a exceder) o valor orçado.

### Exemplo: AWS Budgets

Suponha que você tenha definido um orçamento para o Amazon EC2. Você deseja garantir que o uso do Amazon EC2 pela sua empresa não exceda USD 200 por mês. 

No AWS Budgets, você pode definir um orçamento personalizado para notificação quando o uso atingir metade desse valor (USD 100). Essa configuração permite que você receba um alerta e decida como deseja prosseguir com o uso contínuo do Amazon EC2.

Para saber mais sobre o AWS Budgets, clique em cada marcador.
    
![sdo](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/4f1d3729-a673-4ea8-9837-b73bd507a0c5)

## AWS Cost Explorer

O <a href="https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/">AWS Cost Explorer</a> é uma ferramenta que permite visualizar, interpretar e gerenciar seus custos e uso da AWS ao longo do tempo.

O AWS Cost Explorer inclui um relatório-padrão dos custos e do uso dos cinco principais serviços da AWS de acúmulo de custos. Você pode aplicar filtros e grupos personalizados para analisar seus dados. Por exemplo, você pode exibir o uso de recursos no nível por hora.

#### Exemplo: AWS Cost Explorer

<img width="529" alt="f_LP23hs96z_mx6z_pS6DLACY5OOiDZZb" src="https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/674b67f0-656e-4315-b1a7-6a55ac23e15c">

Esse exemplo de painel do AWS Cost Explorer exibe custos mensais para instâncias do Amazon EC2 em um período de seis meses. A barra de cada mês separa os custos de diferentes tipos de instâncias do Amazon EC2 (como t2.micro ou m3.large). 

Ao analisar os custos da AWS ao longo do tempo, você pode tomar decisões informadas sobre custos futuros e como planejar seus orçamentos.

## AWS Support

A AWS oferece quatro <a href="https://aws.amazon.com/pt/premiumsupport/plans/">planos de suporte</a> diferentes para ajudar você a solucionar problemas, reduzir custos e usar os serviços da AWS de maneira eficiente. 

Você pode escolher entre os seguintes planos do Support para atender às necessidades de sua empresa: 
    
 <ul>
        <li>Basic</li>
        <li>Desenvolvedor</li>
        <li>Empresarial</li>
        <li>Empresarial Rápido</li>
        <li>Empresarial de Grande Porte</li>
    </ul>

## Basic Support

O Basic Support é gratuito para todos os clientes da AWS. Inclui acesso a whitepapers, documentação e comunidades de suporte. Com o Basic Support, você também pode entrar em contato com a AWS para tratar de questões de cobrança e aumento do limite de serviço

Com ele, você tem acesso a uma seleção limitada de verificações do AWS Trusted Advisor. Além disso, você pode usar o AWS Personal Health Dashboard, uma ferramenta com alertas e orientações de correção quando a AWS enfrenta eventos que podem afetar você. 

Se a sua empresa precisa de suporte além do nível Basic, é possível adquirir o Support Desenvolvedor, Empresarial, Empresarial Rápido e Empresarial de Grande Porte.

## Support Desenvolvedor, Empresarial, Empresarial Rápido e Empresarial de Grande Porte

Os planos do Support Desenvolvedor, Empresarial, Empresarial Rápido e Empresarial de Grande Porte têm todos os benefícios do Support Basic, além de poder abrir um número irrestrito de casos de suporte técnico. Esses planos do Support têm pagamento mensal e não exigem contratos de longo prazo.

As informações deste curso destacam apenas uma alguns detalhes para cada plano do Support. Uma visão geral completa do que faz parte de cada plano de Support, incluindo a definição de preço de cada plano, está disponível no <a href="https://aws.amazon.com/pt/premiumsupport/plans/">Planos do AWS Support</a>

Em geral, para definição de preço, o plano Desenvolvedor tem o menor custo, os planos Empresarial e Empresarial Rápido são intermediários e o plano Empresarial de Grande Porte tem o custo mais alto.

Para saber mais sobre os planos do AWS Support

#### Support do Desenvolvedor

Os clientes com um plano Desenvolvedor do Support têm acesso a recursos como:

<ul>
        <li>Orientação de práticas recomendadas</li>
        <li>Ferramentas de diagnóstico do lado do cliente</li>
        <li>Suporte à arquitetura de blocos fundamentais, que consiste em orientações sobre como usar as ofertas, recursos e serviços da AWS combinados</li>
    </ul>

Por exemplo, suponha que sua empresa esteja explorando os serviços da AWS. Você já ouviu falar sobre alguns serviços diferentes da AWS. No entanto, você não tem certeza de como usá-los combinados para criar aplicativos que possam atender às necessidades de sua empresa. Nesse cenário, o suporte à arquitetura de componentes fundamentais incluído no plano de suporte Developer pode ajudar você a identificar oportunidades para combinar serviços e recursos específicos.

#### Support Empresarial

Os clientes com um plano Empresarial do Support têm acesso a recursos adicionais, incluindo: 

<ul>
        <li>Orientação de caso de uso para identificar ofertas, recursos e serviços da AWS que podem atender melhor às suas necessidades específicas</li>
        <li>Todas as verificações do AWS Trusted Advisor</li>
        <li>Suporte limitado para software de terceiros, como sistemas operacionais comuns e componentes de pilha de aplicações</li>
    </ul>

Suponha que sua empresa tenha o plano Empresarial do Support e queira instalar um sistema operacional de terceiros comum em suas instâncias do Amazon EC2. Você pode entrar em contato com o AWS Support para obter assistência com a instalação, configuração e solução de problemas do sistema operacional. Para tópicos avançados, como otimizar o desempenho, usar scripts personalizados ou resolver problemas de segurança, pode ser necessário entrar em contato diretamente com o provedor de software de terceiros.  

#### Support Empresarial Rápido

Em novembro de 2021, a AWS abriu inscrições no plano Suporte AWS Empresarial Rápido. Além de todos os recursos incluídos nos planos Basic, Desenvolvedor e Empresarial do Support, os clientes com um plano Empresarial Rápido do Support têm acesso a:

 <ul>
        <li>Um grupo de Technical Account Managers para orientar proativamente e coordenar o acesso a programas e especialistas da AWS</li>
        <li>A Oficina de otimização de custos (uma por ano)</li>
        <li>Uma equipe de suporte do Concierge para cobrança e assistência à conta</li>
        <li>Ferramentas para monitorar custos e desempenho por meio do Trusted Advisor e do painel/API Health</li>
    </ul>

 O plano Empresarial Rápido do Support também concede acesso a um conjunto específico de serviços de suporte proativo, que são fornecidos por um grupo de Technical Account Managers

  <ul>
        <li>Revisão consultiva e orientação de arquitetura (uma por ano)</li>
        <li>Suporte de gerenciamento de eventos de infraestrutura (uma por ano)</li>
        <li>Fluxos de trabalho de automação de suporte</li>
        <li>30 minutos ou menos tempo de resposta para problemas críticos de negócios</li>
    </ul>

#### Support Empresarial de Grande Porte

Além de todos os recursos incluídos nos planos de suporte Basic, Desenvolvedor, Empresarial e Empresarial Rápido, os clientes com Support Empresarial de Grande Porte têm acesso a:

  <ul>
        <li>Um Technical Account Manager designado para realizar orientação proativa e coordenar o acesso a programas e especialistas da AWS</li>
        <li>Uma equipe de suporte Concierge para cobrança e assistência à conta</li>
        <li>Análises de operações e ferramentas para monitorar o health</li>
        <li>Dias de treinamento e jogos para impulsionar a inovação</li>
        <li>Ferramentas para monitorar custos e desempenho por meio do Trusted Advisor e do painel/API Health</li>
    </ul>

O plano Empresarial de Grande Porte também concede acesso total a serviços proativos, fornecidos por um Technical Account Manager designado:

<ul>
        <li>Revisão consultiva e orientação de arquitetura</li>
        <li>Suporte de gerenciamento de eventos de infraestrutura</li>
        <li>Oficina e ferramentas de otimização de custos</li>
        <li>Suporte a fluxos de trabalho de automação</li>
        <li>Tempo de resposta de 15 minutos ou menos para problemas críticos de negócios</li>
</ul>

#### Technical Account Manager (TAM)

Os planos Empresarial Rápido e Empresarial de Grande Porte do Support inclui acesso a um Technical Account Manager (TAM).

O TAM será seu principal ponto de contato com a AWS. Se sua empresa assina o Support Empresarial de Grande Porte ou Empresarial Rápido, o TAM educa, capacita e desenvolve sua jornada para a nuvem em toda a gama de serviços da AWS. Os TAMs prestam orientação especializada em engenharia, ajudam você a projetar soluções que integram com eficiência os serviços da AWS, auxiliam com arquiteturas econômicas e resilientes e concedem acesso direto aos programas da AWS e a uma ampla comunidade de especialistas.

Por exemplo, suponha que você tenha interesse em desenvolver uma aplicação que use vários serviços da AWS juntos. O TAM pode orientar a usar melhor os serviços em conjunto. Ele consegue isso ao mesmo tempo em que se alinha com as necessidades específicas que sua empresa espera atender com o novo aplicativo.

#### Teste de conhecimento 

Qual plano do Support inclui todas as verificações do AWS Trusted Advisor pelo menor custo?

 <ul>
        <li>Basic</li>
        <li>Developer</li>
        <li>&#10004;Business</li>
        <li>Empresarial de Grande Porte</li>
    </ul>

 Somente os planos Empresarial, Empresarial Rápido e Empresarial de Grande Porte do Support têm todas as verificações do AWS Trusted Advisor. Desses três planos do Support, o plano Empresarial tem um custo mais baixo.

<a href="https://aws.amazon.com/pt/premiumsupport/plans/">Planos do AWS Support</a>

## AWS Marketplace

O <a href="https://aws.amazon.com/marketplace/">AWS Marketplace</a> é um catálogo digital com milhares de ofertas de software de provedores independentes de software. Você pode usar o AWS Marketplace para encontrar, testar e comprar software que pode ser executado na AWS. 

Para cada oferta no AWS Marketplace, você pode acessar informações detalhadas sobre opções de definição de preço, suporte disponível e avaliações de outros clientes AWS.

Você também pode explorar soluções de software por setor e caso de uso. Por exemplo, suponha que sua empresa atue no setor de saúde. No AWS Marketplace, você pode analisar casos de uso que o software ajuda a resolver, como implementar soluções para proteger prontuários de pacientes, ou usar modelos de machine learning para analisar o histórico médico de um paciente e prever possíveis riscos para a saúde.

 ### Categorias do AWS Marketplace

 ![H4Gxj6bGSLSnk7Ws_Gv4r6hYBhBT7A3z2](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/dd58c00d-4cb7-40b5-b8c4-deba5fcdc63b)

O AWS Marketplace oferece produtos em várias categorias, como Software de infraestrutura, DevOps, Produtos de dados, Serviços profissionais, Aplicações de negócios, Machine Learning, Indústrias e Internet das Coisas (IoT).

Dentro de cada categoria, você pode restringir sua pesquisa navegando pelas listas de produtos em subcategorias. Por exemplo, as subcategorias na categoria DevOps incluem áreas como Desenvolvimento de aplicações, Monitoramento e Teste.

<ul>
  <li><a href="https://aws.amazon.com/pt/pricing/">Definição de preços da AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/free/">Nível gratuito da AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/aws-cost-management/">Gerenciamento de custos da AWS</a></li>
  <li><a href="https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/abstract-and-introduction.html">Whitepaper: How AWS Pricing Works (Como funciona a definição de preço da AWS)</a></li>
  <li><a href="https://d1.awsstatic.com/whitepapers/introduction-to-aws-cloud-economics-final.pdf">Whitepaper: Introduction to AWS Economics (Introdução à economia da AWS)</a></li>
  <li><a href="https://aws.amazon.com/pt/premiumsupport/">AWS Support</a></li>
  <li><a href="https://aws.amazon.com/pt/premiumsupport/knowledge-center/">AWS Knowledge Center</a></li>
</ul>

### Teste de conhecimento

  <ul>
        <li>Analisar o custo em que seu uso previsto da AWS incorrerá até o final do mês.</li>
        <li>Criar uma estimativa de custo para seus casos de uso na AWS.</li>
        <li>&#10004;Combinar o uso entre contas para obter descontos de preços por volume.</li>
        <li>Visualizar e gerenciar os custos e o uso da AWS ao longo do tempo.</li>
    </ul>

 As outras respostas estão incorretas porque:

Reveja quanto seu uso previsto da AWS incorrerá até o final do mês. Você pode executar essa ação no AWS Budgets.

Crie uma estimativa para o custo de seus casos de uso na AWS. Você pode executar essa ação na Calculadora de Preços da AWS.

Visualize e gerencie seus custos e uso da AWS ao longo do tempo: você pode executar essa ação no AWS Cost Explorer.

Qual ferramenta de definição de preço é usada para visualizar, entender e gerenciar o custo e o uso da AWS ao longo do tempo?

   <ul>
       <li>Calculadora de Preços da AWS</li>  
        <li> AWS Budgets </li>
        <li>&#10004; AWS Cost Explorer </li>
        <li> Nível gratuito da AWS </li>
    </ul>

O AWS Cost Explorer inclui um relatório-padrão dos custos e do uso dos cinco serviços da AWS mais econômicos. Você pode aplicar filtros e grupos personalizados para analisar seus dados. Por exemplo, você pode exibir o uso de recursos no nível por hora.

As outras respostas estão incorretas porque:

A Calculadora de Preços da AWS permite que você crie uma estimativa para o custo de seus casos de uso na AWS.

O AWS Budgets permite que você crie orçamentos para planejar o uso e os custos do serviço e as reservas de instâncias. No AWS Budgets, você também poderá definir alertas personalizados quando seu uso exceder (ou estiver prestes a exceder) o valor orçado.

O nível gratuito da AWS é um programa que consiste em três ofertas para que os clientes usem os serviços da AWS sem incorrer em custos: sempre gratuito, 12 meses grátis e versão de teste.    

Qual ferramenta de preços permite receber alertas quando o uso do serviço excede um limite que você definiu?

 <ul>
    <li>Painel de cobrança no console de gerenciamento da AWS</li>
    <li>&#10004; AWS Budgets</li>
    <li>Nível gratuito da AWS</li>
    <li>AWS Cost Explorer</li>
  </ul>

No AWS Budgets, você pode definir alertas personalizados que notificam quando o uso do serviço exceder (ou estiver prestes a exceder) o valor que você planejou.

Seu orçamento pode ser baseado em custos ou uso. Por exemplo, você pode definir um alerta que o notificará quando você tiver incorrido USD 100,00 de custos no Amazon EC2 ou 500.000 solicitações no AWS Lambda.

As outras respostas estão incorretas porque:

No painel de cobrança do console de gerenciamento da AWS, você pode visualizar detalhes em sua fatura da AWS, como custos de serviço por Região, gastos do mês até o momento e muito mais. No entanto, você não pode definir alertas no painel de cobrança.

O nível gratuito da AWS é um programa que consiste em três ofertas para que os clientes usem os serviços da AWS sem incorrer em custos: sempre gratuito, 12 meses grátis e versão de teste.

O AWS Cost Explorer é uma ferramenta que permite visualizar, interpretar e gerenciar o custo e o uso da AWS ao longo do tempo.

Sua empresa deseja ter suporte de um technical account manager (TAM) da AWS. Qual plano de suporte você deve escolher?

 <ul>
    <li>Desenvolvedor</li>
    <li>&#10004; Empresarial de Grande Porte</li>
    <li>Basic</li>
    <li>Empresarial</li>
  </ul>

Um Technical Account Manager (TAM) está disponível apenas para clientes da AWS com um plano Empresarial Rápido e Empresarial de Grande Porte do Support. Um TAM oferece orientação, revisões de arquitetura e comunicação contínua com sua empresa enquanto você planeja, implanta e otimiza suas aplicações.

Qual serviço ou recurso é usado para encontrar software de terceiros que pode ser executado na AWS?

  <ul>
    <li>&#10004; AWS Marketplace</li>
    <li>Nível gratuito da AWS</li>
    <li>AWS Support</li>
    <li>Painel de cobrança no console de gerenciamento da AWS</li>
  </ul>

  O AWS Marketplace é um catálogo digital com milhares de ofertas de software de provedores independentes de software. Você pode usar o AWS Marketplace para encontrar, testar e comprar software que pode ser executado na AWS.

As outras respostas estão incorretas porque:

O nível gratuito da AWS consiste em ofertas para que os clientes usem os serviços da AWS sem incorrer em custos. Essas ofertas estão relacionadas aos serviços da AWS, não a software de terceiros que podem ser usados na AWS.

O AWS Support é um recurso que pode responder a perguntas sobre as práticas recomendadas, ajudar na solução de problemas, ajudar a identificar maneiras de otimizar o uso dos serviços da AWS e assim por diante.

Você pode usar o painel de cobrança no console de gerenciamento da AWS para visualizar detalhes como custos de serviço por Região, os principais serviços sendo usados por sua conta e custos de cobrança previstos. No painel de cobrança, você também pode acessar outras ferramentas de cobrança da AWS, como o AWS Cost Explorer, o AWS Budgets e os relatórios do AWS Budgets.
  
# Migração e Inovação

## AWS Cloud Adoption Framework (AWS CAF)

### Seis perspectivas fundamentais do Cloud Adoption Framework

No nível mais alto, o <a href="https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf">AWS Cloud Adoption Framework</a> organiza orientações em seis áreas de foco chamadas perspectivas. Cada perspectiva aborda responsabilidades distintas. O processo de planejamento ajuda as pessoas certas em toda a organização a se prepararem para as mudanças futuras.

Em geral, as perspectivas de negócio, pessoas e governança se concentram nos recursos comerciais, enquanto as perspectivas de plataforma, segurança e operações se concentram em capacidades técnicas.

Para saber mais sobre o AWS CAF, expanda cada uma das seis categorias a seguir.

#### Perspectiva de negócio

A perspectiva de negócio garante que a TI esteja alinhada às necessidades de negócio e que os investimentos em TI estejam vinculados aos principais resultados dos negócios.

Use a perspectiva de negócio para criar um caso de negócio sólido para adoção da nuvem e priorizar as iniciativas de adoção da nuvem. Garanta que suas estratégias e metas de negócios estejam alinhadas com suas estratégias e metas de TI.

Os perfis comuns na perspectiva de negócio são: 

  <ul>
    <li>Gerentes de negócios</li>
    <li>Gerentes financeiros</li>
    <li>Proprietários de orçamento</li>
    <li>Stakeholders de estratégia</li>
  </ul>

#### Perspectiva de pessoas

A perspectiva de pessoas promove o desenvolvimento de uma estratégia de gerenciamento de alterações em toda a organização para a adoção bem-sucedida da nuvem.

Use a perspectiva de pessoas para avaliar estruturas e perfis organizacionais, novos requisitos de habilidades e processos e identificar lacunas. Isso ajuda a priorizar treinamento, pessoal e mudanças organizacionais.

Os perfis comuns da perspectiva de pessoas são: 

 <ul>
    <li>Recursos humanos</li>
    <li>Equipe</li>
    <li>Gerentes de pessoas</li>
  </ul>

#### Perspectiva de governança

A perspectiva de governança se concentra nas habilidades e processos para alinhar a estratégia de TI à estratégia de negócios. Isso garante que você maximize o valor comercial e minimize os riscos.

Use a perspectiva de governança para entender como atualizar as habilidades e os processos da equipe necessários para garantir a governança de negócios na nuvem. Gerencie e mensure os investimentos em nuvem para avaliar os resultados de negócios.

Os perfis comuns na perspectiva de governança são:  

  <ul>
    <li>Chief Information Officer (CIO)</li>
    <li>Gerentes do programa</li>
    <li>Enterprise architect</li>
    <li>Analistas de negócios</li>
    <li>Gerentes de portfólio</li>
  </ul>

#### Perspectiva de plataforma

A perspectiva de plataforma inclui princípios e padrões para implementação de novas soluções na nuvem e migração de cargas de trabalho on-premises para a nuvem.

Use uma variedade de modelos arquitetônicos para entender e comunicar a estrutura dos sistemas de TI e suas relações. Descreva a arquitetura do ambiente de destino em detalhes.

Os perfis comuns da perspectiva de plataforma são: 

 <ul>
    <li>Chief Technology Officer (CTO)</li>
    <li>Gerentes de TI</li>
    <li>Arquitetos de soluções</li>
  </ul>

#### Perspectiva de segurança

A perspectiva de segurança garante que a organização atenda aos objetivos de segurança de visibilidade, auditoria, controle e agilidade. 

Use o AWS CAF para estruturar a seleção e a implementação de controles de segurança que atendam às necessidades da organização.

Os perfis comuns da perspectiva de segurança são: 

 <ul>
    <li>Chief information security officer (CISO)</li>
    <li>Gerentes de segurança de TI</li>
    <li>Analistas de segurança de TI</li>
  </ul>

#### Perspectiva de operações

A perspectiva de operações ajuda você a ativar, executar, usar, operar e recuperar cargas de trabalho de TI para o nível definido com os stakeholders da empresa.

Defina como os negócios diários, trimestrais e anuais são conduzidos. Alinhe e dê suporte às operações do negócio. O AWS CAF ajuda os stakeholders a definir os procedimentos operacionais atuais e identificar mudanças de processo e treinamento necessários para implementar a nuvem com sucesso.

Os perfis comuns da perspectiva de operações são  

<ul>
    <li>Gerentes de operações de TI</li>
    <li>Gerentes de suporte de TI</li>
  </ul>


 #### Qual perspectiva do AWS Cloud Adoption Framework ajuda você a elaborar, implementar e otimizar sua infraestrutura da AWS com base em suas metas e perspectivas de negócio?

  <ul>
    <li>Perspectiva de negócio</li>
    <li>&#10004; Perspectiva de plataforma</li>
    <li>Perspectiva de operações</li>
    <li>Perspectiva de pessoas</li>
  </ul>

A perspectiva de plataforma do AWS Cloud Adoption Framework também inclui princípios para implementar novas soluções e migrar cargas de trabalho on-premises para a nuvem.

As outras respostas estão incorretas porque:

A perspectiva de negócio ajuda você a mudar de um modelo que separa as estratégias de negócios e TI para um modelo de negócios que integra a estratégia de TI.

A perspectiva de operações concentra-se na operação e recuperação de cargas de trabalho de TI para atender às exigências dos stakeholders da empresa.

A perspectiva de pessoas ajuda os funcionários de Recursos Humanos (RH) a prepararem as equipes para a adoção da nuvem, atualizando processos organizacionais e habilidades da equipe para incluir competências baseadas na nuvem.

## Estratégias de migração

### Seis estratégias de migração

Ao migrar aplicações para a nuvem, seis das estratégias de migração(opens in a new tab) mais comuns que você pode implementar são:

<ul>
  <li>redefinição de hospedagem</li>
  <li>redefinição de plataforma</li>
  <li>refatoração/rearquitetura</li>
  <li>recompra</li>
  <li>retenção</li>
  <li>retirada</li>
</ul>

Para saber mais sobre estratégias de migração

### Redefinir hospedagem

Redefinir hospedagem (também conhecido como “lift-and-shift”) envolve a movimentação de aplicações sem alterações. 

No cenário de uma grande migração legada, em que a empresa busca implementar a migração e dimensionar rapidamente para atender a um caso de negócio, a hospedagem da maioria das aplicações é redefinida. 

### Redefinir plataforma

Redefinir plataforma (também conhecido como “lift, tinker and shift”) envolve fazer algumas otimizações na nuvem para obter um benefício tangível. A otimização é alcançada sem alterar a arquitetura central do aplicativo.

### Refatorar/redefinir arquitetura

Refatoração (também conhecida como rearquitetura) envolve reimaginar como uma aplicação é arquitetada e desenvolvida usando recursos nativos da nuvem. A refatoração costuma ser orientada pela forte necessidade que a empresa tem de adicionar recursos, scaling ou desempenho que, de outra forma, seriam difíceis de obter no ambiente atual da aplicação.

### Recomprar

Recomprar envolve a mudança de uma licença tradicional para um modelo de software como serviço. 

Por exemplo, uma empresa pode optar por implementar a estratégia de recomprar migrando de um sistema de gerenciamento de relacionamento com o cliente (CRM) para o Salesforce.com.

### Reter

Reter consiste em manter as aplicações essenciais para a empresa no ambiente de origem. Isso pode incluir aplicativos que exigem refatoração importante antes de serem migrados ou trabalhos que podem ser adiados.

### Retirar

Retirar é o processo de remoção de aplicações que não são mais necessários.

#### Teste de conhecimento

<ul>
  <li>Refatorar</li>
  <li>Retirar</li>
  <li>Redefinir plataforma</li>
  <li>Recomprar</li>
</ul>

Recomprar envolve a substituição de uma aplicação por uma versão baseada na nuvem, como software encontrado no AWS Marketplace.

As outras respostas estão incorretas porque:

a refatoração envolve alterar a forma como uma aplicação é arquitetada e desenvolvida, normalmente usando recursos nativos da nuvem.

A inativação envolve a remoção de uma aplicação que não é mais usado ou que pode ser desativado.

A realocação de plataforma envolve a otimização seletiva de aspectos de uma aplicação para obtenção de benefícios na nuvem sem alterar a arquitetura central da aplicação. Também é conhecida como “lift, tinker, and shift”.

<a href="https://aws.amazon.com/pt/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/">6 estratégias para migrar aplicativos para a nuvem</a>

## AWS Snow Family

### Membros da AWS Snow Family

A <a href="https://aws.amazon.com/pt/snow/"> AWS Snow family</a> é uma coleção de dispositivos físicos para transporte físico de até exabytes de dados para dentro e para fora da AWS. 

A AWS Snow Family consiste nos serviços AWS Snowcone, AWS Snowball e AWS Snowmobile. 

![Z3auH-02lwKHW96e_IIcwz3-CkuSyAs0F](https://github.com/wisomar/Resumo-para-prova-de-AWS-Practitioner/assets/136864602/2bdd2f54-6519-4d0f-8a32-d85d34f94d56)

Para saber mais sobre cada categoria:

#### AWS Snowcone

O <a href="https://aws.amazon.com/pt/snow/">AWS Snowcone</a> é um dispositivo pequeno, robusto e seguro para transferência de dados e computação de borda. 

Ele tem 2 CPUs, 4 GB de memória e até 14 TB de armazenamento utilizável.

#### Snowball

<ul>
  <li><a href="https://aws.amazon.com/pt/snowball/">Snowball Edge Storage</a> Optimized são ideais para migrações de dados de grande escala e fluxos de trabalho de transferência recorrentes, em além da computação local com necessidades maiores de capacidade.</li>
  <ul>
    <li>Armazenamento: 80 TB de capacidade de disco rígido (HDD) para volumes de blocos e armazenamento de objeto compatível com o Amazon S3, além de unidade de estado sólido (SSD) do SATA de 1 TB para volumes de blocos.</li>
    <li>Computação: 40 vCPUs e 80 GiB de memória para dar suporte a instâncias sbe1 do Amazon EC2 (equivalente a C5).</li>
  </ul>
  <li>O Snowball Edge Compute Optimized fornece recursos de computação poderosos para casos de uso, como machine learning, análise de vídeo em movimento completo, análise e pilhas de computação locais.</li>
  <ul>
    <li>Armazenamento: capacidade de HDD utilizável de 80 TB para armazenamento de objeto compatível com o Amazon S3 ou volumes de blocos compatíveis com o Amazon EBS e também 28 TB de capacidade de SSD NVMe utilizável para volumes de blocos compatíveis com o Amazon EBS.</li>
    <li>Computação: 104 vCPUs, 416 GiB de memória e uma GPU NVIDIA Tesla V100 opcional. Os dispositivos executam as instâncias sbe-c e sbe-g do Amazon EC2, que são equivalentes às instâncias C5, M5a, G3 e P3.</li>
  </ul>
</ul>

#### AWS SNOWMOBILE

O <a href="https://aws.amazon.com/pt/snowmobile/">AWS Snowmobile</a> é um serviço de transferência dados na escala de exabytes usado para mover grandes quantidades de dados para a nuvem AWS. 

Você pode transferir até 100 petabytes de dados por Snowmobile, um contêiner de transporte reforçado com 13,71 metros de comprimento puxado por um caminhão semirreboque.

#### Teste de conhecimento

Qual é a capacidade de armazenamento do Snowball Edge Storage Optimized?

<ul>
  <li>40 TB</li>
  <li>60 TB</li>
  <li>&#10004; 80 TB</li>
  <li>100 TB</li>
</ul>

O Snowball Edge Storage Optimized é um dispositivo para transferência de grandes quantidades de dados para dentro e para fora da AWS. Fornece 80 TB de armazenamento de HDD utilizável.

### Inove com os serviços da AWS

Ao examinar como usar os serviços da AWS, é importante focar nos resultados desejados. Você fica devidamente preparado para impulsionar a inovação na nuvem se conseguir articular claramente as seguintes condições: 

<ul>
  <li>O estado atual</li>
  <li>O estado desejado</li>
  <li>Os problemas que você está tentando resolver</li>
</ul>

Considerar alguns dos caminhos que poderá explorar no futuro, enquanto continuar em sua jornada para a nuvem. 

Para saber mais sobre como inovar com a AWS

#### Aplicações sem servidor

Com a AWS, sem servidor significa que você não precisa administrar, provisionar ou administrar servidores de aplicações. Você não precisa se preocupar com tolerância a falhas ou disponibilidade. A AWS lida com esses recursos para você.

O AWS Lambda é um exemplo de um serviço que você pode usar para executar aplicações sem servidor. Se projetar sua arquitetura para acionar funções do Lambda para executar seu código, você poderá ignorar a necessidade de gerenciar uma frota de servidores.

Criar sua arquitetura com aplicações sem servidor permite que os desenvolvedores se concentrem no produto principal em vez de gerenciar e operar servidores.

#### Machine learning

O desenvolvimento tradicional de machine learning (ML) é complexo, caro, demorado e propenso a erros. A AWS oferece o Amazon SageMaker, que remove o trabalho difícil do processo e ajuda você a criar, treinar e implantar modelos de ML rapidamente.

Você pode usar ML para analisar dados, resolver problemas complexos e prever resultados antes que eles aconteçam.

#### Inteligência artificial

A AWS oferece uma variedade de serviços com tecnologia de inteligência artificial (IA). 

Por exemplo, você pode executar as seguintes tarefas:

<ul>
  <li>Receba recomendações enquanto escreve e identifica problemas de segurança no seu código com o Amazon CodeWhisperer.</li>
  <li>Converter fala em texto com o Amazon Transcribe.</li>
  <li>Descobrir padrões em texto com o Amazon Comprehend.</li>
  <li>Identificar atividades on-line potencialmente fraudulentas com o Amazon Fraud Detector.</li>
  <li>Criar chatbots de voz e texto com o Amazon Lex.</li>
</ul>

#### Teste de conhecimento

Qual serviço ajuda você a criar, treinar e implantar rapidamente modelos de machine learning?

<ul>
  <li>Amazon Textract</li>
  <li>Correctly unselected</li>
  <li>AWS DeepRacer</li>
  <li>&#10004; Amazon SageMaker</li>
  <li>Amazon Lex</li>
</ul>

Com o Amazon SageMaker, é rápido e fácil começar a trabalhar em projetos de machine learning. Você não precisa seguir o processo tradicional de reunir manualmente ferramentas e fluxos de trabalho separados.



As outras respostas estão incorretas porque:

O Amazon Textract é um serviço de machine learning que extrai automaticamente texto e dados de documentos digitalizados.

O Amazon Lex é um serviço para criação de interfaces de conversação usando voz e texto.

O AWS DeepRacer é um carro de corrida autônomo de escala 1/18 que você pode usar para testar modelos de aprendizado por reforço.

Saiba mais:

<a href="https://aws.amazon.com/pt/sagemaker/" title="Amazon SageMaker"> Amazon SageMaker</a>

<ul>
  <li><a href="https://aws.amazon.com/codewhisperer/">Amazon CodeWhisperer</a></li>
  <li><a href="https://aws.amazon.com/codewhisperer/introduction/">Amazon CodeWhisperer: introdução</a></li>
  <li><a href="https://aws.amazon.com/pt/premiumsupport/knowledge-center/migration-transfer-aws/">Migração e transferência na AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/aws-brasil/um-processo-para-migracoes-em-massa-para-a-nuvem/">Um processo para migrações em massa para a nuvem</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/aws-brasil/seis-estrategias-para-a-migracao-de-aplicacoes-para-a-nuvem/">Seis estratégias para a migração de aplicações para a nuvem</a></li>
  <li><a href="https://aws.amazon.com/pt/professional-services/aws-cloud-adoption-framework/">AWS Cloud Adoption Framework</a></li>
  <li><a href="https://aws.amazon.com/pt/getting-started/fundamentals/">Fundamentos da AWS: conceitos principais</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/aws-brasil/blog-de-estrategia-empresarial-da-nuvem-aws/">Blog de estratégia empresarial da nuvem AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/blogs/aws-brasil/blog-de-modernizacao-com-a-aws/">Blog de modernização com a AWS</a></li>
  <li><a href="https://aws.amazon.com/pt/solutions/case-studies/data-center-migration/">Histórias de clientes da AWS: migração de data center</a></li>
</ul>

#### Teste de conhecimento

Qual perspectiva do AWS Cloud Adoption Framework ajuda você a estruturar a seleção e a implementação de permissões?

<ul>
  <li>
    <input type="checkbox" disabled> Perspectiva de governança
  </li>
  <li>
    &#10004; Perspectiva de segurança
  </li>
  <li style="color: green">
    <input type="checkbox" disabled checked> Perspectiva de operações
  </li>
  <li>
    <input type="checkbox" disabled> Perspectiva de negócio
  </li>
</ul>

A perspectiva de segurança do AWS Cloud Adoption Framework também ajuda você a identificar áreas de não conformidade e planejar iniciativas de segurança contínuas.

As outras respostas estão incorretas porque:

A perspectiva de governança ajuda você a identificar e implementar as práticas recomendadas para governança de TI e apoiar processos de negócios com tecnologia.

A perspectiva de operações concentra-se na operação e recuperação de cargas de trabalho de TI para atender aos requisitos dos stakeholders da empresa.

A perspectiva de negócio ajuda você a mudar de um modelo que separa as estratégias de negócios e de TI para um modelo de negócios que integra a estratégia de TI.

<a href="https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf">Whitepaper: An Overview of the AWS Cloud Adoption Framework (Uma visão geral do AWS Cloud Adoption Framework)</a>

Quais estratégias fazem parte das seis estratégias de migração de aplicativo? (Selecione DUAS opções.)

<ul>
  <li>Revisitar</li>
  <li>Reter</li>
  <li>Lembrar</li>
  <li>Redesenvolver</li>
</ul>

As estratégias de migração de aplicação são redefinição de hospedagem, redefinição de plataforma, refatoração/rearquitetura, recompra, retenção e inativação.

Qual é a capacidade de armazenamento do AWS Snowmobile?

<ul>
  <li>40 PB</li>
  <li>60 PB</li>
  <li>80 PB</li>
  <li>&#10004;100 PB</li>
</ul>

O AWS Snowmobile é um serviço para transferência de até 100 PB de dados para a AWS. Cada Snowmobile é um contêiner de transporte de 13,71 metros que é puxado por um caminhão semirreboque.

Qual declaração descreve melhor o Amazon Lex?

<ul>
  <li>&#10004; Um serviço para criação interfaces de conversação usando voz e texto</li>
  <li>Um serviço de machine learning que extrai automaticamente texto e dados de documentos digitalizados</li>
  <li>Um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB</li>
  <li>Um serviço que identifica atividades on-line potencialmente fraudulentas</li>
</ul>

No Amazon Lex, você pode criar, testar e implantar rapidamente chatbots de conversação para usar em suas aplicações.

As outras respostas estão incorretas porque:

Um serviço de machine learning que extrai automaticamente texto e dados do documento digitalizado descreve o Amazon Textract.

Um serviço de banco de dados de documentos compatível com cargas de trabalho do MongoDB descreve o Amazon DocumentDB.

Um serviço que identifica atividades on-line potencialmente fraudulentas descreve o Amazon Fraud Detector.


# AWS Well-Architected Framework

O <a href="https://docs.aws.amazon.com/pt_br/wellarchitected/latest/framework/welcome.html">AWS Well-Architected Framework</a>
ajuda você a entender como projetar e operar sistemas confiáveis, seguros, eficientes e econômicos na nuvem AWS. Com ele, é possível avaliar de maneira consistente suas arquiteturas em relação às práticas recomendadas e aos princípios de projeto e a identificar áreas para melhorias.

O Well-Architected Framework se baseia em cinco pilares: 

<ul>
  <li>Excelência operacional</li>
  <li>Segurança</li>
  <li>Confiabilidade</li>
  <li>Eficiência de desempenho</li>
  <li>Otimização de custos</li>
  <li>Sustentabilidade</li>
</ul>

Para saber mais:

### Excelência operacional

Excelência operacional é a capacidade de executar e monitorar sistemas para entregar valor comercial e melhorar continuamente os processos e procedimentos de apoio.  

Os princípios de design para a excelência operacional na nuvem incluem executar operações como código, anotar documentação, antecipar falhas e fazer com frequência alterações pequenas e reversíveis.

### Segurança

O pilar de segurança inclui a capacidade de proteger informações, sistemas e ativos e, ao mesmo tempo, entregar valor comercial por meio de avaliações de risco e estratégias de mitigação. 

Ao considerar a segurança de sua arquitetura, aplique estas práticas recomendadas:

<ul>
  <li>Automatize as práticas recomendadas de segurança quando possível.</li>
  <li>Aplique segurança em todas as camadas.</li>
  <li>Proteja os dados em trânsito e em repouso.</li>
</ul>

### Confiabilidade

Confiabilidade é a capacidade de um sistema fazer o seguinte:

<ul>
  <li>Recuperar-se de interrupções na infraestrutura ou no serviço</li>
  <li>Adquirir dinamicamente recursos de computação para atender à demanda</li>
  <li>Reduzir interrupções, como configurações incorretas ou problemas de rede transitórios</li>
</ul>

A confiabilidade inclui testes de procedimentos de recuperação, scaling horizontal para aumentar a disponibilidade agregada do sistema e recuperação automática de falhas.

### Eficiência de desempenho

A eficiência de desempenho é a capacidade de usar recursos computacionais com eficiência para cumprir requisitos do sistema e manter essa eficiência à medida que a demanda muda e as tecnologias evoluem. 

A avaliação da eficiência de desempenho de sua arquitetura inclui experimentar com mais frequência, usar arquiteturas serverless e projetar sistemas para ter alcance global em minutos.

### Otimização de custos

Otimização de custos é a capacidade de executar sistemas para entregar valor comercial com o menor preço.

A otimização de custos inclui a adoção de um modelo de consumo, análise e atribuição de despesas e uso de serviços gerenciados para reduzir o custo de propriedade.

### Sustentabilidade

Em dezembro de 2021, a AWS introduziu um pilar de sustentabilidade como parte do AWS Well-Architected Framework.

Sustentabilidade é a capacidade de melhorar continuamente os impactos da sustentabilidade, reduzindo o consumo de energia e aumentando a eficiência em todos os componentes de uma carga de trabalho, maximizando os benefícios dos recursos provisionados e minimizando o total de recursos necessários.

Para facilitar um bom design para a sustentabilidade:

<ul>
  <li>Entenda seu impacto</li>
  <li>Estabeleça metas de sustentabilidade</li>
  <li>Maximize a utilização</li>
  <li>Antecipe e adote novas ofertas de hardware e software mais eficientes</li>
  <li>Use serviços gerenciados</li>
  <li>Reduza o impacto downstream de suas cargas de trabalho na nuvem</li>
</ul>

### Teste de conhecimento

Qual pilar do AWS Well-Architected Framework se concentra na capacidade de uma carga de trabalho executar de maneira consistente e correta as funções pretendidas?

<ul>
  <li>Excelência operacional</li>
  <li>Eficiência de desempenho</li>
  <li>Segurança</li>
  <li>Confiabilidade</li>
</ul>

As outras respostas estão incorretas porque:

o pilar de excelência operacional inclui a capacidade de executar cargas de trabalho de maneira eficaz, obter informações sobre suas operações e melhorar continuamente os processos de suporte para entregar valor comercial.

O pilar de eficiência de desempenho se concentra no uso eficiente dos recursos de computação para atender aos requisitos do sistema e para manter essa eficiência à medida que a demanda muda e as tecnologias evoluem.

O pilar de segurança inclui a proteção de dados, sistemas e ativos e tecnologias de nuvem para melhorar a segurança de suas cargas de trabalho.

<a href="https://docs.aws.amazon.com/pt_br/wellarchitected/latest/framework/welcome.html">AWS Well-Architected Framework</a>

### Vantagens da computação em nuvem

Operar na nuvem AWS oferece muitos benefícios em relação à computação em ambientes on-premises ou híbridos. 

Nesta seção, você aprenderá sobre seis vantagens da computação em nuvem:

<ul>
  <li>Trocar despesa antecipada por despesas variáveis.</li>
  <li>Benefícios de enormes economias de escala.</li>
  <li>Parar de tentar adivinhar a capacidade.</li>
  <li>Aumentar a velocidade e a agilidade.</li>
  <li>Parar de gastar dinheiro com execução e manutenção de data centers.</li>
  <li>Ter alcance global em minutos.</li>
</ul>

Para saber mais sobre as vantagens da computação em nuvem:

### Troque despesas iniciais por despesas variáveis.

Despesas iniciais são data centers, servidores físicos e outros recursos nos quais você precisaria investir antes de usá-los.

Em vez de investir substancialmente em data centers e servidores antes de saber como serão usados, você pode pagar somente ao consumir recursos de computação.

### Beneficie-se de grandes economias de escala.

O uso da computação em nuvem permite obter um custo variável menor ao que você conseguiria por conta própria. 

Como o uso por centenas de milhares de clientes se acumula na nuvem, provedores como a AWS podem alcançar economias de escala maiores. As economias de escala se transformam em preços para pagamento conforme o uso mais baixos.

### Pare de tentar adivinhar a capacidade.

Com a computação em nuvem, você não precisa prever a capacidade de infraestrutura necessária antes de implantar uma aplicação. 

Por exemplo, você pode iniciar instâncias do Amazon Elastic Compute Cloud (Amazon EC2) quando necessário e pagar apenas pelo tempo de computação usado. Em vez de pagar por recursos que não são utilizados ou lidar com capacidade limitada, você pode acessar somente a capacidade de que precisa e aumentar ou reduzir a quantidade em resposta à demanda. 

### Aumente a velocidade e a agilidade.

A flexibilidade da computação em nuvem facilita o desenvolvimento e a implantação de aplicações.

Essa flexibilidade também oferece às suas equipes de desenvolvimento mais tempo para experimentar e inovar.

### Parar de gastar dinheiro com execução e manutenção de data centers.

A computação em nuvem em data centers geralmente exige que você gaste mais dinheiro e tempo gerenciando infraestrutura e servidores. 

Um benefício da computação em nuvem é poder se concentrar menos nessas tarefas e mais nas aplicações e clientes.

### Tenha alcance global em minutos.

O espaço global da nuvem AWS para implantação rápida de aplicações para clientes em todo o mundo, ao mesmo tempo em que oferece baixa latência.


### Teste de conhecimento

Que processo é uma vantagem da grande economia em escala?

<ul>
  <li>Implantação de uma aplicação em várias Regiões ao redor do mundo</li>
  <li>&#10004; Fazer o pagamento conforme o uso de preços mais baixos em consequência do uso agregado de serviços dos clientes da AWS</li>
  <li>Pagar pelo tempo de computação à medida que você o usa, em vez de investir antecipadamente em data centers</li>
  <li>Aumentar ou diminuir a capacidade da infraestrutura para atender à demanda</li>
</ul>

A resposta correta é: Fazer o pagamento conforme o uso de preços de pagamento conforme o uso mais baixos em consequência do uso agregado de serviços dos clientes da AWS.

Como o uso de centenas de milhares de clientes é agregado na nuvem, os provedores, como a AWS, podem alcançar maior economia de escala. As economias de escala traduzem-se em preços para pagamento conforme o uso mais baixos. 

As outras respostas estão incorretas porque:

Implantação de uma aplicação em várias Regiões ao redor do mundo: esse processo é um exemplo da obtenção de alcance global em minutos.

Pagar pelo tempo de computação à medida que você o usa em vez de investir antecipadamente em data centers: esse processo é um exemplo de troca de despesa inicial para despesa variável.

Aumentar ou diminuir a capacidade da infraestrutura para atender à demanda: esse processo é um exemplo de parar de adivinhar capacidade.

<a href="https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html">Link para o artigo "Seis vantagens da computação em nuvem"</a>

#### Recursos adicionais

<a href=“https://aws.amazon.com/pt/architecture/well-architected/” target=“_blank”>AWS Well-Architected</a>
<a href=“https://docs.aws.amazon.com/pt_br/wellarchitected/latest/framework/welcome.html” target=“_blank”>AWS Well-Architected Framework</a>
<a href=“https://aws.amazon.com/pt/architecture/” target=“_blank”>Centro de Arquitetura da AWS</a>
<a href=“https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-overview/six-advantages-of-cloud-computing.html” target=“_blank”>Seis vantagens da computação em nuvem</a>
<a href=“https://aws.amazon.com/blogs/architecture/” target=“_blank”>Blog de arquitetura da AWS</a>

### Teste de conhecimento 

Qual pilar do AWS Well-Architected Framework inclui a capacidade de executar cargas de trabalho de maneira eficaz e obter informações sobre as operações?

<ul>
  <li>Otimização de custos</li>
  <li>&#10004; Excelência operacional</li>
  <li>Eficiência de desempenho</li>
  <li>Confiabilidade</li>
</ul>

As outras respostas estão incorretas porque:

O pilar de otimização de custos se concentra na capacidade de executar sistemas para proporcionar valor comercial com o preço mais baixo.

O pilar de eficiência de desempenho se concentra no uso eficiente dos recursos de computação para atender aos requisitos do sistema e manter essa eficiência à medida que a demanda muda e as tecnologias evoluem.

O pilar de confiabilidade se concentra na capacidade de uma carga de trabalho executar de maneira consistente e correta as funções pretendidas.

Quais são os benefícios da computação em nuvem? (Selecione DUAS opções.)

<ul>
  <li>&#10004; Aumente a velocidade e a agilidade.</li>
  <li>Beneficiar-se de economias de escala.</li>
  <li>Trocar despesa variável por despesa antecipada.</li>
  <li>Manter a capacidade da infraestrutura.</li>
  <li>&#10004; Parar de gastar dinheiro com execução e manutenção de data centers.</li>
</ul>

As seis vantagens da computação em nuvem são:

Trocar despesas iniciais por despesas variáveis.

Benefícios com as grandes economias de escala

Parar de adivinhar capacidade.

Aumentar a velocidade e a agilidade.

Parar de gastar dinheiro executando e mantendo data centers.

Ter alcance global em minutos.

# Noções Basicas do AWS Certified Cloud Practitioner.

## Domínios do exame

O exame AWS Certified Cloud Practitioner inclui quatro domínios:

<ul>
  <li>Conceitos de nuvem</li>
   <li>Segurança e conformidade</li>
   <li>Tecnologia</li>
   <li>Cobrança e preços</li>
</ul>

As áreas abordadas descrevem cada domínio no <a href="https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf">guia de exame AWS Certified Cloud Practitioner</a>. Para obter uma descrição de cada domínio, consulte o site do <a href="https://aws.amazon.com/pt/certification/certified-cloud-practitioner/">AWS Certified Cloud Practitioner</a>. Leia as informações do Guia do Exame como parte de sua preparação para o exame.

Cada domínio do exame tem um peso. O peso representa a porcentagem de perguntas do exame que corresponde a esse domínio específico. Os pesos são aproximações, então as perguntas do seu exame podem não corresponder exatamente a essas porcentagens. O exame não indica o domínio associado a uma pergunta. Na verdade, algumas perguntas podem se enquadrar em vários domínios.

<ul>
  <li>
    Domínio
    <ul>
      <li>Porcentagem do exame</li>
    </ul>
  </li>
  <li>
    Domínio 1: Conceitos de nuvem
    <ul>
      <li>26%</li>
    </ul>
  </li>
  <li>
    Domínio 2: Segurança e conformidade
    <ul>
      <li>25%</li>
    </ul>
  </li>
  <li>
    Domínio 3: Tecnologia
    <ul>
      <li>33%</li>
    </ul>
  </li>
  <li>
    Domínio 4: Faturamento e definição de preço
    <ul>
      <li>16%</li>
    </ul>
  </li>
  <li>
    Total
    <ul>
      <li>100%</li>
    </ul>
  </li>
</ul>

### Experiência recomendada

Os candidatos ao exame AWS Certified Cloud Practitioner devem ter uma compreensão básica dos serviços de TI e de como usá-los na plataforma da nuvem AWS. 

Recomendamos que você tenha pelo menos seis meses de experiência com a nuvem AWS em qualquer função, inclusive gerentes de projeto, gerentes de TI, gerentes de vendas, tomadores de decisão e profissionais de marketing. São funções além das de finanças, compras e departamentos jurídicos.

### Whitepapers e recursos

Como parte de sua preparação para o exame AWS Certified Cloud Practitioner, recomendamos ler os seguintes whitepapers:

<a href=“https://aws.amazon.com/pt/architecture/well-architected/” target=“_blank”>Overview of Amazon Web Services (Visão geral da Amazon Web Services)</a>
<a href=“https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/how-aws-pricing-works.pdf” target=“_blank”>How AWS Pricing Works (Como é a definição de preço da AWS)</a>
<a href=“https://aws.amazon.com/premiumsupport/plans/” target=“_blank”>Compare AWS Support Plans (Comparar planos do AWS Support)</a>

### Estratégias do exame

### Leia toda a pergunta.

Primeiro, leia cada pergunta na íntegra. Palavras-chave ou frases na pergunta que, se não forem lidas, podem resultar na seleção de uma resposta incorreta.

### Preveja a resposta antes de ver as outras respostas.

Em seguida, tente prever a resposta correta antes de analisar qualquer resposta. 

Esta estratégia ajuda você a presumir diretamente de seus conhecimentos e habilidades sem se distrair com respostas incorretas. Se a sua previsão é uma das respostas, isso pode ser útil para saber se você está no caminho certo. No entanto, analise todas as outras respostas para essa pergunta.

### Elimine as respostas incorretas.

Antes de selecionar sua resposta a uma pergunta, elimine todas as opções que você acredita estar incorretas. 

Essa estratégia ajuda você a se concentrar na opção correta (ou opções, para perguntas de resposta múltipla) e cumprir todos os requisitos da pergunta.

