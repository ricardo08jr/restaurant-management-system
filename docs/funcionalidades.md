## <a name="_hsyglg13a58d"></a>**Descritivo de requisitos e funcionalidades**
*WEB*

O sistema de gerenciamento de estoque de restaurantes, será responsável pela atualização dos insumos (retirada e saída), unindo-se a um sistema de pedidos e comandas, facilitando na comparação do que foi retirado do estoque e do que saiu (foi vendido), e possibilitando a consulta do valor total vendido no período de funcionamento dos restaurantes.

## **Página Index**
A página Index será composta pelas explicações sobre o sistema, incluindo dúvidas, funcionalidades. Através da index também será possível ser direcionado para o login e cadastro.

Header:

- Sobre;
- Recursos;
- Suporte;
- Login/Cadastro;

## **Página Cadastro/Login**
Cadastro

Para ter acesso ao sistema será necessário primeiro haver o cadastro da empresa, para que posteriormente seja feito o login:

- CNPJ;
- Nome do Estabelecimento;
- Razão Social;
- Telefone de Contato;
- E-mail de Contato;
- Senha;

- Foto; Login

  Caso a empresa já seja cadastrada será requerido o login.

  Haverá diferentes logins um para o dono e outro para o funcionário cada um com permissões e acessos diferentes:

  Escolha do cargo

- Empresa (dono):
  - CNPJ/Razão Social/Nome Fantasia;
  - Senha;
- Funcionário:
  - CNPJ/Razão Social/Nome Fantasia;
  - Nome usuário;
  - Senha;

## **Header**
Terá no header dois ícones um de notificação e outro da foto do perfil; Notificação:

- Situação do estoque (mínimo);
- Validade próxima;
- Aviso de compra;
- Aviso encomenda automática;
- Aviso de mudança na saída;

Perfil:

- Configuração;
- Sair;
- Adicionar outra conta;
- Contas;

## **Configuração**

- CNPJ;


- Nome do Estabelecimento;
- Razão Social;
- Telefone de Contato;
- E-mail de Contato;
- Senha;
- Foto;

Varia de acordo com o tipo de usuário.


## **Menu**
O menu será lateral obtendo as opções:

- Estoque;
- Itens;
- Produtos;
- Fornecedores;
- Estatísticas;
- Registros;
- Histórico;
- Usuários;

## **Página Controle Insumos (Estoque)**
As páginas após o login irão variar de acordo com as permissões então todas serão baseadas nas visualizações do dono.

A página de controle vai ser a que iniciará o sistema, ela será composta por uma tabela com:

- Nome do Insumo/Mercadoria;
- Estoque - a quantidade que está no estoque;
  - Nível de estoque - Baixo, Médio, Alto;

Haverá também três tipos de filtros: categoria, nível de estoque (situação), insumo/mercadoria, ordem alfabética (A a Z, Z a A), além da barra de pesquisa para Insumos/Mercadorias.


Para realizar a entrada, saída e perda de insumo/mercadorias terá um botão de ‘+’, ao clicar aparecerá um formulário onde o usuário escolherá qual três ações deseja fazer e preencherá os dados:

Entrada:

- Seleção do tipo do item;
  - Insumos;
  - Mercadoria;
- Seleção do insumo/mercadoria específico;
- Data;
- Validade;
- Lote;
- Seleção do fornecedor;
  - No caso de ser somente mercadoria ou ter somente um fornecedor já puxar automaticamente o fornecedor por meio da seleção do insumo/mercadoria;
- Quantidade e Unid. de medida;
- Custo (quanto pagou);
- Responsável;

o Será selecionado o usuário e ao final pedida a confirmação por meio da senha;

- Observação;
- Avaliação;
  - Observação da avaliação;

Saída:

- Seleção do tipo da saída;
  - Consumo próprio;
  - Venda;
- Seleção do tipo do item;
  - Insumos;
  - Mercadoria;
- Seleção do insumo/mercadoria específico;


- Data;
- Quantidade e Unid. de medida;
- Observação;

Perda:

Terá quatro opções da perda, por quebra, por vencimento, estragado ou furto:

- Vencimento:

o Seleção do tipo do item;

- Insumos;
- Mercadoria;
  - Seleção do insumo/mercadoria específico;
  - Data;
  - Quantidade e Unid. de medida;
  - Observação;
