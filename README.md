# 📱 Flutter Studies

Repositório de estudos e projetos práticos desenvolvidos em Flutter, explorando diversos conceitos, recursos e boas práticas do framework.

## 📋 Sobre

Este repositório contém uma coleção de aplicações Flutter desenvolvidas para aprendizado e experimentação de diferentes funcionalidades, arquiteturas e padrões de desenvolvimento mobile. Cada projeto explora conceitos específicos do ecossistema Flutter.

## 🚀 Projetos

### 🏦 Bytebank

Uma série de projetos focados no desenvolvimento de um aplicativo bancário, cada um explorando diferentes aspectos e tecnologias:

- **bytebank_api** - Integração com APIs REST e manipulação de dados remotos
- **bytebank_bloc** - Implementação do padrão BLoC (Business Logic Component) para gerenciamento de estado
- **bytebank_http** - Requisições HTTP e comunicação com servidores backend
- **bytebank_internacionalizacao** - Internacionalização e suporte a múltiplos idiomas
- **bytebank_list** - Implementação de listas e widgets de navegação
- **bytebank_sqflite** - Persistência de dados local usando SQLite
- **bytebank_testes** - Testes unitários e de widgets

### 📊 Calculadora IMC

Aplicativo para cálculo do Índice de Massa Corporal (IMC), explorando:

- Formulários e validação de entrada de dados
- Navegação entre telas
- Cálculos e formatação de resultados

### 🦸 Marvel

Aplicativo que exibe uma lista de personagens da Marvel, trabalhando com:

- Consumo de APIs
- Listagem de dados dinâmicos
- Interface temática personalizada

### ✅ Tasks

Dois projetos de gerenciamento de tarefas inspirados no Google Tasks:

- **tasks_list** - Clone do aplicativo Google Tasks com interface completa
  - Gerenciamento de listas de tarefas
  - Interface de usuário moderna e intuitiva
  - Operações CRUD completas

- **tasks_sqflite** - Versão com persistência de dados usando SQLite
  - Armazenamento local de tarefas
  - Banco de dados relacional

### 📝 TodoList

Aplicativo de lista de tarefas utilizando:

- Provider para gerenciamento de estado
- Separação entre tarefas finalizadas e não finalizadas
- Arquitetura baseada em models e providers

### ☁️ Weather App

Aplicativo de previsão do tempo, explorando:

- Integração com APIs de clima
- Exibição de dados meteorológicos
- Interface responsiva

## 🛠️ Tecnologias e Conceitos

Este repositório aborda diversos conceitos e tecnologias do ecossistema Flutter:

- **Gerenciamento de Estado**: BLoC, Provider
- **Persistência de Dados**: SQLite (sqflite)
- **Requisições HTTP**: Consumo de APIs REST
- **Arquitetura**: Separação de responsabilidades, Models, Screens
- **UI/UX**: Material Design, temas customizados, navegação
- **Internacionalização**: Suporte a múltiplos idiomas
- **Testes**: Testes unitários e de widgets
- **Formulários**: Validação e manipulação de inputs

## 🏃 Como Executar

### Pré-requisitos

- Flutter SDK instalado (versão compatível com os projetos)
- Editor de código (VS Code, Android Studio, etc.)
- Emulador ou dispositivo físico configurado

### Executando um projeto

1. Navegue até a pasta do projeto desejado:

```bash
cd nome-do-projeto
```

2. Instale as dependências:

```bash
flutter pub get
```

3. Execute o aplicativo:

```bash
flutter run
```
