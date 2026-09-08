# ☁️ AZ-900 — Microsoft Azure Fundamentals

Este repositório registra meu plano intensivo de estudos para a certificação **Microsoft Certified: Azure Fundamentals (AZ-900)**.

📅 **Período:** 09 a 13 de setembro de 2026  
🎯 **Objetivo:** Construir uma base sólida nos principais conceitos do Microsoft Azure e me preparar para o exame AZ-900.

---

## 🎯 Objetivos

Ao final deste cronograma, devo ser capaz de:

- Explicar os principais conceitos de computação em nuvem.
- Diferenciar IaaS, PaaS e SaaS.
- Entender os modelos de nuvem pública, privada e híbrida.
- Conhecer a infraestrutura global do Azure.
- Identificar os principais serviços de computação, rede e armazenamento.
- Compreender identidade, segurança e governança.
- Entender custos, SLAs e gerenciamento do Azure.
- Resolver questões simuladas no padrão da certificação AZ-900.

---

# 📅 Cronograma

| Dia | Data | Tema principal | Status |
|---|---|---|---|
| 🟦 Quarta | 09/09 | Fundamentos de Cloud Computing | ⬜ |
| 🟩 Quinta | 10/09 | Arquitetura e Serviços do Azure | ⬜ |
| 🟨 Sexta | 11/09 | Redes, Armazenamento e Identidade | ⬜ |
| 🟧 Sábado | 12/09 | Segurança, Governança, Custos e Monitoramento | ⬜ |
| 🟥 Domingo | 13/09 | Revisão Geral + Simulado AZ-900 | ⬜ |

---

# 🟦 Dia 1 — Quarta-feira

## Fundamentos de Cloud Computing

### Estudar

- O que é computação em nuvem
- Responsabilidade compartilhada
- Nuvem pública
- Nuvem privada
- Nuvem híbrida
- CapEx vs OpEx
- Alta disponibilidade
- Escalabilidade
- Elasticidade
- Confiabilidade
- Previsibilidade
- Segurança
- Governança
- Gerenciabilidade

### Modelos de serviço

#### IaaS
Infrastructure as a Service

Exemplos:
- Máquinas virtuais
- Redes
- Discos

#### PaaS
Platform as a Service

Exemplos:
- Azure App Service
- Bancos de dados gerenciados

#### SaaS
Software as a Service

Exemplos:
- Microsoft 365

### Meta do dia

Conseguir explicar:

> O que é Cloud Computing e quais problemas a computação em nuvem resolve?

---

# 🟩 Dia 2 — Quinta-feira

## Arquitetura e Serviços do Azure

### Infraestrutura global

Estudar:

- Regions
- Availability Zones
- Region Pairs
- Datacenters
- Geographies

### Estrutura administrativa

```text
Management Groups
       ↓
Subscriptions
       ↓
Resource Groups
       ↓
Resources
```

### Computação

Estudar:

- Azure Virtual Machines
- Virtual Machine Scale Sets
- Azure App Service
- Azure Functions
- Containers
- Azure Container Instances
- Azure Kubernetes Service

### Meta do dia

Entender como os recursos são organizados e onde as aplicações podem ser executadas dentro do Azure.

---

# 🟨 Dia 3 — Sexta-feira

## Redes, Armazenamento e Identidade

### Networking

Estudar:

- Azure Virtual Network
- Subnets
- Network Security Groups
- Azure DNS
- VPN Gateway
- Azure ExpressRoute
- Load Balancer
- Application Gateway

### Storage

Estudar:

- Storage Accounts
- Blob Storage
- Azure Files
- Queue Storage
- Table Storage
- Managed Disks

### Redundância

Entender:

- LRS
- ZRS
- GRS
- GZRS

### Identidade

Estudar:

- Microsoft Entra ID
- Authentication
- Authorization
- Multi-Factor Authentication
- Single Sign-On
- Conditional Access
- Azure RBAC

### Meta do dia

Conseguir explicar como usuários, máquinas e aplicações se conectam, armazenam dados e recebem permissões dentro do Azure.

---

# 🟧 Dia 4 — Sábado

## Segurança, Governança, Custos e Monitoramento

### Segurança

Estudar:

- Microsoft Defender for Cloud
- Zero Trust
- Defense in Depth
- Network Security Groups
- Microsoft Entra ID

### Governança

Estudar:

- Azure Policy
- Resource Locks
- Tags
- Azure RBAC
- Management Groups

### Custos

Estudar:

- Azure Pricing Calculator
- Azure Cost Management
- Fatores que afetam custos
- Modelos de consumo
- Reservas

### Gerenciamento e monitoramento

Estudar:

- Azure Portal
- Azure Cloud Shell
- Azure CLI
- Azure PowerShell
- Azure Resource Manager
- Azure Monitor
- Azure Advisor
- Service Health

### Meta do dia

Entender como uma empresa controla **segurança, acesso, custos e governança** de seus recursos Azure.

---

# 🟥 Dia 5 — Domingo

# Revisão + Simulado

## Revisão

Revisar principalmente:

### Cloud

- IaaS
- PaaS
- SaaS
- CapEx
- OpEx
- Escalabilidade
- Elasticidade
- Alta disponibilidade

### Arquitetura

- Regions
- Availability Zones
- Resource Groups
- Subscriptions
- Management Groups

### Serviços

- Virtual Machines
- App Service
- Functions
- Containers
- Storage
- Virtual Network

### Segurança

- Entra ID
- MFA
- RBAC
- Conditional Access
- Defender for Cloud

### Governança

- Azure Policy
- Tags
- Resource Locks

### Monitoramento

- Azure Monitor
- Azure Advisor
- Service Health

---

## 📝 Simulado

Realizar pelo menos:

**50 questões AZ-900**

Registrar o resultado:

```text
Questões: 50
Acertos:
Erros:
Percentual:
```

### Revisar todos os erros

Para cada questão errada:

```text
Questão:

Minha resposta:

Resposta correta:

Por que errei:

Conceito que preciso revisar:
```

---

# 📊 Controle de progresso

```text
Fundamentos Cloud          [░░░░░░░░░░] 0%
Arquitetura Azure          [░░░░░░░░░░] 0%
Compute                    [░░░░░░░░░░] 0%
Networking                 [░░░░░░░░░░] 0%
Storage                    [░░░░░░░░░░] 0%
Identidade                 [░░░░░░░░░░] 0%
Segurança                  [░░░░░░░░░░] 0%
Governança                 [░░░░░░░░░░] 0%
Custos                     [░░░░░░░░░░] 0%
Monitoramento              [░░░░░░░░░░] 0%
```

---

# 📂 Organização do repositório

```text
AZ-900/
│
├── README.md
│
├── 01-quarta-fundamentos-cloud.md
├── 02-quinta-arquitetura-azure.md
├── 03-sexta-redes-storage-identidade.md
├── 04-sabado-seguranca-governanca.md
└── 05-domingo-revisao-simulado.md
```

Cada arquivo representa um dia do cronograma e poderá conter:

- 📖 Teoria
- 💡 Exemplos
- 🧠 Conceitos importantes
- ⚠️ Pegadinhas da prova
- 📝 Questões
- ✅ Checklist
- 🔬 Exercícios práticos

---

# 🏆 Objetivo final

```text
        ☁️ MICROSOFT AZURE
               │
               ▼
       Azure Fundamentals
               │
               ▼
            AZ-900
               │
               ▼
          CERTIFICAÇÃO
```

**Meta: chegar ao domingo entendendo os conceitos, e não apenas decorando respostas.**

> Cloud não é apenas saber o nome dos serviços. É entender qual problema cada serviço resolve.