- Quebra:
  - Será puxado todas as saídas de insumo/mercadoria daquele dia, o usuário selecionará qual deseja registrar a perda, e adicionará os dados:
  - Quantidade que perdeu (dentro da quantidade que tinha saído);
    - Ex: saiu 3 tomates, 1 deu perda;
  - Observação;
  - Responsável;
- Furto:

o Seleção do tipo do item;

- Insumos;
- Mercadoria;
  - Seleção do insumo/mercadoria específico;
  - Data;
  - Quantidade e Unid. de medida;
  - Observação;
- Estragado:

o Seleção do tipo do item;

- Insumos;


- Mercadoria;
  - Seleção do insumo/mercadoria específico;
  - Data;
  - Quantidade e Unid. de medida;
  - Observação;

Haverá um botão para extrair o relatório das informações apresentadas;


## **Página Itens**
A página do item será responsável pelo cadastro, exclusão, edição do item e a consulta. O usuário deverá incluir os dados:

Consulta:

- Nome do Item;
- Insumo/Mercadoria;
- Código do Insumo/Mercadoria;
- Imagem Insumo/Mercadoria;

Adicionar:

Botão de ‘+’

- Nome do Insumo/Mercadoria;
- Seleção do tipo item:
  - Insumo;
  - Mercadoria;
- Foto do Insumo/Mercadoria;
- Código do Insumo/Mercadoria (automático);
- Incluir Categoria;
  - Gerenciar;
    - Criar;
    - Excluir;
    - Editar;
- Estoque Mínimo;
- Estoque Máximo;


- Encomenda automática;
  - Adicionar;








- Excluir;
- Editar;
- Fornecedor;
- Escolher período ou estoque mínimo;
- Quantidade média;
- Escolha da mensagem;
- Meio (WhatsApp, e-mail);



- Und. de medida;
  - Gerenciar;
    - Criar;
    - Excluir;
    - Editar;

Excluir:

Botão de excluir na linha da tabela. Edição:

Clicar na linha da tabela do item específico:

- Nome do Insumo/Mercadoria;
- Seleção do tipo item:
  - Insumo;
  - Mercadoria;
- Foto do Insumo/Mercadoria
- Incluir Categoria;
  - Gerenciar;
- Criar;
- Excluir;
- Editar;
  - Estoque Mínimo;


- Estoque Máximo;
- Und. de medida;

Haverá filtros de fornecedor, ordem alfabética (A a Z, Z a A) e categoria, além de uma barra de pesquisa.

## **Página Produtos**
A página dos produtos também fará o gerenciamento (adicionar, editar, excluir, consultar).

Consulta:

- Nome do Produto;
- Código do Produto;
- Preço Produto;
- Imagem Produto;
- Ficha Técnica Produto;
  - Pré-preparo;

Adicionar:

Botão de ‘+’

- Código do Produto (automático);
- Nome do Produto;
- Registro da ficha técnica (obrigatório);
  - Descrição (receita);
  - Descrição (pré-preparo);
  - Adicionar Itens;
- Nome;
- Quantidade;
  - Editar;
  - Excluir;
  - Preço do Produto;

Excluir:

Botão de excluir na linha da tabela


Edição:

Clicar na linha do produto específico

- Nome do produto;
- Preço do produto;

Haverá filtros de produto, ordem alfabética (A a Z, Z a A), preço, insumo (ingredientes), além de uma barra de pesquisa.

## **Página Fornecedores**
A página dos fornecedores terá as funcionalidades de adição, exclusão e edição, além da consulta.

Consulta:

- Nome Fornecedor;
- Insumo/Mercadoria fornecida;
- Avaliação geral do fornecedor (a média das avaliações da entrada);
- E-mail;
- Telefone;

Adicionar:

Botão de ‘+’

- Nome do Fornecedor (empresa);
- CNPJ/CPF do Fornecedor;
- Telefone do Fornecedor;
- E-mail do Fornecedor;
- Controle de Insumos do fornecedor;
  - Adicionar;
  - Remover;

Excluir:

Botão de excluir na linha da tabela Edição:

Clicar na linha da tabela do fornecedor específico


- Nome do Fornecedor (empresa);
- CNPJ/CPF do Fornecedor;
- Telefone do Fornecedor;
- E-mail do Fornecedor;
- Controle de Insumos do fornecedor;
  - Adicionar;
  - Remover;

Haverá filtros de fornecedor, ordem alfabética (A a Z, Z a A), insumo/mercadoria, avaliação geral, além de uma barra de pesquisa.

