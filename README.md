# **NextMove**
<p align="center">
<img src=https://github.com/raffsant/Projeto-API-4-semestre/blob/main/nextmove2.png?raw=true/>

<br>
<p align="center">
  
# Aprendizado por Projeto Integrador

O Projeto Integrador (API) oferece uma experiência prática na resolução de problemas logísticos reais, aplicando a metodologia ágil SCRUM em 3 Sprints. O foco é o desenvolvimento de uma plataforma de Business Intelligence (BI) para monitorar e analisar a eficiência portuária nos portos brasileiros, utilizando dados estatísticos da ANTAQ e informações sobre tempos de processamento e operações.

# Índice
* [Projeto](#projeto-template)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Sprints](#sprints)
* [Backlog do Produto](#backlog-do-produto)
* [Registro das Sprints](#registro-das-sprints)

# Equipe 👨‍💻
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Rafael Santana de Andrade Osses         |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rafaelsantanaandrade/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/raffsant)              |
| Scrum Master  | Alexssander Abreu de Campos |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alexssander-abreu-de-campos-8a6617304/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/alexssander321)     |
| Team Member   | Diego Silva              |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/diego-silva-ab10021b0) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Diegosilva2002)    
|  Team Member  | Rafaela da Silva Melo                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rafaela-melo-14b349357/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/rafaeladasilvamelo)   


# Objetivo do Projeto 🎯
Criar uma plataforma de Business Intelligence (BI) voltada ao acompanhamento da eficiência portuária nos portos brasileiros, utilizando como base os dados estatísticos da ANTAQ e os tempos de processamento das operações.

O sistema deverá possibilitar:

Comparar o desempenho dos terminais portuários;

Mapear os principais fatores que geram paradas ou atrasos;

Mensurar e analisar os tempos médios de execução das atividades;

Disponibilizar painéis visuais interativos que ofereçam insights estratégicos para a tomada de decisão.

## Tecnologias Utilizadas 🗃️

- **Google Colab**: Para gerenciamento e consulta de bancos de dados.
- **GitHub**: Para automação, análise de dados e integração com APIs.
- **Power BI**: Para criação de dashboards e visualização de dados.
- **Python e DAX**: Para análise e organização de dados.
- **GitHub**: Para versionamento e colaboração no projeto.
- **Metodologia Ágil (SCRUM)**: Para gerenciamento do projeto.
- **Ferramentas de Colaboração**: Slack e Jira.



# 📦 Backlog do Produto 

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 1 | 🔥 Alta | **Como analista de dados**, quero acessar, limpar e padronizar os dados da ANTAQ **para iniciar análise consistente da eficiência portuária**. | 6 | 1 |
| 2 | 🔥 Alta | **Como analista de dados**, quero calcular métricas de operação portuária **para avaliar eficiência e identificar gargalos**. | 6 | 1 |
| 3 | 🔥 Alta | **Como analista de dados**, quero criar dashboards no Power BI com filtros e rankings de portos **para apoiar decisões estratégicas**. | 10 | 1 |
| 4 | ⭐ Média | **Como analista**, quero testar dashboards em diferentes dispositivos e ajustar layouts **para garantir responsividade**. | 6 | 1 |
| 5 | ⭐ Média | **Como gestor**, quero acompanhar tempos médios e desempenho mensal dos portos **para planejar recursos e otimizar processos**. | 5 | 1 |
| 6 | 🔥 Alta | **Como responsável por relatórios**, quero detalhar metodologia, glossário e análises **para documentar processos e decisões**. | 14 | 2 |
| 7 | 🔥 Alta | **Como responsável por versionamento**, quero criar repositório, organizar branches e atualizar scripts **para controlar versões e pendências**. | 12 | 2 |
| 8 | 🔥 Alta | **Como gestor**, quero coletar feedback e revisar entregas **para garantir qualidade antes da apresentação**. | 8 | 2 |
| 9 | 🔥 Alta | **Como equipe de apresentações**, quero criar templates, slides iniciais, storyboard e slides finais **para preparar a apresentação oficial**. | 18 | 3 |
| 10 | 🔥 Alta | **Como equipe de apresentações**, quero ensaiar apresentação e preparar roteiro **para garantir impacto e organização**. | 12 | 3 |
| 11 | 🔥 Alta | **Como analista de dados**, quero calcular métricas extras, acompanhar evolução de indicadores e registrar insights **para apoiar decisões futuras**. | 12 | 3 |





## Sprint 1
- [ ] Baixar e tratar dados da ANTAQ (limpeza, normalização e remoção de duplicados/nulos).  
- [ ] Calcular tempos médios de operação portuária.  
- [ ] Criar dashboard inicial no Power BI com visão geral de portos, cargas e operações.  
- [ ] Incluir filtros (período e tipo de carga) e ranking de eficiência dos portos.  
- [ ] Validar visualizações com stakeholders e comparar desempenho mensal dos portos.  


## Sprint 2
- [ ] Destacar indicadores de eficiência como base para gestão estratégica.  
- [ ] Mapear tendências de movimentação de cargas ao longo do ano para apoiar planejamento.  
- [ ] Identificar operações com maiores tempos de espera para reduzir atrasos e custos.  
- [ ] Manter dashboards gerais de portos, cargas e operações para monitorar performance.  
- [ ] Documentar metodologia aplicada em processos e análises.  
- [ ] Registrar análises exploratórias em relatório para manter histórico de estudos.  
- [ ] Anexar códigos e capturas de dashboards para documentação completa.  
- [ ] Estruturar repositório no GitHub para versionar scripts e bases de dados.  
- [ ] Atualizar repositório com códigos revisados e comentados.  
- [ ] Criar issues no Jira para registrar demandas e feedbacks de clientes.  
- [ ] Revisar repositório e organizar releases finais para entrega oficial.  


## Sprint 3
- [ ] Calcular métricas-chave e acompanhar evolução de indicadores para identificar tendências.  
- [ ] Criar painéis comparativos entre portos e operações para apoiar decisões gerenciais.  
- [ ] Revisar dashboards finais e coletar feedback para ajustes antes da entrega.  
- [ ] Registrar insights estratégicos obtidos nas análises para uso futuro.  
- [ ] Finalizar relatórios técnicos com gráficos e dashboards para entrega à banca.  
- [ ] Preparar slides de apresentação inicial.  
- [ ] Montar apresentações finais para a feira de soluções.   
- [ ] Acompanhamento para garantir que a equipe esteja preparada.  
- [ ] Organizar o Jira e documentar histórico para controle da equipe.  

# Registro das Sprints

| Sprint | Previsão | Status | Histórico |
|--------|----------|--------|-----------|
| 01     | 03/10/2025 | Em andamento | [MVP](https://) |
| 02     | 24/10/2025 | A fazer | [MVP](https://) |
| 03     | 14/11/2025 | A fazer | [MVP](https://) |
| Feira de Soluções | 04/12/202 | A fazer | [MVP](https://) |




