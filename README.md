# Resumo do Lab: Configurando Recursos e Dimensionamentos na Azure

Este repositório contém o resumo das lições aprendidas durante o laboratório da DIO sobre configuração de recursos, dimensionamento de máquinas virtuais, área de trabalho virtual e aplicativos de funções na Microsoft Azure.

## 🌐 Máquinas Virtuais (VMs) no Azure

As Máquinas Virtuais (VMs) são serviços de Infraestrutura como Serviço (IaaS) que permitem executar sistemas operacionais e aplicativos em um ambiente virtualizado. Durante o laboratório, aprendemos a:

- Criar e configurar uma máquina virtual no portal da Azure.
- Escolher a imagem do sistema operacional (Windows, Linux etc.).
- Selecionar o tamanho da VM com base nas necessidades de CPU, memória e armazenamento.
- Configurar regras de acesso e segurança usando Grupos de Segurança de Rede (NSG).
- Conectar-se à VM via RDP (Windows) ou SSH (Linux).

### 🔧 Dimensionamento de Recursos

O dimensionamento permite ajustar os recursos computacionais com base na demanda. Vimos como:

- Redimensionar uma VM (ex: mudar de B1s para D2s_v3).
- Configurar escalonamento automático com base em métricas como CPU ou uso de memória.
- Reduzir custos desligando VMs que não estão em uso.

## 💼 Área de Trabalho Virtual (Windows Virtual Desktop)

O Azure Virtual Desktop (AVD) é uma solução que permite criar um ambiente de trabalho remoto completo. Ele é ideal para cenários como:

- Fornecer acesso remoto a ambientes seguros para colaboradores.
- Compartilhar uma máquina virtual entre múltiplos usuários com perfis isolados.
- Usar o modelo de pagamento sob demanda.

Principais pontos abordados:

- Como configurar uma área de trabalho virtual no Azure.
- Vantagens de gerenciamento centralizado e escalabilidade.
- Segurança e autenticação com Azure Active Directory (AAD).

## ⚙️ Aplicativos de Funções (Azure Functions)

Azure Functions é uma oferta de **Computação sem Servidor (Serverless)**, que permite executar código sob demanda sem se preocupar com infraestrutura.

Durante o laboratório, exploramos:

- Criação de uma Function App.
- Definição de gatilhos (triggers), como HTTP, Timer ou eventos de Storage.
- Vantagens: escalabilidade automática, cobrança por execução, integração com outros serviços Azure.

## 📌 Conclusão

Este laboratório foi essencial para compreender como criar, configurar e otimizar o uso de máquinas virtuais, além de conhecer soluções modernas como Azure Virtual Desktop e Azure Functions. A experiência prática reforça o entendimento dos modelos IaaS, DaaS e Serverless da nuvem Microsoft Azure.

---

🔗 **Links úteis**:
- [Portal da Azure](https://portal.azure.com/)
- [Documentação Oficial do Azure](https://learn.microsoft.com/pt-br/azure/)
- [Azure Pricing Calculator](https://azure.microsoft.com/pt-br/pricing/calculator/)
