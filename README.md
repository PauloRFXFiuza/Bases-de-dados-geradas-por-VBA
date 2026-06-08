🇧🇷 Relatório de Análise dos Arquivos (Português)
1. Base de dados de nomes.csv e Base de dados de nomes.xlsm
Estes dois arquivos contêm essencialmente o mesmo conjunto de dados estruturados principais, focado em registros cadastrais e demográficos de indivíduos. No formato Excel (.xlsm), há também análises adicionais em abas separadas.

Planilha1 / Corpo do CSV: É uma base cadastral contendo informações demográficas detalhadas de cidadãos. Cada registro possui campos como:

Identificação e Contato: ID, Nome Completo, Endereço, CEP, Município e UF.

Documentação: RG e CPF.

Filiação: Nome da Mãe e Nome do Pai.

Dados Pessoais: Data de Nascimento, Idade, Etnia, Profissão, Estado Civil e informações sobre filhos (Se possui e a quantidade).

Planilha2 (Apenas no .xlsm): Contém uma Tabela Dinâmica focada em resumir as profissões com base no Estado Civil (ex: contagem de profissionais casados).

Planilha3 (Apenas no .xlsm): Uma área de rascunho ou cálculos estatísticos adicionais contendo menções a "Desafio de Auditoria: 20 Perguntas Objetivas", cálculos de Moda (ex: Moda do município), correspondências e fórmulas de anos.

2. Base de dados de empresa logística LogFiuza.xlsm
Este arquivo é um modelo focado no gerenciamento de operações logísticas de uma empresa de transportes chamada LogFiuza. Ele está dividido em duas abas principais com dados populados:

Aba Lista_CDs: Um cadastro dos Centros de Distribuição (CDs) da empresa. Contém colunas para o ID do CD, Nome do CD, Tipo de Operação (ex: Last Mile Hub, Cross-Docking sem ASM, Híbrido - Fulfillment) e a Cidade/UF onde está localizado.

Aba Transferencias: Histórico detalhado de movimentações e tráfego de mercadorias entre os CDs. Registra informações cruciais como:

Data e hora de saída da origem e chegada ao destino.

Dados completos do CD de Origem e do CD de Destino (Nome, Tipo, Cidade e UF).

Métricas operacionais: Tempo de trânsito, Quantidade de caminhões utilizados e Quantidade de pacotes transportados.

Aba Sheet1: Uma aba vazia sem dados estruturados.

Route 2: 🇬🇧 File Analysis Report (English)
1. Base de dados de nomes.csv and Base de dados de nomes.xlsm
These two files share the same core structural dataset, which centers on demographic and registration records of individuals. The Excel format (.xlsm) also incorporates specific analytical and scratch sheets.

Planilha1 / CSV Body: A master registration database containing detailed personal and demographic information. Each entry includes:

Identification & Contact: ID, Full Name, Address, ZIP Code (CEP), City (Município), and State (UF).

Documentation: National ID (RG) and Tax ID (CPF).

Parentage: Mother's Name and Father's Name.

Personal Background: Birthdate, Age, Ethnicity, Profession, Marital Status, and Child Status (whether they have children and the total count).

Planilha2 (Excel exclusive): Features a Pivot Table summarizing profession metrics segmented by Marital Status (e.g., counting professionals who are married).

Planilha3 (Excel exclusive): A workspace containing auxiliary calculations, metadata mentioning an "Audit Challenge: 20 Objective Questions", Mode calculations for municipalities, and year-matching references.

2. Base de dados de empresa logística LogFiuza.xlsm
This spreadsheet is tailored for tracking and auditing logistics operations for a supply chain enterprise called LogFiuza. It comprises two data-heavy sheets and one blank sheet:

Lista_CDs Sheet: A master list of the company's Distribution Centers (CDs). It details the CD ID, CD Name, Operation Type (such as Last Mile Hub, Cross-Docking without ASM, or Hybrid Fulfillment), and its geographic City/State location.

Transferencias Sheet: A comprehensive ledger documenting fleet transfers and freight movement between distribution nodes. It tracks:

Exact dispatch (Origin Departure) and delivery timestamps (Destination Arrival).

Complete profile of both Origin and Destination CDs (Name, Type, City, and State).

Operational KPIs: Transit duration, Fleet utilization (Number of trucks), and Freight volume (Number of packages).

Sheet1 Sheet: An unpopulated, blank tab.
