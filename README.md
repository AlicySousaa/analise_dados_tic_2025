Projeto de Análise de Dados: TIC Kids Online Brasil 2025

1. Descrição do Projeto

Este projeto consiste num pipeline de análise de dados voltado para o estudo do comportamento digital de crianças e adolescentes no Brasil. A análise baseia-se na geração e processamento de um dataset sintético de 2.500 respondentes, modelado com base na metodologia oficial da pesquisa TIC Kids Online. O objetivo central é fornecer subsídios analíticos para a implementação do sistema "Escudo Digital", focando em cibersegurança e mitigação de riscos online.

2. Estrutura do Dataset

O conjunto de dados é composto por variáveis demográficas e comportamentais geradas via distribuições estatísticas:

2.1 Dados Demográficos

Estado: Abrangência em 10 estados brasileiros com pesos populacionais proporcionais.

Faixa Etária: Segmentação entre 7 e 16 anos, dividida em cinco grupos bienais.

Classe Económica: Classificação baseada no critério Brasil (A, B1, B2, C, D/E).

Género: Distribuição binária para fins estatísticos de amostragem.

2.2 Variáveis de Comportamento e Risco

Uso de Internet: Frequência e intensidade (horas/dia).

Exposição a Riscos: Indicadores de phishing, cyberbullying, mensagens de estranhos e conteúdo inapropriado.

Segurança Digital: Medição de hábitos como uso de senhas fortes, verificação de privacidade e uso de ferramentas de proteção.

3. Metodologia de Análise

A análise é dividida em quatro etapas principais:

Processamento e Limpeza: Conversão de tipos de dados e tratamento de outliers através de funções de clipagem do NumPy.

Análise Exploratória (EDA): Cálculo de estatísticas descritivas e taxas de exposição por segmento.

Modelagem de Score: Criação do "Score de Conhecimento", uma métrica ponderada de 0 a 100 baseada em comportamentos preventivos.

Segmentação de Risco: Algoritmo de classificação que define o perfil de vulnerabilidade do utilizador (Crítico, Alto, Médio ou Baixo) cruzando incidentes sofridos com o nível de conhecimento.

4. Requisitos de Software

Para a execução deste ambiente de análise, são necessárias as seguintes dependências:

Python 3.8 ou superior

Pandas (Manipulação de dados)

NumPy (Operações matemáticas e geração estatística)

Matplotlib (Visualização de dados)

Seaborn (Gráficos estatísticos avançados)

5. Instruções de Execução

Para replicar a análise, siga os comandos abaixo:

# Instalação das dependências
pip install pandas numpy matplotlib seaborn

# Execução do script de análise
python main.py


6. Resultados e Artefatos Gerados

Ao final da execução, o sistema exporta os seguintes ficheiros para análise externa:

tic_kids_dataset_completo.csv: Base de dados bruta com todos os registos.

tic_kids_resumo_por_idade.csv: Tabela agregada com indicadores por faixa etária.

tic_kids_alunos_criticos.csv: Subset contendo utilizadores em situação de vulnerabilidade extrema para intervenção direta.

tic_kids_online_2025_analise.png: Dashboard consolidado com 12 visualizações gráficas.

7. Conclusões para o Escudo Digital

A análise identificou que o conhecimento técnico não cresce na mesma proporção que a exposição aos riscos em faixas etárias mais elevadas. A recomendação técnica é a aplicação de trilhas de aprendizagem diferenciadas, focando em Engenharia Social para os grupos de 13-16 anos e em conceitos básicos de privacidade para o grupo de 7-12 anos.

Responsável: Projeto Escudo Digital

Versão: 1.0.0

Licença: Uso Interno / Educacional
