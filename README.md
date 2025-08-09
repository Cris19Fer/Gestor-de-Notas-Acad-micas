# Gestor-de-Notas-Acad-micas
Explicacion de como realizar el gestor de notas
El objetivo principal de un sistema gestor de notas académicas es facilitar el registro, organización, seguimiento y consulta de las calificaciones de los estudiantes dentro de una institución educativa. Este tipo de sistema permite centralizar la información académica en una plataforma digital, asegurando mayor precisión en el manejo de datos, reducción de errores administrativos y acceso rápido a la información tanto para docentes como para estudiantes y personal administrativo. Además, puede incluir funcionalidades como reportes automatizados, análisis del rendimiento académico, y alertas sobre bajo rendimiento o inasistencias.

Este sistema está dirigido principalmente a instituciones educativas de todos los niveles —desde escuelas primarias hasta universidades—, así como a docentes, coordinadores académicos y estudiantes. Cubre necesidades clave como la transparencia en la evaluación, el ahorro de tiempo en procesos manuales, el acceso remoto a información académica, y el fortalecimiento de la comunicación entre los distintos actores del proceso educativo. Al digitalizar estos procesos, se mejora la eficiencia institucional y se fomenta un entorno más organizado y orientado al aprendizaje.

Funcionales:
1.Registrar un nuevo curso y nota: Esta opción permitirá a los docentes o administradores agregar nuevas materias al sistema y asociar calificaciones específicas para cada estudiante. Incluye campos como nombre del curso, código, nombre del estudiante, nota obtenida y fecha de evaluación.

2.Mostrar todas las notas: Esta funcionalidad permitirá consultar el historial completo de calificaciones por estudiante, curso o período académico. Es útil para hacer seguimientos, identificar promedios, y detectar áreas de mejora.

3.Editar o eliminar notas existentes: A través de esta opción, los usuarios con permisos adecuados podrán corregir errores en las calificaciones registradas o eliminar datos obsoletos, garantizando así la integridad y actualización constante del sistema.

4.Generar reportes académicos: Esta función permitirá exportar o visualizar informes detallados del rendimiento académico por estudiante, grupo o asignatura. Los reportes pueden incluir promedios, gráficos de desempeño y listados de estudiantes con bajo rendimiento académico.

NO FUNCIONALES

1. EL PROGRAMA SE VA A USAR EN PAYTON
2. NO VA A USAR LIBRERIAS EXTERNAS
3. VA A FUNCIONAR CON BUCLES
4. CONDICIONALES EN PSEUDOCODIGO


   #Pseudocodigo.txt diseño del menu principal de pseudocodigo

   INICIO

    DEFINIR opcion COMO ENTERO
    opcion ← 0   // Iniciamos con un valor distinto de 6 para entrar al bucle

    MIENTRAS opcion ≠ 6 HACER

        IMPRIMIR "=============================="
        IMPRIMIR "     GESTOR DE NOTAS"
        IMPRIMIR "=============================="
        IMPRIMIR "1. Registrar nuevo curso y nota"
        IMPRIMIR "2. Mostrar todas las notas"
        IMPRIMIR "3. Editar nota existente"
        IMPRIMIR "4. Eliminar nota"
        IMPRIMIR "5. Generar reporte académico"
        IMPRIMIR "6. Salir"
        IMPRIMIR "Seleccione una opción (1-6):"

        LEER opcion

        SI opcion = 1 ENTONCES
            <registrar nuevo curso y nota>
        
        SINO SI opcion = 2 ENTONCES
            <mostrar todas las notas>

        SINO SI opcion = 3 ENTONCES
            <editar nota existente>

        SINO SI opcion = 4 ENTONCES
            <eliminar nota>

        SINO SI opcion = 5 ENTONCES
            <generar reporte académico>

        SINO SI opcion = 6 ENTONCES
            IMPRIMIR "Saliendo del sistema..."

        SINO
            IMPRIMIR "Opción inválida. Intente nuevamente."

        FIN_SI

    FIN_MIENTRAS

FIN
