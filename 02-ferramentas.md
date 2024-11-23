
# Ferramentas de Infraestrutura como Código (IaC)

Abaixo são apresentadas as principais **ferramentas de Infraestrutura como Código (IaC)**:

---

### **1. [Terraform](https://www.terraform.io/)**
- Ferramenta da HashiCorp para provisionamento multi-nuvem e infraestrutura híbrida.
- **Destaques:**
  - Suporte a múltiplos provedores (AWS, Azure, GCP, VMware, etc.).
  - Linguagem declarativa HCL, fácil de usar e aprender.
  - Estado da infraestrutura armazenado para gerenciamento de mudanças.
  - Modularidade com reutilização de blocos de código.
- **Caso de uso:** Criar ambientes consistentes em várias plataformas e nuvens híbridas.

---

### **2. [AWS CloudFormation](https://aws.amazon.com/cloudformation/)**
- Ferramenta nativa da AWS para gerenciar recursos usando YAML ou JSON.
- **Destaques:**
  - Integração completa com os serviços da AWS.
  - Permite criar, atualizar e excluir stacks de infraestrutura de forma controlada.
  - Suporte a *Change Sets* para pré-visualizar alterações antes de aplicá-las.
- **Caso de uso:** Gerenciar e provisionar infraestrutura exclusivamente na AWS.

---

### **3. [Pulumi](https://www.pulumi.com/)**
- Define infraestrutura usando linguagens de programação como Python, TypeScript, Go, C#, entre outras.
- **Destaques:**
  - Flexibilidade ao usar linguagens familiares ao invés de DSLs.
  - Suporte a múltiplos provedores de nuvem e ambientes locais.
  - Permite incorporar lógica complexa ao provisionamento.
- **Caso de uso:** Provisionar infraestrutura integrada a lógica de aplicações.

---

### **4. [Google Cloud Deployment Manager](https://cloud.google.com/deployment-manager)**
- **Descrição:** Ferramenta nativa do Google Cloud que utiliza arquivos YAML para provisionamento de recursos.
- **Destaques:**
  - Integração total com os serviços do GCP.
  - Suporte a esquemas reutilizáveis para infraestrutura.
  - Facilita a criação de recursos específicos do GCP com templates prontos.
- **Caso de uso:** Gerenciar infraestrutura exclusivamente no Google Cloud.

---

### **5. [Azure Resource Manager (ARM) Templates](https://azure.microsoft.com/en-us/services/resource-manager/)**
- Ferramenta nativa do Azure que usa JSON para provisionar recursos.
- **Destaques:**
  - Configuração declarativa para criar e gerenciar infraestrutura Azure.
  - Suporte a *nested templates* para organizar ambientes complexos.
  - Integração com o Azure DevOps.
- **Caso de uso:** Configurar infraestrutura no Azure com foco em consistência e governança.

---

### **6. [AWS Cloud Development Kit (CDK)](https://aws.amazon.com/cdk/)**
- Framework para definir recursos AWS usando linguagens de programação como Python, Java, TypeScript e C#.
- **Destaques:**
  - Geração automática de templates CloudFormation.
  - Permite combinar infraestrutura e lógica de aplicação.
  - Foco em desenvolvedores que já dominam linguagens de programação.
- **Caso de uso:** Projetos AWS que exigem integração avançada entre infraestrutura e aplicações.

---

### **7. [Ansible](https://www.ansible.com/)**
- Ferramenta de automação que também pode ser usada como IaC para configurar e gerenciar infraestrutura.
- **Destaques:**
  - Baseada em YAML, com sintaxe simples.
  - *Agentless* (não requer agentes nos servidores gerenciados).
  - Boa para gerenciar ambientes em nuvem e híbridos.
- **Caso de uso:** Configuração rápida e reprodutível de ambientes pós-provisionamento.

---

### **8. [Chef](https://www.chef.io/)**
- Usa receitas em Ruby para descrever como a infraestrutura deve ser configurada.
- **Destaques:**
  - Boa para ambientes grandes e corporativos.
  - Oferece controle detalhado sobre a configuração.
- **Caso de uso:** Configuração de servidores e aplicação de políticas em grande escala.

---

### **9. [Puppet](https://puppet.com/)**
- **Descrição:** Ferramenta veterana de automação para configurar infraestrutura.
- **Destaques:**
  - Usa DSL própria para definir estados desejados.
  - Suporte a conformidade e auditorias.
- **Caso de uso:** Manutenção de configurações consistentes em ambientes corporativos.

---

### **10. [SaltStack](https://saltproject.io/)**
- Solução para gerenciar configurações e orquestrar infraestrutura.
- **Destaques:**
  - Alta escalabilidade.
  - Suporte a execução remota de comandos e gerenciamento de estados.
- **Caso de uso:** Gerenciar infraestrutura distribuída e aplicar alterações em massa.

---

### **11. [CFEngine](https://cfengine.com/)**
- Ferramenta de automação para gerenciar configurações em larga escala.
- **Destaques:**
  - Alta eficiência em ambientes corporativos.
  - Suporte a ambientes de legado.
- **Caso de uso:** Gerenciar grandes quantidades de servidores em data centers.

---

### **12. [Vagrant](https://www.vagrantup.com/)**
- Cria e gerencia ambientes de desenvolvimento usando máquinas virtuais ou contêineres.
- **Destaques:**
  - Integração com VirtualBox, VMware e outras plataformas.
  - Ideal para criar ambientes de desenvolvimento replicáveis.
- **Caso de uso:** Preparar ambientes para desenvolvimento local ou equipes.

---

### **13. [Bicep](https://github.com/Azure/bicep)**
- Alternativa ao ARM Templates para Azure com sintaxe mais simples e declarativa.
- **Destaques:**
  - Melhor legibilidade em comparação ao JSON.
  - Totalmente integrado ao Azure Resource Manager.
- **Caso de uso:** Configuração moderna de infraestrutura no Azure.

---
