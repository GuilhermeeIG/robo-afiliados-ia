<h1 align="center">🤖 Robô de Captação de Afiliados</h1>
<p align="center"><b>Automação 24/7 com IA generativa para encontrar e conversar com afiliados</b></p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" /> <img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

> 🔒 O código-fonte deste projeto é **privado**. Este repositório é uma vitrine com a visão geral, a arquitetura e a stack. Quer saber mais? Fale comigo pelo [LinkedIn](https://www.linkedin.com/in/luiz-guilherme-dos-santos-820a792a4/).

## 🎯 O que é

Um robô que trabalha 24 horas por dia em dois motores:

- **Prospecção:** encontra criadores de conteúdo pela API oficial de afiliados da Shopee, faz o primeiro contato e conduz uma régua de follow-up.
- **Atendimento:** lê as respostas, responde dúvidas com IA generativa e encaminha negociações fora do padrão para a equipe.

## ✨ Destaques

- 🧠 **IA generativa (Claude API)** para reescrever e responder mensagens com base num playbook
- 🛡️ **Filtro de conteúdo** antes de cada envio e regras de segurança cobertas por testes (limite de mensagens sem resposta, cota diária, checagem de repetição)
- 🔗 **API oficial de afiliados da Shopee**: recomendação de afiliados e campanhas exclusivas
- 📊 **Playbook no Google Sheets** e alertas no Telegram
- 🧪 **Modo de simulação** (dry-run) para validar tudo antes de ligar
- 🐳 **Publicado em VPS Linux** com Docker e Coolify, com painel web atrás de proxy HTTPS

## 🛠️ Stack

Python 3.12 · FastAPI · Uvicorn · SQLAlchemy · Pydantic · APScheduler · Typer · httpx · Anthropic SDK · gspread · pytest · Docker
