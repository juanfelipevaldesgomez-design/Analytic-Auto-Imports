# Analytic-Auto-Imports
engine-size predice el precio mejor que horsepower (r=0.87 vs 0.81).
Un Porsche mal valorado ($10,295 con 288 hp) distorsionaba la correlación; sin él, sube a 0.81.
Jaguar, Mercedes-Benz y Porsche lideran en precio promedio por marca.
Hardtop y convertible son el doble de caras que hatchback.
city-mpg y highway-mpg están casi redundantes entre sí (0.97).


7. Conclusiones


Lo que más me sirvió fue usar una matriz de correlación completa en vez de ir variable por variable — así encontré cosas que no estaba buscando, como la redundancia entre mpg ciudad y carretera. Es lo primero que contaría en una entrevista.



Con más tiempo armaría un modelo de regresión con las variables más fuertes, y revisaría si marcas con pocos autos (como Alfa Romeo, solo 3 registros) deberían excluirse de las comparaciones por no ser representativas.
