<p>Neste esudo de caso, eu vou trabalhar com o departamento de recursos humanos de uma empresa.</p>
<p align="justify">O objetivo vai ser prever quais funcionários têm mais tendência de deixar a empresa. Este estudo é importante porque mostra o principal problema das empresas que é realizar a contrtação e manter as telentosas na empresa. O processo de contratação  pode levar muito tempo e é gasto muito dinheiro. Se a empresa possui funcionários talentosos, é preciso manter esses funcionários oferecendo mais beneficios ou outros tipos de bonus. Além de gastos com a contratação ha também gastos com o treinamento.
</p>
<p>Algumas afirmações de pesquisas feitas nas empresas:</p>
<ul>
  <li>Contratar e reter funcionários são tarefas extremamente complexas que exigemm capital, tempo e habilidades.</li>
  <li>Pequenos empresários gastam em torno de 40% das horas de trabalho em tarefas que não geram receitas, como a contratação.</li>
  <li>Empresas gastam de 15% a 20% do salário dos funcionários para recrutar um outro candidato.</li>
  <li>Uma empresa, em média, perde entre 1% a 2,5% de sua receita total no tempo em que leva para treinar um novo funcionário.</li>
  <li>A contratação de um novo funcionário custa, em média, $7,5645.00 em uma empresa com aproximadamente 500 funcionários.</li>
  <li>Demora, em média, 52 dias para um funcionário ocupar sua nova posição.</li>
</ul>
<p align="justify">De posse dessas informações, o Departamento de Recursos Humanos da IBM-EUA coletou dados de seus funcionários e gostaria de  fazer uma previsão de quais funcionários estão mais propensos a sair de seu emprego.
</p>

<p>Alguns exemplos de dados coletados dos funcionários pelo RH:</p>
<ul>
  <li>Envolvimento com o trabalho.</li>
  <li>Escolaridade.</li>
  <li>Satisfação com o trabalho.</li>
  <li>Métricas de desempenho.</li>
  <li>Relacionamento.</li>
  <li>Equilibrio entre as atividades pessoais e profissionais.</li>
</ul>
<p>Para esta simulação, o Cientista de Dados irá receber uma Base de Dados do Departamento de RH para fazer análises e a previsão de quem vai deixar a empresa.</p> 
<p>Algoritmos de classificação utilizado neste estudo:</p>
<ul>
  <li>Regressão Logistica.</li>
  <li>Randon Forest</li>
  <li>Gradient-Boosted</li>
</ul>
<p>Vencedor: <b>Regressão Logistica</b></p>
<ul>
  <li>Accuracy = 0.903153</li>
  <ul>
    <li>Test Error = 0.0968468</li>
  </ul>
</ul>
<p>Variáveis Categoricas:</p>
<ul>
  <li>Educação:</li>
    <ul>
      <li>1 Abaixo da faculdade</li>
      <li>2 Faculdade</li>
      <li>3 Bacharelado</li>
      <li>4 Mestre</li>
      <li>5 Doutor</li>
    </ul>
  <li>Satisfação Ambiental:</li>
    <ul>    
      <li>1 Baixa</li>
      <li>2 Média</li>
      <li>3 Alta</li>
      <li>4 Muito Alta</li>
    </ul>
  <li>Envolvimento No Trabalho:</li>
    <ul>    
      <li>1 Baixo</li>
      <li>2 Médio</li>
      <li>3 Alto</li>
      <li>4 Muito Alto</li>
    </ul> 
  <li>Satisfação No Trabalho:</li>
    <ul>    
      <li>1 Baixa</li>
      <li>2 Média</li>
      <li>3 Alta</li>
      <li>4 Muito Alta</li>
    </ul>
  <li>Classificação de Desempenho:</li>
    <ul>    
      <li>1 Baixo</li>
      <li>2 Médio</li>
      <li>3 Alto</li>
      <li>4 Muito Alto</li>
    </ul>
  <li>RelacionamentoSatisfação:</li>
    <ul>    
      <li>1 Baixa</li>
      <li>2 Média</li>
      <li>3 Alta</li>
      <li>4 Muito Alta</li>
    </ul>
  <li>RelacionamentoSatisfação:</li>
    <ul>    
      <li>1 Ruim
      </li>2 Regular
      <li>3 Bom</li>
      <li>4 Muito Bom</li>
    </ul>
</ul>
<p>Dicionário de Dados:</p>
<table>
  <tr>
    <table>
      <tr><td>Age</td><td>&nbsp</td><td>Idade</td></tr>
    </table>
  </tr>
</table>
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
  
