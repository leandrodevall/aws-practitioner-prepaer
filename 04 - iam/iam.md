### IAM (identity and access management)

IAM (Identity and Access Management) é um serviço fundamental que permite que você controle o acesso de usuários e recursos em sua conta AWS. Aqui estão alguns pontos importantes sobre o IAM na AWS:

- Usuários IAM: Você pode criar e gerenciar contas de usuário individuais no IAM. Cada usuário terá suas próprias credenciais de acesso e permissões, permitindo o acesso aos recursos AWS com base nas políticas atribuídas.

- Grupos IAM: Em vez de atribuir permissões individualmente a cada usuário, é prática comum criar grupos e associar políticas a esses grupos. Isso facilita a administração, pois você pode adicionar ou remover usuários de grupos para conceder ou revogar permissões.

- Funções IAM: As funções IAM são entidades que você pode criar e associar a recursos AWS, como instâncias EC2 ou buckets S3. Isso permite que os recursos acessem outros recursos ou serviços AWS, seguindo a política associada à função.

- Políticas IAM: As políticas IAM são documentos JSON que definem permissões. Elas podem ser anexadas a usuários, grupos ou funções e especificam quais ações podem ser realizadas em quais recursos. A AWS fornece políticas predefinidas e você também pode criar políticas personalizadas.

- Autenticação Multifatorial (MFA): O IAM na AWS suporta autenticação de dois fatores (2FA) para aumentar a segurança das contas de usuário. Isso geralmente envolve o uso de um dispositivo MFA, como um token ou um aplicativo de autenticação móvel, junto com a senha.

- Auditoria e Monitoramento: O AWS CloudTrail é um serviço que registra todas as atividades do IAM em sua conta, permitindo que você rastreie quem fez o quê e quando. Além disso, você pode usar serviços como o AWS Config para avaliar o estado das políticas de acesso.

- Acesso temporário: O IAM permite que você conceda acesso temporário a usuários ou serviços por meio do uso de credenciais temporárias, como funções IAM ou credenciais temporárias geradas por serviços, como o AWS Security Token Service (STS).

O IAM na AWS é fundamental para garantir a segurança, a conformidade e a gestão eficaz de recursos na nuvem. É uma parte essencial da estratégia de segurança da AWS e é usado para controlar quem pode acessar quais recursos e o que eles podem fazer com esses recursos dentro da sua conta AWS.

### AWS Organization

Uma Organização AWS é um recurso fornecido pela Amazon Web Services (AWS) que permite gerenciar e governar centralmente várias contas da AWS em sua organização. É uma maneira de consolidar a faturação, estabelecer políticas para compartilhamento de recursos e simplificar tarefas administrativas em várias contas da AWS. Aqui estão alguns aspectos importantes das Organizações AWS:

- Faturação Consolidada: As Organizações AWS permitem que você consolide a faturação de várias contas da AWS, facilitando o acompanhamento e o gerenciamento dos custos. Você pode ter uma conta principal pagante que abrange todas as contas vinculadas em sua organização. Isso pode ajudar a aproveitar descontos por volume e simplificar o processo de pagamento.

- Estratégia de Múltiplas Contas: Com as Organizações AWS, você pode criar e gerenciar várias contas da AWS. Isso é útil para isolar cargas de trabalho, aplicativos ou departamentos em contas separadas da AWS, proporcionando melhor segurança e gerenciamento de recursos.

- Unidades Organizacionais (OUs): Você pode organizar suas contas em OUs para refletir a estrutura organizacional. As OUs ajudam a aplicar políticas e permissões a grupos de contas. Por exemplo, você pode criar OUs separadas para ambientes de desenvolvimento, produção e teste.

- Políticas de Controle de Serviço (SCPs): SCPs são um recurso importante das Organizações AWS. Eles permitem definir permissões detalhadas no nível da organização, limitando quais ações e serviços podem ser usados dentro das contas membros. SCPs podem ser usados para aplicar políticas de segurança e conformidade.

- Controle de Acesso Consolidado: Você pode usar funções do IAM e acesso entre contas para conceder permissões em contas da AWS de forma centralizada. Isso é particularmente útil quando você precisa permitir que usuários ou recursos específicos em uma conta acessem recursos em outra conta.

- Criação e Exclusão de Contas: Você pode automatizar o processo de criação de novas contas da AWS em sua organização usando as Organizações AWS. Você também pode configurar políticas para controlar a criação e exclusão de contas.

- Compartilhamento de Recursos entre Contas: As Organizações AWS facilitam o compartilhamento de recursos, como buckets do Amazon S3 ou bancos de dados do Amazon RDS, entre várias contas, mantendo o controle sobre o acesso e as permissões.

- Quotas de Serviço Consolidadas: Você pode gerenciar quotas de serviços AWS (anteriormente conhecidas como limites de serviço) no nível da organização, permitindo solicitar aumentos de quotas para várias contas simultaneamente.

As Organizações AWS são particularmente valiosas para organizações maiores ou empresas que possuem infraestruturas complexas da AWS e precisam de gerenciamento centralizado, faturação e governança em várias contas da AWS. Isso ajuda a manter a segurança, a conformidade e o controle de custos em um ambiente de nuvem distribuído.