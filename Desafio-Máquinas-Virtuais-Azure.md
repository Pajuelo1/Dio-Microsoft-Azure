Criação de VM no Azure: Passo a Passo pelo Portal Web e Azure CLI

A seguir, descrevo os passos para criar uma máquina virtual (VM) no Azure.

Passo a Passo pelo Portal Web

#### 1. Acesse o Portal do Azure 

- Faça login no [portal do Azure](https://portal.azure.com).

#### 2. Crie uma Nova Máquina Virtual 

- No painel de navegação, clique em **"Máquinas Virtuais"**.
- Clique em **"Criar"** e selecione **"Máquina Virtual"**.

#### 3. Preencha os Detalhes Básicos 

- **Nome da VM**: Digite um nome descritivo para a VM.
- **Região**: Escolha a região onde a VM será hospedada (por exemplo, East US).
- **Opções de Disponibilidade**: Selecione **Conjunto de Disponibilidade** ou **Zona de Disponibilidade** para garantir alta disponibilidade.
- **Imagem**: Escolha o sistema operacional.
- **Tamanho**: Selecione o tamanho da VM conforme suas necessidades de CPU e RAM.
- **Conta de administrador**: Configure o nome de usuário e a senha ou a chave SSH para login.

#### 4. Configure as Opções de Rede 

- **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
- **Sub-rede**: Escolha ou crie uma sub-rede.
- **Grupo de Segurança de Rede**: Configure ou selecione um NSG existente para definir as regras de firewall.

#### 5. Configure o Armazenamento e os Discos 

- **Disco do Sistema Operacional**: Selecione o tipo de disco (SSD Premium, HDD Standard).
- **Discos de Dados**: Adicione discos adicionais, se necessário.

#### 6. Defina as Configurações Avançadas

- **Monitoramento e Diagnóstico**: Habilite ou desabilite o monitoramento, backup e diagnósticos.

#### 7. Revise e Crie 

- Revise todas as configurações.
- Clique em **"Revisar e Criar"**.
- Após a validação, clique em **"Criar"**.

#### 8. Conecte-se à Sua VM 

- Para VM Windows: Use Remote Desktop (RDP).
