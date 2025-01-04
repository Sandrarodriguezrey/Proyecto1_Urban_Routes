# Proyecto de práctica 1: Pruebas de Regresión y diseño de casos de prueba para una aplicación de transporte - Urban Routes

## Descripción del Proyecto :

Urban Routes es una aplicación que crea rutas y calcula la duración y precio del viaje para diferentes tipos de transporte.
Contiene dos campos para las direcciones: "Desde" y "Hasta". Además, cuenta con tres modos ("Óptimo", "Flash" y "Personal"), así como íconos para los tipos de transporte (automóvil del usuario, a pie, taxi, bicicleta, scooter o compartir un automóvil).
Una vez el usuario establece sus ubicaciones "Desde" y "Hasta", la aplicación recibe esa información como puntos "A" y "B". Luego, calcula la duración total de viaje y el precio utilizando un algoritmo específico

## Instrucciones para el Desarrollo del Proyecto :

Encontrar errores (es decir, la diferencia entre el resultado esperado y el resultado actual). Informar de todos los errores que encuentres.

1. Inicia el servidor
2. Ejecutar los casos de prueba
3. Crear informes de errores ( Para documentar los errores que encuentres, utiliza la pestaña "Informes de errores"  ), para la severidad, utiliza uno de los siguientes valores: Bloqueador, Crítico, Grave, Menor o Trivial.

## Desarrollo del Proyecto :

## 1. Análisis detallado de la funcionalidad del aplicativo como usuario en los campos "Desde" y "Hasta" y el funcionamiento del mapa.

Aqui realice un análisis minucioso del comportamiento y la interacción como usuario en los campos "Desde" y "Hasta", así como la funcionalidad del mapa, asegurando que estos elementos respondan de manera correcta y eficiente las acciones realizadas. Para ello, se debe revisar la correcta visualización de la información en el mapa y la integración entre estos componentes, comprobando que el sistema realice las acciones previstas sin errores y brindando una experiencia de usuario coherente con los requisitos establecidos.

## 2. Elaboré al detalle los casos de prueba conforme se iba probando la funcionalidad del aplicativo de acuerdo con el formato asignado. ( se adjunta excel )

Mientras realizaba las pruebas, iba registrando detalladamente cada caso de prueba conforme se iba validando la funcionalidad del aplicativo, utilizando el formato de seguimiento preestablecido (archivo Excel adjunto). Esto incluia la descripción de la prueba, los pasos ejecutados, los resultados esperados y los resultados obtenidos. Cada prueba fue verificada en su totalidad para asegurar una trazabilidad completa y la correcta ejecución de todas las validaciones.
   
## 3. Asigné el estado apropiado de cada prueba como "Aprobado" o " No Aprobado".

Después de haber ejecutado cada caso de prueba, asigne un estado a cada uno de los casos, basado en los resultados obtenidos. El estado puede ser uno de los siguientes:

  :key:   Aprobado:  Si el resultado obtenido cumple con las expectativas y funciona según lo especificado.
  :mega:  No Aprobado: Si el resultado obtenido no cumple con las expectativas o presenta errores.

Aqui considero que ess fundamental que cada estado esté correctamente registrado en el formato de seguimiento para garantizar la coherencia en los resultados de las pruebas.

## 4. Generé "Informe de error" para los casos No aprobados, asignandoles un código para su identificación del BUG.

Para los casos que no eran aprobados, se generaba un Informe de Error detallado, en el cual describo los errores encontrados. Este informe incluye un código único que es para la identificación de cada bug, facilitando su seguimiento y resolución. El informe contiene:
Descripción clara del error.
Pasos para reproducir el error.
Impacto o consecuencias del error en el funcionamiento del sistema.
Este informe debe ser entregado a los desarrolladores para su revisión y corrección.

## 5. Detallé en una pestaña aparte del "Informe de Errores" el Resultado esperado, el Resultado actual y la severidad del caso. ( se adjunta excel ).

Resultado Esperado: Descripción de la funcionalidad que se espera de acuerdo con los requisitos.
Resultado actual: Descripción del comportamiento observado durante la prueba.
Severidad del caso: Clasificación del error según su gravedad (por ejemplo, Alta, Media, Baja) y su impacto en el funcionamiento general del sistema.

Este informe debe proporcionar una visión clara de los errores encontrados, su impacto y la prioridad para su resolución.

## Referencias - se adjuntan capturas de pantalla del aplicativo

1. Mapa ampliado: Se presenta la visualización detallada del mapa, incluyendo las siguientes funcionalidades:

Zoom: Capacidad para acercar o alejar la vista del mapa.
Botón de modo pantalla completa: Permite ampliar el mapa a pantalla completa.
Botón de modo mapa: Activación del modo estándar del mapa.
Botón de modo satélite: Alternativa para visualizar el mapa en modo satélite.

2. Otros objetos del mapa (edificios, metro, parques, íconos de lugares de interés, encabezado de ciudad, pines de dirección, visualización de información)




