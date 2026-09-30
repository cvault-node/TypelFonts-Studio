<p align="center">
 <img width="128" height="128" alt="logo" style= "align-content=center;" src="https://github.com/user-attachments/assets/f3226fe7-37fc-4f28-9c56-03a64b747d8e" /> 
</p>

<h1 align = "center">Typel Fonts</h1>

<p align="center"> 
Editor de fuentes pixel para navegador y Windows. Dibuja cada letra a mano en
una rejilla, comprueba el resultado sobre texto real y expórtala a OTF, TTF, WOFF,
WOFF2 o JSON.
</p>

<p align="center">
  <a href="https://github.com/cvault-node/typelfonts-studio/releases/latest">
    <img src="https://img.shields.io/github/v/release/cvault-node/typelfonts-studio?label=release" alt="Latest release">
  </a>
  <a href="https://github.com/cvault-node/typelfonts-studio/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-ISC-blue.svg" alt="License: ISC">
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Web-brightgreen" alt="Platform: Windows | Web">
</p>

Sitio web: <https://typelfonts.netlify.app>

---

## Capturas

| | |
| --- | --- |
| <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/ac0aad4d-fcd1-4a26-a202-85089f6595d4" /> | <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/6849ffe1-5fcb-40e9-8ca1-083c77bb092a" />
| *Editor: rejilla, guías de métricas y herramientas.* | *Vista previa en vivo mientras se edita.* |
| <img width="400" height="auto" alt="image" src="https://github.com/user-attachments/assets/bee2a5af-51f7-491b-ab9f-ea23e808a148" />| <img width="400" height="auto" alt="image" src="https://github.com/user-attachments/assets/c52011e4-0dc3-4245-b833-e41de5da2059" />|
| *Galería pública, con la fuente de cada autor.* | *Biblioteca con autoguardado.* |

---

## Qué es

Una fuente pixel no es una tipografía que se configura con parámetros. Cada letra
es un dibujo hecho píxel a píxel, y por eso cada una tiene un carácter que no se
puede replicar con ajustes.

Typel Fonts es un editor para crear la tuya. No genera fuentes a partir de
plantillas ni de estilos automáticos: se elige un glifo, se dibuja y se decide.

---

## Pantallas

### Inicio de sesión

Acceso con Google o con correo y contraseña. La sesión se conserva, de modo que
sólo hay que entrar una vez. Sin cuenta se puede consultar la galería, pero crear
y guardar fuentes requiere estar registrado.

### Mis fuentes

Biblioteca personal con todas las fuentes en trabajo y su estado de guardado
visible. Desde aquí se abre el editor o se crea una fuente nueva.

El guardado es automático mientras se edita: no hay botón de guardar. El
indicador de la barra superior informa si está guardando, si ha terminado, o
cuándo fue la última escritura.

### Editor
- **Vista previa en vivo.** Se escribe un texto y se muestra con la fuente en
  edición, no con una aproximación.
- **Historial de 100 pasos** de deshacer y rehacer.
- **Copiar y pegar glifos**, para no repetir letras de estructura parecida.
- **Temas claro y oscuro.**

### Explorar

Galería pública con las fuentes que la comunidad ha publicado. Cada fuente se
prueba con el texto que se escriba, de modo que varias se pueden comparar en la
misma vista. Admiten me gusta y comentarios.

En la versión de escritorio, **Explorar** abre el sitio en el navegador del
usuario, no dentro de la aplicación.

### Perfil

Foto, nombre y biografía breve, con acceso a las fuentes publicadas y a su
edición.

---

## Herramientas del editor

| Herramienta | Función |
| --- | --- |
| Lápiz | Dibujar píxel a píxel. |
| Relleno | Cubrir regiones cerradas en un solo paso. |
| Mover | Reposicionar el glifo en la rejilla sin redibujarlo. |
| Limpiar | Vaciar el glifo. |
| Invertir | Voltear el glifo; útil para simetrizar letras como la B o la E. |
| Copiar y pegar | Trasladar un glifo de una letra a otra. |
| Deshacer y rehacer | 100 pasos de historial. |

### Atajos de teclado

| Tecla | Acción |
| --- | --- |
| `P` | Lápiz |
| `F` | Relleno |
| Flechas | Mover el glifo |
| `Supr` / `Retroceso` | Limpiar el glifo |
| `Esc` | Cerrar la ventana activa |

### Guías de métricas

Sobre la rejilla se muestran cuatro líneas de referencia: altura de mayúscula,
altura de x, línea base y descendente. Cada una se arrastra hasta la posición
deseada. Colocarlas bien es lo que hace que el conjunto de letras se lea de
forma coherente en lugar de como glifos sueltos.

---

## Exportación

| Formato | Uso habitual |
| --- | --- |
| OTF | La mayoría de editores de diseño. |
| TTF | Compatibilidad máxima. |
| WOFF | Web. |
| WOFF2 | Web, con el menor peso. |
| JSON | Datos en bruto, para_other herramienta. |

---

## Publicación

Desde el editor, una fuente se publica en la galería. El número de glifos válidos
se calcula automáticamente; a partir de ahí aparece en **Explorar** con su
nombre y su autor, y queda disponible para que otros la prueben, la descarguen,
la marquen y la comenten.

---

## Versiones

Ambas proceden del mismo código.

**Web.** Versión completa: editor, biblioteca, galería y perfil.

**Escritorio para Windows.** Editor y biblioteca. La galería se abre en el
navegador. Se distribuye como instalador y también en formato portable.

La versión de escritorio arranca como una aplicación nativa, con icono propio y
sin depender de una pestaña del navegador.

---

## Preguntas frecuentes

**¿Puedo usar las fuentes en un juego?**
Sí. OTF y TTF son los formatos que admiten la mayoría de motores; WOFF2 es el
formato para web.

**¿Cuántos glifos necesita una fuente?**
Los que se le den. No hay un mínimo obligatorio, y definir únicamente las
letras que se van a usar produce un archivo bastante más ligero.

**¿Qué es la altura de x?**
La altura de las minúsculas sin ascendente ni descendente, la de la x. Marcar
bien esa guía es lo que mantiene las minúsculas a la misma altura entre sí.

**¿Hay coste?**
No. Sin anuncios, sin límites de uso y sin rastreo.

---

## Historial de Estrellas

<a href="https://www.star-history.com/?repos=cvault-node%2Ftypelfonts-studio&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=cvault-node/typelfonts-studio&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=cvault-node/typelfonts-studio&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=cvault-node/typelfonts-studio&type=date&legend=top-left" />
 </picture>
</a>
