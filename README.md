# 🎯 Guess the Number (Rust)

Um projeto simples desenvolvido em Rust com o objetivo de praticar conceitos fundamentais da linguagem por meio da criação de um jogo de adivinhação.

## 📖 Sobre o Projeto

O programa gera um número aleatório entre **1 e 100** e o jogador deve tentar descobrir qual é esse número.

A cada tentativa, o sistema informa se o valor digitado é:

- Menor que o número secreto;
- Maior que o número secreto;
- Igual ao número secreto.

O jogo continua até que o jogador encontre a resposta correta.

## 🛠️ Tecnologias Utilizadas

- Rust
- Cargo
- Crate `rand`

## 🚀 Como Executar o Projeto

### 1. Instale o Rust

Acesse:

https://www.rust-lang.org/

ou utilize o instalador oficial:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Verifique a instalação:

```bash
rustc --version
cargo --version
```

### 2. Clone o Repositório

```bash
git clone https://github.com/seu-usuario/guess-the-number.git
```

Entre na pasta do projeto:

```bash
cd guess-the-number
```

### 3. Instale as Dependências

Certifique-se de que o arquivo `Cargo.toml` contém:

```toml
[dependencies]
rand = "0.8"
```

### 4. Execute o Programa

```bash
cargo run
```

Saída esperada:

```text
Guess the number!
Please input your guess.
```

Digite um número entre **1 e 100** e pressione **Enter** para fazer sua tentativa.

## 📂 Estrutura do Projeto

```text
guess-the-number/
│
├── src/
│   └── main.rs
│
├── Cargo.toml
├── Cargo.lock
└── README.md
```
