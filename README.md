# ☁️ AWS Solutions Architect - Associate (SAA-C03) | Hands-on Labs

Este repositório reúne a documentação técnica, diagramas e evidências de execução dos **laboratórios práticos** realizados durante a minha jornada de especialização em Arquitetura de Nuvem pela **Escola da Nuvem (EDN)**, focando na certificação **AWS Certified Solutions Architect - Associate (SAA-C03)**.

O objetivo deste repositório é consolidar o aprendizado teórico através da resolução de cenários do mundo real (*Break-Fix*), aplicação de boas práticas de segurança, governança e arquitetura resiliente na **Amazon Web Services (AWS)**.

---

## 🛠️ Tecnologias e Serviços AWS Abordados

- **Identidade e Segurança:** AWS IAM, AWS STS, IAM Identity Center, AWS KMS, AWS Secrets Manager, AWS Control Tower, AWS Organizations.
- **Redes e Conectividade:** Amazon VPC, Subnets (Públicas/Privadas), Route Tables, Internet/NAT Gateways, VPC Endpoints (Gateway & Interface/PrivateLink), VPC Peering, AWS Transit Gateway, Site-to-Site VPN, AWS Direct Connect.
- **Proteção de Borda e Perímetro:** Security Groups, Network ACLs (NACLs), Application Load Balancer (ALB), Network Load Balancer (NLB), AWS WAF, AWS Shield.
- **Armazenamento e Bancos de Dados:** Amazon S3 (Lifecycle, Object Lock, Replication SRR/CRR), Amazon EBS, Amazon RDS.
- **Auditoria, Monitoramento e Conformidade:** AWS CloudTrail, VPC Flow Logs, Amazon GuardDuty, Amazon Macie, Amazon Inspector, AWS Systems Manager (SSM).

---

## 📂 Estrutura de Laboratórios

Abaixo está o índice organizado por módulos do curso. Cada pasta contém um `README.md` dedicado detalhando o problema, o diagnóstico técnico, a solução aplicada com o **Princípio do Menor Privilégio** e as evidências em imagem.

### 🔒 Módulo 1: Design Secure Architectures (Acesso e Segurança)
- [`/modulo-01-seguranca/lab-01-iam-roles-troubleshooting`](./modulo-01-seguranca/lab-01-iam-roles-troubleshooting/): **Resolução de Problemas com IAM Roles e Assunção de Perfil via Console**
  - *Cenário Break-Fix:* Correção de falha de acesso de operador aplicando ajustes em *Identity Policies*, *Trust Policies* e permissões de `sts:AssumeRole`.
- `[Em breve]` **Acesso Privado a Serviços AWS via Gateway VPC Endpoints**
- `[Em breve]` **Criptografia de Dados em Repouso com SSE-KMS e Customer Managed Keys (CMK)**

### 🏗️ Módulo 2: Design Resilient Architectures (Redes e Alta Disponibilidade)
- `[Em breve]` **Segmentação de VPC Multi-AZ com Subnets Públicas, Privadas e NAT Gateway**
- `[Em breve]` **Conectividade Transitiva com AWS Transit Gateway**

---

## 📐 Princípios de Arquitetura Aplicados

Todos os laboratórios são executados seguindo os pilares do **AWS Well-Architected Framework**:
1. **Security (Segurança):** Aplicação estrita do *Princípio do Menor Privilégio* (*Least Privilege*), uso de credenciais temporárias (`AWS STS`) e eliminação de chaves estáticas.
2. **Operational Excellence (Excelência Operacional):** Documentação clara de diagnóstico de causa-raiz e etapas de recuperação (*Troubleshooting*).
3. **Reliability (Confiabilidade):** Estruturação de ambientes resilientes com suporte a *failover* e isolamento de falhas (*Blast Radius* reduzido).

---

## 👤 Autor

**Isaque S.**  
Estudante de Arquitetura de Nuvem e Desenvolvimento de Software | Aluno da Escola da Nuvem  
- 🔗 **LinkedIn:** [Acompanhe minha jornada](https://www.linkedin.com/in/seu-perfil-aqui/)  
- 💼 **GitHub:** [Mais projetos](https://github.com/seu-usuario-aqui)

---
*Este repositório é mantido de forma contínua como portfólio prático de estudos para a certificação AWS SAA-C03.*
# aws-saa-labs
