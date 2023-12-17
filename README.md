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





