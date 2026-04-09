# 📚 Sitema de Gestão de Biblioteca (POO)

> Sistema de gerenciamento de biblioteca desenvolvido para consolidar os quatro pilares da Programação Orientada a Objetos.

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Jest](https://img.shields.io/badge/Tests-Jest-C21325)

## 🚀 Sobre o Projeto

Este projeto foi a avaliação final da disciplina de **Programação Orientada a Objetos** (3º Semestre - ADS). O objetivo foi construir um sistema CLI (Linha de Comando) capaz de gerenciar o ciclo de vida de empréstimos de livros, garantindo a integridade dos dados e aplicando padrões de projeto escaláveis.

### 🧠 Pilares da POO Aplicados

Para demonstrar domínio técnico, a arquitetura foi baseada em:

* **Abstração & Herança:** Criação da classe abstrata `Pessoa`, servindo de base para a classe `Membro`.
* **Encapsulamento:** Uso de modificadores de acesso (`private`, `protected`) e métodos `get/set` para proteção do estado dos objetos.
* **Polimorfismo:** Sobrescrita de métodos (Override) para exibição de dados customizados em diferentes níveis da hierarquia.
* **Associação de Classes:** A classe `Emprestimo` atua como uma classe de associação, vinculando instâncias de `Livro` e `Membro`.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** TypeScript (Tipagem estática para maior segurança).
* **Runtime:** Node.js com `ts-node`.
* **Persistência:** Manipulação de arquivos do sistema (FileSystem) para gravação/leitura de dados em formato `.json`.
* **Testes:** Jest para garantir que as regras de negócio (como "não emprestar livro já emprestado") funcionem perfeitamente.
* **Interface:** Prompt-sync para interação via terminal.

---

## 📂 Funcionalidades Principais

- [x] **Gestão de Acervo:** Adicionar e listar livros com status de disponibilidade.
- [x] **Gestão de Membros:** Cadastro de usuários com matrícula única.
- [x] **Sistema de Empréstimos:** Registro de saída de livros vinculando-os a membros.
- [x] **Devolução:** Atualização automática do status do livro e registro de data.
- [x] **Persistência Automática:** Todos os dados são salvos na pasta `/dados` em arquivos JSON.

---

## ⚙️ Como executar

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/gabrielschug/library-manager-typescript.git](https://github.com/gabrielschug/library-manager-typescript.git)
    ```
2. Instale as dependências:

```
npm install
```

3. Execute o sistema:
```
npm start
```

4. Para rodar os testes:
```
npm test
```
---
## 🤝 Autor
Gabriel Schug - Estudante de Análise e Desenvolvimento de Sistemas
