
![MAEL](https://github.com/Yobeco/MAEL_Gen/blob/main/readme_assets/Logo-MAEL-120.png "Logotipo del proyecto MAEL")

# MAEL Phonofouille

*Una aplicación que pertenece al [__proyecto MAEL__](https://github.com/Yobeco/MAEL_Project)*

Copyright (c) 2022 Yonnel Bécognée

[![Licencia: Libre No Comercial](https://img.shields.io/badge/license-GNU%20GENERAL%20PUBLIC%20LICENSE%20V3-white.svg)](./LICENSE)

[![Python](https://img.shields.io/badge/Python-V3.10%2B-blue?logo=python&logoColor=yellow)](https://www.python.org/)

[![SQLite](https://img.shields.io/badge/SQLite-V3.50.4%2B-003366?logo=sqlite&logoColor=99CCFF)](https://sqlite.org/)

[![Contribuciones bienvenidas](https://img.shields.io/badge/contributions-welcome-009900.svg)](#contributing) [![Apto para principiantes](https://img.shields.io/badge/Beginner%20friendly-FF8000)]()

[![Estado: Activo](https://img.shields.io/badge/status-active-009900.svg)]()

## :fr: [Français](https://github.com/Yobeco/MAEL_Phonofouille/blob/main/README.fr.md) | :es: Español  |  :gb: [English](https://github.com/Yobeco/MAEL_Phonofouille/blob/main/README.md)

---

![](https://github.com/Yobeco/MAEL_Phonofouille/blob/main/readme_assets/Logo-MAEL-120.png)

## A- Descripción :eye:

:computer: **Aplicación de escritorio multiplataforma** (Linux, macOS y Windows) que permite a los docentes encontrar palabras según criterios pedagógicos muy útiles como:

- La presencia y la posición de un sonido dentro de la palabra,  
- La presencia y la posición de letras,  
- El nivel de dificultad de las palabras,  
- El tema,  
- La categoría gramatical de la palabra...

Las **bases de datos** de palabras <img src="https://cdn.simpleicons.org/sqlite/FFFF" width="24" height="24" style="vertical-align: middle;" /> implementadas actualmente son:

- [MiniLex](https://github.com/Yobeco/MAEL_Phrases/blob/main/readme_assets/Minima%20_Lexical_C1fev25.pdf) desarrollado por AMLA Nord  
- [Lexique 3.83](http://www.lexique.org/) <img src="https://cdn.simpleicons.org/creativecommons/FFFF" width="24" height="24" style="vertical-align: middle;" /> BY NC *(¡Muy completa! Y sobre todo: contiene __descripciones fonéticas__)*

**Phonofouille** ya es utilizado tal cual por docentes, pero su verdadero objetivo es ser implementado en JavaScript <img src="https://cdn.simpleicons.org/javascript/FFFF" width="24" height="24" style="vertical-align: middle;" /> dentro de **MAEL Phrase**, con el fin de ayudar a los docentes a crear actividades personalizadas para sus alumnos.

---

## B- Funcionalidades :clipboard:

- Selección de la base de datos.  
- Selección del nivel de dificultad.  
- Selección de los sonidos que deben estar presentes y su posición.  
- Selección de las letras que deben estar presentes y su posición.  
- Selección del número de sílabas.  
- Selección del género (si es pertinente).  
- Selección del tema.  
- Botón para iniciar la búsqueda.  
- Botón para copiar toda la lista de palabras.  
- Doble clic sobre una palabra para copiarla.  
- Clic derecho sobre la lista para reorganizarla o eliminar una fila.  
- Menú de navegación para desplazarse por las páginas de la lista.

---

## C- ¿Cómo usar MAEL Phonofouille? :blush:

El uso es muy sencillo:

1. Elegir la base de datos.  
1. Elegir los criterios de selección de palabras (sin un orden específico).  
1. Iniciar la búsqueda.  
1. Copiar toda la lista o solo una palabra.

---

## D- Principio de funcionamiento :gear:

*(Para ayudar a comprender el código)*

Los distintos widgets de la interfaz generan una [variable de tipo diccionario](/readme_assets/parsed_data_V6.pdf) que contiene los criterios que serán utilizados por **SQLite** <img src="https://cdn.simpleicons.org/sqlite/FFFF" width="24" height="24" style="vertical-align: middle;" /> para realizar la búsqueda. :mag_right:

---

## E- Funcionalidades a desarrollar :rocket:

- Adición de imágenes asociadas a las palabras en la base de datos.  
- Adición de las miniaturas correspondientes en la interfaz del motor de búsqueda de Phonofouille.

Sobre todo, **MAEL Phonofouille** debería ser adaptado a JavaScript <img src="https://cdn.simpleicons.org/javascript/FFFF" width="24" height="24" style="vertical-align: middle;" /> dentro de la interfaz de la plataforma [**MAEL Phrases**](https://github.com/Yobeco/MAEL_Phrase).

### :+1: Ofrece tu ayuda para llevar a cabo esta adaptación. :smile:

---

## F- Participa en el proyecto MAEL :open_hands:

:ring_buoy: Para **obtener ayuda** sobre el uso de **MAEL Phonofouille** o para **participar en el desarrollo** :computer:, escríbeme aquí: