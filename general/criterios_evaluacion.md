---
title: Criterios de evaluación PVLI
---

Dado el carácter práctico de la asignatura de *Programación de Videojuegos en
Lenguajes Interpretados*, la evaluación se llevará a cabo mediante entregas
prácticas (código) que serán entregadas a través del Campus Virtual en las
fechas que se vaya señalando.

Para la evaluación, el alumno realizará y entregará un proyecto, y realizará un
examen final de la asignatura. Además, en la
evaluación habrá una presentación de proyectos, y tanto la asistencia como la
contribución durante el desarrollo de la asignatura serán tenidas en cuenta.

La evaluación en PVLI se hará en función de la fórmula @eq:formulaeval:

```include
general/auxiliary/formula_evaluacion.md
```

**El proyecto tiene que ser aceptable globalmente para aprobar**. El juego tiene que funcionar correctamente y cumplir los requsitos, independientemente de la posible nota numérica, para ser apto. Es decir, la nota se pondrá a partir de un proyecto jugable, aceptable visualmente, sin errores graves de jugabilidad y *terminado*. Si algún requisito básico no se cumple, el proyecto estará suspenso con un 0.

La puntuación de cada parte se hará de forma objetiva e informada, pero estará a discreción del criterio del equipo docente según los estándares exigidos en la asignatura

Todas las notas serán mantenidas hasta el final de la evaluación. Es decir, si
se suspende en la convocatoria de febrero, todo aquello que haya tenido más de
un 5 será mantenido como parte de la nota final, siempre y cuando no haya una
entrega adicional posterior, en cuyo caso se corregirá esta última y *se
mantendrá la última nota, incluso si esta es más baja que la primera*.

- Si una entrega (proyecto o examen) no carga correctamente o no se puede
  ejecutar completamente **sin errores**, la entrega se considerará suspensa con un $0$.
- Si no se siguen **exactamente** los criterios de envío (número de archivos,
  formato de envío, carpetas, tipo de compresión, nombres de archivos), la
  entrega estará suspensa con un $0$.

Si el proyecto o el examen final tienen, cualquiera de ellos, menos de un $5,0$, la
evaluación se considerará suspensa.

## Convocatoria extraordinaria

Los criterios de evaluación en convocatoria ordinaria y extraordinaria son los
 mismos (es decir, hay que entregar también un proyecto y hacer un examen en la 
 convocatoria extraordinaria). El proyecto puede ser realizado de forma individual
  o por grupos, en cuyo caso hay que avisar al equipo docente con la formación del
   grupo, y todos los miembros deben presentarse a la convocatoria extraordinaria.

La parte de evaluación continua que se hace durante el curso se conserva para la
 convocatoria extraordinaria. Si no se ha realizado la contribución de la evaluación
  continua, esta se considera perdida para la convocatoria extraordinaria (esto incluye, por ejemplo, las presentaciones).

## Copias

**Copiar cualquier entrega no está permitido y supondrá una falta grave,
acarreando el suspenso de la convocatoria actual**. Se llevará a cabo un examen
exhaustivo de copias.

## Grupos

La información sobre los grupos puede consultarse en el [documento de grupos](grupos.html).

## Asistencia

La asistencia es obligatoria. El curso es
presencial, y está diseñado como tal. La intención es que el trabajo en clase
sea suficiente para que, junto con la realización de los ejercicios
y prácticas, se adquiera todo el conocimiento necesario para la asignatura.


## Entregas

Todo el material entregado debe estar alojado en un repositorio *git*
a elección de los alumnos. Este repositorio puede ser público o privado, pero
se tiene que asegurar el acceso a los profesores.

Por ejemplo, si el repositorio es privado, se tiene que dar de alta el usuario
de los profesores.

### Cómo entregar

Las entregas consistirán en un archivo comprimido con la versión del repositorio que se envía, y un texto corto con:

- Un enlace al repositorio (commit **exacto**)
- Los miembros del equipo
- Lo que ha hecho cada miembro
- Una descripción de todo lo *relevante* (por favor, sólo lo *relevante*)
- En el repositorio git todo estará en [UTF-8](http://stackoverflow.com/questions/2241348/what-is-unicode-utf-8-utf-16), a no ser que haya una buena razón (que habrá que explicar en el texto)

Por ejemplo:

    entrega: Versión 2 del proyecto
    miembros: Alan Turing y Alonzo Church
    repo: github.com/lambda/pr4
    commit: a0bcf435d55135bf218a504cd8e45fd85b845de5

    Alonzo cree que todo es lambda y ha escrito mucho sobre ello.

    Alan, por su parte, ha creado una máquina teórica.

    Nos hemos dado cuenta de que que ambas soluciones son equivalentes.
    Se puede probar con el script:

    $ node entscheidungsproblem.js

    Y se verá que sale el mismo resultado.
