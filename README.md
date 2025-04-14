# Zabbix Network Maps

Este repositório contém dois mapas personalizados criados no Zabbix para fins de monitoramento de rede corporativa.

## 🗺️ Mapas Criados

### 1. **Topologia de Rede Corporativa**
![zabbix](https://github.com/user-attachments/assets/51d93398-347c-4196-bde7-613e5a8d3547)

Este mapa representa a **estrutura de rede entre Matriz e Filiais**, mostrando conexões com:

- Equipamentos **Fortinet** em todas as localidades
- Status de conectividade entre os links
- Equipamentos de rede com status individual (OK ou com falha)
- Conexões organizadas por:
  - Matriz
  - São Paulo
  - Rio de Janeiro
  - Belo Horizonte
  - Porto Alegre
  - Filiais 1 a 4

🟢 **Elementos com status "OK"** indicam funcionamento normal  
🔴 **Elementos com "New element" ou status diferente** precisam de atenção

---

### 2. **Monitoramento dos Access Points (APs)**
![zabbix ap](https://github.com/user-attachments/assets/9b4fb5da-05d2-4ebc-ba46-ceb3ecc849f2)

Este mapa apresenta o monitoramento detalhado dos **Access Points (APs)** distribuídos entre:

- Matriz (Ruckus)
- Filiais (Ruckus)
- Unidades regionais com APs da **Cisco**:
  - Rio de Janeiro
  - São Paulo
  - Porto Alegre
  - Belo Horizonte

✅ **Ícones verdes** indicam APs ativos  
🔴 **Ícone vermelho com "Novo elemento"** indica novo dispositivo detectado, ainda não homologado no monitoramento

---

## 🧰 Tecnologias Utilizadas

- 🖥️ [Zabbix](https://www.zabbix.com/)
- 🌐 Monitoramento de rede com Fortinet, Ruckus e Cisco
- 🎯 Visão centralizada da infraestrutura

---

## 📁 Estrutura de Arquivos

📦 zabbix-network-maps/ 
┣ 📷 zabbix.png # Mapa da topologia de rede
┣ 📷 zabbix ap.png # Mapa de monitoramento dos Access Points 
┗ 📄 README.md # Este arquivo

---

## 📌 Observações

- Os mapas foram criados via interface gráfica do Zabbix.
- Alguns elementos ainda estão como "New element" e precisam de refinamento.
- As imagens podem ser atualizadas conforme novos equipamentos forem adicionados ou removidos da rede.


