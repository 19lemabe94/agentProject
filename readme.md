# 🚀 BB Comando - Sistema de Controle de Estudos (Agente TI)

![Status do Projeto](https://img.shields.io/badge/Status-Finalizado-success)
![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📋 Sobre o Projeto

O **BB Comando** é uma Single Page Application (SPA) desenvolvida para gerenciar, metrificar e otimizar a rotina de estudos para o concurso de Agente de Tecnologia do Banco do Brasil. 

Diferente de planilhas comuns, este sistema roda inteiramente no navegador, utiliza **LocalStorage** para persistência de dados e oferece um **Dashboard Analítico** em tempo real.

## ✨ Funcionalidades (V9 OmniSync)

* **📅 Cronograma Dinâmico:** Interface estilo Excel para input de carga horária, páginas lidas e questões.
* **📊 Dashboard de BI:** Gráficos interativos (Chart.js) para acompanhar:
    * Evolução semanal de acertos.
    * Precisão global.
    * Volume diário de estudos.
* **🔄 OmniSync (Backup Offline):** Sistema de Exportação/Importação de JSON para sincronizar dados entre PC e Celular sem necessidade de servidor.
* **🎨 UI Responsiva & Temas:**
    * Design "Mobile-First" adaptável.
    * Alternância nativa entre **Dark Mode** e **Light Mode**.
* **🛡️ Segurança de Dados:** Modal de confirmação para exclusão de semanas e validação de inputs.
* **⚡ Performance:** Zero dependências de backend. Carregamento instantâneo.

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semantic:** Estrutura otimizada e acessível.
* **CSS3 Moderno:** Uso de CSS Variables (`:root`), Flexbox e CSS Grid para layout responsivo.
* **Vanilla JavaScript (ES6+):** Lógica de estado, manipulação de DOM e eventos.
* **LocalStorage API:** Persistência de dados do usuário no navegador.
* **Chart.js:** Biblioteca para renderização dos gráficos de desempenho.
* **File API / Blob:** Para geração e leitura dos arquivos de backup `.json`.

## 📱 Screenshots

*(Coloque aqui um print do seu Dashboard e outro da Tabela no celular)*

## 🚀 Como Usar

1.  Baixe o arquivo `index.html` (ou clone este repositório).
2.  Abra o arquivo em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3.  Comece a registrar seus estudos.
4.  Para usar em outro dispositivo: Clique no ícone de **Download** na sidebar, envie o arquivo `.json` para o outro aparelho e use o botão de **Upload**.

## 🤝 Contribuição

Sugestões e pull requests são bem-vindos! Este projeto foi criado com foco na aprovação do BB, mas pode ser adaptado para qualquer ciclo de estudos.

---
Desenvolvido com ☕ e código por **[Seu Nome]**.