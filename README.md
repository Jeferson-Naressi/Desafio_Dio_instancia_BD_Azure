# Configurando-uma instancia de Banco de Dados na Azure
Meu repositório criado para o projeto Dio Configurando uma instância de Banco de Dados na Azure

# Configurando uma Instância de Banco de Dados no Azure
Meu repositório criado para o projeto Dio Configurando uma Instância de Banco de Dados no Azure

## Passo a Passo para Configurar uma Instância de Banco de Dados no Azure

### Passo 1: Acessar o Portal do Azure 
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar um Banco de Dados SQL
2 - __Pesquisar por SQL Databases:__ No menu de navegação à esquerda, clique em “SQL Databases” ou digite “SQL Databases” na barra de pesquisa e selecione a opção.

3 - __Criar um novo Banco de Dados:__ Na página de SQL Databases, clique em “Criar” e depois em “Banco de Dados SQL do Azure”.

### Passo 3: Configurar o Banco de Dados

4 - __Configurações Básicas:__
   - **Assinatura:** Selecione a assinatura do Azure que você deseja usar.
   - **Grupo de Recursos:** Escolha um grupo de recursos existente ou crie um novo.
   - **Nome do Banco de Dados:** Dê um nome ao seu banco de dados.
   - **Servidor:** Crie um novo servidor ou selecione um servidor existente. Para criar um novo servidor, forneça um nome de servidor, um nome de administrador e uma senha.
   - **Localização:** Selecione a localização do servidor.

5 - __Configurações de Elastic Pool (opcional):__
   - **Elastic Pool:** Se você deseja usar um pool elástico, selecione “Sim” e configure o pool. Caso contrário, selecione “Não”.

6 - __Configurações de Computação e Armazenamento:__
   - **Nível de Serviço:** Escolha entre as opções disponíveis (por exemplo, Básico, Standard, Premium) com base nas suas necessidades de desempenho e custo.
   - **Tamanho do Computador:** Selecione o tamanho do computador e a quantidade de armazenamento.

### Passo 4: Configurações Adicionais

7 - __Configurações de Rede:__
   - **Rede Virtual:** Configure a rede virtual se necessário.
   - **Regras de Firewall:** Adicione regras de firewall para permitir o acesso ao banco de dados de endereços IP específicos.

8 - __Configurações de Segurança:__
   - **Autenticação:** Configure a autenticação do banco de dados (por exemplo, autenticação do SQL ou do Azure AD).
   - **Auditoria e Segurança Avançada:** Ative ou desative as opções de auditoria e segurança avançada conforme necessário.

### Passo 5: Revisar e Criar

9 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a implantação do banco de dados.

### Passo 6: Conectar ao Banco de Dados

10 - __Conectar-se ao Banco de Dados:__ Após a criação, vá para a página do banco de dados e clique em “Conectar”. Siga as instruções para se conectar usando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio.

## Links Úteis 

Implantar e configurar servidores, instâncias e bancos de dados para o SQL Azure:https://learn.microsoft.com/pt-br/training/modules/azure-sql-deploy-configure/

Como criar banco de dados Azure SQL: https://youtu.be/CIzs7KY3Jl4?si=9v7tsQ5AxVAA7XL4
