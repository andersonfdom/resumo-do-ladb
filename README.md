# resumo-do-ladb
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
<h2>Microsoft Azure - Localizando Serviços por Categoria</h2>
Aprendi sobre como parametrizar as configurações iniciais do painel Microsoft Azure, e uma noção básica sobre os serviços disponíveis por Categoria
Na categoria Redes, Bastions é um tipo de uma rede segura.

<h2>Microsoft Azure - Benefícios da Nuvem Azure</h2>
O texto aborda conceitos e práticas essenciais da computação em nuvem, com foco na plataforma Microsoft Azure, destacando temas como alta disponibilidade, escalabilidade, elasticidade, segurança, governança, e gerenciamento.

Alta Disponibilidade: Refere-se à garantia de que os serviços estarão sempre disponíveis, com foco em minimizar interrupções. O SLA (Service Level Agreement) define os níveis de serviço, como a disponibilidade de máquinas virtuais e armazenamento. Caso o SLA não seja cumprido, a Microsoft oferece créditos de serviço aos clientes.

Escalabilidade e Elasticidade: A escalabilidade permite aumentar ou reduzir recursos, como memória e armazenamento, conforme a demanda. A elasticidade no Azure ajusta dinamicamente os recursos com base nas necessidades, otimizando custos e garantindo alta disponibilidade. Isso é feito por meio de escalabilidade vertical (aumento de recursos em uma instância) e horizontal (adição de instâncias).

Confiabilidade, Previsibilidade e Segurança: A confiabilidade no Azure envolve a resiliência do sistema, enquanto a previsibilidade foca no desempenho e custos. A segurança é crucial, sendo responsabilidade do cliente garantir a proteção dos dados e o gerenciamento de acessos, enquanto a Microsoft fornece os recursos.

Microsoft Azure Well-Architected Framework: Este framework é um conjunto de melhores práticas para construir soluções eficientes e seguras no Azure, com cinco pilares principais: excelência operacional, segurança, confiabilidade, desempenho e otimização de custos. A aplicação do framework ajuda a garantir soluções robustas e de baixo custo.

Governança e Gerenciabilidade: A governança em nuvem assegura que os recursos estejam em conformidade com políticas de segurança e regulatórias. O gerenciamento é facilitado por ferramentas como o Azure Monitor e APIs, permitindo a automação e o controle eficiente dos recursos na nuvem.

Esses conceitos tornam a plataforma Azure robusta, escalável e segura, ajudando empresas a gerenciar suas infraestruturas de forma eficiente e econômica.

<h2>Microsoft Azure - Modelo de Responsabilidade Compartilhada</h2>
O texto descreve os três principais tipos de serviços em nuvem oferecidos pela Microsoft Azure: IaaS (Infraestrutura como Serviço), PaaS (Plataforma como Serviço) e SaaS (Software como Serviço), destacando as responsabilidades compartilhadas entre o cliente e o provedor de nuvem.

IaaS (Infraestrutura como Serviço):
Este modelo oferece recursos básicos de infraestrutura, como servidores, armazenamento e redes. A Microsoft cuida da infraestrutura física (hosts, rede, datacenters), enquanto o cliente gerencia sistemas operacionais, segurança de rede, backup, e outras configurações. É o modelo mais flexível, onde o cliente tem mais controle sobre a infraestrutura.

PaaS (Plataforma como Serviço):
O PaaS fornece uma plataforma completa para o desenvolvimento, teste e implantação de aplicativos, sem que o cliente precise gerenciar a infraestrutura subjacente (sistema operacional, servidores e rede). A Microsoft assume a maior parte da responsabilidade pela infraestrutura física e sistemas operacionais, com o cliente sendo responsável apenas por aplicações e algumas configurações de rede.

SaaS (Software como Serviço):
No SaaS, a Microsoft fornece aplicativos prontos para uso, como o Microsoft Teams, sem que o cliente precise se preocupar com a infraestrutura ou a manutenção do software. O modelo é baseado em pagamento por assinatura, e o cliente apenas usa os serviços sem preocupações com a gestão técnica.

Modelo de Responsabilidade Compartilhada:
A responsabilidade por dados, dispositivos e identidades sempre fica com o cliente, independentemente do serviço de nuvem (IaaS, PaaS ou SaaS). No entanto, a responsabilidade pela infraestrutura física, como hosts, rede e datacenter, varia conforme o modelo de serviço. No IaaS, o cliente é responsável pela maioria dos componentes, enquanto no PaaS e SaaS, a Microsoft assume maior parte da responsabilidade pela infraestrutura e pelo sistema operacional.

Comparação de Serviços:

IaaS oferece flexibilidade para o cliente configurar e gerenciar a infraestrutura.
PaaS foca no desenvolvimento de aplicativos, com a plataforma gerenciada pelo provedor.
SaaS oferece software pronto para uso com cobrança baseada em assinatura, como Netflix.
Esses modelos permitem que as empresas escolham o nível de controle e gestão que desejam ter sobre seus recursos em nuvem.

