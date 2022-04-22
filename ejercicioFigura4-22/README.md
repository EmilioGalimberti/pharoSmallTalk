packages: EjercicioFigura.st

playground:

|r t c g|
r:= Rectangulo  new.
r ladoMenor: 5.
r ladoMayor: 5.
Transcript show: r tipoRectangulo; cr .
Transcript show: 'Area del rectangulo: '; cr.
Transcript show: r area; cr.
Transcript show: 'Perimetro del rectangulo: '; cr.
Transcript show: r perimetro; cr.

c:= Circulo new.
c radio: 5.
Transcript show: 'Area del circulo: '; cr.
Transcript show: c area; cr.
Transcript show: 'Perimetro del circulo: '; cr.
Transcript show: c perimetro; cr.

t:= Triangulo new.
t base: 5.
t catetoB: 5.
t catetoA: 5.
Transcript show: t tipoTriangulo ;cr.
Transcript show: 'Area del triangulo: '; cr.
Transcript show: t area; cr.
Transcript show: 'Perimetro del triangulo '; cr.
Transcript show: t perimetro; cr.

"le asigno a g las clase grafico"
g := Grafico new.
"agregp figura a la coleccion"
g addFigura: r.
"ver como hacer para mostrar toda la coleccion"
Transcript show: 'promedio de las superficie entre todas las figuras es: ';cr.
Transcript show: g promedio.
