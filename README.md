# Trabajo académico: registro de nacimientos en C++

Programa de consola para gestionar registros de nacimientos y datos asociados.

## Capacidades técnicas

Estructuras de datos, entrada y salida, manejo de archivos y uso de funciones del entorno POSIX.

## Contenido

- [registroBebes.cpp](registroBebes.cpp): código fuente.
- [registros_bebes.txt](registros_bebes.txt): archivo histórico de registros.

## Uso

El código utiliza cabeceras POSIX como `unistd.h` y `sys/resource.h`. Usar Linux o un entorno compatible, por ejemplo WSL, con g++:

```bash
g++ registroBebes.cpp -o registro
./registro
```

Ejecutar desde la raíz para mantener las rutas de archivos.

## Alcance

Ejercicio de programación de sistemas; no equivale a un sistema registral productivo. Para una demostración, utilizar registros ficticios.

El repositorio conserva un ejercicio académico. La documentación describe el uso previsto; no certifica una ejecución reciente ni resultados de rendimiento.
