# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: [08/08/2025]
Empresa: Abstergo Industries 
Responsavel: [Eduardo Cedro de Souza Junior]

## Introdução
Este relatorio apresenta o processo de implementação de ferramentas na empresa *[ Abstergo Industries ]*, realizado por *[Eduardo Cedro de Souza Junior]*. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuiçao de custos imediatos.
Na produção farmacêutica, a AWS oferece soluções escaláveis e eficientes que podem substituir infraestruturas físicas caras, melhorar a gestão de dados e otimizar processos.
*========================================================================================================================================*
## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto
*========================================================================================================================================*

## Etapa 1: Amazon EC2 Auto Scaling (Escalonamento Automático de Servidores)
*Nome da ferramenta*
- [Amazon EC2 Auto Scaling] 

*Foco da ferramenta:*
- [Garantir que a *Abtergo* tenha o número correto de instâncias EC2 em execução 
    para lidar com a carga da sua aplicação, de forma automática e eficiente]

*Descrição de caso de uso:*
- [A Abstergo Industries possui servidores físicos que ficam subutilizados fora de picos de produção.
    Com o Amazon EC2 Auto Scaling, a infraestrutura ajusta automaticamente o número de instâncias (servidores virtuais) 
    conforme a demanda.
    Economia: Paga-se apenas pelo uso real, evitando custos com servidores parados.]

*========================================================================================================================================*

## Etapa 2: Amazon S3 Intelligent-Tiering (Armazenamento de Dados com Custos Otimizados) 
*Nome da ferramenta*
- [Amazon S3 Intelligent-Tiering]

*Foco da ferramenta:*
- [ Otimizar custos de armazenamento em nuvem automaticamente, movendo dados entre camadas (tiers) de 
    armazenamento conforme padrões de acesso sem comprometer a disponibilidade ou a performance.]

*Descrição de caso de uso:*
- [A indústria farmacêutica lida com grandes volumes de dados (pesquisas, registros de produção, compliance).
    O Amazon S3 Intelligent-Tiering classifica automaticamente os dados em camadas de armazenamento 
    (frequente, pouco acessado, arquivamento).
    Economia: Redução de até 70% nos custos de armazenamento em comparação a servidores locais.]

*========================================================================================================================================*

Etapa 3: AWS Lambda (Processamento sem Servidores Permanentes)
*Nome da ferramenta*
- [AWS Lambda]

*Foco da ferramenta:*
- [Eliminar custos com servidores para tarefas eventuais.]

*Descrição de caso de uso:*
- [A Abstergo Industries executa tarefas como análise de lotes e relatórios de forma esporádica.
    O AWS Lambda permite rodar códigos (ex: Python, Java) sem manter servidores ativos 24/7.
    Economia: Cobrança apenas pelo tempo de execução (milissegundos), sem custos fixos.]

*========================================================================================================================================*

## Conclusão
A implementação dos serviços *AWS* na *Abstergo Industries* proporcionará:

 -Redução imediata de custos com infraestrutura física e servidores ociosos.
 -Otimização de armazenamento de dados com menor custo operacional.
 -Processamento eficiente de tarefas sem necessidade de servidores dedicados.
 
*========================================================================================================================================*
# Recomendações:

Monitorar os custos mensais no AWS Cost Explorer para ajustes contínuos.
Explorar outros serviços como Amazon RDS (banco de dados gerenciado) 
e AWS Batch (processamento em lote).

*========================================================================================================================================*
## Anexos
[lista de anexos, como manuais, documentos:


# AWS Calculator
  Acesse : https://calculator.aws/#/
  Configure uma estimativa de custo exclusivo que atenda às suas 
  necessidades de negócios com produtos e serviços da AWS.

# Manual Básico de EC2 Auto Scaling  
    A AWS tem um guia passo a passo: https://docs.aws.amazon.com/autoscaling/ec2/userguide/.
1 *Acesse o Console AWS* : 
    Serviço "EC2".  
2 *Crie um Launch Template*:
    (modelo da máquina virtual).  
3 *Configure o Auto Scaling Group* :  
   - Defina mínimo/máximo de instâncias (ex: 2 a 10 servidores).  
   - Escolha políticas de escalonamento (ex: aumentar se CPU > 70%).  
4. *Teste* : Simule carga e verifique se novas instâncias são ativadas.  

# Relatório de Economia - AWS Lambda  
  Simule custos em: https://aws.amazon.com/lambda/pricing/.
*Cenário:* 
  Processamento de lotes farmacêuticos (100.000 execuções/mês).  
*Custo AWS Lambda*: 
  US$ 0.02 (R$ 0.10)  
- *Custo Servidor Local*: 
  US$ 200 (R$ 1.000)  
*Economia estimada: 99%*
]

Assinatura do Responsavel pelo Projeto:

[Eduardo Cedro de Souza Junior]
