# Criando sua Primeira Máquina Virtual no Azure:

## Introdução

Este guia passo a passo irá te conduzir na criação de sua primeira máquina virtual (VM) no Microsoft Azure. Uma VM é um computador virtual que roda em um data center da Microsoft e pode ser acessado remotamente.

## Pré-requisitos

* **Conta Azure:** Tenha uma conta Azure ativa. Crie uma gratuitamente em https://portal.azure.com/.
* **Navegador web:** Use um navegador moderno como Chrome, Edge, Firefox ou Safari.

## Passo a Passo

### 1. Acessando o Portal do Azure
1. Abra seu navegador e vá para https://portal.azure.com/.
2. Faça login com suas credenciais da Microsoft.

### 2. Criando uma Nova Máquina Virtual
1. Na barra de pesquisa, digite "Máquinas Virtuais" e selecione o serviço.
2. Clique em "Criar".

### 3. Básicos
* **Nome:** Defina um nome descritivo para sua VM.
* **Grupo de recursos:** Selecione um grupo de recursos existente ou crie um novo.
* **Região:** Escolha a região mais próxima de você para reduzir a latência.

### 4. Instâncias
* **Imagem:** Escolha a imagem base do sistema operacional (Windows, Linux, etc.).
* **Tamanho:** Selecione o tamanho da VM, que define a quantidade de vCPUs e memória RAM.

### 5. Configurações de Instância
* **Nome de usuário e senha:** Defina as credenciais para acessar a VM remotamente.
* **Porta pública:** Abra a porta para acesso remoto (SSH para Linux, RDP para Windows).
* **Disco:** Escolha o tamanho do disco da VM.

### 6. Redes
* **Rede virtual:** Crie uma nova rede virtual ou selecione uma existente.
* **Sub-rede:** Crie uma nova sub-rede ou selecione uma existente.
* **Grupo de segurança de rede:** Configure as regras de firewall para controlar o tráfego.

### 7. Revisão e Criação
* **Revise:** Verifique todas as configurações antes de criar.
* **Criar:** Clique em "Criar" para iniciar o provisionamento da VM.

### 8. Conectando-se à VM
* **Endereço público:** Após a criação, anote o endereço IP público da VM.
* **Conexão remota:**
  * **Windows:** Use o Remote Desktop Connection (RDP).
  * **Linux:** Use um cliente SSH como PuTTY.

## Personalizando sua VM
* **Extensões:** Adicione extensões para personalizar sua VM.
* **Scripts de configuração:** Use scripts para automatizar a configuração inicial.

## Próximos Passos
* **Gerenciamento:** Use o portal do Azure para gerenciar sua VM (reiniciar, parar, etc.).
* **Exploração:** Descubra outros serviços do Azure para expandir sua solução.

## Documentação Oficial
Para mais informações e configurações avançadas, consulte a documentação oficial da Microsoft: https://docs.microsoft.com/azure/virtual-machines/

**Observações:**
* Os custos variam de acordo com o tamanho da VM, região e serviços adicionais.
* Para ambientes de produção, considere alta disponibilidade e recuperação de desastres.

**Com este guia, você está pronto para criar e gerenciar suas próprias máquinas virtuais no Azure!**

