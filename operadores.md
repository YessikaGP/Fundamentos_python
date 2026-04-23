# Operadores Matemáticos en Python

---

## Ejercicio 1

**Expresión:** `5 + 3 * 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Suma (`+`)
   - Multiplicación (`*`)

   La multiplicación tiene mayor prioridad que la suma.

2. Realizar la multiplicación primero:
   - `3 * 2 = 6`

3. Realizar la suma:
   - `5 + 6 = 11`

**Resultado final:**
```python
11
```

---

## Ejercicio 2

**Expresión:** `8 / 2 + 4 * 3`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - División (`/`)
   - Multiplicación (`*`)
   - Suma (`+`)

   División y multiplicación tienen mayor prioridad que la suma. Se evalúan de izquierda a derecha.

2. Realizar la división primero (va antes que `*` por posición):
   - `8 / 2 = 4.0`

3. Realizar la multiplicación:
   - `4 * 3 = 12`

4. Realizar la suma:
   - `4.0 + 12 = 16.0`

**Resultado final:**
```python
16.0
```

> **Nota:** La división `/` siempre devuelve un flotante en Python.

---

## Ejercicio 3

**Expresión:** `(7 + 3) * 2 - 5`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Multiplicación (`*`)
   - Resta (`-`)

   Los paréntesis tienen la mayor prioridad.

2. Resolver el paréntesis primero:
   - `7 + 3 = 10`

3. Realizar la multiplicación:
   - `10 * 2 = 20`

4. Realizar la resta:
   - `20 - 5 = 15`

**Resultado final:**
```python
15
```

---

## Ejercicio 4

**Expresión:** `10 - 4 + 2 * 3`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Multiplicación (`*`)
   - Resta (`-`) y Suma (`+`)

   La multiplicación tiene mayor prioridad. Resta y suma tienen igual prioridad y se evalúan de izquierda a derecha.

2. Realizar la multiplicación primero:
   - `2 * 3 = 6`

3. Resolver de izquierda a derecha:
   - `10 - 4 = 6`
   - `6 + 6 = 12`

**Resultado final:**
```python
12
```

---

## Ejercicio 5

**Expresión:** `(10 / 2) * (3 + 2) - 4`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Multiplicación (`*`)
   - Resta (`-`)

2. Resolver los paréntesis de izquierda a derecha:
   - `10 / 2 = 5.0`
   - `3 + 2 = 5`

3. Realizar la multiplicación:
   - `5.0 * 5 = 25.0`

4. Realizar la resta:
   - `25.0 - 4 = 21.0`

**Resultado final:**
```python
21.0
```

---

## Ejercicio 6

**Expresión:** `2 + 3 * (4 - 1)`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Multiplicación (`*`)
   - Suma (`+`)

2. Resolver el paréntesis primero:
   - `4 - 1 = 3`

3. Realizar la multiplicación:
   - `3 * 3 = 9`

4. Realizar la suma:
   - `2 + 9 = 11`

**Resultado final:**
```python
11
```

---

## Ejercicio 7

**Expresión:** `5 * 2 ** 3`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Potencia (`**`)
   - Multiplicación (`*`)

   La potencia tiene mayor prioridad que la multiplicación.

2. Resolver la potencia primero:
   - `2 ** 3 = 8`

3. Realizar la multiplicación:
   - `5 * 8 = 40`

**Resultado final:**
```python
40
```

---

## Ejercicio 8

**Expresión:** `6 + 4 / 2 ** 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Potencia (`**`) — mayor prioridad
   - División (`/`)
   - Suma (`+`)

2. Resolver la potencia primero:
   - `2 ** 2 = 4`

3. Realizar la división:
   - `4 / 4 = 1.0`

4. Realizar la suma:
   - `6 + 1.0 = 7.0`

**Resultado final:**
```python
7.0
```

---

## Ejercicio 9

