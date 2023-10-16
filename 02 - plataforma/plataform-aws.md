## Plataforma aws

A aws tem data centers distribuidos globalmente em continentes como América do Norte, Europa, Ásia, América do Sul, Oriente Médio e África. Cada uma dessas regiões são consideradas denominadas como Region, dentro de cada region temos um conjunto de n Zonas.

### Region (Região)

- Uma região é uma área geográfica específica em todo o mundo onde a AWS tem data centers e recursos de infraestrutura.

- Cada região da AWS é completamente independente das outras em termos de infraestrutura física e recursos.

- As regiões são projetadas para fornecer alta disponibilidade e durabilidade, permitindo que você execute aplicativos em várias regiões para alcançar resiliência.

- Alguns exemplos de regiões da AWS incluem a Região Leste dos EUA (Norte da Virgínia), Região Oeste dos EUA (Oregon), Região UE (Irlanda) e muitas outras em todo o mundo.

### Availability Zone (Zona de Disponibilidade)

- Uma Availability Zone (AZ) é uma unidade lógica dentro de uma região da AWS.

- Cada AZ é um data center ou grupo de data centers isolados fisicamente, mas conectados em rede dentro da mesma região.

- As AZs são projetadas para serem independentes umas das outras em termos de energia, refrigeração e conectividade, para garantir alta disponibilidade.

- Você pode implantar recursos, como instâncias EC2, em diferentes AZs para melhorar a resiliência de suas aplicações.

Uma "região" é uma área geográfica mais ampla que contém várias "zonas de disponibilidade" (AZs). Você escolhe uma região ao criar recursos da AWS, e dentro dessa região, você pode selecionar uma ou mais AZs para distribuir e replicar seus serviços para garantir alta disponibilidade e resiliência.

Por exemplo, se você está executando uma aplicação crítica na AWS, pode implantar instâncias EC2 em várias AZs dentro de uma região para garantir que a falha em uma AZ não afete a disponibilidade do seu aplicativo. Isso é parte do conceito de arquitetura de alta disponibilidade na AWS.

### Widgeds de interface

recursos da interface para organizar e order informações importante para o usuario. São os quadrados de informação.

### Alerta de Custos _Cloud Watch_

O Amazon CloudWatch é um serviço de monitoramento e observabilidade da Amazon Web Services (AWS) que permite que você colete e acompanhe métricas, logs e eventos de recursos da AWS e de aplicativos. Ele ajuda a entender o desempenho dos recursos da sua infraestrutura, permite a detecção de problemas e fornece insights sobre como melhorar a eficiência operacional.

- Cloud Watch desativado por default
- Billing
- Criação de cota:

A criação de alertas de custo na Amazon Web Services (AWS) envolve o uso do serviço AWS Cost Explorer e do AWS Budgets para definir limiares de gastos e receber notificações quando os custos excederem esses limites.

case:

Cloud Watch > billing > alert > $10 USD > email notification

- habilitar opção de envio de alerta no billing (faturamento)

- Cloud Watch > lista de alarmes > criar alarme > pesquisar billing e "encontrar faturamento > carga total estimada", podemos tbm criar por serviço

- no processo de configuração da metrica podemos definir uma condição: maior que o limite (10 USD), realizar alguma ação:
  Notificação
  - Alarme
  - Definir que tipo de alarme e como será notificado

para realizar envido de notificação utilizamos outro serviç Amazon Simple Queue Service (SQS).

Toda integração com serviço do SNS precisa ser confirmado, com isso o email que será enviado para notificação precisa passar pelo processo de confirmação

