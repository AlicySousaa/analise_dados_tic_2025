# Análise de Dados TIC 2025

Análise de segurança digital infantil no Brasil baseada em TIC Kids Online Brasil 2025.

## O que faz?

- Gera dataset com 2.500 respondentes
- Cria 12 gráficos de análise
- Exporta dados em CSV
- Gera relatório executivo
- Identifica alunos em risco

##  Como usar?

### 1. Instale as dependências
```bash
pip install -r requirements.txt
```

### 2. Execute o script
```bash
python tic_kids_analise_2025.py
```

### 3. Verifique os resultados
```
✅ tic_kids_online_2025_analise.png  (gráficos)
✅ tic_kids_resumo_por_idade.csv     (dados por série)
✅ tic_kids_resumo_por_estado.csv    (dados por estado)
✅ tic_kids_dataset_completo.csv     (todos os dados)
✅ tic_kids_alunos_criticos.csv      (alunos em risco)
```

##  Requisitos

- Python 3.8+
- pip

##  Dados Gerados

| Arquivo | Descrição |
|---------|-----------|
| `tic_kids_online_2025_analise.png` | 12 gráficos (300 DPI) |
| `tic_kids_resumo_por_idade.csv` | Resumo por faixa etária |
| `tic_kids_resumo_por_estado.csv` | Resumo por estado |
| `tic_kids_dataset_completo.csv` | 2.500 respondentes |
| `tic_kids_alunos_criticos.csv` | Alunos para intervenção |

##  Análises Incluídas

✅ Estatísticas gerais  
✅ Exposição a riscos online (phishing, golpes, cyberbullying)  
✅ Comportamentos de segurança (senhas, antivírus)  
✅ Plataformas mais usadas  
✅ Análise por faixa etária  
✅ Análise por gênero  
✅ Análise por classe econômica  
✅ Segmentação por perfil de risco  
✅ Gap de conhecimento vs meta  
✅ Correlações entre variáveis  
✅ Mapa de riscos por estado  
✅ Recomendações de ensino  

##  Resultados Esperados

```
Conhecimento atual:       42/100
Meta:                     70/100
Alunos em risco crítico:  18%
Taxa de golpe:            12%

Com Escudo Digital:
Conhecimento esperado:    70/100 (+28 pontos)
Alunos em risco:          5% (-13%)
Taxa de golpe:            3% (-75%)
```

##  Customizar

Abra `tic_kids_analise_2025.py` e mude:

```python
# Linha 22: número de respondentes
n_respondentes = 2500  # Mude para 5000, 1000, etc

# Linha 23-30: dados para customizar
# (estados, faixas etárias, plataformas, etc)
```

##  Documentação

- **README-SCRIPT-PYTHON.md** - Guia detalhado
- **EXEMPLOS-AVANCADOS.md** - Casos de uso avançados
- **DOCUMENTACAO.md** - Referência completa

##  Contribuir

Encontrou um bug? Tem uma ideia?  
Abra uma [Issue](https://github.com/AlicySousaa/analise_dados_tic_2025/issues)

## ✅ Status

- ✅ Python 3.8+
- ✅ Production Ready

---

**Integrado com:** [Escudo Digital](https://github.com/) (Jogo Educativo)
