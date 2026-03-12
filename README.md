# Guia de Carreira Digital com IA 2025–2026

Este repositório contém o código-fonte da landing page do **Guia de Carreira Digital com IA 2025–2026**, elaborado para a **Sutari Intelligence**.

## 📌 Sobre o Projeto

O Guia é uma página interativa voltada a direcionar profissionais na jornada de aprendizado e estruturação de carreira em Inteligência Artificial. Através de diagnósticos, panoramas salariais, escopo das posições (Engenharia de Dados vs. IA vs. Automação) e propostas de conteúdo prático, a página captura leads e oferece um conteúdo centralizado para os interessados na área.

## 🛠️ Tecnologias Utilizadas

A página foi construída em um único arquivo (Single File) priorizando velocidade e independência de configuração, utilizando a tríade base da web:

*   **HTML5:** Estruturação semântica de conteúdo.
*   **CSS3:** Estilização com design system próprio (variáveis globais), responsividade nativa e microinterações.
*   **JavaScript (Vanilla):** Lógica de formulário (gate de acesso) e navegação interativa (tabs de trilhas, diagnóstico, etc.).
*   **Fontes:** Fraunces e Plus Jakarta Sans via Google Fonts.

## 🚀 Como Executar

O projeto é puramente estático (`.html`). Nenhum build ou instalação de dependências são necessários.

1. Clone o repositório ou baixe o arquivo fonte.
2. Dê um duplo clique em `guia-carreira-ia.html` para abri-lo e interagir diretamente em seu navegador padrão.

*Dica para desenvolvedores:* Para uma melhor experiência de desenvolvimento com live-reload, recomenda-se abrir a pasta do projeto no VS Code e utilizar a extensão **Live Server**, ou executar rodar algum servidor HTTP estático (ex: `npx serve .`).

## 📁 Estrutura do Arquivo

O arquivo `guia-carreira-ia.html` concentra tudo o que é necessário para a página rodar:
- **Nav/Hero:** Cabeçalho, Copy principal e o Gate Form de captação de lead.
- **Diagnosis:** Seção para identificar qual perfil e paralisação atual o usuário se encontra.
- **Market Data:** Paralelos do mercado, salários base e níveis de senioridade vs demanda.
- **Paths (Trilhas):** As opções de caminho de carreira em IA (Fundamentos, Engenharia de Prompt, Agentes Autônomos).
- **Rule of 6 / Messages / Conclusion:** Resumo de metodologias para estudos e blocos finais de persuasão.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
