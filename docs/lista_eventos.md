## **1. Gerenciamento do Restaurante** {#gerenciamento-do-restaurante}

### Descrição  
**Dentro do sistema o dono poderá gerenciar o seu restaurante com as seguintes funcionalidades:**

- Verificar cadastro do estabelecimento

- Cadastro do estabelecimento

- Verificação de autenticação via e-mail ou SMS

- Localizar estabelecimento

- Logar dentro do sistema

- Editar informações do estabelecimento

- Excluir estabelecimento

**Dados**

- Dados_Estabelecimento

- Dados_Gerenciamento

**Ação**

- Gerenciar Restaurante

**Resposta / Estados**

- Restaurante_Gerenciado

- Restaurante_Não_Gerenciado

## **2. Gerenciamento do Usuário** {#gerenciamento-do-usuário}

### Descrição  
**Dentro do sistema o estabelecimento poderá criar e gerenciar um cadastro para cada funcionário:**

- Verificar usuário existente

- Cadastro do usuário

- Consultar perfil do usuário

- Editar informações do usuário

- Excluir usuário

**Dados**

- Dados_Usuário

- Dados_Gerenciamento

**Ação**

- Gerenciar Usuário

**Resposta / Estados**

- Usuário_Gerenciado

- Usuário_Não_Gerenciado

## **3. Gerenciamento de Estoque** {#gerenciamento-de-estoque}

### Descrição  
**O estabelecimento poderá gerenciar todos os insumos e mercadorias no estoque com funcionalidades como:**

- Visualizar estoque (com filtros e nível)

- Registrar entrada

  - Seleção do tipo do item

  - Seleção do insumo/mercadoria específico

  - Seleção do fornecedor

- Registrar saída

  - Seleção do tipo da saída

  - Seleção do tipo do item

  - Seleção do insumo/mercadoria específico

  - Localizar entrada antiga

- Registrar perda

  - Seleção do tipo de perda

  - Localizar saída

  - Localizar itens do lote

**Dados**

- Dados_Gerenciamento

**Ação**

- Gerenciar Estoque

**Resposta / Estados**

- Estoque_Gerenciado

- Estoque_Não_Gerenciado

## **4. Gerenciamento de Item** {#gerenciamento-de-item}

### Descrição  
**Página responsável pelo cadastro, exclusão e edição do item (que pode ser insumo ou mercadoria):**

- Verificar item existente

- Criar item

- Incluir unidade de medida

- Incluir categoria

- Incluir fornecedor

- Localizar item

- Excluir item

- Editar item

- Encomenda automática / Controle de pedido automático

- Adicionar / Excluir / Editar (itens relacionados)

**Dados**

- Dados_Item

- Dados_Gerenciamento

- Dados_Unidade_Medida

- Dados_Categoria

**Ação**

- Gerenciar Item

**Resposta / Estados**

- Item_Gerenciado

- Item_Não_Gerenciado

## **5. Gerenciamento de Categoria** {#gerenciamento-de-categoria}

### Descrição  
**O estabelecimento poderá gerenciar categorias com as operações:**

- Criar categoria

- Localizar categoria

- Editar categoria

- Excluir categoria

**Dados**

- Dados_Categoria

- Dados_Gerenciamento

**Ação**

- Gerenciar Categoria

**Resposta / Estados**

- Categoria_Gerenciada

- Categoria_Não_Gerenciada

## **6. Gerenciamento de Unidade de Medida** {#gerenciamento-de-unidade-de-medida}

### Descrição  
**O estabelecimento poderá gerenciar unidades de medida:**

- Criar unidade de medida

- Localizar unidade de medida

- Editar unidade de medida

- Excluir unidade de medida

**Dados**

- Dados_Unidade_Medida

- Dados_Gerenciamento

**Ação**

- Gerenciar Unidade de Medida

**Resposta / Estados**

- Unidade_Medida_Gerenciada

- Unidade_Medida_Não_Gerenciada

## **7. Gerenciamento de Produtos** {#gerenciamento-de-produtos}

### Descrição  
**Gerenciar os produtos do cardápio:**

- Adicionar produto

- Registro da ficha técnica

- Localizar item / produto

- Adicionar itens ao produto

- Editar produto

- Excluir produto

**Dados**

- Dados_Item

- Dados_Produto

- Dados_Gerenciamento

