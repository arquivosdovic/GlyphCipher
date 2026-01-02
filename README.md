# 🔐 Emoji Cipher Portal

Um sistema interativo de criptografia visual baseado em substituição de caracteres. O projeto permite transformar textos comuns em sequências de emojis ou símbolos exóticos (como caracteres orientais e árabes), garantindo uma forma divertida e criativa de trocar mensagens secretas.

## 🚀 Funcionalidades

O projeto é dividido em dois módulos principais:

* **Modo Simplificado:** Focado na usabilidade para chats. Permite alternar entre a ordem de emojis do **WhatsApp** e a ordem padrão do **Teclado do Celular**, garantindo que a decodificação seja precisa em diferentes plataformas.
* **Modo Avançado:** Um sistema de cifra personalizada onde o usuário define uma **Chave Numérica** e um **Salto**. Isso altera matematicamente quais emojis representam cada letra, criando infinitas combinações de codificação.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura das páginas e interface.
* **CSS3:** Design moderno, responsivo e com suporte a Dark Mode no modo avançado.
* **JavaScript (Vanilla):** Lógica de manipulação de strings, mapeamento de arrays e algoritmos de conversão baseados em `CodePoints`.

## 📂 Estrutura do Projeto

```text
├── index.html           # Menu principal e apresentação do sistema
├── simplificado.html    # Criptografia baseada em layouts de teclados reais
├── avancado.html        # Criptografia matemática com chaves e saltos
└── README.md            # Documentação do projeto
