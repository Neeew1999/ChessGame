
# ♟️ ChessGame em Java

Este projeto implementa um **jogo de xadrez** simples, utilizando Java. O código inclui a interface gráfica e a lógica para jogar xadrez. O jogo é executado através de um arquivo JAR.

## 📁 Estrutura do Projeto

```
📦 raiz-do-projeto
├── ChessGame.jar             # Arquivo JAR compilado do jogo
├── GridLayoutXadrez.class    # Arquivo compilado da classe GridLayoutXadrez
├── GridLayoutXadrez.java     # Código fonte da classe GridLayoutXadrez
├── out/                      # Arquivo de saída da compilação
├── resources/                # Recursos como imagens e sons
└── src/                      # Código fonte do projeto
```

## 📝 Descrição do Jogo

O jogo de xadrez é uma implementação simples utilizando Java. Ele oferece uma interface gráfica para movimentação das peças em um tabuleiro de 8x8. O objetivo é capturar o rei adversário, como no xadrez tradicional.

## ⚙️ Como Executar

1. Certifique-se de ter o **Java 8 ou superior** instalado.
2. Compile o código (se necessário) com o seguinte comando:

```bash
javac src/GridLayoutXadrez.java
```

3. Para executar o jogo, basta rodar o arquivo JAR:

```bash
java -jar ChessGame.jar
```

## 📌 O que o código faz

- Exibe um tabuleiro de xadrez interativo.
- Permite a movimentação das peças de acordo com as regras do xadrez.
- Implementa a lógica para verificar xeque e xeque-mate.

## 💡 Exemplo de Saída

Após iniciar o jogo, uma janela gráfica será aberta com o tabuleiro de xadrez. Você poderá mover as peças de acordo com as regras.

## ❌ Tratamento de Erros

O jogo trata erros como:
- Movimentos inválidos (ex: movimento fora das regras do xadrez).
- Erros de inicialização ao carregar o tabuleiro ou as peças.

## 👨‍💻 Autor

- Desenvolvido por: **New Cleiton dos Santos**
- Curso: Analise e Desenvolvimento de Sistemas
