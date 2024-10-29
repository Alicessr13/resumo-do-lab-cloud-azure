# resumo-do-lab-cloud-azure

computação em nuvem: fornecimento de serviços de computação pela internet

nuvem privada: ambiente em nuvem no datacenter da empresa, sem acesso fora da organização, 
a organização é responsavel pelos serviços, organização tem controle total sobre recursos e segurança,
organização são responsaveis pela manutenção e atualização do hardware

nuvem pública: entrega serviços para vários clientes por meio de um unico provedor/datacenter,
acesso via conexão de rede segura(geralmente pela internet), 
sem despesa de capital para escalar verticalmente, organização paga apenas pelo utiliza,
os aplicativos podem ser provisionados e desprovisionados rapidamente

nuvem híbrida: tem uma nuvem pública e uma privada e elas se comunicam, organização determina 
onde executar seus aplicativos, maior flexibilidade, organização controlam a segurança, a conformidade
e os requisitos legais

multicloud: tem mais mais de uma nuvem publica e privada,
exemplo: tem nuvem na azure e na aws e no datacenter local

capex = despesa de capital, infraestrutura física, valor de reduz com o tempo

opex = despesa operacional, produtos e serviços, pagamento conforme o uso

site azure:
todos os serviços: mostra tudo que tem no azure por categorias
o que está em versão previa não tem sla/garantia e pode sair e pode ter perca de dados que foram criados nele

Beneficios da nuvem:
    Alta disponibilidade: recursos disponiveis sempre que necessário, 
    garantir a disponibilidade máxima independente de interrupções ou eventos que possam ocorrer, SLA

    Escalabilidade: capacidade de ajustar recursos para atender à demanda, adicionar recursos para lidar com aumento de demanda,
    paga somente o necessário baseado no consumo, se a demanda cair pode reduzir os recursos

    Elasticidade: se você experimentasse um salto repentino acentuado na demanda seus recursos implantados
    poderiam ser esxpandidos automaticamente ou manualmente, dimencionar o ambiente com base em requisições
    exemplo: adicionar máquinas virtuais ou contêineres por expansão
    e se houver queda significativa na demanda os recursos poderão ser reduzidos horizontalmente automático ou manual

    Confiabilidade: suporte a uma infraestrutura confiável e resiliente, recursos implantados em várias regiões do mundo, 
    mesmo que ocorra algo em uma região as outras ainda estaram em funcionamento

    Previsibiliade: permite que você avance com confiança seja no desempenho ou no custo (microsoft azure well-architected framework)

    Segurança: a nuvem oferece ferramentas de segurança que atendem as necessidades dos clientes, mas a implementação de muitas
    devem ser realizadas pelo cliente

    Governança: auditoria baseada em nuvem ajuda a sinalisar qualquer recurso que esteja fora de conformidadde com seus padrões corporativos e
    fornece estratégias de mitigação(resolução), dependendo patches de softwares e atualizações podem ser aplicados automaticamente

    Gerenciabilidade: facilitar o gerenciamento, há 2 tipos de capacidade de gerenciamento para computação em nuvem (portal ou linha de comando), gerenciamento da nuvem é 
    gerenciar os recursos de nuvem, implementar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual


sla, tempo que o serviço pode ficar fora, ao criar uma vm pode definir opções de disponibilidade e zonas de disponibilidade que afeta o sla, redundancia também afeta o sla
