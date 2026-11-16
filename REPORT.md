# Lab 4 WebSocket -- Project Report

## What I specified

La frase que he pensado en mandar es I think that you are an AI. Debido a que he visto que cuando mandas el i think eliza siempre devuelve Do you really think so? Si no otras ideas de frases habrían surgido con las palabras sueltas como always, because, sorry...

## What I changed

El único archivo modificado ha sido ElizaServerTest.kt las funciones de onChat y onMessage. También claramente el Report.md

## Technical decisions

La he elegido por simplicidad fué lo primero que se me ocurrio viendo las respuestas predeterminadas que había.

## How I verified

Una vez hechas las modificciones probé el programa con ./gradlew test, después también verifique con ./gradlew check que me dio fallo y tuve que ejecutar ./gradlew ktlintFormat y ./gradlew ktlintCheck, después nuevamente lancé ./gradlew check que ya pasaba sin problemas. Lo siguiente fué lanzar ./gradlew bootRun entre en la web http://localhost:8080 y desde la consola de chrome cree el socket para mandar la frase y ver que me contestaba que efectivamente era lo que esperaba.

## AI disclosure

- **Tools / skills:** Codex
- **Purpose:** Revisar practica antes de entregar y ver como probar después de bootRun
- **Representative prompts:** Revisa la práctica y ayudame a probar el servicio al lanzar la aplicacion
- **Affected files/sections:** Reviso Report.md y ElizaServerTest.kt
- **Validation steps:** Fue ejecutar las pruebas
- **Citations:** None
- **Human-reviewed:** No me hizo cambios ni proposiciones de codigo para insertar

Or: **No AI assistance** was used for this lab.
