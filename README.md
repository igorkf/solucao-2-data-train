# 1º lugar Public - 2ª competição Data Train.
      
Essa foi minha solução para a 2ª competição da Data Train - Goiânia, que ficou em 1º lugar na Public Leaderboard. O desafio consistia em prever as probabilidade de crianças com até 1 ano de vida falecerem.
     
Após a limpeza e preparação dos dados, eu criei 3 novas features a partir das features disponíveis.     
No final usei o XGBoost como modelo de classificação.    
Para validação do modelo, usei tanto validação cruzada k-fold como stratified k-fold, pois os dados eram desbalanceados (a proporção entre óbitos e sobreviventes não era 50/50).
