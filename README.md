# 🌐 Monitoramento de Links de Internet com Grafana + Zabbix

Este repositório apresenta um painel **autoral** desenvolvido no **Grafana** para o **monitoramento contínuo de conectividade de links de internet**. O monitoramento é realizado via **Zabbix** utilizando checagens **ICMP (ping)**, cobrindo **ambientes de matriz e filial**, com checagem externa (WAN) adicional.

![Painel de Monitoramento](./39f41f38-50c5-46fb-a45f-ddb5cb4db17d.png)

---

## ⚙️ Arquitetura do Monitoramento

- **Ferramentas Utilizadas**:
  - [Grafana](https://grafana.com/) — visualização e dashboards
  - [Zabbix](https://www.zabbix.com/) — engine de monitoramento (backend)
  - [Zabbix Plugin para Grafana](https://grafana.com/grafana/plugins/alexanderzobnin-zabbix-datasource/) — integração nativa

- **Protocolo de Monitoramento**:
  - **ICMP (Ping)** — para medir **latência** e **disponibilidade**

---

## 🧩 O que o Painel Monitora?

### 🌍 Localizações
- 📍 Goiânia — **Matriz**
- 📍 São Paulo — **Filial**
- 🌐 Checagem WAN — (Ping para servidores externos como Google)

### 📡 Provedores Monitorados
- **Algar**
- **Vivo**
- **Google (verificação externa)**

### 📈 Métricas Exibidas
- Status de disponibilidade do link (ON/OFF)
- Latência atual (em microssegundos ou milissegundos)
- Gráficos em tempo real da latência (ICMP response time)
- Provedor e link principal/backup
- Horário sincronizado no painel

---

## 💡 Benefícios

- **Monitoramento contínuo** da estabilidade de links críticos
- **Identificação visual rápida** de falhas
- Interface **moderna e amigável**
- Suporte para **múltiplos locais e provedores**

---

## 🛠️ Requisitos

- Grafana (v9 ou superior recomendado)
- Zabbix Server configurado com hosts de rede
- Plugin Zabbix Datasource instalado no Grafana
- Permissões adequadas de API no Zabbix para leitura

---

## 🧑‍💻 Autor

Desenvolvido por **Valdivino Aquino**  
Especialista em TI, Infraestrutura e Monitoramento | [LinkedIn](https://www.linkedin.com/in/valdivinoaquino)

---

## 📄 Licença

Este projeto é de autoria própria e disponibilizado com fins educacionais, demonstrativos e de inspiração para outros profissionais de TI.  
Reprodução total ou parcial com créditos é bem-vinda.

---
