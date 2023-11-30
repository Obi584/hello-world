# TC1033_301_NOV30_23
# Alberto Palomino Carvajal
# Carrera - IDM

## Aprendiendo MARKDOWN

[Markdown](https://www.markdownguide.org/cheat-sheet/)

**Aprendiendo Markdown**

*Itálico*

# Lista ordenada
1. Tacos de Barbacoa
2. Tacos de Chicharrón en tortilla de harina
3. Chilaquiles
4. Torta de cochinita pibil
5. Tacos de lechón
6. Torta ahogada
7. Tacos Pioneros
8. Los Chelos
9. La Posta
10. Las Dinoquesadillas
11. Memela de chinameca
12. Pescadillas
13. Ceviche mixto

# Lista desordenada
- Estudiar c++
- Otra vez
- Otra vez pero con el nombre de la clase
- Aplicar los conocimientos aprendidos
- muchas horas ;-;

# Código

```cpp
//
// Created by Alberto Palomino on 23/11/23.
//

#include "Empleado.h"

// Método consstructor
Empleado::Empleado() {
    Fecha _cumple;
    nombre = "Alberto";
    sueldo = 20000.00;
    _cumple.setDia(1);
    _cumple.setMes(9);
    cumple = _cumple;
}


// Método destructor
Empleado::~Empleado() {
    cout << "Se destruyó un empleado" << endl;
}


// Métodos de acceso
string Empleado::getNombre() {
    return nombre;
}

float Empleado::getSueldo() {
    return sueldo;
}

Fecha Empleado::getFecha() {
    return cumple;
}


// Métodos de modificación
void Empleado::setNombre(string _nombre) {
    nombre = _nombre;
}

void Empleado::setSueldo(float _sueldo) {
    sueldo = _sueldo;
}

void Empleado::setFecha(Fecha _cumple) {
    cumple = _cumple;
}


// Otros
void Empleado::subeSueldo(float incremento) {
    if (incremento >= 1 && incremento <= 10) {
        sueldo *= (100 + incremento) / 100;
    }
    else {
        cout << "Porcentaje inválido" << endl;
    }
}
```

| Mes | Actividad |
| -------- | -------- |
| Diciembre | Programar C++ Apuntes 1 |
| Enero | Programar C++ Apuntes 2 |
| Febrero | Programar C++ Presentación 1 |
| Marzo | Programar C++ Presentación 2 |
| Abril | Programar C++ Presentación 3 |
| Mayo | Programar C++ Presentación 4 |




![Mono de nieve](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQa0gENC085JCjcLatjyRm2ivSITgKViFVB_Q&usqp=CAU)

HELLO WORLD
