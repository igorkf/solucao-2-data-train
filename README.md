O desafio consistia em prever as probabilidade de crianças com até 1 ano de vida falecerem.     
     
Após a limpeza e preparação dos dados, eu criei 3 novas features a partir das features disponíveis.     
No final usei o XGBoost como modelo de classificação.    
Para validação do modelo, usei tanto validação cruzada k-fold como stratified k-fold, pois os dados eram desbalanceados (a proporção entre óbitos e sobreviventes não era 50/50).

Link para a competição no Kaggle:    
https://www.kaggle.com/c/data-train-secitec-ifg/submissions
