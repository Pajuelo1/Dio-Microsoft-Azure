Configuração de um Serviço de Banco de Dados no Azure: Passo a Passo pelo Portal Web.

A seguir, apresento um guia detalhado para configurar um serviço de banco de dados no Azure.

Passo a Passo pelo Portal Web

1. Crie sua Conta no Azure 

- Crie uma conta no [portal.azure.com](https://portal.azure.com) e siga o processo para criar uma conta.

2. Navegue até o Portal do Azure 

- Entre no painel principal do portal do Azure.
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
