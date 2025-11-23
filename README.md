# 🎅 Correio do Papai Noel

Um site temático e interativo que permite às crianças enviarem suas cartinhas de Natal diretamente para o "Polo Norte". O projeto apresenta um design visual estilo aquarela, animação de neve e música ambiente para criar uma experiência mágica.


## ✨ Funcionalidades

* **Envio de Cartas:** Formulário funcional integrado com [FormSubmit](https://formsubmit.co/).
* **Atmosfera Natalina:**
    * 🌨️ Animação de neve caindo (JavaScript).
    * 🎵 Música de fundo com tratamento para *autoplay* (JavaScript).
    * 🎨 Design responsivo com ilustrações em aquarela.
* **Página de Confirmação:** Redirecionamento automático para uma página de agradecimento personalizada com confirmação de entrega.
* **Elementos Visuais:** Personagens (Papai Noel e Elfo) e cenários que se adaptam a diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica das páginas.
* **CSS3:** Estilização, Flexbox para layout, Media Queries para responsividade e animações.
* **JavaScript:** Lógica para a chuva de neve e controle de áudio.
* **Google Fonts:** Tipografias *Nunito* (textos) e *Mountains of Christmas* (títulos).
* **FormSubmit:** Backend gratuito para processamento do formulário de e-mail.

## 📂 Estrutura do Projeto

```text
/
├── index.html        # Página principal com o formulário
├── obrigado.html     # Página de confirmação de envio
├── style.css         # Estilos globais e responsividade
├── script.js         # Lógica da neve e player de música
├── Image/            # Pasta com os assets (fundo.png, santa.png, elfo.png, etc.)
└── Music/            # Pasta com os áudios (natal.mp3, sino.mp3)