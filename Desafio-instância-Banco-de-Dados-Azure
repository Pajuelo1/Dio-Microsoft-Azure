Configuração de um Serviço de Banco de Dados no Azure: Passo a Passo pelo Portal Web.

A seguir, apresento um guia detalhado para configurar um serviço de banco de dados no Azure.

Passo a Passo pelo Portal Web

1. Crie sua Conta no Azure 

- Se ainda não possui uma conta no Azure, visite [portal.azure.com](https://portal.azure.com) e siga o processo para criar uma conta. Com a conta pronta, você está pronto para prosseguir!

2. Navegue até o Portal do Azure 

- Após o login, vá para o painel principal do portal do Azure.
- No menu superior, clique em **"Criar um recurso"**.
- Pesquise por **"SQL Database"** ou clique na categoria **"Banco de Dados"** e selecione **"SQL Database"**.

3. Crie um Novo Banco de Dados 

1. **Clique em "Criar"** para iniciar o assistente de configuração.
2. **Preencha os Detalhes**:
   - **Nome do Banco de Dados**: Escolha um nome exclusivo.
   - **Assinatura**: Selecione a assinatura do Azure que você está utilizando.
   - **Grupo de Recursos**: Crie um novo grupo ou selecione um existente.
   - **Servidor**: Crie um novo servidor ou escolha um já existente. Ao criar um novo servidor, preencha o nome, localização e defina as credenciais de administrador (usuário e senha).

4. Configurações do Banco de Dados 

- **Plano de Tarifação**: Escolha o plano adequado às suas necessidades (DTU ou vCore). Para testes, você pode selecionar o plano básico ou gratuito.
- **Backup e Recuperação**: Configure a política de backup para atender aos requisitos de segurança e conformidade da sua organização.

5. Revise e Crie 

- Revise todas as configurações para garantir que tudo esteja correto.
- Clique em **"Revisar e Criar"** e depois em **"Criar"**. Aguarde alguns minutos para que o Azure configure o banco de dados.

6. Conecte-se ao Seu Banco de Dados

- Após a criação, conecte-se ao banco de dados usando ferramentas como **SQL Server Management Studio (SSMS)** ou **Azure Data Studio**.
- Use as credenciais configuradas anteriormente para acessar.

7. Explore e Utilize Seu Banco de Dados!

- Agora que seu banco de dados está pronto, você pode começar a adicionar dados, executar consultas e explorar o SQL Database do Azure!

---
Passo a Passo Usando Azure CLI

1. Configure o Azure CLI

Certifique-se de que o Azure CLI está instalado e atualizado. Abra o terminal de comando ou o Azure Cloud Shell e faça login:

```bash
az login
```

2. Crie um Grupo de Recursos (se necessário)

```bash
az group create --name MeuGrupoDeRecursos --location eastus
```

3. Crie um Servidor de Banco de Dados SQL

```bash
az sql server create \
  --name MeuServidorSQL \
  --resource-group MeuGrupoDeRecursos \
  --location eastus \
  --admin-user adminuser \
  --admin-password MinhaSenhaSegura!
```

4. Crie um Banco de Dados SQL

```bash
az sql db create \
  --resource-group MeuGrupoDeRecursos \
  --server MeuServidorSQL \
  --name MeuBancoDeDados \
  --service-objective S0
```

5. Configure Firewall para Acesso ao Servidor

Permita acesso ao servidor de banco de dados SQL adicionando regras de firewall:

```bash
az sql server firewall-rule create \
  --resource-group MeuGrupoDeRecursos \
  --server MeuServidorSQL \
  --name PermitirMinhaIP \
  --start-ip-address <Seu-IP> \
  --end-ip-address <Seu-IP>
```

Substitua `<Seu-IP>` pelo seu endereço IP público atual.

6. Conecte-se ao Seu Banco de Dados 

Conecte-se ao banco de dados usando o **SQL Server Management Studio (SSMS)** ou **Azure Data Studio** com as credenciais de administrador que você criou.

7. Monitore e Utilize o Banco de Dados 

- Utilize o **Azure Monitor** e o **Log Analytics** para monitorar o desempenho.
- Use o **Azure Data Studio** para gerenciar o banco de dados, executar consultas e adicionar dados.
