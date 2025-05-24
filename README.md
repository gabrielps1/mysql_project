# Sistema de Pedido de Marmitas - Restaurante da Janete

Este projeto foi desenvolvido para atender às necessidades de um restaurante local que estava em grande progresso na cidade.

## Funcionalidades

O sistema permite:

- Cadastro de opções de **cardápio**, com:
  - Nome do prato
  - Descrição
  - Data que será ofertado
- Cadastro de **tamanhos de marmitas**:
  - Pequena (P)
  - Média (M)
  - Grande (G)
  - Com seus respectivos valores
- Cadastro de **clientes**, com os seguintes dados:
  - Nome completo
  - CPF
  - Endereço completo (rua, número, complemento, bairro, cidade, CEP)
  - Telefone de contato
- Cadastro de **pedidos** realizados pelos clientes:
  - Seleção do cliente
  - Uma ou mais marmitas com:
    - Tamanho (P, M ou G)
    - Quantidade
  - Data do pedido
  - Forma de entrega: **Retirada** ou **Delivery**
  - Forma de pagamento
  - Endereço de entrega
  - Valor total do pedido
- Cadastro de **cupom de desconto**, utilizando uma palavra-chave para aplicar descontos no pedido.

## Tecnologias utilizadas

- **C# com Windows Forms**
- **MySQL** para o banco de dados

## Como executar

1. Baixe o projeto.
2. Abra o arquivo `Janete.sql` em algum editor MySQL.
3. Vá em **File** > **Open SQL Script** e execute o script para criar o banco de dados.

## Autor

Desenvolvido por **Gabriel Pereira Silva**, graduando em Ciência da Computação.
