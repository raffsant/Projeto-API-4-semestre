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

# Backlog do Projeto - User Stories

## Sprint 1 - Coleta e Planejamento
| ID | Prioridade | User Story | Estimativa (h) |
|----|-----------|------------|----------------|
| 1  | 🔥 Alta   | Como analista de dados, quero baixar e integrar dados de atracação e carga **para consolidar as informações portuárias em uma única base**. | 5 |
| 2  | 🔥 Alta   | Como analista de dados, quero filtrar registros relevantes para a análise **a fim de trabalhar apenas com informações úteis**. | 3 |
| 3  | 🔥 Alta   | Como analista de dados, quero aplicar filtragem da carga de soja **para realizar análises específicas desse produto**. | 3 |
| 4  | 🔥 Alta   | Como analista de dados, quero limpar, normalizar e estruturar os dados **para garantir consistência e qualidade**. | 8 |
| 5  | ⭐ Média  | Como analista de dados, quero documentar o código em Python **para facilitar manutenções e reaproveitamento futuro**. | 5 |
| 6  | ⭐ Média  | Como analista de dados, quero publicar os avanços no GitHub **para versionar o trabalho e compartilhar com a equipe**. | 3 |
| 7  | 🔥 Alta   | Como analista de dados, quero gerar relatórios **para comunicar os resultados da análise de forma clara**. | 8 |

## Sprint 2 - Eficiência e tempos de operação
| ID | Prioridade | User Story | Estimativa (h) |
|----|-----------|------------|----------------|
| 8  | 🔥 Alta   | Como analista de dados, quero avaliar produtividade dos terminais **para identificar os pontos fortes e fracos**. | 10 |
| 9  | 🔥 Alta   | Como analista de dados, quero criar ranking dos top 10 terminais **para facilitar decisões estratégicas**. | 8 |
| 10 | 🔥 Alta   | Como analista de dados, quero identificar tempo médio de operação por terminal **para medir eficiência**. | 8 |
| 11 | 🔥 Alta   | Como analista de dados, quero visualizar portos mais ágeis e os portos com maior espera **para priorizar melhorias**. | 8 |
| 12 | 🔥 Alta   | Como analista de dados, quero analisar movimentação mensal por terminal **para acompanhar padrões e sazonalidade**. | 6 |
| 13 | 🔥 Alta   | Como analista de dados, quero avaliar volume de transporte por porto **para entender a carga movimentada**. | 6 |
| 14 | 🔥 Alta   | Como analista de dados, quero identificar os principais portos que movimentam soja **para análise específica do produto**. | 6 |
| 15 | 🔥 Alta   | Como analista de dados, quero gerar relatório **para comunicar resultados da análise de eficiência e produtividade**. | 8 |

## Sprint 3 - Movimentação e Análise de Carga
| ID | Prioridade | User Story | Estimativa (h) |
|----|-----------|------------|----------------|
| 16 | 🔥 Alta   | Como analista de dados, quero calcular indicador de eficiência (infraestrutura x carga) **para medir a performance portuária**. | 10 |
| 17 | 🔥 Alta   | Como analista de dados, quero filtrar por terminal e período **para análises detalhadas**. | 6 |
| 18 | 🔥 Alta   | Como analista de dados, quero implementar buscas e filtros personalizados **para facilitar exploração dos dados**. | 8 |
| 19 | 🔥 Alta   | Como analista de dados, quero filtrar por terminal e tempo **para análises comparativas de performance**. | 6 |
| 20 | 🔥 Alta   | Como analista de dados, quero visualizar ranking **para identificar rapidamente os melhores e piores desempenhos**. | 6 |
| 21 | 🔥 Alta   | Como analista de dados, quero desenvolver visualizações de eficiência portuária e operação **para facilitar entendimento do desempenho**. | 10 |
| 22 | 🔥 Alta   | Como analista de dados, quero criar interface intuitiva **para que usuários explorem os dados de forma fácil**. | 12 |
| 23 | 🔥 Alta   | Como analista de dados, quero gerar relatório **para consolidar insights da movimentação e eficiência**. | 8 |







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




