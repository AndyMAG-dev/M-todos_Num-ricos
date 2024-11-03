### Lista Completa de Funciones en el Módulo Sympy

- Símbolos Básicos

   - **Variables**: Puedes crear variables simbólicas usando `sympy.symbols('nombre_variable')`.
   - **Constantes**: `sympy.pi` para π, `sympy.E` para \(e\), `sympy.I` para \(i\).

- Operaciones Matemáticas

   - **Suma y Resta**: `+`, `-`
   - **Multiplicación y División**: `*`, `/`
   - **Potenciación**: `**`
   - **Raíz cuadrada**: `sqrt()`
   - **Logaritmos**: `log()`, `log10()`, `log2()`
   - **Funciones trigonométricas**: `sin()`, `cos()`, `tan()`, `asin()`, `acos()`, `atan()`
   - **Funciones hiperbólicas**: `sinh()`, `cosh()`, `tanh()`, `asinh()`, `acosh()`, `atanh()`
   - **Funciones exponenciales**: `exp()`, `E**x` para \(e^x\)

- Funciones Especiales

   - **Factorial**: `factorial()`
   - **Permutaciones y combinaciones**: `perm()`, `comb()`
   - **Series Taylor**: `taylor_series()`
   - **Serie de Fourier**: `fourier_series()`

- Operaciones de Álgebra Lineal

   - **Matrices**: `Matrix()`, operaciones como suma, multiplicación, transposición, etc.
   - **Vectores**: `Vector()`, operaciones similares a las matrices.
   - **Determinantes y trazas**: `det()`, `trace()`
   - **Espacios vectoriales**: `VectorSpace()`

- Cálculo Diferencial e Integral

   - **Derivadas**: `diff()`
   - **Integrales indefinidas**: `integrate()`
   - **Integrales definidas**: `integrate()`, especificando límites de integración.
   - **Series de Taylor**: `taylor_series()`

- Resolución de Ecuaciones

   - **Resolución de ecuaciones**: `solve()`
   - **Simplificación de ecuaciones**: `simplify()`, `expand()`, `cancel()`
