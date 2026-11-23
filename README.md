# grupoH_planta-en-crisis_jaimes-darrin
Planta en Crisis: Operación Números

Grupo:H

Integrantes:

-Darrin Jaimes Noboa

-Harley Bodero

-Leyton SanLucas

-César Naranjo

-Erick Palacios

## TABLA ÚNICA DE ANÁLISIS DE REQUISITOS Y PRUEBAS

| ID | Tipo de requisito | Descripción del requisito | Caso de prueba propuesto | Resultado esperado |
| :---: | :---: | :--- | :--- | :--- |
| **RF-01** | Funcional | El sistema permitirá que un equipo avance a la siguiente estación de su zona (materia prima, producción, calidad o despacho) solo cuando resuelva correctamente el ejercicio matemático presentado. | Ingresar una respuesta incorrecta y luego la correcta en un ejercicio de la estación de materia prima. | Con la respuesta incorrecta el sistema informa el error y el equipo permanece en la estación; con la correcta se habilita el paso a la siguiente estación. |
| **RF-02** | Funcional | El sistema generará imprevistos en la planta (tubería rota, máquina detenida o corte de luz) que los jugadores deberán solucionar para poder continuar. | Activar el imprevisto de tubería rota durante una partida y hacer que el equipo lo resuelva (por ejemplo, girando la válvula). | Mientras el imprevisto sigue activo el equipo no puede avanzar; al solucionarlo, el sistema lo desactiva y la partida continúa. |
| **RF-03** | Funcional | El sistema medirá el tiempo de cada equipo y declarará ganador al que resuelva correctamente todas las estaciones y el reto final en el menor tiempo. | Simular una partida en la que dos equipos completan el reto final con tiempos distintos. | El sistema muestra el tiempo de cada equipo y declara ganador al de menor tiempo. |
| **RNF-01** | No funcional | Compatibilidad: el juego deberá ejecutarse en computadora, celular y gafas Meta Quest, y permitir que jugadores de distintos dispositivos participen en la misma partida. | Unir a una misma partida a un jugador en computadora, uno en celular y uno con Meta Quest, y pedirles completar una estación. | Los tres jugadores ingresan a la partida, ven la misma estación y la completan sin errores ni cierres inesperados. |
| **RNF-02** | No funcional | Rendimiento: el sistema deberá validar cada respuesta y mostrar el resultado en un máximo de 2 segundos con los seis equipos conectados. | Con los seis equipos en partida, enviar varias respuestas y medir el tiempo entre el envío y el mensaje de resultado. | Cada respuesta se valida y muestra su resultado en 2 segundos o menos. |
