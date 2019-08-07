# Lais Electra Ximenes Chess (LEXChess)

<iframe width="560" height="315" src="https://www.youtube.com/embed/qG59OobzCcE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<img width=600px src="https://github.com/DevJoseWeb/Lais-Electra-Ximenes-Chess/blob/master/monstra.jpg" />
<img width=600px src="https://raw.githubusercontent.com/geohot/twitchchess/master/screenshot.png" />

Instalar:
```
 pip3 install python-chess torch torchvision numpy flask
 # then...
 ./play.py   # runs webserver on localhost:5000
```

Para mais velocidade
```
 pip_pypy install python-chess flask
 pypy ./play.py
 # web browse to localhost:5000
```

Training Set
-----

The value function was trained on 5M board positions from http://www.kingbase-chess.net/

