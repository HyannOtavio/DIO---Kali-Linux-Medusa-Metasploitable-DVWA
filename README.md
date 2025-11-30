# DIO---Kali-Linux-Medusa-Metasploitable-DVWA

# 🔐 Projeto: Auditoria de Força Bruta com Kali Linux, Medusa e Ambientes Vulneráveis

Este projeto foi desenvolvido como parte do desafio de cibersegurança da DIO, com o objetivo de configurar um ambiente controlado, executar ataques simulados de força bruta e documentar todo o processo de forma clara e prática.

---

## 🎯 Objetivos do Projeto

- Compreender ataques de força bruta em diferentes protocolos (FTP, HTTP, SMB).
- Utilizar o **Medusa** no Kali Linux para auditoria de segurança ofensiva.
- Simular cenários reais utilizando **Metasploitable 2** e **DVWA**.
- Criar wordlists simples e customizadas.
- Registrar evidências, aprendizados e medidas de mitigação.
- Publicar a documentação como portfólio técnico no GitHub.

---

## 🛠️ Ambiente Utilizado

### ✔️ Máquinas Virtuais (VirtualBox)
- **Kali Linux** (atacante)
- **Metasploitable 2** (vítima)
- **DVWA (Damn Vulnerable Web Application)** — executando no Metasploitable

### ✔️ Configuração de Rede
- Tipo de rede: **Host-Only (Rede Interna)**
- Objetivo: isolamento total do ambiente para testes seguros.

---

## 📌 Passo 1 — Verificando Conectividade

No Kali Linux:

```bash
ifconfig
