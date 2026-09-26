# 📚 Sistema de Gestão de Biblioteca em C

Sistema em linha de comandos (CLI) desenvolvido em linguagem C para gestão completa do acervo de uma biblioteca escolar/universitária.

## 🚀 Tecnologias Utilizadas
- **Linguagem:** C (C99/C11)
- **Estruturas de Dados:** `struct`, Arrays, Strings (`string.h`)

## 📌 Funcionalidades
- **Gestão do Acervo:** Cadastro, listagem, ordenação (por Título ou Autor) e pesquisa de livros por ISBN, Título ou Sobrenome do Autor.
- **Gestão de Utilizadores:** Registos de utilizadores com validação de matrícula e e-mail.
- **Empréstimos e Devoluções:** Registo de empréstimos, controlo de disponibilidade e histórico por utilizador.
- **Validação de Dados:** Funções de verificação para ISBN (13 dígitos), formato de e-mail e formato de datas.

## 📂 Como Compilar e Executar
```bash
# Compilar o código
gcc -o biblioteca miguel_ariel_sprint4.c

# Executar a aplicação
./biblioteca
