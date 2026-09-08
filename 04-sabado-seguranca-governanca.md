# 🟧 Dia 4 — Segurança, Governança, Custos e Monitoramento

📅 **Sábado — 12/09/2026**  
🎯 **Objetivo:** Entender como o Azure protege, governa, monitora e controla custos dos recursos.

---

# 🔐 1. Zero Trust

O modelo Zero Trust trabalha com princípios como:

```text
Verificar explicitamente

Usar acesso com menor privilégio

Assumir possibilidade de comprometimento
```

Não se deve confiar automaticamente em uma solicitação apenas porque ela veio de determinada rede.

---

# 2. Defense in Depth

Utilização de várias camadas de proteção.

Exemplo conceitual:

```text
Dados
  ↑
Aplicação
  ↑
Computação
  ↑
Rede
  ↑
Perímetro
  ↑
Identidade
  ↑
Segurança física
```

A ideia é evitar depender de apenas um mecanismo de segurança.

---

# 3. Microsoft Defender for Cloud

Serviço voltado ao gerenciamento da postura de segurança e proteção de workloads em ambientes de nuvem.

Ajuda a identificar:

- Recomendações de segurança
- Vulnerabilidades
- Configurações inadequadas
- Ameaças

---

# 🏛️ 4. Governança

Governança permite estabelecer controles sobre como os recursos da organização são utilizados.

Ferramentas importantes:

- Azure Policy
- Resource Locks
- Tags
- RBAC
- Management Groups

---

# 5. Azure Policy

Permite criar e aplicar regras relacionadas à configuração e conformidade dos recursos.

Exemplo:

```text
POLÍTICA

Recursos somente podem
ser criados em regiões
autorizadas.
```

---

# 6. Resource Locks

Protegem recursos contra alterações ou exclusões acidentais.

Tipos importantes:

```text
Delete
ReadOnly
```

---

# 7. Tags

Tags são metadados utilizados para organizar recursos.

Exemplo:

```text
Environment = Production
Department  = TI
Project     = ERP
Owner       = Infraestrutura
```

---

# 💰 8. Custos

O Azure utiliza, em muitos serviços, modelos baseados no consumo.

O custo pode variar de acordo com fatores como:

- Serviço
- Região
- Consumo
- Tipo de recurso
- Transferência de dados
- Modelo de compra

---

# 9. Azure Pricing Calculator

Ferramenta utilizada para estimar o custo de serviços Azure antes da implantação.

---

# 10. Azure Cost Management

Ajuda organizações a analisar e controlar seus gastos com Azure.

---

# 🛠️ 11. Ferramentas de gerenciamento

Principais formas de administrar Azure:

```text
Azure Portal
Azure CLI
Azure PowerShell
Azure Cloud Shell
```

---

# 12. Azure Resource Manager

O **ARM** é a camada de gerenciamento e implantação dos recursos do Azure.

Permite trabalhar com recursos de maneira consistente e automatizada.

---

# 📊 13. Azure Monitor

Plataforma de monitoramento utilizada para coletar, analisar e responder a dados de monitoramento de recursos e aplicações.

---

# 14. Azure Advisor

Analisa recursos e fornece recomendações.

As recomendações podem envolver áreas como:

- Custos
- Segurança
- Confiabilidade
- Desempenho
- Excelência operacional

---

# 15. Azure Service Health

Fornece informações sobre problemas e eventos relacionados aos serviços Azure que podem afetar os recursos do cliente.

---

# 🧠 Não confunda

```text
Azure Monitor
→ Monitoramento e observabilidade

Azure Advisor
→ Recomendações

Service Health
→ Saúde/incidentes dos serviços Azure

Azure Policy
→ Regras e conformidade

RBAC
→ Permissões de acesso
```

---

# 📝 Perguntas

1. O que significa Zero Trust?
2. O que é Defense in Depth?
3. Para que serve Defender for Cloud?
4. Para que serve Azure Policy?
5. Para que servem Resource Locks?
6. Para que servem Tags?
7. Para que serve Pricing Calculator?
8. Qual a função do Azure Monitor?
9. Qual a função do Azure Advisor?
10. Para que serve Service Health?

---

# ⚠️ Foco para prova

Uma questão pode perguntar:

> Quero impedir que recursos sejam criados fora de determinadas regiões.

Resposta provável:

**Azure Policy**

Outra:

> Quero evitar que uma VM importante seja excluída acidentalmente.

Resposta:

**Resource Lock**

Outra:

> Quero receber recomendações para otimizar meus recursos.

Resposta:

**Azure Advisor**

---

# ✅ Checklist

- [ ] Zero Trust
- [ ] Defense in Depth
- [ ] Defender for Cloud
- [ ] Azure Policy
- [ ] Resource Locks
- [ ] Tags
- [ ] RBAC
- [ ] Pricing Calculator
- [ ] Cost Management
- [ ] Azure Portal
- [ ] CLI
- [ ] PowerShell
- [ ] Cloud Shell
- [ ] ARM
- [ ] Azure Monitor
- [ ] Advisor
- [ ] Service Health

**Status:** ⬜ Não iniciado