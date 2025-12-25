📊 Controle de Férias – Dashboard em Power BI

Projeto desenvolvido para apoiar pequenas e médias empresas no acompanhamento e planejamento de férias de colaboradores.

🧭 Visão Geral do Projeto

Este dashboard foi criado para empresas que não utilizam um sistema próprio para gerenciar férias, fornecendo uma visualização clara, organizada e acessível.

O objetivo é facilitar:
 - O planejamento das férias,
 - A análise de pendências,
 - A prevenção de vencimentos atrasados,
 - A tomada de decisão por parte do RH e gestores.

📄 Estrutura do Dashboard
🏠 Página 1 — Capa

Tela inicial com apresentação visual do projeto, nome da empresa (caso aplicável) e identificação do painel.
Tem como objetivo introduzir o usuário às funcionalidades.

📅 Página 2 — Visão Geral (Resumo dos KPIs de Férias)

Painel principal, consolidando:
 - Quantidade de colaboradores
 - Férias vencidas
 - Férias próximas do vencimento
 - Distribuição por departamento, filial, cargo ou situação
 - Gráficos dinâmicos para filtragem rápida
 - Indicadores de status da férias de modo geral
Esta página oferece uma visão ampla e estratégica do status das férias na empresa.

👤 Página 3 — Visão Individual do Colaborador

Tela dedicada ao acompanhamento detalhado de cada funcionário.

Inclui:
 - Dados cadastrais
 - Período aquisitivo e concessivo
 - Histórico de férias já tiradas
 - Situação atual
 - Um indicador gauge mostrando o tempo restante até o vencimento
 - Informações essenciais para decisões de curto prazo (RH + gestor direto)
É a página indicada para reuniões de alinhamento, tratativas individuais e análises caso a caso.

⚠ Página 4 — Alertas e Pendências

Tela voltada exclusivamente para gestão de riscos e pendências:
 - Colaboradores com férias vencidas
 - Colaboradores muito próximos do vencimento
 - Indicadores de atraso
 - Listagem para ação imediata
 - Possibilidade de filtrar por unidade, área ou cargo
Ajuda o RH a agir rapidamente e evitar problemas trabalhistas ou operacionais.

🛠 Ferramentas Utilizadas

 - Power BI Desktop
 - Power Query
 - Excel
 - DAX
 - Canvas (edição visual)

📁 Arquivos do Repositório
rh-controle-ferias-powerbi/
│
├─ 📂 base_de_dados/
│   └─ dados-exemplo.xlsx
│
├─ 📂 dashboard/
│   └─ controle-ferias.pbix
│
└─ README.md

🚀 Como Utilizar

1. Baixe a planilha de exemplo na pasta /base_de_dados.
2. Abra o arquivo .pbix no Power BI Desktop.
3. Acesse Página Inicial → Transformar Dados → Configurações da Fonte de Dados.
4. Selecione a conexão do Excel e clique em Alterar Fonte.
5. Escolha sua planilha real que baixou.
6. Confirme e clique em Aplicar para atualizar o dashboard.

