# 🛒 Simulação de Mercado em Python

## Sobre o Projeto
Este projeto é uma aplicação de terminal que simula um pequeno sistema de mercado, permitindo cadastrar produtos, listar itens disponíveis, adicionar compras ao carrinho e finalizar pedidos.
Ele foi desenvolvido para praticar conceitos fundamentais de Python, incluindo:

Programação orientada a objetos (POO)
Estruturas de dados (listas e dicionários)
Modularização
Boas práticas de organização
Interação com o usuário via terminal

## Funcionalidades
O sistema oferece as seguintes operações:

1. Cadastrar Produto: Permite adicionar produtos ao catálogo informando nome e preço.

2. Listar Produtos: Exibe todos os produtos cadastrados com seus dados formatados.

3. Comprar Produto: O usuário escolhe um produto pelo código e o adiciona ao carrinho.
Se o item já existir, a quantidade é automaticamente incrementada.

4. Visualizar Carrinho: Lista tudo que foi adicionado ao carrinho, incluindo quantidade de cada item.

5. Fechar Pedido: Calcula o valor total da compra, exibe a fatura e limpa o carrinho.

6. Sair: Encerra o sistema.

## Estrutura do Projeto
📁 MercadoPy
├── mercado.py
├── teste.py
├── README.md
├── models
│   └── produto.py
└── utils
    └── helper.py
    
mercado.py: arquivo principal contendo o menu e fluxos da aplicação.
models/produto.py: classe Produto, responsável por nome, preço e código.
utils/helper.py: funções auxiliares (ex.: formatação monetária).

## Tecnologias Utilizadas
- Python 3.10+
- Programação Orientada a Objetos
- Modularização e separação de responsabilidades

##  Como Executar

Para rodar este código, você pode:
1.  Clonar o repositório: git clone https://github.com/beatrizalmc/Simulacao-de-Mercado-com-Python.git
2.  Entre na pasta: cd Simulacao-de-Mercado-com-Python
3.  Execute o programa: python mercado.py

## Exemplo de Menu
<img width="288" height="188" alt="image" src="https://github.com/user-attachments/assets/4823f2fa-d3e6-48b9-9b56-7d6d89581130" />
