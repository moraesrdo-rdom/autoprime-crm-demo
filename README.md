# 🚗 AutoPrime OS — Sistema de Gestão Automotiva, CRM & IA de Triagem

![Status](https://img.shields.io/badge/Status-Prot%C3%B3tipo%20Funcional%20(MVP)-emerald?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **Demonstração Interativa:** [Acesse o protótipo rodando ao vivo aqui](https://moraesrdo-rdom.github.io/autoprime-crm-demo/)

---

## 📋 Sobre o Projeto

O **AutoPrime OS** é um protótipo funcional (*MVP navegável*) de uma plataforma integrada para concessionárias e lojas de veículos seminovos. O sistema foi projetado para centralizar a operação comercial, eliminando planilhas paralelas e conectando a vitrine digital diretamente ao funil de vendas e ao atendimento automatizado por Inteligência Artificial.

Este projeto demonstra a arquitetura de experiência do usuário (UX) e os fluxos de dados entre os setores comercial, administrativo e de marketing digital automotivo.

---

## ✨ Funcionalidades Demonstradas

* **📊 Dashboard Executivo:** Indicadores em tempo real de volume de estoque, leads ativos no funil, test-drives agendados e ticket médio.
* **🗂️ CRM Kanban Interativo:** Pipeline visual de vendas (*Novos Leads $\rightarrow$ Em Negociação $\rightarrow$ Test-Drive / Visita $\rightarrow$ Venda Fechada*) com movimentação dinâmica de cards e pontuação de temperatura do lead.
* **🌐 Vitrine Digital Integrada (Visão do Cliente):** Alternância instantânea entre o painel administrativo e o site público da loja. Ao simular interesse em um veículo na vitrine, o lead é capturado e injetado automaticamente no CRM.
* **🤖 Agente de IA para Triagem de Leads:** Simulador de atendimento automatizado que consulta o estoque ativo, responde dúvidas sobre modelos disponíveis e registra o lead qualificado diretamente no funil de vendas.
* **💬 Chat Interno da Equipe:** Canal de comunicação rápida entre vendedores e setor de financiamento (F&I) para aprovação de fichas em tempo real.
* **🔄 Painel de Integradores (Marketplaces):** Monitoramento de sincronização via feed XML/API com portais automotivos (Webmotors, OLX Autos e Mercado Livre).
* **📅 Calendário de Agendamentos:** Controle de visitas e test-drives vinculados aos leads e consultores.

---

## 🛠️ Stack Tecnológica & Arquitetura Planejada

* **Protótipo Front-end (Atual):** HTML5 Semântico, Tailwind CSS (via CDN), FontAwesome e Vanilla JavaScript (ES6+) com gerenciamento de estado em memória.
* **Arquitetura de Produção (Escalável):**
  * **Front-end:** Next.js (React) + Tailwind CSS + Shadcn/UI
  * **Back-end & Banco de Dados:** PostgreSQL / Supabase (Auth, Storage para fotos de veículos e Realtime para o chat)
  * **IA & Automações:** Integração com APIs de LLM (Gemini / OpenAI) + Webhooks WhatsApp (Evolution API)
  * **Integrações:** Rotas dinâmicas geradoras de feeds XML/JSON padronizados para portais classificados.

---

## 🚀 Como Testar Localmente ou Online

1. Acesse o link do **GitHub Pages** no topo desta página para testar diretamente no navegador (desktop ou mobile).
2. Para rodar localmente, basta clonar este repositório e abrir o arquivo `index.html` em qualquer navegador moderno — não requer instalação de dependências para esta versão demonstrativa.

```bash
git clone [https://github.com/](https://github.com/)[SEU-USUARIO]/autoprime-crm-demo.git
