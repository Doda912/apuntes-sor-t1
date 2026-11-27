
- **Alumno:** Dodanis Gonzalez
- **Bloque:** B0 — Prerrequisitos
- **Fase / ejercicio:** Fase 0.1
- **Fecha de inicio:** 27/11/2026
- **Fecha de entrega:** 27/11/2026

---

## 🎯 Qué se pedía

Actualizar el repositorio del Bloque 1 para tener la nueva organización del material y las prácticas. Para ello había que eliminar el repositorio antiguo, crear uno nuevo desde la plantilla del profesor y clonarlo en nuestro ordenador.

## ⌨️ Comandos y pasos importantes

- `cd ~` — Ir a la carpeta principal del usuario.
    
- `git clone git@github.com:Doda912/bloque-1-entorno.git B1_Entorno` — Clonar el repositorio de GitHub indicando el nombre de la carpeta local.
    
- `ls` — Mostrar los archivos y carpetas del directorio actual.
    
- `ls -1` — Mostrar el contenido en una lista.
    
- `git log --oneline -1` — Comprobar el último commit del repositorio.
    

## 🛠️ Qué he hecho

1. Comprobé que no tenía apuntes personales importantes dentro del repositorio antiguo.
    
2. Eliminé el repositorio antiguo desde GitHub, entrando en Settings y después en Danger Zone.
    
3. Borré la carpeta local antigua llamada `B1_Entorno`.
    
4. Creé un repositorio nuevo desde la plantilla del profesor utilizando **Use this template**.
    
5. Le puse el nombre `bloque-1-entorno` y lo configuré como público.
    
6. Abrí Git Bash y ejecuté el comando `git clone` para descargar el nuevo repositorio con el nombre local `B1_Entorno`.
    
7. Finalmente, utilicé `ls` y `git log --oneline -1` para comprobar que se había descargado correctamente.
    

## 🚩 Qué me ha fallado y cómo lo he resuelto

Nada. La clonación del repositorio se realizó correctamente y pude comprobar que aparecían las carpetas y los archivos nuevos.

## 🤔 Respuestas a las preguntas

**Pregunta 1.** ¿Qué tres carpetas tiene el repositorio nuevo y qué guarda cada una?

-B1_Lab_Comun,B1_Lab_HyperV y B1_Lab_VirtualBox, cada una guarda practicas que hacer.

**Pregunta 2.** ¿Por qué el segundo argumento de git clone es obligatorio? ¿Qué habría pasado sin él?

-directamente el segundo argumento permite copiar el repositorio.

**Pregunta 3.** ¿Qué se puede deshacer: borrar la carpeta local o borrar el repositorio de GitHub?

-La carpeta local.

**Pregunta 4.** ¿Con qué comando compruebas que estás en la versión nueva? ¿Qué tiene que decir la respuesta?

-ls y git log --oneline -1,ls muestra las carpetas nuevas y git log --oneline -1 muestra:

fb5f6d9 (HEAD -> main, origin/main, origin/HEAD) Initial commit.


**Pregunta 5.** ¿Qué es Use this template y en qué se diferencia de un fork?

-Use this template crea un repositorio totalmente nuevo  y fork crea un vinculo.

**Pregunta 6.** ¿Había algo tuyo en el repositorio viejo? Si lo había, ¿dónde lo guardaste?

-no no habia nada mio.

## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/FNu9peTBlDA
- **Playlist:** B0_Prerrequisitos


## 💭 Dudas / a repasar

- Repasar las diferencias entre crear un repositorio desde una plantilla y hacer un fork.
    
- Entender mejor cómo funciona el comando `git clone` y la importancia de indicar el nombre de la carpeta local.
    
- Comprobar que el último commit coincide con la fecha de actualización indicada en las instrucciones.
