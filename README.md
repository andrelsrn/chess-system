# ♟️ Chess System (Sistema de Xadrez)

Um sistema de jogo de Xadrez desenvolvido em **Java** com interface de console. Este projeto foi criado com foco na aplicação e consolidação dos conceitos de **Programação Orientada a Objetos (POO)**.

## ✨ Funcionalidades

O sistema simula o jogo de xadrez, implementando as principais regras:

* **Validação de Movimentos:** Assegura que todas as peças (Peão, Torre, Cavalo, Bispo, Rainha e Rei) sigam suas regras de movimento específicas.
* **Interface de Console:** O tabuleiro e o jogo são exibidos e controlados diretamente pelo terminal.
* **Detecção de Xeque e Xeque-Mate:** O sistema é capaz de identificar quando um Rei está em Xeque e quando a partida termina em Xeque-Mate.
* **Lógica de Partida:** Controla a alternância de turnos entre as cores e a contagem de movimentos.
* **Movimento Especial: Roque** 
* **Movimento Especial: En Passant** 
* **Movimento Especial: Promoção de Peão** 
## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java (JDK 17+)
* **Paradigmas:** Programação Orientada a Objetos (POO)
* **Ambiente:** Aplicação de Console/Terminal

## 🚀 Como Rodar o Projeto

### Pré-requisitos

Para executar este projeto, você precisará ter o **Java Development Kit (JDK)** instalado na sua máquina.

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/andrelsrn/chess-system.git
    cd chess-system
    ```

2.  **Compile e Execute (via Terminal):**
    
    * **Compilar:** Navegue até a pasta `src` e compile os arquivos.
        ```bash
       
        javac -cp src src/application/*.java src/chess/*.java src/board/*.java
        ```
        (***Nota:*** *A compilação pode variar dependendo da estrutura exata e do seu IDE.*)

    * **Executar:** A classe principal para execução é `application.main`.
        ```bash
        java -cp src application.main
        ```

3.  **Execute (via IDE):**
    * Abra o projeto na sua IDE favorita (IntelliJ IDEA, Eclipse, VS Code c/ extensão Java).
    * Procure pelo arquivo principal (`main.java` dentro da pasta `application`).
    * Execute a classe **`main`**.

## 🎮 Como Jogar

O jogo é inteiramente operado pelo console, seguindo a notação padrão do xadrez.

1.  **Início do Turno:** O sistema solicitará a coordenada de origem da peça que você deseja mover.
    * **Exemplo de entrada:** `a2`
2.  **Escolha do Destino:** Em seguida, o sistema solicitará a coordenada de destino para onde a peça selecionada irá.
    * **Exemplo de entrada:** `a4`
3.  **Turno:** Os jogadores se alternam, com o jogador das peças brancas começando.

## 🤝 Autor

* **Andre L. S. R. N.** - [GitHub Profile](https://github.com/andrelsrn)

## 📄 Licença

Este projeto está sob a licença [MIT License](https://github.com/andrelsrn/chess-system/blob/main/LICENSE) (Se você adicionar o arquivo `LICENSE` no seu repositório).
