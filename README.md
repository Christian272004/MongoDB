1. Obtenir de tots els empleats, el nom, cognoms i salari. Mostrar només 4 registres
```js 
db.empleats.find({},{_id:0,nom:1,cognoms:1,salari:1}).limit(4)
```

2. Mostra la quantitat de departaments que hi ha 
```js
db.departaments.find({},{}).count()
```

3. Recupera l’empleat “emplat_id=100” 
```js
db.empleats.find({empleat_id:"100"},{})
```

4. Recupera els empleats amb el càrrec de “President” 
```js
db.empleats.find({feina.nom:"President"},{})
```

5. Recupera els empleats que treballen al departament de “IT” 
```js


```