## **Página de Estatísticas**
Na página de estatísticas serão mostrados os gráficos de comparação de dados:

- Gráfico de demanda Insumo/Mercadoria;
- Gráfico de demanda Produto;
- Gráfico de Perdas;

Haverá os filtros que serão: período, insumo/mercadoria, item, categoria, ordem alfabética (A a Z, Z a A) que aparecerão respectivamente no Gráfico de demanda de Insumo e Perdas.

Já para perdas os filtros serão: período, produto, valor e ordem alfabética (A a Z, Z a A).

## **Página de Registros**
A página de Registros será composta pelos registros de entrada, saída e pedidos. Terão filtros específicos de cada ação:

Entrada:

- Período;
- Responsável;
- Insumo/Mercadoria;
- Item;
- Categoria;


- Ordem Alfabética;
- Fornecedor;
- Avaliação geral;

Saída:

- Tipo saída;
- Período;
- Responsável;
- Insumo/Mercadoria;
- Item;
- Categoria;
- Ordem Alfabética; Pedidos:
- Período;
- Insumo/Mercadoria;
- Item;
- Categoria;
- Ordem Alfabética;

Nas devidas páginas aparecerão os seguintes dados: Entrada:

- Data;
- Insumo/Mercadoria;
- Fornecedor;
- Avaliação;
- Observação da avaliação;
- Lote;
- Responsável;
- Quantidade;
- Custo;
- Validade;


Saída:

- Data;
- Insumo/Mercadoria;
- Responsável;
- Quantidade;
- Tipo saída; Pedidos Automáticos:
- Item (Insumo/Mercadoria);
- Quantidade;
- Fornecedor;
- Dia do pedido;
- Futuros pedidos;

o São os pedidos que estão próximos de ser feito pois o item está próximo de chegar no estoque mínimo;

Também haverá um botão de gerar relatório do que está sendo apresentado.
## **Usuários**
Nesta página o dono terá acesso a todos os usuários que estão cadastrados a este estabelecimento e as permissões de cada função;

Usuário:

- Consultar
  - Nome do Usuário;
  - Cargo do Usuário;
  - Imagem Usuário;
- Adicionar;
  - Nome usuário;
  - Senha;
  - Selecionar Cargo;
- Adicionar Cargo;
  - Excluir;
  - Editar;


Cargos:

- Adicionar;
  - Definir permissões;
- Estoque;
- Itens;
- Produtos;
- Fornecedores;
- Estatísticas;
- Histórico;
- Usuários;
- Comanda;
  - Editar;
  - Excluir;

## **Caixa**
O caixa vai ser a página que terá interligação com o app de pedidos do garçom, podendo visualizar os registros do dia (pedido e mesa), abrir o dia e fechar e o subtotal recebido.

Nesta página também será definida pelo dono as quantidades de mesa que ele obtém no estabelecimento.

Haverá um ícone com ‘caixa anteriores’, um histórico dos caixas.

*APP*

O aplicativo será especificamente para controle de mesas/comandas e seus pedidos,

para que seja contabilizado na página ‘Caixa’ do sistema na web (descrito acima).

O acesso dos usuários (garçons) será definido pelo dono na página ‘Usuários’ da web,

com a definição de cargos.

## **Menu**
No menu terá o perfil, com ícones das funcionalidades:

- Configuração;
- Sair;


## **Tela Login**
O usuário terá que realizar o login para ter acesso às funcionalidades do app, por meio:

- CNPJ/Razão Social/Nome Fantasia;
- Nome usuário;
- Senha;

## **Tela Home**
Será responsável pela visualização das mesas, mostrando:

- Número da mesa;
- Situação da mesa (ocupada, desocupada e fechou): nas cores vermelho, verde e amarelo respectivamente;
## **Tela Mesa**
Quando clicar em cima de uma mesa o usuário será direcionado a tela das mesas onde terá acesso:

- Lista de pedidos;
  - Nome do produto;
  - Quantidade e valor;
  - Remover pedido (‘x’);
  - Responsável (funcionário);
- Subtotal;
- Adicionar pedido (Botão ‘+’);
  - Lista de produtos disponíveis;
    - Nome do produto;
    - Código produto;
    - Imagem do produto;
  - Botão de quantidade;
  - Remover produto deste pedido;
  - Botão ‘Lançar Pedido’;
- Fechar conta;

