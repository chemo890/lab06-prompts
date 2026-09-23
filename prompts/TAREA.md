# Tarea: Mi prompt profesiona

Elige una funcionalidad sencilla de software que te gustaría construir (por ejemplo: registro de clientes, cálculo de notas o un CRUD de productos) y crea el archivo prompts/TAREA.md. En él vas a documentar cómo llevaste un prompt básico hasta un prompt profesional, iterando al menos tres veces.

## Funcionalidad elegida

hare sobre calculo de notas.

## Version 1: prompt basico

MI primer prompt
text
quiero que hagas un calculo de notas en java

¿Por que?
Como ejemplo de un prompt basico y sin estructura

## Version 2
Mi segundo prompt donde le indique el contexto, que quiero especialmente en mi programa
```text
Acuta como un profesional de 10 años de experiencia como desarrollador java y quiero que realices un programa java sobre calculo de notas, que pueda ingresar nombre del alumno notas y al consultar me salga el promedio si aprobó o no
```
¿Por que?
Porque necesito que la ia tenga un contexto ya que pido una funcionalidad directa a la ia
¿Que mejoró?
La respuesta fue bastante buena dividio y organizo el codigo, realizo la funcionalidad solicitada.

## Version 3: prompt final

Prompt:
```text
    Eres desarrollador de aplicaciones java con mas de 10 años de experiencia, quiero que hagas un programa java sobre notas, ingresaremos nombre y nota luego calcularemos el promedio final y si esta aprobado si supera 13.y menu simple donde pueda ingresar el alumno con notas o solicitar informacion de un alumno, Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). bueno ahora te doy el formato de respuesta: me explicas primero el codigo luego la distribucion de cada clase. y como restriccion evita usar librerias externas y crear clases innecesarias
```
¿Por que?
Por que el formato me ayudara a que se me sea mas facil entender la estructura del codigo ademas de darle un orden
¿Que mejoró?
la presentacion y explicacion del codigo ademas, la ia supo organizar muy bien el codigo.

## Componentes del prompt final
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol        |Sí|
| Instruccion|Sí|
| Contexto   |Sí|
| Ejemplo    |Sí|
| Formato    |Sí|
| Restricciones    |Sí|

## Evaluacion del resultado

| Qué revisar| Cumple (Sí / No)|
|------------|--------------------|
|¿Calcula promedio?|Sí|
|¿Explica el codigo?|Sí|
|¿Usa los estilos solicitados?|Sí|
|¿Evita usar librerias externas y crear clases innecesarias?|Sí|
|¿explica la distribucion del codigo?|Sí|

## Errores que evite

Fui directo con mi prompt, no utilice palabras abiertas como (imagina, Elige, Que te parece)
las restricciones tambien ayudan a evitar estructuras no requeridas o informacion de mas