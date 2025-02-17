# GrafanaPiDashboard

# 🚀 Grafana AutoStart no Raspberry Pi  

Este projeto configura um Raspberry Pi para rodar o Grafana e garantir que, caso o dispositivo desligue ou reinicie, ele volte automaticamente para a página do Grafana em tela cheia.  

## 📌 Funcionalidades  
- Inicializa o Raspberry Pi diretamente na interface gráfica.  
- Abre o Grafana automaticamente no navegador em modo **kiosk** (tela cheia).  
- Evita que a tela entre em modo de espera ou bloqueie.  

## 🛠️ Configuração  

### 1️⃣ **Instalar o Chromium**  
Se ainda não estiver instalado, execute:  
```sh
sudo apt update && sudo apt install -y chromium-browser
