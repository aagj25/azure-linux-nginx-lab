# 🧪 Azure Linux VM + Nginx Web Server

Projeto prático de implementação de servidor web utilizando Linux (Ubuntu Server) e Nginx em ambiente cloud.

---

## 📌 Objetivo

Desenvolver experiência prática em:

* Provisionamento de infraestrutura na nuvem
* Administração de sistemas Linux
* Publicação de aplicação web
* Configuração básica de rede

---

## ☁️ Infraestrutura

* Máquina Virtual Linux (Ubuntu Server)
* IP público configurado
* Acesso remoto via SSH
* Liberação de porta HTTP (80)

---

## ⚙️ Tecnologias utilizadas

* Microsoft Azure
* Linux (Ubuntu Server)
* Nginx
* SSH

---

## 🚀 Etapas do projeto

### 1. Criação da VM

* Provisionamento da máquina virtual Linux no Azure
* Definição de usuário administrador
* Configuração de acesso via SSH

---

### 2. Acesso ao servidor

```bash
ssh usuario@ip-da-vm
```

---

### 3. Atualização do sistema

```bash
sudo apt update && sudo apt upgrade -y
```

---

### 4. Instalação do Nginx

```bash
sudo apt install nginx -y
```

---

### 5. Verificação do serviço

```bash
sudo systemctl status nginx
```

---

### 6. Liberação de porta

* Configuração da porta 80 (HTTP) nas regras de rede da VM

---

### 7. Teste de acesso

Acessar via navegador:

```
http://IP-DA-VM
```

---

### 8. Customização da página

```bash
sudo nano /var/www/html/index.nginx-debian.html
```


---

## 🧠 Aprendizados

* Deploy de servidor web em ambiente cloud
* Gerenciamento de serviços no Linux
* Configuração de acesso remoto via SSH
* Noções de rede e liberação de portas

---

## 💼 Aplicação profissional

Este projeto simula a implementação de um servidor web em ambiente cloud, demonstrando conhecimentos em infraestrutura, Linux e publicação de serviços.

