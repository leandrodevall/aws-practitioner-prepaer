### EC2 Elast Compute Cloud Iaas VM

Amazon Elastic Compute Cloud (EC2) é um serviço de computação em nuvem oferecido pela Amazon Web Services (AWS) que permite aos usuários executar máquinas virtuais escaláveis em um ambiente de nuvem. Com o EC2, você pode provisionar, configurar e gerenciar servidores virtuais de acordo com suas necessidades de computação, permitindo flexibilidade, escalabilidade e controle sobre seus recursos de computação na nuvem. É amplamente utilizado para hospedar aplicativos, executar cargas de trabalho, criar servidores web, processar dados e muito mais na AWS.

### tipos de EC2

Amazon Elastic Compute Cloud (EC2) oferece uma variedade de tipos de instâncias para atender às diversas necessidades de computação dos usuários. Até minha última atualização em setembro de 2021, aqui estão alguns dos tipos de instâncias EC2 mais comuns:

- Instâncias de Propósito Geral (General Purpose):

Exemplos: t2.micro, t3.large, m5.xlarge
Adequadas para uma ampla variedade de cargas de trabalho, incluindo aplicativos da web, servidores de aplicativos, desenvolvimento e testes.

- Instâncias de Computação Otimizada (Compute Optimized):

Exemplos: c4.large, c5.2xlarge, c6g.xlarge
Projetadas para cargas de trabalho que exigem alta capacidade de processamento, como análise de dados, modelagem científica e aplicativos de alto desempenho.

- Instâncias de Memória Otimizada (Memory Optimized):

Exemplos: r5.large, r6g.2xlarge, x1e.8xlarge
Ideais para cargas de trabalho que requerem grande capacidade de memória, como bancos de dados em memória, análise de big data e aplicativos de análise em tempo real.

- Instâncias de Armazenamento Otimizado (Storage Optimized):

Exemplos: i3.large, i3en.2xlarge, d3.xlarge
Projetadas para cargas de trabalho com requisitos intensivos de armazenamento, como bancos de dados NoSQL, data warehousing e aplicativos de análise.

- Instâncias GPU (Graphics Processing Unit):

Exemplos: p3.2xlarge, g4dn.xlarge, a4i.large
Destinadas a cargas de trabalho que envolvem processamento gráfico intensivo, como aprendizado de máquina, renderização 3D e simulações.

- Instâncias FPGA (Field-Programmable Gate Array):

Exemplos: f1.2xlarge
Projetadas para cargas de trabalho que requerem aceleração de hardware personalizada, como criptografia, compressão e processamento de sinais digitais.


### Valores EC2

1 Sob demanda mais caro

2 Saving plans mais barato mas precisa de contrato 1 a 3 anos

3 Spot 90% mais barato, utiliza recursos que AWS nao está utilizando
utilizar em fluxos tolerante a falhas

4 Host dedicados mais caro de todos, dedicado (fin/gov)

5 Capacidade por demanda, um pouco caro > espeficiar quantidade
de hardware necessario por tempo.