# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-15
Se pide diseñar un Modelo Entidad-Relación (MER) para la gestión de torneos de videojuegos, que permita administrar los videojuegos oficiales, los torneos, los equipos, los jugadores, los partidos y las estadísticas de rendimiento.

El modelo debe contemplar:

- Videojuegos: registrar código, nombre, género y desarrollador.
- Torneos: almacenar ID, nombre, fecha de inicio, fecha de fin y videojuego asociado.
- Equipos: registrar tag, razón social, país de origen y fecha de fundación.
- Jugadores: almacenar ID, nickname, nombre real y nacionalidad. Un jugador pertenece a un único equipo en cada torneo.
- Inscripciones: representar los equipos que participan en cada torneo.
- Partidos: registrar los encuentros entre dos equipos, con fecha y hora, resultado final y equipo ganador.
- Estadísticas: registrar el rendimiento individual de cada jugador en cada partido, incluyendo bajas, muertes, asistencias y daño total infligido.

Finalmente, se deben identificar las entidades, sus atributos, las relaciones y las cardinalidades, contemplando las relaciones muchos a muchos (N:M), la participación de los equipos en distintos torneos y el registro de estadísticas individuales por partido.
<img width="1932" height="1352" alt="EJERCICIO 15 drawio" src="https://github.com/user-attachments/assets/6e8b64ec-960d-4476-ad78-25aa265aad4d" />
