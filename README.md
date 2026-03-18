# 🧪 Azure Linux VM + Nginx Web Server

Projeto prático de implementação de servidor web utilizando Linux (Ubuntu Server) e Nginx em ambiente cloud.


## 📌 Objetivo

Desenvolver experiência prática em:

* Provisionamento de infraestrutura na nuvem
* Administração de sistemas Linux
* Publicação de aplicação web
* Configuração básica de rede

## ☁️ Infraestrutura

* Máquina Virtual Linux (Ubuntu Server)
* IP público configurado
* Acesso remoto via SSH
* Liberação de porta HTTP (80)

![Resource Group](images/1-resource_group.png)

---

## 🚀 Etapas do projeto

### 1. Criação da VM

* Provisionamento da máquina virtual Linux no Azure
* Definição de usuário administrador
* Configuração de acesso via SSH

![VM Config](images/2-vm_configs.png)

---

### 2. Acesso ao servidor

![SSH](images/3-connect_ssh.png)

---

### 3. Atualização do sistema

![Update](images/4-update_server.png)

---

### 4. Instalação do Nginx

![Nginx Install](images/5-install_nginx.png)

---

### 5. Verificação do serviço

![Nginx Config](images/6-config_nginx.png)

---

### 6. Teste de acesso e Customização da página

```bash
sudo nano /var/www/html/index.nginx-debian.html
```

Acessar via navegador:

![HTTP Test](images/7-test_http_server.png)

---

## 🧠 Aprendizados

* Deploy de servidor web em ambiente cloud
* Gerenciamento de serviços no Linux
* Configuração de acesso remoto via SSH
* Noções de rede e liberação de portas

