RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 31/08/2025
Empresa: Abstergo Industries
Responsável: Bruno Monteiro Cardoso

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Bruno Monteiro Cardoso. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
Nome da ferramenta: AWS Trusted Advisor
Foco da ferramenta: Otimização de custos através de recomendações de boas práticas.
Descrição de caso de uso: Utilizar o AWS Trusted Advisor para realizar uma análise completa do ambiente atual da Abstergo Industries. Esta ferramenta irá inspecionar os recursos e identificar oportunidades de economia, como instâncias EC2 ociosas, volumes EBS não utilizados e endereços IP elásticos não associados. O objetivo é gerar um relatório inicial com ações diretas para eliminar gastos desnecessários.

Etapa 2:
Nome da ferramenta: AWS Cost Explorer
Foco da ferramenta: Visualização e análise detalhada de custos e padrões de uso.
Descrição de caso de uso: Implementar o AWS Cost Explorer para visualizar os gastos da empresa de forma granular. Com essa ferramenta, será possível identificar quais serviços estão gerando os maiores custos, analisar tendências de consumo por dia ou mês e, o mais importante, prever os gastos futuros. Isso permitirá que a Abstergo Industries crie orçamentos e alertas para evitar surpresas na fatura e tome decisões proativas de otimização.

Etapa 3:
Nome da ferramenta: Amazon S3 Intelligent-Tiering
Foco da ferramenta: Otimização de custo de armazenamento de dados.
Descrição de caso de uso: Aplicar o Amazon S3 Intelligent-Tiering aos buckets de armazenamento de dados da empresa. Este serviço monitora automaticamente os padrões de acesso aos objetos e os move para a camada de armazenamento mais econômica (como a camada de acesso infrequente), sem comprometer o desempenho ou a disponibilidade. Isso garantirá uma economia significativa em custos de armazenamento, especialmente para dados que não são acessados com frequência.