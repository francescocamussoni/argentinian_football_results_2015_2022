### Argentinian football results from 2015 to 2022
This dataset contains information about all matches played in the first division of Argentinian football from 2015 to 2022. There are two identical files in terms of information but one is in English (*_eng*) and one in Spanish (*_spa*).

### Context
I came across the idea of analysing particularities of Argentinian football but I didn't find any dataset that includes the information I wanted in an easy and summarised way. So I decided to generate this information myself.

### Content
It contains the information of 2821 first division matches of Argentinian football by grouping data from promeidos.com.ar, transfermarkt.de and oddportal.com on `afa_2015_2022_eng.csv`:
* `tournament`: name of the current tournament when the match was played. *promiedos*
* `week`: on which date the match was played. *promiedos*.
* `match`: number of the match within the date. *promiedos*.
* `team_home(away)`: name of the home(away) team *promiedos*.
* `goals_home(away)`: number of goals scored by the home(away) team. *promiedos*.
* `possesion_home(away)`: possession percentage of the home(away) team. *promiedos*.
* `on_target_home(away)`: shots on goal by home(away) team. *promiedos*.
* `attemps_home(away)`: total attempts of home(away) team. *promiedos*.
* `fouls_home(away)`: fouls committed by home team. *promiedos*.
* `corner_kicks_home(away)`: corner kicks taken by home team. *promiedos*.
* `yellow_cards_home(away)`: yellow cards of home(away) team. *promiedos*.
* `red_cards_home(away)`: red cards of the home(away) team. *promiedos*.
* `team_value_home(away)`: market value according to home team. *transfermarkt*.
* `mean_height_home(away)`: average height of home(away) team. *transfermarkt*. 
* `mean_age_home(away)`: average age of home(away) team. *transfermarkt*. 
* `lefties_proportion_home(away)`: proportion of left-handed players in home(away) team. *transfermarkt*.
* `result`: result of the match.
* `game_datetime`: date of the match. *oddsportal*.
* `odds_home(away)`: bet return for a win of the home (away) team. *oddsportal*.
* `odds_draw`: return bet for a draw. *oddsportal*.

The names of the teams and tournaments are the ones that are used on promiedos.com.ar.

### Inspiration:
* How well do people bet on Argentinian football?
* How strong is the correlation between the money spent on a team and the results obtained?
* Who is the best team in recent years?
* Do Boca and River only play on Sundays?

### Contribute
If you notice a mistake you can fix that by submitting a pull request.
 
 -----
 
### Resultados del fútbol argentino desde 2015 hasta 2022
Este set de datos contiene información acerca de todos los partidos realizados en la primera división del fútbol argentino desde el 2015 hasta el 2022. Hay dos archivos identicos en cuanto a información pero uno está en ingles(*_eng*) y otro en español (*_spa*)

### Contexto
Tuve la idea de analizar particularidades del futbol argentino pero no encontré ningún set de datos que incluya la información que deseaba de forma fácil y resumida. Entonces decidí generar esta información por mi mismo.

### Contenido
Contiene la información de 2821 partidos de primera división del fútbol argentino agrupando datos de promeidos.com.ar, transfermarkt.de and oddportal.com en el archivo `afa_2015_2022_spa.csv`:
* `torneo`: nombre del torneo en curso cuando se jugó el partido. *promiedos*
* `fecha`: en qué fecha se jugó el partido. *promiedos*.
* `partido`: número de partido dentro de la fecha. *promiedos*.
* `equipo_local(visitante)`: nombre del equipo local(visitante) *promiedos*.
* `goles_local(visitante)`: número de goles anotados por el equipo local(visitante). *promiedos*.
* `goles_visitante(visitante)`: porcentaje de posesión del equipo local(visitante). *promiedos*.
* `tiros_arco_local(visitante)`: tiros al arco del equipo local(visitante). *promiedos*.
* `intentos_local(visitante)`: intentos totales del equipo local(visitante). *promiedos*.
* `faltas_local(visitante)`: faltas cometidas por el equipo local(visitante). *promiedos*.
* `tiros_esquina_local(visitante)`: tiros de esquina realizados por el equipo local(visitante). *promiedos*.
* `amarillas_local(visitante)`: tarjetas amarillas del equipo local(visitante). *promiedos*.
* `rojas_local(visitante)`: tarjetas rojas del equipo local(visitante). *promiedos*.
* `valor_mercado_local(visitante)`: valor de mercado según del equipo local(visitante). *transfermarkt*.
* `altura_media_local(visitante)`: altura media del equipo local(visitante). *transfermarkt*. 
* `edad_media_local(visitante)`: edad media del equipo local(visitante). *transfermarkt*. 
* `proporcion_zurdos_local(visitante)`: proporcion de jugadores zurdos en el equipo local (visitante). *transfermarkt*.
* `resultado`: resultado del encuentro.
* `fecha_encuentro`: fecha del encuentro. *oddsportal*.
* `apuesta_local(visitante)`: retorno de apuesta para una victoria del equipo local(visitante). *oddsportal*.
* `apuesta_empate`: retorno de apuesta para un empate. *oddsportal*.

Los nombres de los equipos y de los torneos son los que se encuentran en promiedos.com.ar

Inspiración:
* Qué tan bien apuesta la gente para el fútbol argentino?
* Qué tan fuerte es la correlación entre el dinero gastado en un equipo y los resultados obtenidos?
* Quien es el mejor equipo de estos últimos años?
* Boca y River solo juegan los domingos?

Contribuí
Si encontras algun error no dudes en enviar un pull request.
