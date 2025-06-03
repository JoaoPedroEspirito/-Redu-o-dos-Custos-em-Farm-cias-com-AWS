# -Redução-dos-Custos-em-Farmacias-com-AWS! 

---

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 29/05/2025
**Empresa:** Abstergo Industries
**Responsável:** João Pedro A E Santo

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por João Pedro A E Santo. O objetivo do projeto foi elencar três serviços da AWS com a finalidade de realizar diminuição de custos imediatos, aumentar a segurança e otimizar os processos operacionais da empresa.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em três etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1: **AWS Lambda – Computação Serverless**

**Foco da ferramenta:** Redução de custos operacionais, eliminação de servidores ociosos e aumento de escalabilidade.

A AWS Lambda permite executar códigos sem a necessidade de provisionamento ou gerenciamento de servidores. A cobrança é feita apenas pelo tempo de execução do código, medido em milissegundos, o que elimina custos com servidores ociosos e reduz despesas operacionais.

**Benefícios:**

* **Eficiência de Custos:** O modelo de cobrança por uso garante que a empresa pague apenas pelo tempo de execução real do código, evitando gastos com recursos não utilizados.

* **Escalabilidade Automática:** O Lambda escala automaticamente conforme a demanda, sendo ideal para cargas de trabalho intermitentes ou imprevisíveis.

* **Integração com Outros Serviços:** Pode ser integrado com diversos serviços da AWS, como S3, DynamoDB e API Gateway, facilitando a criação de arquiteturas serverless eficientes.

---

### Etapa 2: **Amazon CloudFront – Rede de Distribuição de Conteúdo (CDN)**

**Foco da ferramenta:** Aumento da performance de sites e aplicações e redução de custos de largura de banda.

O Amazon CloudFront é um serviço de CDN que entrega conteúdo com baixa latência e alta velocidade para usuários ao redor do mundo, além de proteger contra ataques DDoS através da integração com o AWS Shield.

**Benefícios:**

* **Redução de Latência:** Distribui conteúdo por meio de uma rede global de pontos de presença, melhorando a velocidade de entrega para os usuários finais.

* **Economia de Largura de Banda:** Ao armazenar em cache o conteúdo mais próximo dos usuários, reduz a necessidade de transferências repetidas de dados, resultando em economia de custos.

* **Segurança Integrada:** Oferece integração com o AWS Shield para proteção contra ataques DDoS e suporte ao AWS WAF para filtragem de tráfego malicioso.

---

### Etapa 3: **AWS Backup – Gerenciamento Centralizado de Backups**

**Foco da ferramenta:** Automação, segurança e gerenciamento de backups em toda a infraestrutura AWS.

O AWS Backup permite criar, gerenciar e automatizar backups de diversos serviços (EBS, RDS, DynamoDB, S3, etc.) em um painel centralizado, garantindo alta durabilidade, criptografia dos dados e recuperação eficiente.

**Benefícios:**

* **Automação de Backups:** Permite configurar políticas de backup automatizadas para diversos serviços da AWS, garantindo consistência e conformidade.

* **Redução de Custos com Armazenamento:** Ao utilizar classes de armazenamento como S3 Glacier e S3 Glacier Deep Archive, é possível reduzir significativamente os custos de armazenamento de longo prazo.

* **Recuperação Rápida:** Facilita a restauração de dados em caso de falhas ou perda de informações, minimizando o tempo de inatividade.

---

## Validação Técnica da Implementação

A combinação dos serviços AWS Lambda, Amazon CloudFront e AWS Backup é tecnicamente válida e funcional, sendo amplamente utilizada por empresas que buscam escalabilidade, automação e redução de custos na nuvem.

* **AWS Lambda:** Permite a execução de código sem a necessidade de gerenciamento de servidores, com escalabilidade automática e cobrança baseada no tempo de execução, o que resulta em economia significativa, especialmente para aplicações com uso intermitente.

* **Amazon CloudFront:** Melhora a performance de entrega de conteúdo e reduz custos de largura de banda ao armazenar em cache o conteúdo em pontos de presença globais, além de oferecer segurança integrada contra ataques DDoS.

* **AWS Backup:** Automatiza o processo de backup e permite o uso de soluções de armazenamento de baixo custo, como o S3 Glacier, otimizando despesas com armazenamento de dados e garantindo a recuperação eficiente em caso de falhas.

---

## Considerações sobre Redução de Custos

* **AWS Lambda:** Ideal para cargas de trabalho event-driven, o Lambda elimina a necessidade de manter servidores em execução contínua, resultando em economia significativa. Empresas que adotaram o Lambda relataram reduções de custos de até 85% em comparação com arquiteturas tradicionais.

* **Amazon CloudFront:** Ao reduzir a carga nos servidores de origem e minimizar transferências de dados, o CloudFront contribui para a diminuição dos custos operacionais. Empresas como a Arc XP conseguiram economizar até US\$ 500.000 por ano em custos de transferência de dados utilizando o CloudFront em conjunto com o Lambda\@Edge.([Amazon Web Services, Inc.][1])

* **AWS Backup:** Automatiza o processo de backup e permite o uso de soluções de armazenamento de baixo custo, como o S3 Glacier, otimizando despesas com armazenamento de dados.

---

## Conclusão

A implementação dos serviços AWS Lambda, Amazon CloudFront e AWS Backup proporcionará uma significativa redução de custos para a Abstergo Industries, além de melhorias em segurança, automação e escalabilidade. A adoção de arquiteturas serverless, uso de CDN e centralização de backups contribui diretamente para uma infraestrutura mais moderna, eficiente e resiliente.

Recomenda-se complementar este projeto futuramente com a adoção de ferramentas como o AWS Cost Explorer para monitoramento de custos e o AWS Trusted Advisor para otimização contínua dos recursos.

---

## Anexos

* [O que é AWS Lambda](https://aws.amazon.com/pt/lambda/)
* [Sobre Amazon CloudFront](https://aws.amazon.com/pt/cloudfront/)
* [Sobre AWS Backup](https://aws.amazon.com/pt/backup/)

---

**Assinatura do Responsável pelo Projeto:**
João Pedro A E Santo

---
