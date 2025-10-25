# Governo---MEC
Ministério da Educação (MEC) | Power BI | SQL | Data Analytics
📘 Descrição

O Hub Analítico da Educação em Saúde integra informações estratégicas sobre os programas de formação em saúde vinculados ao Ministério da Educação (MEC).
Desenvolvido no Power BI, o projeto centraliza indicadores de supervisão, tutoria, preceptoria e residência, facilitando o acesso e a análise de dados para gestores públicos.

Foram criados mais de 15 relatórios analíticos, dos quais cinco estão disponíveis publicamente:
👉 Acessar Hub Público (Power BI Service)

🩺 Principais Painéis Públicos
Residência Médica: Apresenta dados sobre vagas autorizadas e ocupadas, especialidades, fontes de financiamento e distribuição geográfica dos programas.
Supervisão Acadêmica: Monitora instituições supervisoras, tutores e supervisores de programas de residência, consolidando dados por região, UF e município.
Outros painéis disponíveis: 
Residência Multiprofissional
PRODEPS – Programa de Desenvolvimento da Preceptoria em Saúde
CAMEM – Comissão de Acompanhamento das Escolas Médicas

(os demais relatórios estão disponíveis apenas em ambiente interno do MEC)

⚙️ Arquitetura e Tecnologias
Camada	Tecnologia / Ferramenta	Descrição
Banco de Dados (SGBD)	PostgreSQL	Consolidação e integração de dados oriundos de diferentes programas federais.
Consultas SQL	Views, joins e funções agregadoras	Criação de datasets analíticos otimizados e reutilizáveis.
ETL / Power Query	M Language	Padronização, limpeza e normalização de dados.
Modelagem de Dados	Star Schema (Fato e Dimensão)	Estrutura analítica otimizada para desempenho no Power BI.
Camada Semântica	DAX (Data Analysis Expressions)	Cálculo de indicadores e funções de tempo.
Publicação	Power BI Service	Hospedagem, controle de acesso e atualização automatizada.

🎯 Objetivo
Criar um ecossistema analítico unificado que permita a visualização integrada dos dados da Educação em Saúde, fortalecendo a governança da informação, a transparência e a tomada de decisão baseada em evidências.

🧩 Destaques Técnicos
Mais de 15 relatórios Power BI integrados em um hub de navegação único.
Uso de Row-Level Security (RLS) para controle de acesso por programa.
Aplicação da identidade visual do Governo Federal para padronização institucional.
Scripts SQL otimizados e modelagem escalável para replicação em novos painéis.
Publicação contínua e versionamento automatizado no Power BI Service.

🏛️ Créditos
Desenvolvido pela Secretaria de Educação Superior (SESu/MEC), por meio da Diretoria de Desenvolvimento da Educação em Saúde (DDES).
Autor: Prof. Salvador Melo
Analista de Dados | Especialista em Power BI e Governança de Dados
