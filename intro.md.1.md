# Notas en formato Zettelkasten

```
id: "{{date: 20250060528}}"
title: "Suma de Vectores"
created: "{{date: 2025-06-05}}"
tags: [#computacion, #zettelkasten]
type: permanent # fleeting | literature | permanent
area: [] # ejemplo: [algoritmos, estructuras-de-datos]
related: []
```

# Titulo: Suma de Vectores

## 💡 Idea principal

> La suma de vectores es una operación que consiste en sumar las componentes correspondientes de dos o más vectores. Esta operación es fundamental en el álgebra lineal y tiene aplicaciones en diversas áreas, como la física, la informática y la economía.

---

## 🔍 Explicación detallada

La suma de vectores se realiza sumando las componentes correspondientes de cada vector. Si tenemos dos vectores $\mathbf{a}$ y $\mathbf{b}$ de la misma dimensión, su suma $\mathbf{c} = \mathbf{a} + \mathbf{b}$ se define como:
$$
\mathbf{c} = \begin{bmatrix}
    a_1 + b_1 \\
    a_2 + b_2 \\
    \vdots \\
    a_n + b_n
\end{bmatrix}
$$

Esta operación es conmutativa y asociativa, lo que significa que el orden en que se suman los vectores no afecta el resultado.

---

## 🧪 Ejemplo o implementación matemática

$$
\text{Vector } \mathbf{a} = \begin{bmatrix}
    a_1 \\
    a_2 \\
    \vdots \\
    a_n
\end{bmatrix}, \quad
\text{Vector } \mathbf{b} = \begin{bmatrix}
    b_1 \\
    b_2 \\
    \vdots \\
    b_n
\end{bmatrix} \quad \Rightarrow \quad
\text{Suma } \mathbf{c} = \mathbf{a} + \mathbf{b} = \begin{bmatrix}
    a_1 + b_1 \\
    a_2 + b_2 \\
    \vdots \\
    a_n + b_n
\end{bmatrix}
$$

Un ejemplo de suma de dos vectores $\mathbf{a}$ y $\mathbf{b}$ de dimensión $n$, donde cada componente se suma individualmente para obtener el vector resultante $\mathbf{c}$.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMjgxMjMyMDgsLTIwODg3NDY2MTJdfQ
==
-->