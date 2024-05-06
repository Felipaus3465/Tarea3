# Tarea3
Autor: Luis Felipe Calderón Pérez
Todo el codigo esta hecho en HTML, javascript y D3.
*Es importante mencionar que dentro del código en HTML se encuentra documentación oportuna para mejorar el entendimiento del mismo.*
# Librerias usadas

"<script src="https://d3js.org/d3.v7.min.js"></script>"
"<script src="https://d3js.org/d3-fetch.v1.min.js"></script>"

# Código mapa de USA

Los datos se cargan como un .txt, ya que no existe una función predeterminada en D3 que lea un ".bna". Déspues se parsea correctamente los datos y una vez parseados se hace un inner join con los datos de states_name.csv y por último se crea el gráfico con zoom del mapa de USA.

# Jerarquía de distritos de CR

root como raíz.

Hijos directos de root

todos los id de distritos_cr (490 en total).

los demas campos son hijos del id de distritos_cr.

*Es importante mencionar que debido a esta jerarquia algunas visualizaciones son complejas de entender en un inicio.*

# Jerarquía de Flare.json
 Despues de cargar los datos como un .csv, porque así separa de una vez por coma los datos del flare.json. Se llama a la
 función de buildHierarchy, en donde se crea la siguiente jerarquía.

flare como raíz.

Hijos directos de flare

analytics
animate
data
display
flex
physics
query
scale
util
vis

luego a cada hijo directo le crea los hijos que tenga

# Jerarquía de Vue.json

VUE como raíz.

Hijos directos DE VUE

VUE
@babel
@vitejs
@vue
csstype
esbuild
estree-walker
fsevents
function-bind
has
is-core-module
magic-string
nanoid
path-parse
picocolors
postcss
resolve
rollup
source-map
sourcemap-codec
supports-preserve-symlinks-flag
vite
vue

cada uno de esos hijos tiene n hijos, según los datos de "vue.json".

# Enlace a la pagina web de las visualizacines
https://felipaus3465.github.io/Tarea3/