# Lab Mobile Kickoff

Este projeto é o ponto de partida (kickoff) para o Laboratório Mobile. O objetivo principal é estabelecer a estrutura base de uma aplicação Flutter seguindo padrões de organização de pastas e modelagem de dados.

## 🚀 Estrutura do Projeto

O projeto foi organizado seguindo uma arquitetura simplificada para facilitar a manutenção:

- **`domain`**: Contém as entidades e modelos de negócio (ex: Classe `Servico`).
- **`data`**: Responsável pela manipulação de dados e repositórios (ex: `ServicoRepository`).
- **`presentation`**: Camada visual contendo as telas e widgets da interface.
- **`application`**: Camada de lógica de aplicação e estados.

## 🛠️ Funcionalidades Iniciais

- [x] Configuração inicial do ambiente Flutter.
- [x] Implementação da interface básica com `AppBar` customizada.
- [x] Criação do modelo de dados `Servico`.
- [x] Implementação de repositório em memória (fake repository).

## 📱 Como executar

1. Certifique-se de ter o Flutter instalado.
2. Clone o repositório.
3. No terminal, execute:
   ```bash
   flutter pub get
   flutter run