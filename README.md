<div align="center">

<img src="preview/rs-inicio.png" alt="Raspadinha 2" width="100%">

# Raspadinha 2

**Raspadinha com PIX, prêmios e painel administrativo.**

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PIX](https://img.shields.io/badge/PIX-Ecompag-32BCAD?style=for-the-badge)
[![Telegram](https://img.shields.io/badge/Telegram-%40vsf__lima-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/vsf_lima)

</div>

---

## 📖 Sobre

Versão 2 do sistema de raspadinha em PHP, com banco configurado em `secrets.php`, pagamentos PIX via Ecompag, webhook automático e painel administrativo em `/dash`.

## ✨ Recursos

| Módulo | Descrição |
|---|---|
| Raspadinha | Cartelas com prêmios |
| PIX Ecompag | Client ID e Client Secret |
| Webhook | `https://seudominio/ecompag_webhook.php` |
| Admin | Painel em `/dash` |
| Banco | Configuração em `secrets.php` |
| Histórico | Cartelas e resultados |

## 🖼️ Prévia

<p align="center"><img src="preview/rs-jogo.png" alt="Prévia" width="100%"></p>

## 📦 Instalação

1. Envie os arquivos para a hospedagem (PHP 8+ e MySQL/MariaDB).
2. Crie o banco e importe o SQL do pacote.
3. Configure o banco em `secrets.php`.
4. Acesse `/dash` com `admin@eu.com` / `qwe123#` e **troque a senha**.
5. Em **Config. Ambiente → Gateway Ecompag**, cole o Client ID e o Client Secret.
6. A URL do webhook é montada automaticamente em `https://seudominio/ecompag_webhook.php`.

## ⬇️ Download

📦 **[Release v1.0](https://github.com/VSFLima/raspadinha-2/releases/tag/v1.0)**

| Arquivo | Tamanho |
|---|---|
| [`raspadinha2.zip`](https://github.com/VSFLima/raspadinha-2/releases/download/v1.0/raspadinha2.zip) | 28 MB |

## ⚠️ Aviso

Este projeto é disponibilizado no estado em que foi recebido, para fins de estudo e implantação. Conteúdo destinado a maiores de 18 anos. Jogue com responsabilidade. A legalidade de apostas varia de país para país — verifique a legislação local. Troque todas as credenciais padrão antes de usar em produção.

## 🙏 Créditos

- **Distribuição:** [@vsf_lima](https://t.me/vsf_lima) — Telegram
- **Sistema original:** jc_scripts / ecompag

---

<p align="center">Feito com ❤️ para a comunidade — <a href="https://t.me/vsf_lima">@vsf_lima</a></p>
