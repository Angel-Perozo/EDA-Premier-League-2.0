# EDA-Premier-League-2.0
EDA Premier League

Análisis exploratorio de datos histórico de la Premier League de Inglaterra, analizaremos las primeras 30 temporadas del torneo.

Los datos tienen origen en la plataforma Kaggle:
https://www.kaggle.com/datasets/evangower/premier-league-matches-19922022

El conjunto de datos original está compuesto por 11646 registros en 8 columnas, en las que no se registran datos faltantes
y que presentan la siguiente estructura: 

Season_End_Year --> Contiene el año de finalización del campeonato
Wk              --> La semana o jornada en disputa
Date            --> La fecha en que se celebró el cotejo
Home            --> El nombre del equipo que fungió de Local
HomeGoals       -->Goles anotados por el equipo Local
AwayGoals       -->Goles anotados por el equipo Visitante
Away            -->El nombre del equipo que hizo de Visitante
FTR             -->Resultado del enfrentamiento, H = Victoria local,  A = Victoria visitante, D = Draw

Y aunque la data es bastante robusta y completa me pareció necesaria la creación de nueva data para facilita su entendimiento.

TotalGoals      -->Alberga el total de goles anotados en el partido	
WinningTeam     -->El nombre del equipo que resultó ganador del encuentro
LosingTeam      -->El equipo derrotado. Si en estas 2 columnas no hay registro es por que fue un empate	
Result          -->Una representación del resultado final del encuentro

Podremos visualizar cuantos equipos han disputado el torneo a lo largo de estos 30 años, entendiendo que el mismo tiene un formato
en el que los 3 últimos de la tabla de posiciones pierden la categoría y son ocupados dichos puestos por los 3 primeros del torneo 
Championschip que es el torneo de 2da categoría en Inglaterra. El total de partidos disputados, los goles anotados en los mismos, 
y por supuesto los rendimientos individuales de los equipos a lo largo de este tiempo.

Realizaremos además un cuadro histórico que albergará a todos y cada uno de los campeones de cada temporada, así como se analizará 
el rendimiento de los equipos en base a victorias, derrotas, puntos, goles anotados, goles recibidos y otras características que surgen
a medida que entendemos mejor nuestro conjunto de datos.

Como bonus analizaremos lo que fué la carrera de Alex Ferguson, quien estando al frente del Manchester United alcanzo records tan impresionantes 
que lo llevaron a ser merecedor en el año de 1999 de las distinción de Caballero, título que le fue  entregado por la Reina Isabel II



