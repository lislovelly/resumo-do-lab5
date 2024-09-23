# resumo-do-lab5

## Exploração Inicial e Escolha de Padrões

Minha exploração começou com a necessidade de compreender as diferenças entre os ambientes de teste e de produção. Decidi que a melhor forma de aprender seria criar algumas máquinas virtuais (VMs) em ambos os ambientes.

Para o ambiente de teste, escolhi configurações mais econômicas e flexíveis. Isso me permitiu experimentar sem preocupações excessivas com custos. Aprendi que essas VMs são ideais para desenvolvimento e testes de aplicativos, oferecendo um excelente espaço para aprender e experimentar.

Já para o ambiente de produção, optei por configurações otimizadas para desempenho e confiabilidade. Essas VMs são cruciais para aplicativos críticos e em larga escala. As configurações predefinidas nesses modelos garantiram que eu estivesse utilizando as melhores práticas desde o início.

## Validação e Criação de VMs 

Para validar os modelos de VMs, utilizei o portal do Azure, onde comparei diferentes opções e explorei suas especificações. A documentação oficial do Azure foi uma fonte constante de aprendizado, ajudando-me a entender as características de cada modelo e suas melhores aplicações.

Decidi criar uma VM com configurações predefinidas para um projeto específico. Escolhi um modelo que já vinha com aplicativos instalados, o que economizou tempo e garantiu que a VM estivesse otimizada para a tarefa.

## Processo de Criação de VM

A criação de uma VM no Azure envolve várias etapas:

Assinatura e Grupo de Recursos: Selecionei a assinatura adequada para a cobrança e gestão de recursos. Criei um grupo de recursos para organizar a VM e os recursos associados, facilitando a gestão e a manutenção.

Configurações Iniciais: Escolhi um nome único e descritivo para a máquina virtual. Optei por uma região e zona de disponibilidade que garantiam redundância e baixa latência, essenciais para a confiabilidade do serviço.

Dimensionamento e Escalabilidade: Criei um conjunto de dimensionamento e configurei a escala para garantir que a VM pudesse lidar com picos de demanda. Escolhi um tamanho de VM adequado para a carga de trabalho específica, considerando as séries disponíveis e as necessidades de desempenho.

## Configurações Avançadas

Tamanhos de Discos: Selecionar o tamanho adequado dos discos foi crucial para garantir o desempenho e a capacidade de armazenamento necessários.

Exclusão de Recursos: Aprendi a importância de excluir máquinas virtuais corretamente, removendo também IPs e NICs (Network Interface Cards) associados, para evitar cobranças desnecessárias.

Monitoramento e Alertas: Configurei regras de monitoramento e alertas recomendadas para garantir que eu pudesse responder rapidamente a qualquer problema. Utilizei a seção avançada para instalar extensões e adicionar funcionalidades extras à VM.

## Finalização

Marcas: Adicionei marcas aos recursos para facilitar a organização e a gestão.

Revisão e Criação: Revisei todas as configurações cuidadosamente antes de criar a VM, garantindo que tudo estivesse conforme o planejado.

## Experiências Adicionais

Além da criação e gestão de VMs, explorei outras áreas do Azure:

Área de Trabalho do Azure: Criei imagens personalizadas, permitindo que os usuários se conectassem rapidamente às suas sessões. Também configurei pools de hosts, tanto pessoais quanto em grupo, otimizando o uso dos recursos.

Aplicativos de Funções: Aprendi a criar e gerenciar aplicativos de funções, utilizando código ou imagens de container. Configurei a pilha de runtime e opções de hospedagem, garantindo que os aplicativos estivessem prontos para uso em diversos cenários.

Conclusão
Essa jornada no Azure me proporcionou um conhecimento profundo sobre a criação, configuração e gestão de máquinas virtuais. A capacidade de otimizar serviços e garantir a conformidade com as melhores práticas foi fundamental para o sucesso dos projetos em que trabalhei. Com essas habilidades, estou confiante de que posso enfrentar desafios ainda maiores no futuro, utilizando a poderosa infraestrutura do Azure.
