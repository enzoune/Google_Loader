# 🌈 Google-Style Animated Loader

> Uma recriação técnica do famoso componente de carregamento do Google, desenvolvida com foco em precisão visual, animações de keyframes e código CSS limpo.

## 📖 Sobre o Projeto

Este projeto integra o meu portfólio de estudos em **Programação Full-Stack**. O objetivo foi construir um **Google Loader** que simula o movimento fluido de pontos coloridos, um padrão de design amplamente reconhecido pela sua simplicidade e elegância.

O desafio técnico consistiu em coordenar o tempo de animação de múltiplos elementos independentes para criar um movimento harmônico e contínuo.

## ✨ Destaques e Diferenciais Técnicos

* **Arquitetura Minimalista:** Implementação estruturada em uma classe contêiner (`.wrapper`) contendo quatro elementos de marcação (`span.dot`), mantendo o DOM leve e eficiente.
* **Domínio de Animações CSS3:** Uso avançado de `@keyframes` para gerenciar transformações de escala e posição, recriando a identidade visual do Google puramente via código.
* **Sincronização de Timeline:** Implementação de atrasos de animação (`animation-delay`) para cada "ponto", garantindo o efeito cascata característico do componente original.
* **Design Responsivo e Vetorial:** Por ser construído inteiramente com CSS, o loader é perfeitamente escalável, mantendo a nitidez em qualquer densidade de tela (Retina/4K).
* **Organização Profissional:** Separação estrita de responsabilidades entre a estrutura semântica (`index.html`) e a lógica visual localizada no diretório `css/style.css`.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Marcação estrutural para os elementos de animação.
* **CSS3:** Gerenciamento de cores, formas geométricas (border-radius) e lógica de animação infinita.
