# meu-primeiro-web-scraper
Documentando meu passo a passo aprendendo a desenvolver um web scraper

# 🕸️ ShieldScout: Web Scraper para Reconhecimento e Cyber Sec

Seja bem-vindo(a) ao meu repositório de estudos! Este projeto documenta o desenvolvimento do **ShieldScout**, um web scraper automatizado em Python focado em inteligência de fontes abertas (OSINT) e reconhecimento de segurança (Recon).

O objetivo do robô é analisar sites públicos para coletar dados de segurança estruturais, ajudando a mapear superfícies de ataque e identificar possíveis vulnerabilidades de forma passiva e automatizada.

---

## 📋 Funcionalidades e Condições do Projeto
O scraper será desenvolvido em módulos para atender aos seguintes critérios técnicos de Cyber Sec:
* **Análise de Certificado SSL/TLS:** Verificar a validade, emissor e expiração do certificado do alvo.
* **Identificação de Tecnologias (Fingerprinting):** Descobrir quais servidores web, linguagens e CMS o site utiliza através dos cabeçalhos HTTP (`X-Powered-By`, `Server`).
* **Monitoramento de Exposições:** Buscar por arquivos sensíveis expostos publicamente (ex: `.env`, `robots.txt`, `sitemap.xml`, diretórios de backup).
* **Varredura Passiva:** Operar de forma a coletar apenas dados públicos e legítimos, sem realizar ataques ativos ou invasões.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python 3
* **Bibliotecas:** `requests` (Requisições HTTP), `beautifulsoup4` (Análise de HTML), `ssl` & `socket` (Análise de certificados)
* **Ambiente de Desenvolvimento:** VS Code / Terminal

--
## Linha do tempo / evolução
* 📁 **[passo_01_conexao_e_headers](./passo_01_conexao_e_headers/)**
