# 🦁 BB Comando - Sistema de Alta Performance (Agente de TI)

![Status](https://img.shields.io/badge/Status-V20_Stable-success)
![Tech](https://img.shields.io/badge/Stack-VanillaJS_%7C_Chart.js_%7C_CSS3-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎯 Sobre o Projeto

O **BB Comando** é uma *Single Page Application* (SPA) de alta fidelidade desenvolvida para gerenciar, metrificar e otimizar a preparação para o concurso de **Agente de Tecnologia do Banco do Brasil**.

Diferente de planilhas estáticas, este sistema opera como um **Dashboard Tático**, rodando inteiramente no navegador (Client-Side) com persistência de dados via `LocalStorage` e sincronização offline via arquivos JSON.

---

## 🚀 Funcionalidades Principais (V20)

### 🧠 1. Smart Review (Algoritmo de Revisão)
O sistema analisa os tópicos estudados de Segunda a Sábado e, com um clique, **gera automaticamente** um cronograma de revisão ativa para o Domingo, calculando slots de tempo baseados na carga horária da semana.

### 📊 2. Deep Analytics & BI
Dashboard integrado com **Chart.js** que oferece visão em tempo real:
* **Eficiência por Tópico:** Tabela dinâmica que classifica seus melhores e piores tópicos baseada na taxa de acerto.
* **Distribuição de Carga:** Gráficos comparativos de Horas Planejadas vs. Executadas por disciplina.
* **KPIs Globais:** Contadores de Questões, Horas Líquidas e Progresso do Edital.

### 🔄 3. Edital Sync (Bidirecional)
Integração total entre o Cronograma e a aba de Edital.
* Ao lançar horas no cronograma, o sistema **atualiza automaticamente** o badge de horas acumuladas na árvore do Edital.
* Checkboxes customizados para controle visual de tópicos vencidos.

### 🎨 4. UI/UX Avançada (Mobile First)
* **Design System:** Tipografia elegante (*Inter* + *Playfair Display*), paleta de cores institucional (Dark/Light Mode) e componentes visuais refinados.
* **Custom Modals:** Substituição de todos os `alert()` e `confirm()` nativos por um sistema de modais responsivos, com scroll interno e prevenção de erros de layout.
* **Inputs Inteligentes:** Selects dinâmicos que carregam tópicos baseados na disciplina escolhida.

### 💾 5. OmniSync (Backup Offline)
Sistema robusto de Importação/Exportação de dados em JSON, permitindo transição fluida entre Desktop e Mobile sem necessidade de servidor ou login.

---

## 🛠️ Tecnologias

* **Core:** HTML5 Semântico, CSS3 (Grid/Flexbox/Variables), JavaScript (ES6+).
* **Libs:** [Chart.js](https://www.chartjs.org/) para visualização de dados.
* **Storage:** LocalStorage API + File API (Blob).
* **Fontes:** Google Fonts (Inter & Playfair Display).

## 📱 Screenshots

*hmmmmmmm*

## ⚡ Como Usar

1. **Clone ou Baixe:**
   ```bash
   git clone [https://github.com/19lemabe94/agentProject.git](https://github.com/19lemabe94/agentProject.git)
