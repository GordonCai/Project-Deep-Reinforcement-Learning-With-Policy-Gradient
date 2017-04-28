Pong:
ANN1: layer:1, width: 200, exp: prob
ANN2: layer:1, width: 400, exp: greedy-0.1-0.01, finish:8000
#ANN3: layer:1, width: 200, exp: greedy-0.1-0.01, finish:8000
ANN4: layer:1, width: 600, exp: dropout-0.7, finish:8000 
#ANN5: layer:1, width: 256, exp: prob, Silvia's model
#ANN6: layer:1, width: 200, exp: prob, changed gradient

#CNN1: 
#CNN2: 32,10,48,8
#CNN3: 32,12,48,8

Breakout:
ANN1: layer:1, width: 600, exp: prob
ANN2: layer:1, width: 770, exp: dropout-0.8
#ANN3: layer:1, width: 500, exp: dropout-0.8
#ANN4: layer:1, width: 1500, exp: dropout-0.6
ANN5: layer:1, width: 300, exp: prob

#CNN1: 32,12,48,8