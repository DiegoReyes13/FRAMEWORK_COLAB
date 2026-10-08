Matriz de trazabilidad — Apunta (Prototipo Front-End)

Guia
C creada — Existe el HTML/CSS y se puede ver el requerimiento representado
P Parcial — El elemento aparece en una vista existente, pero de forma incompleta o sin una vista dedicada propia.
NC No creada — Todavía no existe ninguna vista para este requerimiento.

Requerimientos funcionales
| ID | Requerimiento | Vista (archivo) | Estado 
| RF-01 | El sistema deberá permitir a un estudiante registrarse usando su correo institucional. | — | NC |
| RF-02 | El sistema deberá permitir iniciar sesión con correo y contraseña. | login.html | C (vista) | 
| RF-03 | El sistema deberá permitir subir material de estudio (PDF, imagen o documento) clasificado por materia, profesor, tema y tipo. | — | NC |
| RF-04 | El sistema deberá permitir buscar y filtrar material por materia, profesor y palabra clave. | inicio.html (barra de búsqueda visible) | P 
| RF-05 | El sistema deberá permitir calificar de 1 a 5 estrellas y comentar el material consultado. | — | NC
| RF-06 | El sistema deberá permitir reportar material inapropiado o con posibles derechos de autor. | — | NC 
| RF-07 | El sistema deberá permitir que un profesor marque un material como "verificado oficialmente". | inicio.html, minijuegos.html (insignia "Verificado" visible en las tarjetas) | C (vista) 
| RF-08 | El sistema deberá ofrecer minijuegos educativos (trivia, flashcards) asociados a una materia. | minijuegos.html | C (vista) 
| RF-09 | El sistema deberá permitir crear y consultar un calendario personal de exámenes y tareas. | inicio.html (panel "Próximos exámenes") | C (vista) 
| RF-10 | El sistema deberá enviar notificaciones cuando se suba material nuevo en una materia que el usuario sigue. | — | NC

________

Requerimientos no funcionales
| ID | Categoría | Requerimiento no funcional | Estado en el prototipo |
| RNF-01 | Seguridad | Las contraseñas deberán almacenarse cifradas y el acceso a cada módulo deberá restringirse según el rol del usuario. | P 
| RNF-02 | Usabilidad | Un usuario nuevo deberá poder encontrar y descargar un material de manera accesible y rápida. | P 
| RNF-03 | Responsividad | La interfaz deberá adaptarse correctamente a pantallas de celular, tablet y escritorio. | NC 
| RNF-04 | Rendimiento | Las búsquedas de material deberán mostrar resultados de manera rápida. | NC No aplica todavía: no hay buscador funcional
| RNF-05 | Disponibilidad | La plataforma deberá mantener un alto porcentaje de tiempo de actividad, con respaldos automáticos de la base de datos. | No aplica al prototipo front-end (requiere backend e infraestructura). |
| RNF-06 | Escalabilidad | La arquitectura deberá soportar el crecimiento de usuarios registrados sin comprometer el rendimiento. | No aplica al prototipo front-end (requiere backend e infraestructura). |