# TREINAMENTO DE REDE RNT E TESTE COM MODELO TREINADO  
Projeto desenvolvido para treinamento de rede neural RNT na tarefa de previsão da cotação do dólar em reais, com salvamento do modelo treinado para execução de novo treinamento com os mesmos dados.   

## 🧰 Tecnologias utilizadas  
```python
# IMPORTAÇÃO DE BIBLIOTECAS

import pandas as pd
import numpy as np
from sklearn.preprocessing import MinMaxScaler
from keras.models import Sequential
from keras.layers import Dense, LSTM
import matplotlib.pyplot as plt

from sklearn.metrics import mean_squared_error
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import r2_score
```
---  
## 📊 Parâmetros numéricos  
- Ajuste de parâmetros para treinamento
<img src='https://github.com/rosacarla/treinamento-teste-modelo-treinado-RNT/blob/main/images/treinamento.png'>

 - Ajuste de parâmetros do modelo treinado
<img src='https://github.com/rosacarla/treinamento-teste-modelo-treinado-RNT/blob/main/images/modelo-treinado.png' width=320>

---  
## ©️ Licença  
Distribuído sob a licença MIT. Veja `LICENSE`para informações adicionais.    

---  
## 📫 Contato  
Autora: Carla Edila Silveira  
E-mail: rosa.carla@pucpr.edu.br  
