# azure-vm-implantacao-dio
Implantação de maquinas virtuais
# 💻 Implantação de Máquinas Virtuais no Microsoft Azure

Este repositório documenta a experiência prática do desafio da DIO envolvendo a criação, configuração e gerenciamento de Máquinas Virtuais (VMs) no Microsoft Azure, incluindo a desanexação de discos de dados.

## 📌 Objetivos

- Implantar e configurar máquinas virtuais no Azure.
- Gerenciar discos de VM, incluindo desanexar discos.
- Documentar todo o processo de forma clara e didática.
- Utilizar o GitHub para compartilhamento de conhecimento técnico.

## 🧠 Conceitos Abordados

- Criação de VM via portal do Azure
- Escolha da imagem e tamanho da VM
- Configuração de rede e segurança
- Conexão remota à VM (RDP/SSH)
- Adição e desanexação de discos de dados
- Boas práticas de gerenciamento

## 🔧 Etapas Realizadas

### 1. Criação da Máquina Virtual
- Sistema Operacional: Ubuntu Server 22.04 LTS
- Tamanho: Standard B1s
- Rede virtual e grupo de segurança configurados

### 2. Adição de Disco de Dados
- Disco de 32 GB criado e anexado
- Formatado e montado dentro da VM

### 3. Desanexando Disco da VM
- Parar a VM (necessário para alterações em disco)
- Selecionar o disco na seção "Discos"
- Clicar em "Desanexar"
- Disco fica disponível para uso em outra VM

### 4. Testes e Validações
- Verificação via `lsblk` antes e depois
- Monitoramento de status da VM e disco

## 📸 Imagens

As capturas de tela estão disponíveis na pasta [/images](./images) para ilustrar cada etapa.

## 📚 Referências

- [Documentação oficial do Azure sobre VMs](https://learn.microsoft.com/azure/virtual-machines/)
- [Gerenciar discos de dados no Azure](https://learn.microsoft.com/azure/virtual-machines/disks-types)

## 🚀 Autor

Jeymeson Guimarães  
Desafio da DIO - Trilha Azure Administrator

