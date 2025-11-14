# infra-meuprojetoweb

Infraestrutura como código para o projeto **meuprojetoweb**, utilizando **Terraform** e **Azure**.

## 📌 Recursos criados
- Resource Group
- Virtual Network
- Subnets (backend e Bastion)
- Network Security Group
- VM Linux (Ubuntu)
- Azure Bastion

## 🚀 Como usar
1. Instale o Terraform: [https://developer.hashicorp.com/terraform/downloads](https://developer.hashicorp.com/terraform/downloads)
2. Configure suas credenciais do Azure:
   ```bash
   az login
