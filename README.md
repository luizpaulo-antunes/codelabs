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


▶️ Como Rodar o Projeto
Siga as etapas abaixo para rodar o projeto localmente:

1. Pré-requisitos
Instale o Flutter na sua máquina.
Configure o emulador Android ou iOS ou conecte um dispositivo físico.
2. Clonar o Repositório
bash
Copiar código
git clone https://github.com/seu-usuario/namer-app.git
cd namer-app
3. Instalar Dependências
bash
Copiar código
flutter pub get
4. Rodar o Projeto
Execute o seguinte comando para rodar o projeto:

bash
Copiar código
flutter run
🖼️ Demonstração
Tela Inicial

Gera pares de palavras aleatórias.
Botões de "Like" e "Próximo".
Tela de Favoritos

Exibe todas as palavras marcadas como favoritas.
Opção de remover favoritos.
📌 Melhorias Futuras
Integração com Backend: Sincronizar os favoritos com uma API.
Suporte a Multilinguagem: Adicionar tradução para outros idiomas.
Armazenamento Local: Persistir favoritos no dispositivo usando SQLite ou SharedPreferences.
🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um issue ou enviar um pull request.

📄 Licença

Pode passar.

Desenvolvido com ❤️ por Luiz Paulo.
