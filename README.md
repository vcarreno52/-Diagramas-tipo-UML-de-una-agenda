# -Diagramas-tipo-UML-de-una-agenda
 diagramas tipo UML.
El diagrama busca capturar una situación común en la vida académica: Cómo un estudiante que organiza su tiempo y actividades mediante una agenda que incluye tareas, eventos y evaluaciones. Los conceptos de herencia y composición reflejan cómo estas actividades están jerárquicamente relacionadas y forman parte de un sistema más amplio que puede extenderse o adaptarse según las necesidades del usuario.
![Descripción de la imagen](https://github.com/vcarreno52/-Diagramas-tipo-UML-de-una-agenda/blob/main/Untitled%20diagram-2024-11-18-003233.png?raw=true)

# Herencia en el modelo
La clase Asignación se presenta como una superclase que abstrae características comunes de diferentes tipos de asignaciones. Mediante el mecanismo de herencia, clases más específicas como Presentación, Evento, Tarea y Evaluación extienden las propiedades y comportamientos generales de Asignación.

# Composición en el modelo 
la relación de composición entre Agenda y Asignación indica que la agenda está formada por asignaciones que registran las actividades planificadas. Cada asignación corresponde a una categoría específica (como presentación, tarea, evento o evaluación) que fue heredada de la clase Asignación.



