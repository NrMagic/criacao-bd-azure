# Laboratório: Configuração de Banco de Dados no Microsoft Azure

Este repositório contém resumos, anotações e dicas sobre a configuração de instâncias de Banco de Dados na plataforma **Microsoft Azure**.  
O objetivo é servir como material de apoio para estudos e futuras implementações.

---

## 🎯 Objetivos de Aprendizagem
- Aplicar conceitos aprendidos em um ambiente prático
- Documentar processos técnicos de forma clara e estruturada
- Utilizar o GitHub como ferramenta de compartilhamento de documentação técnica

---

## 🛠️ Passo a Passo: Criando uma Instância de Banco de Dados no Azure

### 1. Acessar o Portal Azure
- Entre em [portal.azure.com](https://portal.azure.com) com sua conta Microsoft.

### 2. Criar um Recurso
- Clique em **Criar um recurso**.
- Selecione **Banco de Dados SQL** (ou MySQL/PostgreSQL, conforme sua necessidade).

### 3. Configurar o Servidor
- Defina:
  - **Nome do servidor**
  - **Usuário administrador**
  - **Senha**
  - **Região**

### 4. Definir o Banco de Dados
- Escolha o **nome do banco**.
- Selecione o **plano de serviço** (ex.: Básico, Standard, Premium).
- Configure **backup e redundância**.

### 5. Regras de Firewall
- Adicione o IP do seu computador para permitir conexões externas.

### 6. Revisar e Criar
- Revise as configurações.
- Clique em **Criar** e aguarde a implantação.

---


## 💡 Dicas e Boas Práticas
- Sempre configure **backup automático**.  
- Use **Azure Monitor** para acompanhar desempenho.  
- Restrinja acessos via firewall apenas a IPs confiáveis.  
- Considere usar **Azure CLI** para automação.

---

## 📚 Referências
- [Documentação oficial do Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/database/)  
- [Azure CLI - SQL Database](https://learn.microsoft.com/pt-br/cli/azure/sql/db)  
