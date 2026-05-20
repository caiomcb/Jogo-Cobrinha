**Jogo da Cobrinha**

Um clássico jogo arcade desenvolvido inteiramente em Java. O objetivo principal é controlar a serpente pela tela, coletando as comidas para crescer e acumular pontos, evitando colidir com as paredes ou com o próprio corpo. O projeto conta com efeitos sonoros dinâmicos e animações visuais para uma experiência mais imersiva.

## Sobre o Projeto
Este projeto foi construído para colocar em prática conceitos importantes de programação orientada a objetos (POO), computação gráfica nativa e manipulação de eventos do sistema. 

### Principais mecânicas implementadas:
* **Movimentação Incremental:** Controle fluido da cobrinha pela grade da tela respondendo aos comandos do teclado.
* **Sistema de Colisão Preciso:** Detecção de contato da cabeça da serpente com o próprio corpo, com as bordas da tela (gerando Game Over) e com o objeto da comida.
* **Geração Aleatória de Itens:** Reposicionamento automático da comida dentro dos limites da tela a cada pontuação.
* **Gerenciamento de Assets Portáteis:** Sistema de áudio (`Clip` e `AudioInputStream`) e imagens (`ImageIcon`) carregados via caminhos relativos (`getClass().getResource`), garantindo que o jogo rode em qualquer sistema operacional sem dependências de arquivos locais do disco rígido.

## Tecnologias Utilizadas
* **Java:** Linguagem principal do projeto.
* **AWT / Swing:** Bibliotecas nativas utilizadas para a construção da interface gráfica (renderização da janela, componentes, desenho da tela de fim de jogo e animação do texto).
* **Manipulação de Áudio:** Uso das classes nativas para execução dos efeitos sonoros de pontuação e fim de jogo.

## Como executar o projeto
Se você quiser rodar este jogo na sua máquina, siga os passos abaixo:

Passo 1: Pré-requisitos
Você precisa ter o Java Development Kit (JDK) instalado no seu computador para o jogo funcionar.

Passo 2: Baixar o Jogo
* **Opção A:** Procure o botão verde chamado **Code** no topo desta página, clique nele e escolha **Download ZIP**. Depois, extraia a pasta no seu computador.
* **Opção B (Via Terminal):** Se você tiver o Git instalado, mude o diretório no terminal para onde deseja salvar e clone o projeto: `git clone https://github.com/caiomcb/Jogo-Cobrinha.git`

Passo 3: Rodando

Após baixar os arquivos, basta abrir a pasta do projeto na sua IDE (como Eclipse, IntelliJ ou VS Code), encontrar o arquivo principal dentro da pasta `src` e executá-lo (Run).
