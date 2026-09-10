# 📧 Email Simulator

Este projeto é um simulador de cliente de email em linha de comando desenvolvido em Python. Ele permite simular o fluxo básico de comunicação entre usuários, incluindo o envio de mensagens, leitura, gerenciamento da caixa de entrada e exclusão de emails.

---

## 🎯 Origem e Propósito

Este projeto faz parte do desafio prático do currículo **[Scientific Computing with Python](https://www.freecodecamp.org/)** da plataforma **freeCodeCamp**.

O objetivo principal do exercício foi praticar:
- Programação Orientada a Objetos (POO) em Python (classes `User`, `Email` e `Inbox`).
- Gerenciamento de estado e coleções de dados (listas de emails).
- Lógica de indexação e manipulação de objetos na memória.
- Métodos de interação e formatação de saída no terminal.

---

## 🚀 Funcionalidades

- **Classe `User`**:
  - `send_email(recipient, subject, body)`: Cria e envia uma mensagem para a caixa de entrada de outro usuário.
  - `check_inbox()`: Exibe a lista de emails recebidos na caixa de entrada.

- **Classe `Inbox`**:
  - `read_email(index)`: Permite visualizar o conteúdo completo de um email específico.
  - `delete_email(index)`: Remove um email da caixa de entrada com validação de índice.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3** (sem bibliotecas externas)

---

## 💻 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/brumarcuz/email_simulator.git