**Expresión:** `10 % 3 + 2 * 5`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Módulo (`%`) y Multiplicación (`*`) — misma prioridad, se evalúan de izquierda a derecha
   - Suma (`+`)

2. Resolver el módulo primero (va antes por posición):
   - `10 % 3 = 1` (el residuo de dividir 10 entre 3)

3. Realizar la multiplicación:
   - `2 * 5 = 10`

4. Realizar la suma:
   - `1 + 10 = 11`

**Resultado final:**
```python
11
```

---

## Ejercicio 10

**Expresión:** `(8 + 2) * 3 ** 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Potencia (`**`)
   - Multiplicación (`*`)

2. Resolver el paréntesis primero:
   - `8 + 2 = 10`

3. Resolver la potencia:
   - `3 ** 2 = 9`

4. Realizar la multiplicación:
   - `10 * 9 = 90`

**Resultado final:**
```python
90
```

---

## Ejercicio 11

**Expresión:** `7 + 2 * (3 + 5) / 4`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Multiplicación (`*`) y División (`/`) — misma prioridad, izquierda a derecha
   - Suma (`+`)

2. Resolver el paréntesis:
   - `3 + 5 = 8`

3. Resolver multiplicación y división de izquierda a derecha:
   - `2 * 8 = 16`
   - `16 / 4 = 4.0`

4. Realizar la suma:
   - `7 + 4.0 = 11.0`

**Resultado final:**
```python
11.0
```

---

## Ejercicio 12

**Expresión:** `2 ** 3 * 4 / 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Potencia (`**`) — mayor prioridad
   - Multiplicación (`*`) y División (`/`) — misma prioridad, izquierda a derecha

2. Resolver la potencia:
   - `2 ** 3 = 8`

3. Resolver multiplicación y división de izquierda a derecha:
   - `8 * 4 = 32`
   - `32 / 2 = 16.0`

**Resultado final:**
```python
16.0
```

---

## Ejercicio 13

**Expresión:** `9 - 6 + 3 ** 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Potencia (`**`) — mayor prioridad
   - Resta (`-`) y Suma (`+`) — misma prioridad, izquierda a derecha

2. Resolver la potencia:
   - `3 ** 2 = 9`

3. Resolver resta y suma de izquierda a derecha:
   - `9 - 6 = 3`
   - `3 + 9 = 12`

**Resultado final:**
```python
12
```

---

## Ejercicio 14

**Expresión:** `(7 - 2) * 5 + 3 ** 2`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Paréntesis `()`
   - Potencia (`**`)
   - Multiplicación (`*`)
   - Suma (`+`)

2. Resolver el paréntesis:
   - `7 - 2 = 5`

3. Resolver la potencia:
   - `3 ** 2 = 9`

4. Realizar la multiplicación:
   - `5 * 5 = 25`

5. Realizar la suma:
   - `25 + 9 = 34`

**Resultado final:**
```python
34
```

---

## Ejercicio 15

**Expresión:** `4 * 2 ** 3 / 8 + 1`

**Pregunta:** ¿Cuál es el resultado? ¿Por qué?

**Paso a paso:**

1. Identificar las operaciones y su prioridad:
   - Potencia (`**`) — mayor prioridad
   - Multiplicación (`*`) y División (`/`) — misma prioridad, izquierda a derecha
   - Suma (`+`)

2. Resolver la potencia:
   - `2 ** 3 = 8`

3. Resolver multiplicación y división de izquierda a derecha:
   - `4 * 8 = 32`
   - `32 / 8 = 4.0`

4. Realizar la suma:
   - `4.0 + 1 = 5.0`

**Resultado final:**
```python
5.0
```

---

## Tabla de Precedencia de Operadores (de mayor a menor)

| Prioridad | Operador | Descripción |
|-----------|----------|-------------|
| 1 | `()` | Paréntesis |
| 2 | `**` | Potencia |
| 3 | `*`, `/`, `//`, `%` | Multiplicación, División, División entera, Módulo |
| 4 | `+`, `-` | Suma, Resta |
