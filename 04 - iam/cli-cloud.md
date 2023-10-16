### console web, cli script, cloudshell

Console Web

- Um console web geralmente se refere a uma interface de usuário fornecida por um aplicativo ou serviço da web. No contexto da computação em nuvem, muitos provedores de nuvem oferecem consoles web que permitem aos usuários interagir e gerenciar seus recursos de nuvem por meio de um navegador da web.

- No caso da AWS, o console web é chamado de Console de Gerenciamento da AWS. Você pode acessá-lo visitando o site da AWS e fazendo login em sua conta. A partir daí, você pode criar, configurar e gerenciar vários recursos da AWS usando uma interface gráfica de usuário (GUI).

Script de Linha de Comando (CLI)

- Um script de Linha de Comando (CLI) é um script ou programa que pode ser executado em um terminal de texto para realizar tarefas ou automações específicas. Esses scripts são frequentemente usados para automatizar tarefas repetitivas e interagir com sistemas ou serviços por meio de comandos de texto.

- Na AWS, você pode usar a AWS Command Line Interface (CLI) para interagir com os serviços da AWS por meio de comandos de texto no terminal. Isso permite que você automatize tarefas, gerencie recursos e realize diversas operações na AWS usando scripts.

AWS CloudShell

A AWS CloudShell é um ambiente de linha de comando interativo baseado na web oferecido pela Amazon Web Services (AWS). Ele permite que você acesse uma instância efêmera do Amazon Linux 2 diretamente do console da AWS, sem a necessidade de configurar seu próprio ambiente de desenvolvimento. Você pode usar a AWS CloudShell para executar comandos da AWS CLI, scripts e até mesmo instalar ferramentas adicionais para desenvolvimento e gerenciamento de recursos na AWS.

### AWS acess key e SDK

AWS Access Keys (Chaves de Acesso da AWS) e o SDK (Software Development Kit) da AWS são componentes importantes para interagir e programar com os serviços da Amazon Web Services. Aqui está uma explicação mais detalhada sobre ambos:

AWS Access Keys (Chaves de Acesso da AWS)

- As AWS Access Keys são credenciais de autenticação que consistem em uma chave de acesso (Access Key ID) e uma chave secreta (Secret Access Key). Elas são usadas para autenticar aplicativos, scripts ou serviços que desejam acessar recursos na AWS em nome de um usuário ou uma conta.

- Você pode criar pares de chaves de acesso na AWS e atribuí-los a usuários ou funções para controlar quem tem permissão para acessar recursos e serviços. É importante manter essas chaves secretas, pois elas são usadas para assinar solicitações de API da AWS.

- As chaves de acesso são frequentemente usadas com a AWS CLI, SDKs da AWS, e bibliotecas de terceiros para automatizar tarefas, gerenciar recursos e interagir com os serviços da AWS por meio de código.

SDK da AWS (Software Development Kit)

- O SDK da AWS é um conjunto de bibliotecas e ferramentas fornecido pela Amazon para várias linguagens de programação. Ele simplifica a interação e a integração de aplicativos com os serviços da AWS, permitindo que os desenvolvedores acessem facilmente recursos da AWS em seus programas.

- O SDK da AWS oferece uma API de alto nível para serviços individuais da AWS, o que significa que os desenvolvedores não precisam se preocupar com os detalhes de comunicação com a API da AWS. Eles podem usar métodos e classes fornecidos pelo SDK para realizar operações comuns nos serviços da AWS.

- O SDK da AWS está disponível para várias linguagens de programação populares, como Python, Java, JavaScript (Node.js), Ruby, C#, e outras. Cada SDK é projetado para a linguagem de programação específica, tornando a integração com a AWS mais conveniente.

Para começar a usar o SDK da AWS, você geralmente precisará configurar as credenciais de autenticação (Access Key ID e Secret Access Key) em seu ambiente de desenvolvimento, para que o SDK possa autenticar suas solicitações à AWS. Certifique-se de proteger essas credenciais adequadamente e não compartilhá-las publicamente.

Em resumo, as AWS Access Keys são usadas para autenticação e autorização ao acessar a AWS, enquanto o SDK da AWS facilita o desenvolvimento de aplicativos que interagem com os serviços da AWS.


cada usuario tem duas chaves:

- acess key para console
- private key para CLI