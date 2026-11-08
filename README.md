# Pikman · plataformas (3 niveles)

Juego de plataformas para celular, en un solo `index.html` con sus imágenes en la carpeta `images/`.

## Niveles
1. **Desierto**: aprende a saltar, esquiva a Walter y junta cristales.
2. **Morado**: hay una brecha que no se cruza sin el globo. Toma el chili antes de saltar.
3. **RV**: brecha con globo y la pelea final contra **Big Walter**.

## Enemigos
- **Walter** te ve cuando estás en su misma plataforma: pone un `!` rojo, se alerta y te persigue. Anticipa hacia dónde vas. Si lo despistas, va al último lugar donde te vio antes de volver a patrullar.
- **Big Walter** tiene ataques con aviso: se sacude y se pone rojo antes de cargar, y al chocar con la pared se marea (es el momento de pisarlo). Cuando le queda la mitad de la vida, también lanza humo-cigarros que hay que saltar. Tu cigarro los bloquea.

## Controles
- Celular: ◀ ▶ para moverse, ▲ para saltar. Si presionas saltar un poco antes de caer, saltas al tocar el suelo.
- Con el globo (chili) puedes lanzar cigarros con el botón del cigarro.
- Pisotones seguidos en el aire suman más puntos (x2, x3...).
- Al final de cada nivel ganas de 1 a 3 estrellas según los cristales que juntaste.
- Computadora: flechas o A/D, espacio o W para saltar, X para lanzar cigarro.

## Cómo subirlo a GitHub Pages
1. Crea un repositorio nuevo en github.com (por ejemplo `pikman-plataformas`).
2. "Add file → Upload files" y arrastra el contenido de este zip (`index.html`, `images/`, este README y la licencia).
3. Settings → Pages → Source: **Deploy from a branch**, rama **main**, carpeta **/ (root)** → Save.
4. En 1–2 minutos queda en `https://tu-usuario.github.io/pikman-plataformas/`.

En Chrome del celular: menú (⋮) → **Añadir a pantalla de inicio**.

## Créditos
Sonidos de salto, cristal, golpe, globo y victoria: [Kenney.nl](https://www.kenney.nl), licencia CC0. El texto de la licencia está en `LICENSE-Kenney-CC0.txt`.
