# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts. Herramienta de IA usada: (escribe aqui cual usaste) ## Ejercicio 2: Tokens y ventana de contexto

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. |35|8|
| The students program in Java. |30 |6|
| desafortunadamente |18|4|

Al realizar el ejercicio 2 oberseve que chat-gpt guarda memoria entre chats, pero en una version anterior no lo hacia, que pasa si no guarda memoria?. me pregunta sobre mas detalles.

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 |100%| BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec|
| 0.5 |65.3%|BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 1 |44.5% |BiblioTec, LibroYa, PrestaLibro, LibroYa, LibroYa|
| 1.8 |32.2%|LectoGo, BiblioTec, BiblioTec, LibroYa, LibroYa|

Al subir la temperatura empienzan a salir mas nombres, que no se vieron antes. El simulador no dara otra palabra ya que tiene una cantidad limitada de palabras(BilblioTec PrestaLibro, LibroYa,LectoGo, PaginaLibre, NubeDeTinta)
## Ejercicio 4: Prompt vago vs estructurado 

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema    |si|si|
| Menciona a los usuarios principales |no|si|
| Tiene exactamente 3 funcionalidades |no|si|
| Esta en 3 parrafos                  |no|si|
| Lo usaria en un informe real        |no|si|

## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol        |La respuesta es mas detallada ofreciendo una estructura |
| Instruccion|Creo un archivo java sencillo |
| Contexto   |Creo un programa en java dedicado a gestionar productos de una tienda |
| Ejemplo    |Con el ejemplo, realiza y acopla el ejemplo al codigo |
| Formato    |Realiza la respuesta con cuerdo al formato que se le asigno |
## Ejercicio 6: Del prompt basico al profesional

| Qué revisar| Cumple (Sí / No)|
|------------|--------------------|
|¿Está escrito en Java y usa Swing?|Sí|
| ¿Pide correo y contraseña?|Sí|
|¿Explica el funcionamiento antes o después del código?|Sí|
|¿El código está organizado en clases?|Sí|
|¿Valida los datos que ingresa el usuario?|Sí|
### Prompt
```text
Actua como desarrollador Java. Crea un ejemplo de login para una aplicacion de escritorio utilizando Swing. El usuario debe ingresar correo y contrasena. Explica brevemente el funcionamiento y presenta el codigo organizado por clases.

Mejora el codigo anterior con estas restricciones: no uses librerias externas, valida que el correo contenga @ y que la contrasena tenga al menos 8 caracteres, y muestra los mensajes con JOptionPane.
```
