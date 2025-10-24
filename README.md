# 🍲 Sabor Express (Python)

Uma aplicação de console em Python para gerenciamento de restaurantes. Este projeto foi desenvolvido como um exercício prático para aplicar e solidificar os conceitos fundamentais de **Programação Orientada a Objetos (OOP)**.

O sistema permite cadastrar restaurantes, atribuir avaliações, adicionar itens ao cardápio e controlar o estado de atividade de cada restaurante.

## ✨ Funcionalidades Principais

-   **Cadastro de Restaurantes:** Permite criar novas instâncias de restaurantes.
-   **Listagem de Restaurantes:** Exibe todos os restaurantes cadastrados com seus detalhes (nome, categoria, avaliação, etc.).
-   **Gerenciamento de Estado:** Permite "ativar" ou "desativar" um restaurante.
-   **Gestão de Cardápio:** Permite adicionar itens (como pratos ou bebidas) ao cardápio de um restaurante específico.
-   **Sistema de Avaliação:** Permite que restaurantes recebam avaliações, e o sistema calcula a média de notas.

## 🛠️ Conceitos Técnicos e de OOP Aplicados

O principal objetivo deste projeto foi demonstrar um bom design de classes e o relacionamento entre elas.

-   **Classes e Objetos:** O projeto é estruturado em torno de classes como `Restaurante`, `Cardapio`, `ItemCardapio` e `Avaliacao`, que servem como moldes para os objetos utilizados no programa.
-   **Método Construtor (`__init__`):** Utilizado para inicializar os atributos de cada objeto (como nome, categoria, etc.) no momento da sua criação.
-   **Abstração:** Foco em criar uma representação simplificada de um restaurante, expondo apenas os métodos e atributos necessários para a interação.
-   **Encapsulamento:** Uso de `@property` (properties) para controlar o acesso e a modificação de atributos (como `ativo`), garantindo que o estado do objeto seja sempre válido.
-   **Composição:** Demonstração de como um objeto (Restaurante) é "composto" por outros objetos (como uma instância de `Cardapio` ou uma lista de `Avaliacao`).
-   **Métodos Mágicos (`__str__`):** Implementação de métodos especiais para definir uma representação em string "amigável" para os objetos, facilitando a exibição na função `listar_restaurantes`.

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/Vencce/SaborExpress-Python.git](https://github.com/Vencce/SaborExpress-Python.git)
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd SaborExpress-Python
    ```

3.  **Execute o arquivo principal:**
    ```bash
    python app.py
    ```

---

Desenvolvido por [Vitor Ferreira](https://github.com/Vencce) como parte dos estudos de Programação Orientada a Objetos com Python.
