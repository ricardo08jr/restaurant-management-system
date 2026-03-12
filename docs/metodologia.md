# Metodologia — Sistema de Gerenciamento para Restaurantes (TCC)

**Trabalho:** Trabalho de Conclusão de Curso (TCC)  
**Período:** No ano de 2024 
**Resumo:** Metodologia aplicada para projetar a solução conceitual de um sistema de gestão para restaurantes — controle de estoque, comandas, gestão de funcionários e painéis de estatísticas — voltado a restaurantes de médio a grande porte.

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
**Anexo:** `docs/publico_alvo.md` — perfil comercial e operacional, principais necessidades e restrições.

---

### 3. Personas (página 24)
**Objetivo:** representar usuários centrais (Gerente, Garçom, Estoquista, Cozinha).  
**Método:** criação de personas com objetivos, dores e jornadas.  
**Anexo:** `docs/personas.md` — persona, cenário, tarefas críticas.

---

### 4. Escopo (página 28)
**Objetivo:** delimitar o MVP e funcionalidades prioritárias.  
**Método:** workshop de priorização (MoSCoW).  
**Anexo:** `docs/escopo.md` — lista de funcionalidades classificadas.

---

### 5. Lista de requisitos e restrições (página 29)
**Objetivo:** registrar requisitos funcionais e não-funcionais e restrições (legais, infra).  
**Método:** engenharia de requisitos com identificação e priorização.  
**Anexo:** `docs/requisitos.md` 

---

### DOCUMENTAÇÃO TÉCNICA (Apartir da página 32)
**Objetivo:** compilar especificações técnicas, diagramas e descrições de módulos.  
**Anexos:** arquivos em `docs/` e `diagrams/` (descrições detalhadas).

---

### 8. Lista de requisitos e funcionalidades (página 32)
**Observação:** versão estruturada e rastreável de requisitos (veja `docs/requisitos.md`).  
**Formato recomendado:** tabela com vinculação para diagramas e casos de uso.

---

### 9. Descritivo de requisitos e funcionalidades (página 38)
**Objetivo:** detalhar cada requisito (pré-condição, fluxo principal, fluxos alternativos, pós-condição).  
**Anexo:** `docs/descritivo_requisitos.md`.

---

### 10. Lista de eventos (página 52)
**Objetivo:** identificar eventos/funcionalidades do sisttema.  
**Método:** elicitação dos requisitos, sua descrição, estimulo, ação e resposta.  
**Anexo:** `docs/lista_eventos.md` 

---

### 11. Diagrama de contexto (página 57)
**Objetivo:** visão de alto nível dos atores e integrações externas.  
**Método:** diagrama em ferramenta de desenho e export para PNG/SVG.  
**Anexos:**  `diagrams/diagrama_contexto.png`.

---

### 12. DFD nível 0 (página 58)
**Objetivo:** mapear processos principais e fluxos de dados.  
**Anexos:** `diagrams/dfd_nivel0.png`.

---

### 13. Mapa do site (página 62)
**Objetivo:** organizar arquitetura de informação e rotas/telas do sistema.  
**Anexo:** `diagrams/sitemap.png` .

---

### 14. Modelo do Banco de Dados (página 70)
**Objetivo:** modelar entidades, chaves e relacionamentos.  
**Anexos:** `docs/modelo_bd.md` descrevendo tabelas e campos.

---

### 16. Guia de estilos (página 72)
**Objetivo:** padronizar tipografia, cores, espaçamentos e componentes.  
**Anexo:** `design/guia_de_estilos.pdf` ou `design/guide.md` .

---

### 17. Design (página 75)
**Objetivo:** criar wireframes e mockups navegáveis.  
**Método:** do wireframe ao protótipo de média/alta fidelidade.  

---

## Validação e métricas
- **Avaliação heurística:** checklist de usabilidade aplicado por avaliadores.  
- **Testes de usabilidade:** idealmente 5 usuários representativos, com tarefas cronometradas.  
- **Métricas sugeridas:** tempo médio por tarefa, taxa de erro, SUS (System Usability Scale) e feedback qualitativo.  
- **Relatório:** `relatorios/analise_ux.pdf`.



## Onde colocar no repositório (exemplo prático)
