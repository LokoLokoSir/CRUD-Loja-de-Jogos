# CRUD-Loja-de-Jogos

Este é um projeto **simples de gerenciamento de um catálogo de jogos**, simulando as operações básicas de uma plataforma como a Steam, desenvolvido em Java. O sistema manipula objetos do tipo `Jogo` e armazena-os em uma lista (`ArrayList`).

O catálogo de jogos suporta as seguintes operações CRUD (Create, Read, Update, Delete):

* **Adicionar Jogo** (Criação)
* **Visualizar Catálogo** (Leitura)
* **Atualizar Dados** de um jogo (Atualização)
* **Deletar Jogo** (Exclusão)

---

## Tecnologias Utilizadas

| Tecnologia | Notas |
| :--- | :--- |
| **Java** | Linguagem principal (versão 8+ recomendada) |
| **Estrutura de Dados** | `java.util.ArrayList` para armazenar o catálogo |
| **Entrada/Saída** | `java.util.Scanner` para interação via console |

---

## Como Executar o Projeto

Para rodar este projeto, você deve ter o **Java Development Kit (JDK)** instalado em sua máquina.

### Instruções de Compilação e Execução

O projeto é composto pelas classes `Jogo`, `JogoController` e `Main`.

#### 1. Compilação (Via Terminal)

Navegue até o diretório onde os arquivos `.java` estão salvos e use o compilador Java:

```bash
javac Jogo.java JogoController.java Main.java
```

## Print do Console

ID: 0 | Nome: Hollow Knight | Descrição: Uma aventura de ação épica em um vasto reino arruinado de insetos e heróis. | Preço: R$ 46,99 | Gêneros: Metroidvania, Soulslike, Plataforma

ID: 1 | Nome: Stardew Valley | Descrição: Será que você vai aprender a viver da terra, a transformar esse matagal em um próspero lar? | Preço: R$ 24,99 | Gêneros: Simulador Rural, RPG

ID: 2 | Nome: Hades | Descrição: Desafie o deus dos mortos enquanto você batalha para sair do Submundo. | Preço: R$ 73,99 | Gêneros: Roguelike, Hack and Slash

Digite o ID do jogo que deseja atualizar:

1

Digite qual propriedade do jogo deseja atualizar (nome, descricao, preco, generos):

generos

Escreva a atualização:

Simulador Rural, RPG, Tranquilo

ID: 0 | Nome: Hollow Knight | Descrição: Uma aventura de ação épica em um vasto reino arruinado de insetos e heróis. | Preço: R$ 46,99 | Gêneros: Metroidvania, Soulslike, Plataforma

ID: 1 | Nome: Stardew Valley | Descrição: Será que você vai aprender a viver da terra, a transformar esse matagal em um próspero lar? | Preço: R$ 24,99 | Gêneros: Simulador Rural, RPG, Tranquilo

ID: 2 | Nome: Hades | Descrição: Desafie o deus dos mortos enquanto você batalha para sair do Submundo. | Preço: R$ 73,99 | Gêneros: Roguelike, Hack and Slash

Digite o ID do jogo que deseja deletar:

2

ID: 0 | Nome: Hollow Knight | Descrição: Uma aventura de ação épica em um vasto reino arruinado de insetos e heróis. | Preço: R$ 46,99 | Gêneros: Metroidvania, Soulslike, Plataforma

ID: 1 | Nome: Stardew Valley | Descrição: Será que você vai aprender a viver da terra, a transformar esse matagal em um próspero lar? | Preço: R$ 24,99 | Gêneros: Simulador Rural, RPG, Tranquilo

## Autor

José Guilherme Colatino Pessoa
