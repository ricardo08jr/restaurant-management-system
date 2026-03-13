# Lista de Requisitos e Restrições

## Vendas Online

- Gerenciamento de entregadores
- Subtração automática do estoque
- Emissão de nota fiscal
- Emitir nota e imprimir (conexão com hardware)

## Gerenciamento de Produtos de Limpeza e Descartáveis

- Cadastro
- Alteração
- Exclusão
- Visualização

## Gerenciamento de Pagamentos

- Cadastrar pagamento
- Consultar contas
- Alterar pagamento
- Excluir pagamento
- Estimar tempo a pagar

## Gerenciamento de Filiais

- Exibir contas
- Consultar estoque das filiais
- Realizar pedidos entre filiais

## Assinatura

- Planos e assinaturas

## Gerenciamento de Setores

- Cadastro
- Edição
- Exclusão

## Cálculo Inteligente

- Estimar a quantidade de produtos que podem ser produzidos com os alimentos disponíveis no estoque

## Preços Automáticos

- Definição de preço com base no custo do insumo e no lucro desejado

## Importação de Dados em Planilhas

- Texto
- HTML
- Excel

## App Cliente

- Sem acesso a recursos de estoque
- Não possui interligação com sistemas embarcados

## Gerenciamento de Clientes

- Cadastrar
- Excluir
- Editar

---

# Funcionalidades dos Usuários

A última etapa do processo de aprofundamento na temática do projeto foi a definição das funcionalidades dos usuários, resultado da compreensão das prioridades do público-alvo e do entendimento do ciclo de negócios.

Observou-se que, geralmente, o **chefe de cozinha** é responsável pela fiscalização do estoque. No entanto, essa atribuição pode variar dependendo da gestão do estabelecimento. Essa particularidade influenciou a decisão de **centralizar o controle de acesso dos usuários no usuário root**, representado pelo dono do restaurante.

Dessa forma, a página de gerenciamento de usuários foi projetada para permitir a **configuração das permissões individuais**, que podem ser ativadas ou desativadas conforme necessário. O usuário principal possui **acesso total a todas as funcionalidades do software**.

## Permissões e Acessos

Os usuários poderão ter acesso às seguintes áreas do sistema:

- Gerenciamento de estoque
- Gerenciamento de itens
- Gerenciamento de produtos
- Gerenciamento de fornecedores
- Gerenciamento de usuários
- Gerenciamento do caixa
- Acesso às estatísticas

---
