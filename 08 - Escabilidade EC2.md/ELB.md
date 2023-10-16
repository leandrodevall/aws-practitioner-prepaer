 O Elastic Load Balancing (ELB) é um serviço da Amazon Web Services (AWS) que distribui automaticamente o tráfego de entrada de aplicações em várias instâncias EC2, contêineres, endereços IP e funções Lambda para garantir que as aplicações tenham alta disponibilidade e desempenho.

Aqui estão algumas características principais do ELB:



Tipos de Balanceador de Carga: O ELB oferece três tipos de balanceadores de carga que se adequam a diferentes necessidades de aplicação - o Balanceador de Carga de Aplicação (ALB) para tráfego HTTP e HTTPS, o Balanceador de Carga de Rede (NLB) para tráfego TCP, UDP e TLS, e o Classic Load Balancer para tráfego HTTP, HTTPS, TCP e SSL.

Alta disponibilidade: O ELB distribui automaticamente o tráfego em várias instâncias em várias zonas de disponibilidade para garantir a continuidade do serviço, mesmo se uma ou mais instâncias falharem.

Escalabilidade: O ELB escala automaticamente a sua capacidade de balanceamento de carga em resposta ao tráfego de entrada.

Integração com o Auto Scaling: O ELB trabalha em conjunto com o Auto Scaling da AWS para garantir que há capacidade suficiente para atender ao tráfego de entrada e para substituir as instâncias que falham.

Segurança: O ELB oferece recursos de segurança como a integração com o AWS Certificate Manager para SSL/TLS, e a integração com o AWS Identity Access Management (IAM) para controle de acesso.

Monitoramento e Auditoria: O ELB integra-se com o Amazon CloudWatch e o AWS CloudTrail para monitorar o desempenho de suas aplicações e registrar as ações realizadas no seu balanceador de carga.

Resumindo, o Elastic Load Balancing é uma ferramenta essencial para a distribuição eficiente de tráfego, melhorando a disponibilidade e a tolerância a falhas das suas aplicações na AWS.