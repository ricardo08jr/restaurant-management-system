# Lista de Requisitos e Funcionalidades

## WEB

### Gerenciamento de Restaurante
- Cadastro do estabelecimento
- CNPJ
- Nome do Estabelecimento
- Razão Social
- Telefone de Contato
- E-mail de Contato
- Senha
- Excluir estabelecimento
- Editar informações do estabelecimento

---

### Gerenciamento de Usuário
- Cadastrar usuário
- Nome do Usuário
- Senha do Usuário
- Incluir cargo
- Consultar usuário
- Excluir usuário
- Editar usuário
- Remover cargo

---

### Gerenciamento de Cargo
- Criar cargo
- Nome do Cargo
- Código do Cargo
- Consultar cargo
- Excluir cargo
- Editar cargo
- Permissões pré-definidas
- Gerenciar permissões do cargo

---

### Gerenciamento de Fornecedor
- Cadastrar fornecedor
- Nome do Fornecedor (empresa)
- CNPJ/CPF do Fornecedor
- Telefone do Fornecedor
- E-mail do Fornecedor
- Consultar fornecedor
- Excluir fornecedor
- Editar fornecedor
- Controle de Insumo/Mercadoria
- Adicionar Insumo/Mercadoria
- Remover Insumo/Mercadoria
- Avaliar fornecedor

---

### Gerenciamento de Insumo
- Cadastrar Insumo
- Nome do Insumo
- Código do Insumo
- Incluir Setor
- Incluir Categoria
- Estoque Mínimo
- Estoque Máximo
- Unidade de medida
- Cadastrar Pedido automático

#### Operações
- Consultar Insumo
- Editar Insumo
- Excluir Insumo

#### Entrada de Insumo
- Registrar entrada do Insumo
- CNPJ/CPF do Fornecedor
- Quantidade de Insumo
- Código do Lote
- Nome do Insumo
- Validade do Lote
- Data da Entrada
- Preço do Insumo
- Nome do Responsável

#### Retirada de Insumo
- Registrar retirada
- Quantidade
- Nome do Insumo
- Data de retirada
- Responsável pela retirada

#### Colocar Insumo em Uso
- Quantidade
- Nome do Insumo
- Data
- Responsável

#### Registrar Perda de Insumo
- Nome do Insumo
- Data da Perda
- Causa da Perda
- Quantidade
- Descrição da Perda

#### Consumo Próprio
- Quantidade
- Nome do Insumo
- Data
- Responsável
- Descrição

---

### Gerenciamento de Mercadoria
- Cadastrar Mercadoria
- Nome da Mercadoria
- Código da Mercadoria
- Incluir Setor
- Incluir Categoria
- Estoque Mínimo
- Estoque Máximo
- Editar Mercadoria
- Excluir Mercadoria

#### Entrada de Mercadoria
- CNPJ/CPF do Fornecedor
- Quantidade
- Código do Lote
- Nome da Mercadoria
- Validade do Lote
- Data da Entrada
- Preço
- Responsável

#### Venda / Retirada
- Quantidade
- Nome da Mercadoria
- Data
- Responsável

#### Registrar Perda
- Nome da Mercadoria
- Data
- Causa da Perda
- Quantidade
- Descrição

#### Consumo Próprio
- Quantidade
- Nome da Mercadoria
- Data
- Responsável
- Descrição

---

### Gerenciamento de Produto
- Cadastro de Produto
- Código do Produto
- Nome do Produto
- Registro da Ficha Técnica (obrigatório)
- Preço do Produto

#### Operações
- Consultar Produto
- Editar Produto
- Excluir Produto

#### Ficha Técnica
- Adicionar insumos
- Editar insumos
- Excluir insumos

#### Venda
- Registrar venda do produto

---

### Gerenciamento de Registros
- Consultar registros
- Emissão de relatórios

#### Relatórios
- Relatório de fornecedores
- Relatório de entrada e saída (mercadoria ou insumo)
- Relatório de estoque
- Relatório de perdas

---

### Emissão de Gráficos (Estatísticas)
- Gráfico de demanda
- Venda de produtos
- Insumos
- Mercadorias
- Gráfico de lucro das vendas
- Gráfico de perdas

---

### Gerenciamento de Categoria
- Cadastrar categoria
- Código da categoria
- Nome da categoria
- Excluir categoria
- Editar categoria

---

### Notificação de Estoque Mínimo
- Insumo
- Encomendar insumo
- Mercadoria
- Encomenda automática

---

### Notificação de Validade
- Insumo
- Mercadoria

---

### Controle de Caixa
- Consulta dos valores totais no período
- Consulta dos pedidos do dia e anteriores
- Abrir o dia
- Fechar o dia

---

# APP

### Gerenciamento de Pedido
- Adicionar pedido
- Consultar pedidos
- Consultar produtos
- Fechar conta