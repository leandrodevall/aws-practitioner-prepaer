bloquear algo do host
- Security group

bloquear algo da subnet
- NACL


### VPC Peering

Se eu tiver duas VPCs dentro de uma region e uma
precisa se comunicar com a outra, por default não é possivel. No caso teriamos que ter uma estrategia de Peering.


### VPC Endpoints

Case: Se eu tenho um vpc dentro de uma region e precisa me comunicar com um S3, essa comunicação é dentro da rede AWS ou da internet comumn?

resposta: internet comumn

porém conseguimos corrigir isso usando VPC Endpoint

temos dois tipos:

Gateway para s3, dynamoDB

do tipo Interface para os demais outros


### VPC Monitoramento (VPC Flow Logs)

- verificar o trafego que acontece dentro da VPC e subnets, excelente para troubhc

- precisar habilitar, vem desabilitado por default
 
### Direct Connect

Link dedicado empresa e aws


