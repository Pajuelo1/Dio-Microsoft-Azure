Criação de Conta de Armazenamento no Azure: Passo a Passo pelo Portal Web

Passo a Passo pelo Portal Web

#### 1. Acesse o Portal do Azure 

- Faça login no [portal do Azure](https://portal.azure.com).

#### 2. Crie uma Conta de Armazenamento

- No painel de navegação, acesse o campo de pesquisar e escreva **"Contas de Armazenamento"**.
- Clique em **"Criar"**.

#### 3. Preencha os Detalhes Básicos 

- **Subscrição**: Já vem preenchido pois é de acordo com a sua assinatura no Azure.
- **Grupo de Recursos**: Se já tiver um criado basta selecionar. Caso não tenha, clique em 'Criar novo'.
- **Nome da Conta**: Esse campo é importante pois o nome da conta precisa ser único. 
- **Região**: Escolha a região onde a VM será hospedada (por exemplo, East US).
- **Desempenho**: Standard ou Premium. - Ambos são usados para diferentes propósitos.
  
#### 4. Proteção de Dados

- **DESABILITE AS OPÇÕES**: Ativar a eliminação recuperável para blobs - Ativar a eliminação recuperável para contentores e Ativar a eliminação recuoerável para partilhas de ficheiros.

#### 5. Revise e Crie 

- Revise todas as configurações.
- Clique em **"Revisar e Criar"**.
- Após a validação, clique em **"Criar"**.

#### 8. Conecte-se à Sua VM 

- Para VM Windows: Use Remote Desktop (RDP).
