# Metodologia — Sistema de Gerenciamento para Restaurantes (TCC)

**Trabalho:** Trabalho de Conclusão de Curso (TCC)  
**Período:** No ano de 2024 
**Resumo:** Metodologia aplicada para projetar a solução conceitual de um sistema de gestão para restaurantes — controle de estoque, comandas, gestão de funcionários e painéis de estatísticas — voltado a restaurantes de médio a grande porte.

---
## Sumário
- [Visão geral da metodologia](#visão-geral-da-metodologia)
- [Fases do processo (resumo)](#fases-do-processo-resumo)
- [Análise de Similares](#1-análise-de-similares-página-7)
- [Público-alvo](#2-público-alvo-página-23)
- [Personas](#3-personas-página-24)
- [Escopo](#4-escopo-página-28)
- [Lista de requisitos e restrições](#5-lista-de-requisitos-e-restrições-página-29)
- [Documentação técnica](#documentação-técnica-apartir-da-página-32)
- [Funcionalidades](#6-lista-de-requisitos-e-funcionalidades-página-32)
- [Lista de eventos](#7-lista-de-eventos-página-52)
- [Diagrama de contexto](#8-diagrama-de-contexto-página-57)
- [DFD nível 0](#9-dfd-nível-0-página-58)
- [Mapa do site](#10-mapa-do-site-página-62)
- [Modelo do Banco de Dados](#11-modelo-do-banco-de-dados-página-70)
- [Guia de estilos](#12-guia-de-estilos-página-72)
- [Design](#13-design-página-75)
---

## Visão geral da metodologia
Adotamos uma abordagem **centrada no usuário** que combina:

- Pesquisa de mercado;
- Definição clara de requisitos (funcionais e não-funcionais);
- Modelagem técnica (diagramas, ERD, DFD);
- Design de interface e identidade visual;
- Validação com stakeholders e testes de usabilidade.

O objetivo foi garantir rastreabilidade entre necessidades, requisitos, modelagem e design visual, entregando um conjunto de Anexos prontos para apresentação de TCC.

---

## Fases do processo (resumo)
1. **Pesquisa** — Análise de similares, contexto do mercado e entrevistas.  
2. **Descoberta e definição** — Público-alvo, personas, escopo e requisitos.  
3. **Modelagem de eventos e dados** — Lista de eventos, diagrama de contexto, DFD nível 0 e ERD.  
4. **Design** — Logotipo, guia de estilos e telas/protótipos.  
5. **Documentação técnica** — Especificações detalhadas e descritivos de requisitos.  
6. **Validação** — Revisão por pares, testes de usabilidade básicos.  

---

### 1. Análise de Similares (página 7)
**Objetivo:** mapear concorrentes e soluções existentes.  
**Método:** Para entender melhor a demanda e pontos a serem melhorados, foram selecionados três sistemas de gerenciamento já integrados e com influência no mercado atual (Consumer, Nex, Vhsys).  
**Anexos:** `docs/analise_similares.md` — matriz comparativa, pontos fortes/fracos e oportunidades de diferenciação.
[Análise de Similares](analise_similares.md)

---

### 2. Público-alvo (página 23)
**Objetivo:** definir o segmento prioritário (restaurantes médio/grandes em crescimento).  
**Método:** análise documental e entrevistas/observação quando possível.  
**Anexo:** `docs/publico_alvo.md` — perfil comercial e operacional, principais necessidades e restrições.[Público Alvo](publico_alvo.md)

---

### 3. Personas (página 24)
**Objetivo:** representar usuários centrais (Gerente, Garçom, Estoquista, Cozinha).  
**Método:** criação de personas com objetivos, dores e jornadas.  
**Anexo:** `docs/personas.md` — persona, cenário, tarefas críticas.[Persona](persona.md)

---

### 4. Escopo (página 28)
**Objetivo:** Definir e apresentar o escopo do sistema, um software online voltado para a gestão de restaurantes, com foco principal no controle de estoque de insumos e gerenciamento de pedidos, visando melhorar a organização, acompanhamento e eficiência operacional do estabelecimento.  
**Método:** Utilização do modelo Golden Circle, de Simon Sinek, para estruturar o projeto em três níveis de definição: por quê (motivo da criação do sistema), como (processos e estratégias para implementar a solução) e o quê (o produto final entregue).  
**Anexo:** `docs/escopo.md` — lista de funcionalidades classificadas.[Escopo](escopo.md)

---

### 5. Lista de requisitos e restrições (página 29)
**Objetivo:** registrar requisitos funcionais e não-funcionais e restrições (legais, infra).  
**Método:** engenharia de requisitos com identificação e priorização.  
**Anexo:** `docs/requisitos.md` [Requisitos](requisitos.md)

---

### DOCUMENTAÇÃO TÉCNICA (Apartir da página 32)
**Objetivo:** compilar especificações técnicas, diagramas e descrições de módulos.  
**Anexos:** arquivos em `docs/` e `diagrams/` (descrições detalhadas).



### 6. Funcionalidades
**Objetivo:** detalhar cada requisito (pré-condição, fluxo principal, fluxos alternativos, pós-condição).  
**Anexo:** `docs/funcionalidades.md`. [Funcionalidades](funcionalidades.md)

---

### 7. Lista de eventos (página 52)
**Objetivo:** identificar eventos/funcionalidades do sisttema.  
**Método:** elicitação dos requisitos, sua descrição, estimulo, ação e resposta.  
**Anexo:** `docs/lista_eventos.md` [Lista de Eventos](lista_eventos.md)

---

### 8. Diagrama de contexto (página 57)
**Objetivo:** visão de alto nível dos atores e integrações externas.  
**Método:** diagrama em ferramenta de desenho e export para PNG/SVG.  
**Anexos:**.[Diagrama de Contexto](diagrama_contexto.md)

---

### 9. DFD nível 0 (página 58)
**Objetivo:** mapear processos principais e fluxos de dados.  
**Anexos:** .[DFD 0](dfd.md)

---

### 10. Mapa do site (página 62)
**Objetivo:** organizar arquitetura de informação e rotas/telas do sistema.  
**Anexo:** .[Mapa do Site](mapa_site.md)

---

### 11. Modelo do Banco de Dados (página 70)
**Objetivo:** modelar entidades, chaves e relacionamentos.  
**Anexos:** `docs/modelo_bd.md` descrevendo tabelas e campos. [ERD](modelo_bd.md)

---

### 12. Guia de estilos (página 72)
**Objetivo:** padronizar tipografia, cores, espaçamentos e componentes.  
**Anexo:** `design/guia.md` .[Guia](../design/guia.md)

---

### 13. Design (página 75)
**Objetivo:** criar wireframes e mockups navegáveis.  
**Método:** do wireframe ao protótipo de média/alta fidelidade.  
[Design](../design/design.md)
---
