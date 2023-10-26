Neste esudo de caso, eu vou trabalhar com o departamento de recursos humanos de uma empresa.

O objetivo vai ser prever quais funcionários têm mais tendência de deixar a empresa.
Este estudo é importante porque mostra o principal problema das empresas que é realizar a contrtação e manter as telentosas na empresa.
O processo de contratação  pode levar muito tempo e é gasto muito dinheiro.
Se a empresa possui funcionários talentosos, é preciso manter esses funcionários oferecendo mais beneficios ou outros tipos de bonus.
Além de gastos com a contratação ha também gastos com o treinamento.

Algumas afirmações de pesquisas feitas nas empresas:

  - Contratar e reter funcionários são tarefas extremamente complexas que exigemm capital, tempo e habilidades.
  - Pequenos empresários gastam em torno de 40% das horas de trabalho em tarefas que não geram receitas, como a contratação.
  - Empresas gastam de 15% a 20% do salário dos funcionários para recrutar um outro candidato.
  - Uma empresa, em média, perde entre 1% a 2,5% de sua receita total no tempo em que leva para treinar um novo funcionário.
  - A contratação de um novo funcionário custa, em média, $7,5645.00 em uma empresa com aproximadamente 500 funcionários.
  - Demora, em média, 52 dias para um funcionário ocupar sua nova posição.

De posse dessas informações, o Departamento de Recursos Humanos da IBM-EUA coletou dados de seus funcionários e gostaria de  fazer uma previsão
de quais funcionários estão mais propensos a sair de seu emprego.

Alguns exemplos de dados coletados dos funcionários pelo RH:

  - Envolvimento com o trabalho.
  - Escolaridade.
  - Satisfação com o trabalho
  - Métricas de desempenho.
  - Relacionamento
  - Equilibrio entre as atividades pessoais e profissionais.
 
Para esta simulação, o Cientista de Dados irá receber uma Base de Dados do Departamento de RH para fazer análises e a previsão de quem vai deixar a empresa. 

Algoritmos de classificação utilizado neste estudo:

 - Regressão Logistica
 - Randon Forest
 - Gradient-Boosted

  Vencedor: Regressão Logistica
      
    Accuracy = 0.903153
    Test Error = 0.0968468

Dicionário dos dados:

  - Educação
    1 'Abaixo da faculdade'
    2 'Faculdade'
    3 'Bacharelado'
    4 'Mestre'
    5 'Doutor'

  - Satisfação Ambiental
    1 'Baixa'
    2 'Média'
    3 'Alta'
    4 'Muito Alta'

  - Envolvimento no Trabalho
    1 'Baixo'
    2 'Médio'
    3 'Alto'
    4 'Muito Alto'

  - Satisfação no Trabalho
    1 'Baixa'
    2 'Média'
    3 'Alta'
    4 'Muito Alta'

  - Classificação de Desempenho
    1 'Baixo'
    2 'Bom'
    3 'Excelente'
    4 'Excelente'

  - RelacionamentoSatisfação
    1 'Baixa'
    2 'Média'
    3 'Alta'
    4 'Muito Alta'

  - WorkLifeBalance
    1 'Ruim'
    2 'Bom'
    3 'Melhor'
    4 'Melhor'

  - Age:....................................... Idade        
  - Attrition:................................. Saiu    
  - BusinessTravel:............................ Viagem de negócios    
  - DailyRate:................................. Diária    
  - Department:................................ Departamento    
  - DistanceFromHome:.......................... Distância de casa    
  - Education:................................. Educação    
  - EducationField:............................ Campo da educação    
  - EmployeeCount:............................. Contagem de funcionários    
  - EmployeeNumber:............................ Número de empregado    
  - EnvironmentSatisfaction:................... Satisfação Ambiental    
  - Gender:..................................... Gênero    
  - HourlyRate:................................. Taxa horária    
  - JobInvolvement:............................. Envolvimento no Trabalho    
  - JobLevel:................................... Nível de emprego    
  - JobRole:.................................... Cargo de Trabalho    
  - JobSatisfaction:............................ Satisfação no Trabalho    
  - MaritalStatus:............................... Estado civil    
  - MonthlyIncome:............................... Renda Mensal    
  - MonthlyRate:................................. Taxa Mensal    
  - NumCompaniesWorked:.......................... NumCompaniesWorked    
  - Over18:...................................... Mais de 18    
  - OverTime:.................................... Ao longo do tempo    
  - PercentSalaryHike:........................... PorcentagemSalárioCaminhada    
  - PerformanceRating:........................... Classificação de desempenho    
  - RelationshipSatisfaction:.................... RelacionamentoSatisfação    
  - StandardHours:............................... Horas padrão    
  - StockOptionLevel:............................ Nível de opção de estoque    
  - TotalWorkingYears:........................... Total de anos de trabalho    
  - TrainingTimesLastYear:....................... Tempos de treinamentoÚltimo ano    
  - WorkLifeBalance:............................. WorkLifeBalance    
  - YarsAtCompany:.............................. AnosNaEmpresa    
  - YearsInCurrentRole:.......................... Anos na função atual    
  - YearsSinceLastPromotion:..................... AnosDesdeÚltimaPromoção    
  - YearsWithCurrManager:........................ AnosComCurrManager
    
Importação das bibliotecas e base de dados

- Base de dados: https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset
- Cálculo de salário: https://www.mom.gov.sg
- Stock: https://www.moneyunder30.com
  
