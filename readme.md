# 📝 Flutter Task Manager App

Aplicativo de gerenciamento de tarefas desenvolvido em **Flutter**, utilizando **GetX** para gerenciamento de estado e **Firebase** para autenticação e persistência de dados.

---

## 🚀 Funcionalidades

### 🔐 Autenticação
- Cadastro de usuário com nome, email e senha
- Login com email e senha
- Logout

### ✅ Tarefas
- Criar tarefa com título, descrição e data de criação
- Editar tarefa
- Deletar tarefa
- Marcar tarefa como:
  - Concluída
  - Favorita
- Visualizar:
  - Todas as tarefas
  - Apenas tarefas favoritas

### 👤 Multiusuário
- Cada usuário visualiza apenas **suas próprias tarefas**
- As tarefas são vinculadas ao `uid` do usuário no Firebase

---

## ✨ Diferenciais

- Persistência local de dados (ex: Hive, GetStorage, SharedPreferences)
- Campo de busca por título ou descrição
- Filtros por:
  - Nome
  - Data de criação
  - Concluídas
  - Favoritas
- Ordenação alfabética ou por data
- Tema Light/Dark com seleção dinâmica
- Suporte Offline First com sincronização em background ao reconectar
- O aplicativo é responsivo e se adapta a diferentes tamanhos de tela, incluindo smartphones e tablets.

---