**Ação**

- Gerenciar Produto

**Resposta / Estados**

- Produto_Gerenciado

- Produto_Não_Gerenciado

## **8. Gerenciamento de Fornecedores** {#gerenciamento-de-fornecedores}

### Descrição  
**Gerenciar fornecedores do estabelecimento:**

- Verificar fornecedor existente

- Adicionar fornecedor

- Incluir item (fornecedor fornece)

- Localizar fornecedor

- Editar fornecedor

- Excluir fornecedor

**Dados**

- Dados_Item

- Dados_Gerenciamento

- Dados_Fornecedor

**Ação**

- Gerenciar Fornecedor

**Resposta / Estados**

- Fornecedor_Gerenciado

- Fornecedor_Não_Gerenciado

## **9. Gerenciamento de Login** {#gerenciamento-de-login}

### Descrição  
**Controle de acesso dos funcionários ao sistema:**

- Verificar login

- Entrar (autenticar)

- Mudar senha

- Sair da conta

**Dados**

- Dados_Login

- Dados_Gerenciamento

- Dados_Senha

**Ação**

- Gerenciar Login

**Resposta / Estados**

- Login_Gerenciado

- Login_Não_Gerenciado

## **10. Gerenciamento de Cargo** {#gerenciamento-de-cargo}

### Descrição  
**Gerenciamento de cargos e permissões:**

- Registrar cargo

- Incluir permissões ao cargo

- Localizar cargo

- Editar cargo

- Excluir cargo

**Dados**

- Dados_Cargo

- Dados_Gerenciamento

**Ação**

- Gerenciar Cargo

**Resposta / Estados**

- Cargo_Gerenciado

- Cargo_Não_Gerenciado

## **11. Controle de Estatísticas** {#controle-de-estatísticas}

### Descrição  
**Visualização de gráficos do estabelecimento com base em: demanda, lucro das vendas e perdas.**

- Selecionar tema

- Aplicar filtros

- Gerar gráfico

**Dados**

- Dados_Tema

- Dados_Filtro

- Dados_Estatística

**Ação**

- Controlar Estatística

**Resposta / Estados**

- Estatística_Controlada

- Estatística_Não_Controlada

## **12. Geração de Relatório** {#geração-de-relatório}

### Descrição  
**Geração de relatórios do estabelecimento (fornecedores, entradas e saídas, estoque, perdas):**

- Selecionar tema

- Gerar relatório

**Dados**

- Dados_Tema

- Dados_Relatório

- Dados_Gerenciamento

**Ação**

- Gerar Relatório

**Resposta / Estados**

- Relatório_Gerenciado

- Relatório_Não_Gerenciado

## **13. Envio de Notificações** {#envio-de-notificações}

**Descrição  
** Notificações baseadas em eventos do sistema, por exemplo:

- Situação do estoque

- Validade próxima

- Aviso de compra

- Aviso de encomenda automática

- Aviso de mudança na saída

**Ação**

- Enviar Notificação

**Resposta / Estados**

- Notificação_Enviada

- Notificação_Não_Enviada

## **14. Gerenciamento do Caixa** {#gerenciamento-do-caixa}

### Descrição  
**Integração do caixa com o app de pedidos do garçom; funcionalidades:**

- Abrir o caixa

- Visualizar registros do dia (pedidos e mesas)

- Fechar o caixa

- Subtotal recebido

**Dados**

- Dados_Mesa

- Dados_Pedido

- Dados_Gerenciamento

**Ação**

- Gerenciar Caixa

**Resposta / Estados**

- Caixa_Gerenciado

- Caixa_Não_Gerenciado

## **15. Controle de Pedidos** {#controle-de-pedidos}

### Descrição  
**Interação entre aplicativo do garçom e o caixa; funções disponíveis no app do garçom:**

- Localizar mesa

- Acessar a mesa

- Adicionar pedido

- Incluir produto e/ou mercadoria

- Cancelar pedido

- Lançar pedido

- Localizar pedido

- Excluir produto/mercadoria do pedido

- Fechar conta

- Gerar valor do custo

- Gerar nova mesa

**Dados**

- Dados_Controle

- Dados_Mesa

- Dados_Pedido

**Ação**

- Controlar Pedidos

**Resposta / Estados**

- Pedido_Controlado

- Pedido_Não_Controlado
