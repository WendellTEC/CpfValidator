📄 Validador de CPF - Java SE 21
📌 Sobre o projeto
Este projeto é uma aplicação simples desenvolvida em Java SE 21 com o objetivo de demonstrar, de forma didática, como funciona a validação de um CPF.

A aplicação recebe um CPF como entrada, realiza o tratamento dos dados e executa as validações necessárias para verificar se o CPF é válido ou não.

---

⚙️ Funcionalidades
- Entrada de CPF pelo usuário
- Validação de tamanho (garante 11 dígitos usando do-while)
- Remoção automática de caracteres especiais (. e -)
- Separação dos dígitos em uma lista
- Verificação completa do CPF

---

🧠 Lógica da aplicação
1. Entrada de dados

O usuário insere o CPF, que passa por um "do-while" garantindo que:
- Tenha exatamente 11 dígitos
- Caracteres especiais sejam removidos automaticamente

---
  
2. Tratamento
- O CPF (String) é convertido em uma lista
- Cada número ocupa um índice da lista

---
  
3. Validação

A validação é feita por uma classe específica que possui 4 métodos:
- Verificador do 1º dígito
- Verificador do 2º dígito
- Verificador de números iguais (ex: 11111111111)
- Verificador geral
  - Responsável por chamar todos os outros métodos
  - Não possui retorno
  - Exibe no console se o CPF é válido ou inválido

---

🎯 Objetivo
O principal objetivo deste projeto é ser simples e educativo, ajudando no entendimento da lógica de validação de CPF e na organização básica de um projeto Java com separação por pacotes.

---

▶️ Como executar
1. Compile o projeto com Java 21
2. Execute a classe principal do pacote app
3. Insira um CPF quando solicitado

---

🧪 Exemplo de uso

Digite o CPF: 123.456.789-09
CPF inválido

---
📚 Conceitos aplicados
- Estruturas de repetição (do-while)
- Manipulação de String
- Listas
- Programação orientada a objetos
- Separação por pacotes
