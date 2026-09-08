# 🟩 Dia 2 — Arquitetura e Serviços do Azure

📅 **Quinta-feira — 10/09/2026**  
🎯 **Objetivo:** Entender como o Microsoft Azure é estruturado e conhecer seus principais serviços de computação.

---

# 1. Infraestrutura global do Azure

A infraestrutura do Azure é distribuída geograficamente.

Conceitos importantes:

- Datacenters
- Regions
- Availability Zones
- Region Pairs
- Geographies

---

# 2. Azure Regions

Uma **Region** é uma área geográfica que contém infraestrutura do Azure.

Ao criar determinados recursos, podemos escolher em qual região eles serão executados.

A escolha pode depender de:

- Latência
- Disponibilidade dos serviços
- Custos
- Requisitos legais
- Residência dos dados

---

# 3. Availability Zones

As **Availability Zones** são locais fisicamente separados dentro de uma região Azure compatível.

O objetivo é aumentar a resiliência.

Exemplo conceitual:

```text
Azure Region
│
├── Zone 1
│
├── Zone 2
│
└── Zone 3
```

Uma falha em uma zona não significa necessariamente que as outras zonas também serão afetadas.

---

# 4. Estrutura dos recursos

Uma estrutura importante para o AZ-900:

```text
Management Groups
       │
       ▼
Subscriptions
       │
       ▼
Resource Groups
       │
       ▼
Resources
```

---

# 5. Management Groups

Permitem organizar e aplicar governança a várias subscriptions.

Exemplo:

```text
Empresa
│
├── Brasil
│   ├── Subscription Produção
│   └── Subscription Desenvolvimento
│
└── Europa
    └── Subscription Produção
```

---

# 6. Subscriptions

Uma **Azure Subscription** funciona como um limite administrativo e de cobrança para recursos Azure.

Uma organização pode possuir várias subscriptions.

---

# 7. Resource Groups

Um **Resource Group** é um contêiner lógico para recursos relacionados.

Pode conter:

- Máquinas virtuais
- Redes
- Bancos de dados
- Storage Accounts
- Outros recursos

---

# 8. Resources

Resources são os serviços efetivamente criados no Azure.

Exemplos:

```text
Virtual Machine
Storage Account
Virtual Network
Database
Web App
```

---

# 9. Azure Virtual Machines

Azure Virtual Machines oferecem servidores virtuais na nuvem.

É um exemplo clássico de:

**IaaS**

O cliente possui bastante controle sobre:

- Sistema operacional
- Software
- Configuração
- Aplicações

---

# 10. Virtual Machine Scale Sets

Permitem administrar grupos de máquinas virtuais e aumentar ou diminuir a quantidade de instâncias conforme a necessidade.

---

# 11. Azure App Service

Plataforma para hospedar aplicações web e APIs.

É associado ao modelo:

**PaaS**

O desenvolvedor pode concentrar-se mais na aplicação e menos na administração da infraestrutura.

---

# 12. Azure Functions

Permite executar código baseado em eventos sem que o desenvolvedor precise administrar diretamente servidores.

É um exemplo importante de computação **serverless**.

---

# 13. Containers

Containers empacotam aplicações e suas dependências.

São mais leves que máquinas virtuais porque normalmente compartilham o kernel do sistema operacional do host.

---

# 14. Azure Container Instances

Permite executar containers no Azure sem administrar diretamente uma infraestrutura completa de máquinas virtuais.

---

# 15. Azure Kubernetes Service

O **AKS** é o serviço gerenciado do Azure para Kubernetes.

É utilizado para executar e administrar aplicações baseadas em containers em maior escala.

---

# 🧠 Mapa mental

```text
Compute
│
├── Virtual Machines
│
├── VM Scale Sets
│
├── App Service
│
├── Functions
│
├── Container Instances
│
└── AKS
```

---

# ⚠️ Para a prova

Saiba identificar cenários.

**Preciso controlar o sistema operacional:**

→ Virtual Machine

**Quero hospedar uma aplicação web sem administrar servidores:**

→ App Service

**Quero executar código baseado em eventos:**

→ Azure Functions

**Preciso orquestrar muitos containers:**

→ AKS

---

# 📝 Perguntas

1. O que é uma Azure Region?
2. Para que servem Availability Zones?
3. O que é uma Subscription?
4. O que é um Resource Group?
5. Qual serviço fornece máquinas virtuais?
6. Para que serve App Service?
7. O que significa serverless?
8. Para que serve AKS?

---

# ✅ Checklist

- [ ] Regions
- [ ] Availability Zones
- [ ] Management Groups
- [ ] Subscriptions
- [ ] Resource Groups
- [ ] Resources
- [ ] Virtual Machines
- [ ] Scale Sets
- [ ] App Service
- [ ] Functions
- [ ] Containers
- [ ] AKS

---

## 🎯 Meta do dia

Conseguir visualizar a estrutura:

```text
Azure
  ↓
Região
  ↓
Subscription
  ↓
Resource Group
  ↓
Resource
```

E saber escolher um serviço básico de computação para cada cenário.

**Status:** ⬜ Não iniciado