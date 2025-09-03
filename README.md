<h1>Abstergo Cloud Strategy</h1>
Plano estratégico de adoção de Cloud na Abstergo Industries, com foco em soluções AWS para armazenamento, bancos de dados e Business Intelligence, visando otimização de custos, e eficiência operacional. 


<h2>RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS</h2>
<b>Data</b>: 01/09/2025
<b>Empresa</b>: Abstergo Industries
<b>Responsável</b>: Jose Modolo Neto

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Jose Modolo Neto. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
Amazon S3 (Simple Storage Service)
Foco da ferramenta: Armazenamento seguro e escalável.
Descrição do caso de uso:
O Amazon S3 será utilizado como o repositório central de objetos digitais da empresa, implementando armazenamento distribuído com redundância geográfica em múltiplas zonas de disponibilidade (AZs). A configuração terá versionamento de objetos e lifecycle policies para otimizar os custos entre classes de armazenamento (Standard, Infrequent Access e Glacier). E também,  serão aplicadas políticas de IAM e bucket policies para garantir acesso controlado e seguro. Essa abordagem elimina a necessidade de aquisição de storage físico, aumenta a resiliência contra perda de dados, garantindo escalabilidade imediata conforme a demanda da Abstergo Industries.

Etapa 2:
Amazon RDS (Relational Database Service)
Foco da ferramenta: Gerenciamento de banco de dados em nuvem.
Descrição do caso de uso:
O Amazon RDS será implementado para prover bancos de dados relacionais críticos (ex.: MySQL ou PostgreSQL) em ambiente gerenciado, com suporte a Multi-AZ Deployment para alta disponibilidade e Read Replicas para balanceamento de carga em consultas analíticas. A configuração prevê backups automáticos e snapshots manuais para atender requisitos de adequação. O uso de monitoramento via CloudWatch permitirá acompanhar métricas de performance em tempo real, reduzindo a necessidade de administração manual de servidores. Essa arquitetura proporciona maior credibilidade operacional, segurança de dados e escalabilidade sob demanda, ao mesmo tempo que otimiza custos com infraestrutura local.

Etapa 3:
Amazon QuickSight
Foco da ferramenta: Business Intelligence e visualização de dados.
Descrição do caso de uso:
O Amazon QuickSight será configurado como camada de visualização analítica, integrado ao Amazon RDS e ao Amazon S3 por meio de SPICE Engine (Super-fast, Parallel, In-memory Calculation Engine) para consultas de alta performance em grandes volumes de dados. Vão ser desenvolvidos dashboards interativos com métricas financeiras chave (KPIs), como fluxo de caixa, alteração de custos operacionais e projeções de receita. A solução suportará atualizações automáticas de datasets e controle de acesso baseado em grupos IAM, garantindo segurança na distribuição de relatórios. Com isso, a área financeira terá acesso a relatórios em tempo real e insights estratégicos sem necessidade de processamento manual de dados.
Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado redução de custos operacionais, maior segurança e disponibilidade dos dados, escalabilidade sob demanda e geração de insights estratégicos em tempo real, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos
Amazon S3 Documentation:
https://docs.aws.amazon.com/s3/

Amazon RDS Documentation:
https://docs.aws.amazon.com/rds/

Amazon QuickSight Documentation:
https://docs.aws.amazon.com/quicksight/

Assinatura do Responsável pelo Projeto:

Jose Modolo Neto
