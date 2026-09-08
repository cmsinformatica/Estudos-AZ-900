# 🟨 Dia 3 — Redes, Storage e Identidade

📅 **Sexta-feira — 11/09/2026**  
🎯 **Objetivo:** Compreender os fundamentos de networking, armazenamento e identidade no Azure.

---

# 🌐 1. Azure Virtual Network

O **Azure Virtual Network (VNet)** permite criar redes virtuais dentro do Azure.

Exemplo:

```text
Internet
   │
   ▼
Azure VNet
│
├── Subnet Web
├── Subnet Application
└── Subnet Database
```

---

# 2. Subnets

Uma VNet pode ser dividida em várias **subnets**.

Isso permite segmentar logicamente os recursos.

---

# 3. Network Security Groups

Os **NSGs** permitem controlar tráfego de rede por meio de regras.

As regras podem considerar elementos como:

- Origem
- Destino
- Porta
- Protocolo
- Permitir ou negar

---

# 4. VPN Gateway

Permite estabelecer conectividade VPN entre redes.

Exemplo:

```text
Empresa
   │
Internet
   │
VPN
   │
Azure
```

---

# 5. ExpressRoute

Fornece conectividade privada entre infraestrutura externa e serviços Microsoft através de um provedor de conectividade.

Diferentemente de uma VPN tradicional, a conexão não depende da Internet pública como caminho de transporte.

---

# 6. Azure DNS

Serviço de hospedagem e gerenciamento de domínios DNS utilizando a infraestrutura do Azure.

---

# 7. Load Balancer

Distribui tráfego entre diferentes recursos.

```text
Usuário
   │
   ▼
Load Balancer
   │
 ┌─┴────┐
 ▼      ▼
VM1    VM2
```

---

# 💾 8. Azure Storage

Serviços de armazenamento são fundamentais no Azure.

Principais tipos:

- Blob Storage
- Azure Files
- Queue Storage
- Table Storage
- Managed Disks

---

# 9. Blob Storage

Armazenamento de objetos.

Pode ser utilizado para:

- Imagens
- Vídeos
- Backups
- Logs
- Arquivos

---

# 10. Azure Files

Permite disponibilizar compartilhamentos de arquivos gerenciados na nuvem.

---

# 11. Managed Disks

Discos gerenciados utilizados principalmente com Azure Virtual Machines.

---

# 12. Redundância

Termos importantes:

### LRS

Locally Redundant Storage.

Mantém múltiplas cópias dos dados dentro de uma única região, em um datacenter primário.

### ZRS

Zone-Redundant Storage.

Replica dados de forma síncrona entre zonas de disponibilidade da região primária.

### GRS

Geo-Redundant Storage.

Replica os dados para uma região secundária.

### GZRS

Geo-Zone-Redundant Storage.

Combina redundância entre zonas na região primária com replicação geográfica para uma região secundária.

---

# 👤 13. Microsoft Entra ID

O **Microsoft Entra ID** é o serviço de gerenciamento de identidade e acesso baseado em nuvem da Microsoft.

Anteriormente era conhecido como:

**Azure Active Directory (Azure AD)**

---

# 14. Authentication

Authentication responde:

> **Quem é você?**

Exemplo:

```text
Usuário
   ↓
Login + credencial
   ↓
Identidade verificada
```

---

# 15. Authorization

Authorization responde:

> **O que você pode fazer?**

---

# 16. MFA

**Multi-Factor Authentication**

Exige mais de um fator de autenticação.

Isso aumenta a segurança das contas.

---

# 17. Single Sign-On

O **SSO** permite que uma identidade autenticada acesse diferentes aplicações compatíveis sem realizar um novo login completo para cada uma.

---

# 18. Conditional Access

Permite aplicar políticas de acesso considerando sinais e condições.

Exemplos:

- Usuário
- Localização
- Aplicação
- Dispositivo
- Risco

---

# 19. Azure RBAC

**Role-Based Access Control**

Permite controlar quem pode acessar recursos e quais ações podem executar.

Exemplo:

```text
Cristiano
   │
   ▼
Virtual Machine
   │
Role
   │
Reader
```

O usuário poderia visualizar o recurso sem necessariamente poder modificá-lo.

---

# ⚠️ Pegadinha importante

```text
Authentication
     ↓
Quem é você?

Authorization
     ↓
O que você pode fazer?
```

---

# 📝 Perguntas

1. Para que serve uma VNet?
2. Para que servem subnets?
3. O que faz um NSG?
4. Qual a diferença entre VPN Gateway e ExpressRoute?
5. Para que serve Blob Storage?
6. Qual a diferença entre LRS e GRS?
7. O que é Microsoft Entra ID?
8. Authentication e Authorization são a mesma coisa?
9. O que é MFA?
10. Para que serve RBAC?

---

# ✅ Checklist

- [ ] VNet
- [ ] Subnets
- [ ] NSG
- [ ] VPN Gateway
- [ ] ExpressRoute
- [ ] DNS
- [ ] Load Balancer
- [ ] Blob Storage
- [ ] Azure Files
- [ ] Managed Disks
- [ ] LRS
- [ ] ZRS
- [ ] GRS
- [ ] GZRS
- [ ] Entra ID
- [ ] MFA
- [ ] SSO
- [ ] Conditional Access
- [ ] RBAC

**Status:** ⬜ Não iniciado