# 📊 Projetos de Análise de Dados - DataCamp

Este repositório reúne os projetos práticos desenvolvidos durante os meus estudos e certificações na plataforma **DataCamp**, utilizando **Python** e bibliotecas como **Pandas** para limpeza, manipulação e análise exploratória de dados.

## 🛠️ Ferramentas
- Python
- Pandas
- Matplotlib
- Google Colab

## 📁 Projetos

### 🏫 [Explorando Escolas de NYC](Explorando%20Escolas%20de%20NYC.ipynb)
Análise dos resultados do SAT (exame usado na admissão das universidades dos EUA) nas escolas públicas de Nova York. Cada seção da prova (matemática, leitura e escrita) vale até 800 pontos.

**Perguntas respondidas:**
1. **Quais escolas têm os melhores resultados em matemática?**
   Escolas com média de pelo menos 80% da nota máxima (640 de 800), ordenadas da maior para a menor.
2. **Quais são as 10 melhores escolas no SAT completo?**
   Criei a coluna `total_SAT`, somando as três notas, e ordenei as escolas por ela.
3. **Qual distrito (*borough*) tem a maior variação de desempenho?**
   Agrupei as escolas por distrito com `groupby` e calculei a quantidade de escolas, a média e o desvio padrão do `total_SAT`, para encontrar o distrito com o maior desvio padrão.

### 🎬 [Análise de Filmes da Netflix](Netflix_analise.ipynb)
Análise exploratória dos filmes da Netflix lançados nos anos 1990, no papel de uma produtora especializada em estilos nostálgicos.

**Perguntas respondidas:**
1. **Qual foi a duração de filme mais frequente nos anos 1990?**
   Filtrei os filmes da década e usei um histograma para encontrar a faixa de duração mais comum.
2. **Quantos filmes de ação curtos (menos de 90 minutos) foram lançados nos anos 1990?**
   Filtrei os filmes de ação da década e contei os que tinham menos de 90 minutos.

## 🚧 Próximos passos
Novos projetos serão adicionados conforme eu avanço nas trilhas de Análise de Dados com Python e SQL no DataCamp.
