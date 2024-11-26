# Gera Palavras

## 📝 Sobre o Projeto

O **GeraPalavras** é um aplicativo simples desenvolvido em Flutter que gera pares de palavras aleatórias e permite ao usuário marcar como favoritos. Ele possui funcionalidades como histórico de palavras geradas, gerenciamento de favoritos, e um layout responsivo para dispositivos móveis e desktops.

---

## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- **[Flutter](https://flutter.dev/)**: Framework para desenvolvimento de aplicativos multiplataforma (Android, iOS, Web, Desktop).
- **[Dart](https://dart.dev/)**: Linguagem de programação utilizada pelo Flutter.
- **[Provider](https://pub.dev/packages/provider)**: Biblioteca para gerenciamento de estado.
- **[English Words](https://pub.dev/packages/english_words)**: Biblioteca para geração de palavras aleatórias em inglês.
- **Material Design 3**: Tema visual baseado no design system do Google.

---

## 🛠️ Funcionalidades

- **Geração de Palavras Aleatórias**: Exibe pares de palavras gerados dinamicamente.
- **Favoritar Palavras**: Permite marcar palavras como favoritas e gerenciá-las.
- **Histórico de Palavras Geradas**: Mantém um histórico das palavras visualizadas.
- **Design Responsivo**: Layout adaptável para diferentes tamanhos de tela (mobile, tablet e desktop).
- **Navegação por Aba ou Menu Lateral**: Alterna entre a página inicial e a de favoritos.

---

## 📂 Estrutura de Pastas

Abaixo está a organização do projeto:

```plaintext
lib/
├── app/
│   └── app_state.dart      # Gerenciamento do estado do aplicativo
├── pages/
│   ├── favorites_page.dart # Tela de favoritos
│   └── home_page.dart      # Tela inicial do aplicativo
├── widgets/
│   ├── big_card.dart       # Componente para exibir a palavra gerada
│   └── history_list_view.dart # Componente do histórico de palavras
└── main.dart               # Ponto de entrada da aplicação
