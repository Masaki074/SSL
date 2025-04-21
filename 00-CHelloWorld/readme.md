# "Hello, World!" en C

### Objetivos
- Demostrar capacidad para editar, compilar, y ejecutar programas C mediante el desarrollo de un programa simple
- Tener un primer contacto con las herramientas necesarias para abordar la resolución de los trabajos posteriores
- Creación de repositorio personal git
- Armado de equipo de trabajo

### Tareas

- **Compilador seleccionado: GCC**

- **Versión del compilador: 14.2.0**
     
      gcc --version

- **Versión estándar del compilador**

      $ echo | gcc -dM -E -x c - | grep __STDC_VERSION__
      #define __STDC_VERSION__ 201710L


- **Versión de C usado: C23**

      gcc -std=c23 -o hello.exe hello.c

- **Generar .txt output**

      ./hello > output.txt


