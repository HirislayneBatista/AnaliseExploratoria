# #**📊 Projeto Final do Curso de Python da FEA.dev: Análise de Dados Educacionais**

Neste desafio, foi analisado um conjunto de dados sobre o desempenho acadêmico de estudantes, com o objetivo de realizar uma análise exploratória a fim de responder a uma pergunta norteadora, gerando insights a partir dos dados.

---

## **🚀 O Desafio**

### **Pergunta Norteadora**:  
**"Quais fatores demográficos, acadêmicos e comportamentais mais influenciam a classificação e a média de notas dos estudantes?"**

As variáveis de interesse são **`Classificacao_Notas` e `Media_Notas`**. O objetivo é investigar como elas se relacionam com outros fatores, como por exemplo idade, gênero, faltas, horas de estudo e participação em atividades extracurriculares. 📝

---

## **📌 Etapas do Desafio**

1. **Importação e Exploração dos Dados**:
   - Ler o dataset e obter uma visão geral das informações.
   - Verificar o formato dos dados, tipos de variáveis e valores ausentes ou duplicados.

2. **Preparação e Limpeza**:
   - Renomear colunas, tratar valores ausentes e ajustar os dados conforme necessário.
   - Criar novas colunas, se útil para a análise ou visualização.

3. **Análise Exploratória**:
   - Investigar a relação entre **`Classificacao_Notas` e `Media_Notas`** com outras variáveis.
   - Exemplos de perguntas a explorar:
     - Alunos que participam de atividades extracurriculares têm melhor desempenho?
     - O número de faltas impacta a classificação?
     - Há diferenças de desempenho por idade, gênero ou etnia?

4. **Visualização de Dados**:
   - Criar gráficos (ex.: histogramas, boxplots, scatter plots) para apresentar os padrões encontrados de forma clara e visualmente atraente. 📈

5. **Conclusões**:
   - Resumir os principais insights.
   - Destacar os fatores mais relevantes que influenciam as classificações e as médias de notas.

---

## **📚 Origem dos Dados**
Este dataset foi disponibilizado por Rabie El Kharoua no Kaggle e está licenciado sob CC BY 4.0:  

> El Kharoua, R. (2024). Students Performance Dataset.  
> Disponível em: [Kaggle Dataset Link](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset).

---

## **📊 Descrição das Colunas do DataFrame**

### **Identificação do Estudante**  
- **ID_Aluno**: Identificador único para cada aluno (de 1001 a 3392).

### **👥 Detalhes Demográficos**  
- **Idade**: Idade dos estudantes, variando de 15 a 18 anos.  
- **Genero**: Gênero do estudante:
  - 0: Masculino
  - 1: Feminino  
- **Etnia**: Etnia dos estudantes:
  - 0: Caucasiano
  - 1: Afrodescendente
  - 2: Asiático
  - 3: Outra

### **👨‍👩‍👧 Educação dos Pais**  
- **Escolaridade_Pais**: Nível de escolaridade dos pais:
  - 0: Nenhum
  - 1: Ensino Médio
  - 2: Alguma Faculdade
  - 3: Graduação
  - 4: Pós-Graduação ou Superior

### **📚 Hábitos de Estudo**  
- **Horas_Estudo_Semanais**: Tempo de estudo semanal em horas (0 a 20).  
- **Faltas**: Número de faltas no ano letivo (0 a 30).  
- **Aulas_Particulares**: Participação em aulas particulares:
  - 0: Não
  - 1: Sim

### **👨‍👩‍👧 Envolvimento Parental**  
- **Apoio_Pais**: Nível de apoio dos pais:
  - 0: Nenhum
  - 1: Baixo
  - 2: Moderado
  - 3: Alto
  - 4: Muito Alto

### **🏫 Atividades Extracurriculares**  
- **Atividades_Extracurriculares**: Participação em atividades extracurriculares:
  - 0: Não
  - 1: Sim  
- **Esportes**: Participação em esportes:
  - 0: Não
  - 1: Sim  
- **Musica**: Participação em atividades musicais:
  - 0: Não
  - 1: Sim  
- **Voluntariado**: Participação em atividades de voluntariado:
  - 0: Não
  - 1: Sim

### **📈 Desempenho Acadêmico**  
- **Media_Notas**: Média das notas (GPA), variando de 0.0 a 4.0.  
- **Classificacao_Notas**: Classificação do aluno com base na média das notas:
  - 0: 'A' (Média >= 3.5)
  - 1: 'B' (3.0 <= Média < 3.5)
  - 2: 'C' (2.5 <= Média < 3.0)
  - 3: 'D' (2.0 <= Média < 2.5)
  - 4: 'E' (Média < 2.0)

---