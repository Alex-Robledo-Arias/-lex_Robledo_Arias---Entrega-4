# Alex_Robledo_Arias---Entrega-4
Juego de colocación de piezas en el ordenador. Entrega Control de versiones GitHub Infomática básica

El juego se puede jugar en: https://alexrobledoarias.itch.io/entrega-3

Instrucciones para crear el README.md
Opción 1: Crear el README.md desde tu ordenador
1. Abrir la carpeta del proyecto
o Ve a la carpeta local donde tienes tu juego guardado como “carpeta de proyecto”
de Construct 3.
2. Crear el archivo README.md
o Clic derecho dentro de la carpeta → Nuevo → Documento de texto.
o Nombra el archivo exactamente: README.md (borra la extensión .txt si aparece).
o Asegúrate de que el nombre final sea README.md.
3. Escribir la descripción del juego
o Abre README.md con un editor de texto (Bloc de notas, VS Code).
o Escribe el contenido. Puedes empezar con este mínimo:
 Título del juego.
 Breve descripción.
 Componentes del ordenador usados (en español).
 Cómo jugar.
 Créditos y licencia (CC-BY-NC-SA 4.0).
4. Guardar el archivo
o Guarda los cambios y cierra el editor.
5. Registrar el cambio con GitHub Desktop (commit)
o Abre GitHub Desktop.
o En la lista de cambios, verifica que README.md aparece marcado.
o En el cuadro de “Summary”, escribe:
 “Añadir README.md con descripción del juego Monta un PC”
o Pulsa Commit to main.
6. Subir el cambio a GitHub (push)
o Pulsa Push origin.
o Espera a que termine la subida.
7. Comprobar en GitHub
o Abre tu repositorio en la web (botón “View on GitHub”).
o Recarga la página: el contenido del README.md debe aparecer en la portada del
repositorio.
Opción 2: Crear o editar el README.md directamente en GitHub (web)
1. Entrar en tu repositorio
o Ve a github.com e inicia sesión.
o Abre el repositorio de tu juego.
2. Crear un nuevo archivo
o Haz clic en Add file (arriba a la derecha de la lista de archivos).
o Selecciona Create new file.
3. Nombrar el archivo
o En el campo de nombre escribe: README.md.
4. Redactar el contenido
o En el área de texto, pega o escribe la descripción del juego:
 Título, breve descripción, componentes, cómo jugar, créditos y licencia.
o Si quieres, usa el ejemplo que ya tienes preparado.
5. Registrar el cambio (commit en la web)
o En la sección “Commit new file”, escribe el mensaje:
 “Añadir README.md con descripción del juego Monta un PC”
o Selecciona Commit directly to the main branch.
6. Crear el archivo
o Haz clic en Commit new file.
7. Comprobar el resultado
o Vuelve a la portada del repositorio.
o Verás el README.md mostrando el texto con formato (títulos, listas).
¿Qué opción usar?
• GitHub Desktop (Opción 1):
o Úsala si ya trabajas con archivos locales y quieres practicar el flujo completo (crear,
editar, commit, push).
• GitHub web (Opción 2):
o Ideal para empezar rápido, sin tocar archivos locales. Muy visual y directo.
Sugerencias de contenido para tu README.md
• Título: “Monta un PC – Videojuego Educativo”
• Descripción breve: objetivo del juego y contexto de la asignatura.
• Componentes del ordenador (en español):
o Caja ATX (torre), Placa base, Procesador (CPU), Disipador de CPU, Memoria RAM,
Tarjeta gráfica, Fuente de alimentación (PSU).
• Cómo jugar: pasos para desbloquear, arrastrar y colocar componentes; condición de
victoria.
• Objetivos educativos: qué aprende el jugador.
• Créditos y licencia: bloque final con CC-BY-NC-SA 4.0.
Ejemplo de README.md
# Monta un PC – Videojuego Educativo
## Descripción
Este proyecto es un videojuego educativo creado en **Construct 3** para la asignatura de
**Informática Básica**.
El objetivo del juego es que el jugador aprenda a identificar y colocar correctamente los
componentes principales de un ordenador dentro de una torre ATX.
El juego incluye:
- Menú de bienvenida con botón para iniciar la partida.
- Mecánica de arrastrar y soltar componentes.
- Preguntas con entrada de texto: el jugador debe escribir el nombre correcto del componente
para desbloquearlo.
- Colocación de los componentes en la torre mediante objetos invisibles y comportamiento
“Pegado”.
- Sistema de puntuación que aumenta cada vez que el jugador acierta.
- Menú final con mensaje de victoria y botón para reiniciar el juego.
## Componentes del ordenador utilizados
- **Caja ATX** (torre del ordenador)
- **Placa base**
- **Procesador (CPU)**
- **Disipador de CPU** (ventilador o cooler)
- **Memoria RAM**
- **Tarjeta gráfica**
- **Fuente de alimentación (PSU)**
## Mecánicas principales
1. **Importar sprites** de los componentes y añadir referencia al ratón para poder
interactuar.
2. Asignar comportamiento **Arrastrar y soltar** a los objetos, inicialmente deshabilitado.
3. Añadir comportamiento **Pegado** para que los componentes se fijen a la torre.
4. Crear **entradas de texto** para que el jugador escriba el nombre del componente.
5. Programar la condición:
- Si el texto introducido coincide con el nombre correcto → habilitar arrastrar y soltar.
6. Colocar **objetos invisibles** en la torre como puntos de referencia.
- Cuando el componente se superpone al objeto invisible → se pega a la torre.
7. Crear una **variable global de puntuación**.
- Cada acierto suma +1.
- Se muestra en pantalla mediante un objeto de texto.
8. Al colocar todos los componentes correctamente → aparece mensaje de victoria y menú
final.
## Objetivos educativos
- Aprender los nombres y funciones de los componentes básicos de hardware.
- Relacionar teoría de Informática Básica con práctica interactiva.
- Desarrollar habilidades de lógica y asociación mediante mecánicas de juego.
## Cómo jugar
1. Escribe el nombre correcto del componente en la caja de texto.
2. Si aciertas, podrás arrastrar y soltar el componente.
3. Colócalo en el lugar correcto de la torre.
4. Repite hasta completar los 7 componentes.
5. ¡Gana la partida cuando todos estén colocados correctamente!
## Créditos
- Autor: Apellido1 Apellido2 Nombre
- Asignatura: Informática Básica – Práctica 4
- Grado: Diseño de Videojuegos
- Universidad: Universidad de Burgos
- Curso académico: 2025 - 2026
- Herramienta: Construct 3
- Control de versiones: GitHub Desktop
## Licencia
Este proyecto está bajo la licencia **Creative Commons Attribution-NonCommercial-
ShareAlike 4.0 (CC-BY-NC-SA-4.0)**.
Esto significa que puedes compartir y adaptar el contenido **solo para fines no comerciales**,
siempre que: se dé crédito al autor original y las obras derivadas se distribuyan con la misma
licencia.
