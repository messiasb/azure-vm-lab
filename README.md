# azure-vm-lab
Este repositório contém resumo como criar VM na AZURE  / lab na DIO


# 🖥️ Laboratório - Criação de Máquina Virtual no Azure

Este repositório documenta o processo de criação e configuração de uma **máquina virtual (VM)** utilizando o **Microsoft Azure**. O objetivo é fixar os conceitos aprendidos durante as aulas e fornecer uma referência prática para estudos futuros.

---

## 📌 Objetivo

- Criar uma máquina virtual via **Portal do Azure**
- Configurar as opções principais: sistema operacional, rede e tamanho
- Acessar a VM via RDP (Windows) ou SSH (Linux)
- Documentar todas as etapas e aprendizados

---

## 🚀 Etapas Realizadas

### 1. Acesso ao Portal
- Link: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação da Máquina Virtual
- Recurso: **Máquina Virtual (Azure Virtual Machine)**
- Nome da VM: `vm-dio-lab`
- SO: Windows Server 2019 (ou Ubuntu, se preferir)
- Tamanho: B1s (grátis no plano gratuito)
- Usuário e senha definidos
- Grupo de recursos: `rg-lab-vm`
- Localização: `Brazil South` (ou região mais próxima)

### 3. Configurações de Rede
- IP Público: Sim
- Porta RDP (3389) aberta para acesso remoto

### 4. Acesso
- Windows: via **Área de Trabalho Remota (mstsc)**
- Linux: via **SSH (terminal)**

### 5. Encerramento
- Desligamento da VM ao final para **economizar créditos**

---

## 📷 Prints

Imagens salvas na pasta `/images/` com:
- Criação no portal
- Configuração final
- Acesso remoto funcionando

---

## 💡 Dicas & Boas Práticas

- Use **regiões mais próximas** para menor latência
- **Sempre desligue a VM** se não estiver usando, pra evitar cobranças
- Nomeie os recursos com padrão (`vm-lab`, `rg-vm-lab`, etc.)
- Use **tags** no Azure para facilitar rastreamento de custo
- **Orçamento e alertas** te salvam de surpresas (já fez um, né? 😎)

---

## 📚 Referências

- [Documentação Oficial - Criar VM no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [GitHub Markdown Guide](https://www.markdownguide.org/basic-syntax/)

