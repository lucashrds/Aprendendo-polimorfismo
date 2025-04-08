# 📦 Projeto de Polimorfismo em Java 🚀
## Descrição 📝
Este projeto demonstra o conceito de polimorfismo em Java, criando um sistema de gerenciamento de produtos com diferentes tipos (comum, usado e importado). Cada tipo de produto possui uma forma diferente de exibir sua etiqueta de preço.

## Funcionalidades ✨
✅ Cadastro de produtos comuns, usados e importados

✅ Cálculo automático de preços (incluindo taxas para produtos importados)

✅ Geração de etiquetas de preço específicas para cada tipo de produto

✅ Formatação de datas para produtos usados

## Classes Principais 🏗️
Product (Classe base)

Atributos: nome, preço

Método: priceTag() (gera etiqueta básica)

UsedProduct (Produto usado)

Herda de Product

Adiciona: data de fabricação

Sobrescreve priceTag() para incluir "(used)" e a data

ImportedProduct (Produto importado)

Herda de Product

Adiciona: taxa alfandegária

Sobrescreve priceTag() para incluir o valor total com taxa

## Como Executar ▶️
Abra o projeto no Eclipse

Execute a classe Program no pacote application

Siga as instruções no console para cadastrar produtos

Veja as etiquetas de preço geradas para cada produto

## Tecnologias Utilizadas 💻
Java 8+

Eclipse IDE

Paradigma de Orientação a Objetos

Polimorfismo (sobrescrita de métodos)

## Aprendizados 📚
Implementação de herança em Java

Uso de polimorfismo com sobrescrita de métodos

Trabalho com datas usando LocalDate

Formatação de valores monetários e datas

Criação de sistemas com classes especializadas

Exemplo de Saída 🖨️
Copy
Nome do produto $ 100.00
Nome do produto (used) $ 50.00 (Manufacture date: 15/03/2020)
Nome do produto $ 150.00 (Customs fee: $ 20.00)
Divirta-se explorando o projeto! 😊👨‍💻
