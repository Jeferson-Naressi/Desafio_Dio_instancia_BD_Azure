# 📚  Tipos de Serviço de Nuvem na Azure e Banco de Dados no Azure  

---

## 🎯 Objetivo 
Nesta resumo vamos:  
- Entender os **modelos de serviço em nuvem** (IaaS, PaaS e SaaS).  
- Explorar o **modelo de responsabilidade compartilhada**.  
- Realizar um **desafio prático** criando uma instância de banco de dados no Azure.  
- Consolidar o aprendizado documentando tudo no GitHub.  

---

## 1. Introdução à Nuvem e Serviços do Azure  

A computação em nuvem oferece diferentes níveis de serviços que variam de acordo com o quanto o cliente precisa gerenciar e o quanto o provedor assume.  
No Azure, esses modelos se dividem principalmente em **IaaS, PaaS e SaaS**.  

---

## 2. Modelos de Serviço em Nuvem  

### 🔹 **IaaS (Infrastructure as a Service)**  
- Cliente gerencia: Sistema Operacional, Aplicações, Dados e Segurança.  
- Provedor gerencia: Rede, Servidores, Armazenamento e Virtualização.  
- **Exemplo:** Máquinas Virtuais no Azure.  

💡 **Quando usar:** ideal para quem precisa de flexibilidade total para instalar e configurar sistemas e aplicações.  

---

### 🔹 **PaaS (Platform as a Service)**  
- Cliente gerencia: Aplicações e Dados.  
- Provedor gerencia: Infraestrutura, SO, Banco de Dados, Middleware e Ferramentas.  
- **Exemplo:** Azure App Service, Azure SQL Database.  

💡 **Quando usar:** ótimo para desenvolvedores que querem focar apenas no código e deixar a gestão da infraestrutura para o provedor.  

---

### 🔹 **SaaS (Software as a Service)**  
- Cliente apenas consome o software pronto.  
- Provedor gerencia toda a infraestrutura e o aplicativo.  
- **Exemplo:** Microsoft 365, Outlook.com.  

💡 **Quando usar:** indicado quando o objetivo é simplesmente **usar a aplicação final** sem se preocupar com instalação ou manutenção.  

---

## 3. Modelo de Responsabilidade Compartilhada  

No Azure (e em qualquer provedor de nuvem), as responsabilidades são divididas:  

- **On-premises** → Cliente gerencia tudo.  
- **IaaS** → Cliente ainda cuida de bastante coisa (SO, apps e dados).  
- **PaaS** → Cliente se preocupa apenas com dados e aplicativos.  
- **SaaS** → Cliente só consome; provedor faz todo o resto.  

---

## 4. Desafio Prático – Criando um Banco de Dados no Azure  

### 🎯 Objetivo  
Configurar uma **instância de Banco de Dados SQL no Azure** para aplicar os conceitos aprendidos.  

### 📌 Passo a Passo  

1. Acesse o [Portal do Azure](https://portal.azure.com/).  
2. No painel de serviços, selecione **Azure SQL**.  
3. Clique em **Criar instância de banco de dados**.  
4. Preencha as informações básicas:  
   - **Grupo de Recursos**  
   - **Nome do Servidor**  
   - **Nome do Banco de Dados**  
   - **Localização (Região)**  
   - **Nível de desempenho (DTUs/vCores)**  
5. Configure rede e autenticação.  
6. Revise e crie o recurso.  
7. Após a implantação, conecte-se ao banco usando **SSMS** ou **Azure Data Studio** para validar.  

---

## 5. Aprendizados das Aulas  

- Diferenças entre **IaaS, PaaS e SaaS** ficaram mais claras.  
- Entendimento do **modelo de responsabilidade compartilhada**.  
- Experiência prática na **criação de uma instância SQL no Azure**.  
- Importância de documentar tudo em **Markdown no GitHub** para fixação e futuro estudo.  

---

## 6. Referências  

- [Documentação Oficial Microsoft Azure](https://learn.microsoft.com/pt-br/azure/)  
- [Criar uma Instância Gerenciada de SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/database/sql-database-paas-overview)  
- [Guia de Markdown no GitHub](https://guides.github.com/features/mastering-markdown/)  

---

## 👨‍🏫 Conclusão  

Hoje aprendemos que a nuvem não é “um único modelo”, mas sim **camadas de serviços** que variam do controle total pelo cliente até a entrega completa pelo provedor.  
Além disso, vimos como aplicar isso na prática configurando um **Banco de Dados SQL no Azure**.  

---
