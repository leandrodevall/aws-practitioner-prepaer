### NACL

Uma Lista de Controle de Acesso à Rede (NACL) no Amazon Web Services (AWS) funciona como um mecanismo de segurança para controlar o tráfego de rede que entra e sai de uma sub-rede da sua Virtual Private Cloud (VPC). Aqui está um detalhamento de como as NACLs funcionam:

Definição de Regras: Uma NACL consiste em um conjunto de regras de controle de acesso que você define. Cada regra é composta por um número de regra, uma ação (permitir ou negar), um intervalo de portas (opcional), um protocolo (como TCP, UDP ou ICMP), e um intervalo de endereços IP de origem ou destino.

Prioridade das Regras: As regras em uma NACL são avaliadas em ordem, da regra com o número mais baixo para a regra com o número mais alto. Portanto, a ordem das regras é importante, já que a primeira regra correspondente é aplicada. Se uma regra permitir o tráfego, a NACL permitirá o acesso. Se uma regra negar o tráfego, o acesso será bloqueado.

Padrão Deny All: Por padrão, quando você cria uma NACL, todas as regras negam o tráfego. Isso significa que, a menos que você crie regras permitindo o tráfego explicitamente, nenhum tráfego será permitido. Você pode criar regras que permitem tráfego específico, com base nas necessidades da sua aplicação.

Associação com Sub-Redes: Cada sub-rede em sua VPC pode ser associada a uma NACL. Isso significa que as regras da NACL se aplicam a todas as instâncias e recursos dentro da sub-rede.

Evaluando o Tráfego: Quando o tráfego entra ou sai de uma sub-rede, as regras na NACL associada a essa sub-rede são verificadas. A primeira regra correspondente à configuração do tráfego é aplicada. Se nenhuma regra corresponder, a ação padrão (geralmente "negar") será aplicada.

Monitoramento e Ajuste: Após configurar a NACL, é importante monitorar o tráfego e ajustar as regras conforme necessário. Isso garante que o tráfego desejado seja permitido e que a segurança da sua VPC seja mantida.

Conjunto de Regras de Entrada e Saída: É importante observar que as NACLs têm conjuntos separados de regras de entrada e saída. As regras de entrada controlam o tráfego que entra na sub-rede, enquanto as regras de saída controlam o tráfego que sai dela.

Em resumo, as NACLs são uma camada de segurança na AWS que permitem controlar o tráfego de rede com base em regras definidas por você. Elas são uma parte importante da estratégia de segurança da sua VPC, juntamente com outros recursos de segurança, como grupos de segurança.