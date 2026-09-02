# Simulado: Trilha da Produtividade ⏱️

## 📖 Sobre o Projeto
Uma aplicação web gamificada de página única (SPA) desenvolvida para facilitar a retenção de conhecimento sobre Gestão do Tempo, Matriz de Eisenhower, Técnica Pomodoro e Metodologia 5S. 

Utilizando a mecânica de "Flashcards" interativos, o projeto aplica o conceito psicológico de **Recuperação Ativa (Active Recall)** aliado ao **Feedback Visual Imediato**, garantindo maior engajamento e consolidação da memória, especialmente estruturado para o apoio pedagógico no ensino médio e técnico.

## 🎮 Funcionalidades
* **Mecânica de Flashcards (Flip 3D):** Interação dinâmica que estimula a decisão do usuário antes da revelação da resposta e justificativa.
* **Sistema de Score Progressivo:** Acompanhamento de pontuação em tempo real ao longo de 30 questões.
* **Barra de Progresso Visível:** Feedback visual imediato do avanço no simulado.
* **Mobile-First:** Interface 100% responsiva, priorizando a usabilidade em dispositivos móveis.

## 🛠️ Tecnologias Utilizadas
* **HTML5 & Vanilla JavaScript:** Estruturação semântica e controle de estado do jogo rodando inteiramente no lado do cliente (Client-side).
* **Tailwind CSS (via CDN):** Estilização utilitária ágil, garantindo animações de rotação 3D fluidas sem a necessidade de arquivos CSS complexos.

## 🚀 Arquitetura e Implantação
Para proteger a lógica do gabarito e evitar inspeções simples do código-fonte, a arquitetura recomendada utiliza:
1. **GitHub:** Repositório configurado como **Privado** para ocultar a base de questões.
2. **Vercel / Plataforma Front-end:** Deploy contínuo importando o repositório privado para gerar o link público de acesso aos usuários.
