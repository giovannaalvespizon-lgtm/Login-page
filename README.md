# 🔐 DevClub Login - Interface Glassmorphism

Uma interface de autenticação moderna, minimalista e totalmente responsiva desenvolvida para o **DevClub Login**. O grande diferencial técnico deste projeto é a aplicação do conceito de **Glassmorphism** (efeito de vidro translúcido) sobre um plano de fundo abstrato, priorizando o refinamento estético, o uso correto de ícones vetoriais e micro-interações fluidas na jornada do usuário (UI/UX).

---

## 🚀 Tecnologias e Conceitos Aplicados

* **HTML5 Estruturado e Semântico:** Uso correto da tag `<main>` para envelopar o formulário de login, garantindo a organização do escopo principal da página, além de inputs devidamente tipados (`type="email"` e `type="password"`).
* **CSS3 Avançado & Estilização Futurista:**
  * **Efeito Glassmorphism:** Implementação da propriedade `backdrop-filter: blur(15px);` combinada com fundos semitransparentes (`rgba`) e bordas sutis, gerando o visual de vidro fosco que se sobrepõe ao plano de fundo de forma harmônica.
  * **Layout Centralizado Total (Viewport):** Uso avançado de Flexbox no `body` (`display: flex; min-height: 100vh;`) para garantir que o módulo de login permaneça perfeitamente centralizado em qualquer resolução de tela.
  * **Transições e Pseudo-classes:** Desenvolvimento de um botão de ação com efeito inverso no *hover* (`transition: 0.5s;`), que troca suavemente a cor sólida por uma estrutura vazada com bordas translúcidas.
  * **Posicionamento Absoluto:** Alinhamento estratégico dos ícones de formulário dentro dos campos de texto através de `position: absolute;` e cálculo de centralização vertical (`transform: translateY(-50%);`).
* **Ecossistemas e Tipografia Externa:** 
  * Integração com a biblioteca externa **Boxicons** via CDN para renderização de ícones de usuário e cadeado.
  * Importação e otimização da fonte **Lato** diretamente do Google Fonts.

---

## 🛠️ Funcionalidades da Interface

* **Campos de Entrada Inteligentes:** Inputs customizados com remoção de contornos padrões (`outline: none`), cantos arredondados adaptáveis e placeholders estilizados em tonalidades suaves.
* **Componentes de Formulário:** Caixa de seleção (*checkbox*) com propriedade `accent-color` para manter a identidade visual cromática nos seletores do navegador, links de recuperação de credenciais e redirecionamento de cadastro.
* **Fundo Fluido Multitelas:** Imagem de fundo configurada com `background-size: cover;` para evitar distorções visuais em monitores ultrawide ou telas mobile.

---
Desenvolvido com dedicação e foco no crescimento profissional.

Giovanna Pizon

Desenvolvedora Frontend
