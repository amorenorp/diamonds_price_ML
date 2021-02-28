# Diamond's Price with Machine Learning: Kaggle competition

## Bienvenidos al precio justo! 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgpoUccQWTBL37cuniLyCoOx-oU6ajmBCziA&usqp=CAU)


#### ***Objetivo*** : 
Entrenar difrerentes modelos de ML para encontrar el que menor `*Squared mean error*` tiene. 

#### ***Proceso*** : 
En los diferentes Jupyter notebook podeis encontrar diferentes modelos entrenados y sus respectivos `mse`. 

Usamos el data base de diamantes que podeis encontrar en este enlace de [Kaggel.](https://www.kaggle.com/c/diamonds-datamad0121/leaderboard)

Todos los modelos han sido entrenados con la misma limpieza del dataframe. 

Tras estudiar la correlaccion entre variables, decidí añadir una columna con el precio por quilate, dividiendo la columna `price` entre la columna `carat`.  Tras eso realizo un gruopby de `cut`, `color`, `clarity` y observamos como tienen un órden por lo que le asignamos un valor en escala. 

[](https://github.com/amorenorp/diamonds_price_ML/blob/main/img/gruopby.png)

Probamos varios modelos de ML: 

[](https://github.com/amorenorp/diamonds_price_ML/blob/main/img/varios.png)
[](https://github.com/amorenorp/diamonds_price_ML/blob/main/img/Random%20Forest.png)


Después probamos con H2o:

[](https://github.com/amorenorp/diamonds_price_ML/blob/main/img/h2o_2.png)

Cargamos los .csv en la competicion de Kaggel y obtenemos estos resultados con 2 modelos de H2o:
[](https://github.com/amorenorp/diamonds_price_ML/blob/main/img/Captura%20de%20pantalla%202021-02-28%20a%20las%2022.18.59.png)

