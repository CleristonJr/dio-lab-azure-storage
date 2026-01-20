# ☁️ Armazenamento de E-Commerce com Azure

Projeto prático do Bootcamp da **DIO**, focado na configuração de infraestrutura em nuvem. O objetivo foi provisionar uma conta de armazenamento para gerenciar arquivos estáticos de um site de e-commerce.

## 📋 Detalhes do Desafio
Configurar um **Azure Storage Account** para hospedar imagens de produtos, garantindo disponibilidade e otimização de custos para um ambiente de desenvolvimento.

## 🛠️ Infraestrutura Criada

### Recurso Principal
* **Serviço:** Azure Storage Account
* **Nome:** `storecleriston2026`
* **Tipo:** StorageV2 (general purpose v2)
* **Redundância:** LRS (Locally-redundant storage)
* **Região:** East US 2

### Estrutura de Dados
Foi criado um container chamado `imagens-produtos` para simular o diretório de mídia da aplicação, onde foi realizado o upload de arquivos de teste.

## 📸 Evidências

### 1. Visão Geral do Recurso
![Azure Overview](https://github.com/CleristonJr/dio-lab-azure-storage/blob/main/azure-overview.png?raw=true)
*Painel de controle mostrando o recurso online na região East US 2.*

### 2. Upload de Arquivos (Blob)
![Container Upload](https://github.com/CleristonJr/dio-lab-azure-storage/blob/main/container-upload.png?raw=true)
*Container com arquivo de imagem carregado com sucesso.*

## 🧠 Aprendizados e Troubleshooting
Durante o processo, enfrentei um bloqueio de criação de recursos na região **East US** e **West US** devido a políticas da assinatura acadêmica.
* **Solução:** Identifiquei que a região **East US 2** estava disponível para a subscrição e redirecionei o deploy do Grupo de Recursos e do Storage Account para esta localização, resolvendo o erro `RequestDisallowedByAzure`.

---
## 👨‍💻 Autor
Cleriston Jr.
www.linkedin.com/in/cleriston-júnior-ba419218b
