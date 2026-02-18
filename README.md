# 🛒 Achadinhos Bot - Monitor de Ofertas & Afiliados

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

Um bot inteligente desenvolvido para automatizar o monitoramento de preços em e-commerces, validar promoções reais e distribuir links de afiliados automaticamente em canais do Telegram e grupos de WhatsApp.

## 🚀 Funcionalidades

- **Web Scraping Dinâmico:** Monitoramento de lojas (Amazon, Magalu, Shopee, etc.) utilizando `Playwright` ou `BeautifulSoup`.
- **Análise de Preços:** Verificação se a oferta é real comparando com o histórico (evita "metade do dobro").
- **Gerador de Deep Links:** Converte links de produtos comuns em links de afiliados (com seu ID de rastreamento) automaticamente.
- **Integração Multi-Plataforma:**
  - Envio formatado para Canais do **Telegram** (foto + preço + link).
  - Envio para grupos de **WhatsApp**.
- **Filtro de Categorias:** Monitora apenas nichos específicos (ex: Hardware, Smartphones, Fraldas).

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Scraping:** Playwright / BeautifulSoup4
- **Dados:** Pandas (Tratamento) & SQLite (Armazenamento de histórico)
- **Bots/API:** `python-telegram-bot` & Integração WhatsApp (Evolution API ou Twilio)
- **Agendamento:** Schedule / Crontab

## 📦 Como Rodar Localmente

### Pré-requisitos
- Python 3.10+
- Conta de Afiliado (Amazon, Magalu, etc.)
- Token do Bot Telegram (via @BotFather)

### Instalação

1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/achadinhos-bot.git](https://github.com/seu-usuario/achadinhos-bot.git)
   cd achadinhos-bot
