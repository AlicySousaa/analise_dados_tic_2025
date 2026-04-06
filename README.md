Análise de Dados: TIC Kids Online Brasil 2025 – Projeto Escudo Digital
Sobre o Projeto
Este repositório contém a análise estatística e o processamento de dados baseados na metodologia TIC Kids Online Brasil. O estudo visa mapear a vulnerabilidade de crianças e adolescentes (7 a 16 anos) no ambiente digital, servindo como base analítica para o desenvolvimento do Escudo Digital, uma solução educacional voltada à cibersegurança.

Tecnologias Utilizadas
Linguagem: Python 3.x

Bibliotecas de Análise: Pandas, NumPy

Visualização de Dados: Matplotlib, Seaborn

Metodologia: Análise Quantitativa e Probabilística

Metodologia de Dados
O dataset processado conta com 2.500 respondentes sintéticos, modelados com base em distribuições reais de demografia e comportamento digital:

Distribuição Geográfica: Representação de 10 estados brasileiros com pesos populacionais reais.

Segmentação Etária: 5 grupos distintos (7-8, 9-10, 11-12, 13-14 e 15-16 anos).

Modelagem Estatística: Uso de distribuições Binomiais para eventos de risco e distribuições Normais para métricas de tempo de uso e score de conhecimento.

Indicadores Analisados
A análise foca em quatro pilares fundamentais:

Exposição a Riscos: Mensagens de estranhos, links suspeitos (phishing), compartilhamento de dados, cyberbullying, conteúdo inapropriado e golpes.

Comportamentos de Segurança: Uso de senhas fortes, verificação de privacidade e uso de ferramentas de proteção.

Score de Conhecimento: Uma métrica composta (0-100) que avalia a proficiência técnica do usuário em segurança digital.

Perfil de Risco: Classificação algorítmica dos usuários em níveis (Crítico, Alto, Médio e Baixo).

Como Executar
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instale as dependências:

Bash
pip install pandas numpy matplotlib seaborn
Execute o script de análise:

Bash
python analise_tic_kids.py

Estrutura de Saída
O script gera automaticamente os seguintes arquivos para suporte à decisão:

tic_kids_dataset_completo.csv: Base de dados bruta.

tic_kids_resumo_por_idade.csv: Agrupamento estatístico por faixa etária.

tic_kids_alunos_criticos.csv: Lista de usuários identificados em situação de vulnerabilidade alta para intervenção prioritária.

tic_kids_online_2025_analise.png: Painel visual com 12 gráficos de indicadores-chave.

🔍 Principais Insights
Gap de Conhecimento: Identificou-se que a média de conhecimento está abaixo da meta de 50 pontos em faixas etárias iniciais.

Fator de Exposição: O aumento da idade está correlacionado a uma maior exposição a conteúdos inapropriados e tentativas de phishing.

Eficácia Educacional: A análise de correlação confirma que o aumento no score de conhecimento reduz diretamente a taxa de sucesso de golpes sofridos.

Autor: [Seu Nome/Projeto Escudo Digital]

Data: 06 de Abril de 2026

Status: Análise Concluída / Fase de Implementação de Piloto.
