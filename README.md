# ♟️ Chess System Java

<p align="center">
  <img src="https://img.shields.io/badge/Java-17+-blue" />
  <img src="https://img.shields.io/badge/OOP-Object%20Oriented-green" />
  <img src="https://img.shields.io/badge/Status-Concluído-success" />
</p>

---

## 📌 Sobre o projeto

Este projeto consiste em um **sistema de jogo de xadrez desenvolvido em Java**, com foco na aplicação de conceitos de **programação orientada a objetos** e lógica de regras complexas.

O sistema implementa as principais regras do xadrez, permitindo simular partidas completas diretamente no console.

Projetos desse tipo são amplamente utilizados como prática para reforçar lógica e modelagem de domínio, já que envolvem regras detalhadas e validações complexas. ([Jogo de Xadrez][1])

---

## 🎯 Objetivo

O objetivo deste projeto é consolidar conhecimentos em:

* Programação Orientada a Objetos (POO)
* Lógica de programação avançada
* Modelagem de sistemas complexos
* Estruturação de código limpo e organizado

---

## 🛠️ Tecnologias utilizadas

* **Java 17+**
* **Programação Orientada a Objetos**
* Execução via terminal (console)

---

## 🧠 Conceitos aplicados

* Encapsulamento
* Herança
* Polimorfismo
* Abstração
* Estrutura de dados
* Regras de negócio complexas
* Manipulação de matriz (tabuleiro)

---

## ♟️ Funcionalidades do sistema

* Movimentação de peças (Rei, Rainha, Torre, Bispo, Cavalo e Peão)
* Validação de jogadas
* Captura de peças
* Controle de turno (jogador vs jogador)
* Verificação de **xeque**
* Verificação de **xeque-mate**

Sistemas de xadrez normalmente incluem validação de movimentos legais e detecção de situações como check e checkmate, sendo um excelente exercício de lógica e estrutura de código. ([GitHub][2])

---

## ⚙️ Como executar o projeto

### 🔧 Pré-requisitos

* Java 17+
* Git

---

### ▶️ Passo a passo

```bash
# Clonar o repositório
git clone https://github.com/oCauaAlves/chess-system-java.git

# Entrar na pasta
cd chess-system-java

# Compilar o projeto
javac application/Program.java

# Executar o programa
java application.Program
```

---

## 🖥️ Como jogar

1. O jogo inicia com o tabuleiro padrão de xadrez
2. Os jogadores alternam turnos
3. Informe a posição de origem e destino das peças
4. O sistema valida automaticamente se a jogada é válida

Exemplo:

```
Origem: e2
Destino: e4
```

---

## 🗄️ Estrutura do projeto

```
src
 ├── application     # Classe principal (execução)
 ├── boardgame       # Estrutura do tabuleiro
 ├── chess           # Regras do xadrez
 │    ├── pieces     # Classes das peças
```

---

## 📸 Demonstração (adicione prints aqui)

```markdown
![Exemplo](./assets/chess.png)
```

💡 Dica: print do terminal rodando o jogo fica MUITO bom aqui.

---

## 🚀 Possíveis melhorias

* Interface gráfica (JavaFX ou Swing)
* Implementação de IA para jogar contra o computador
* Multiplayer online
* Salvamento de partidas
* Interface web (Spring + frontend)

---

## 📈 Diferenciais deste projeto

✔ Forte uso de lógica de programação
✔ Implementação de regras reais de negócio
✔ Código orientado a objetos bem estruturado
✔ Excelente projeto para demonstrar raciocínio lógico

---

## 👨‍💻 Autor

**Cauã Alves**

* 💼 GitHub: https://github.com/oCauaAlves
* 🔗 LinkedIn: https://www.linkedin.com/in/caua-alves-2b634a276/

---

## ⭐ Considerações finais

Este projeto foi desenvolvido com o objetivo de aprofundar conhecimentos em lógica e programação orientada a objetos, simulando um sistema real com regras complexas.

Projetos como este demonstram capacidade de resolver problemas e estruturar soluções — habilidades essenciais para desenvolvedores backend.

Se gostou do projeto, fique à vontade para explorar e evoluir 🚀

[1]: https://chess-game-download.netlify.app/?utm_source=chatgpt.com "Java Chess Game"
[2]: https://github.com/fredzqm/Chess?utm_source=chatgpt.com "GitHub - fredzqm/Chess: My wonderful java chess game"
