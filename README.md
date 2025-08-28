# 📄 Relatório de Implementação de Serviços AWS

**Data de início do projeto:** 27/08/2025  
**Empresa:** Abstergo Industries  
**Responsável pelo projeto:** Gabriel Alexander dos Santos

---

## 🧭 Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, conduzido por **Gabriel Alexander dos Santos**. O objetivo principal foi identificar e aplicar **três serviços estratégicos da AWS** com foco na **redução imediata de custos operacionais**, sem comprometer a escalabilidade, a segurança e a eficiência dos sistemas internos.

---

## 🛠️ Descrição e Etapas do Projeto

O projeto foi dividido em três etapas, cada uma com foco específico e aplicação prática voltada às necessidades da empresa.

| Etapa | Ferramenta                         | Foco da Ferramenta                                | Caso de Uso                                                                 |
|-------|------------------------------------|---------------------------------------------------|------------------------------------------------------------------------------|
| 1     | Amazon EC2 com Auto Scaling        | Infraestrutura escalável e resiliente             | Implementação de instâncias EC2 com Auto Scaling para suportar aplicações críticas que recebem pedidos simultâneos de múltiplos parceiros. O uso de balanceamento de carga (ELB) garante alta disponibilidade, enquanto o Auto Scaling ajusta automaticamente a capacidade computacional conforme a demanda, otimizando custos e desempenho. Ideal para sistemas de pedidos, controle de estoque e integração com ERPs. |
| 2     | Amazon S3 com Lifecycle Policies   | Armazenamento seguro e econômico                  | Criação de uma central de arquivos corporativos acessível por empresas parceiras, com controle de acesso via políticas de bucket e versionamento ativado para rastrear alterações. O uso de Lifecycle Policies permite a movimentação automática de documentos antigos para classes de armazenamento mais econômicas (ex: S3 Glacier), garantindo retenção segura e redução de custos sem comprometer a disponibilidade. |
| 3     | AWS API Gateway + AWS Lambda       | Integração entre empresas e automação de processos| Desenvolvimento de APIs RESTful com API Gateway e execução de lógica de negócio via AWS Lambda, permitindo que empresas parceiras consultem disponibilidade de produtos, enviem pedidos e recebam atualizações em tempo real. A arquitetura serverless elimina a necessidade de servidores dedicados, reduz custos operacionais e garante escalabilidade automática com segurança integrada. |

---

## ✅ Benefícios da Implementação

### 🔹 Operacionais
- Escalabilidade sob demanda  
- Redução de custos operacionais  
- Alta disponibilidade e confiabilidade  

### 🔹 Segurança e Conformidade
- Proteção de dados sensíveis  
- Criptografia e controle de acesso  
- Aderência a normas como LGPD  

### 🔹 Estratégicos
- Integração com parceiros  
- Automação de processos  
- Agilidade na tomada de decisão  
- Preparação para crescimento  

---

## 🎯 Conclusão

A implementação dos serviços AWS na **Abstergo Industries** resultou em ganhos significativos de **eficiência, segurança e escalabilidade**. Recomenda-se a continuidade do uso das ferramentas adotadas e a exploração de novas soluções em nuvem que possam ampliar ainda mais os resultados obtidos.

---

## 🔗 Links Úteis

- [Documentação oficial da AWS](https://docs.aws.amazon.com/)  
- [Amazon EC2 – Guia de Auto Scaling](https://docs.aws.amazon.com/autoscaling/)  
- [Amazon S3 – Lifecycle Policies](https://docs.aws.amazon.com/AmazonS3/latest/userguide/lifecycle-configuration-examples.html)  
- [AWS Lambda – Introdução](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)  
- [API Gateway – Criação de APIs RESTful](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html)  
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)  

---

**Assinatura do Responsável pelo Projeto:**  
Gabriel Alexander dos Santos