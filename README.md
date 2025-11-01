# 🧩 Jogo do Sudoku em Java (Terminal)

![Java Badge](https://img.shields.io/badge/Feito%20com-Java-007396?style=for-the-badge&logo=java)
![Status Badge](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 🌟 Sobre o Projeto

Este projeto consiste na implementação de um **Jogo de Sudoku interativo** desenvolvido integralmente em **Java**. O principal objetivo foi consolidar conhecimentos em **Programação Orientada a Objetos (POO)** e manipulação eficiente de estruturas de dados, criando uma experiência de jogo funcional e envolvente diretamente no terminal.

O desafio focou na criação de um tabuleiro dinâmico, validação de movimentos e na gestão do *game state* utilizando classes e métodos Java bem definidos.

### 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java
* **Ambiente:** Terminal / Console
* **Paradigma:** Programação Orientada a Objetos (POO)

---

## 🚀 Começando

Para executar o jogo do Sudoku no seu ambiente, siga os passos abaixo.

### Pré-requisitos

Você precisa ter o **Java Development Kit (JDK)** instalado em sua máquina. Recomenda-se a versão 11 ou superior.

```bash
# Verifique sua versão do Java
java -version
```

### Instalação e Execução

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/](https://github.com/)[seu-usuario]/[seu-repositorio-sudoku].git
    cd [seu-repositorio-sudoku]
    ```

2.  **Compile o Código Fonte:**
    Se você estiver usando um ambiente de desenvolvimento (como VS Code ou IntelliJ), ele pode compilar automaticamente. Caso contrário, use o terminal:
    ```bash
    javac src/*.java
    ```

3.  **Execute o Jogo:**
  Assumindo que o método `main` está na classe **`App.java`**:
   ```bash
   java App
```

---

## 🎮 Como Jogar (Uso)

O jogo é totalmente interativo via terminal.

1.  O **tabuleiro de Sudoku 9x9** será exibido com os números iniciais.
2.  O programa solicitará que você insira os movimentos.
3.  **Formato de Entrada:** A entrada deve ser no formato: `linha coluna valor`

    > **Exemplo:** Para inserir o número **5** na **linha 3** e **coluna 7**:
    > ```
    > 3 7 5
    > ```

### ✨ Funcionalidades Destacadas

* **Validação de Movimento:** Verifica instantaneamente se o número inserido é válido (se não conflita na linha, coluna ou bloco 3x3).
* **Estrutura POO:** O projeto utiliza classes bem definidas para isolar responsabilidades (`Tabuleiro`, `Jogador`, `Validador`).
* **Interface no Terminal:** Apresentação clara do tabuleiro e mensagens de *feedback* ao usuário.

---

## 🤝 Contribuição

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar.

1.  Faça um *Fork* do projeto.
2.  Crie uma *branch* para sua *feature* (`git checkout -b feature/NovaFuncionalidade`).
3.  Faça o *commit* das suas mudanças (`git commit -m 'feat: Adiciona Nova Funcionalidade'`).
4.  Faça o *Push* para a *Branch* (`git push origin feature/NovaFuncionalidade`).
5.  Abra um *Pull Request*.

---

### 👩‍💻 Autora
Feito com 💛 por Bruna Guimarães

---

### 🌟 Apoie o projeto
Se você gostou, não esqueça de deixar uma ⭐ no repositório!
Isso ajuda muito o projeto a crescer e me incentiva a continuar criando. 🙌





