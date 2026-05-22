1. ¿Para qué sirve export? ¿Qué pasa si no lo pones?
Señala qué partes del archivo están disponibles para otros módulos.
export const funcion = [...];

2. ¿Para qué sirve import? ¿Cómo se indica la ruta del archivo?
Trae lo que otro módulo ha exportado.
import { funcion } from './ruta/del/archivo.js';

3. ¿Por qué usamos type="module" en el HTML?
Para que el navergdaor permita usar las funciones de import y export. Si no lo pones el navegador da un mensaje de error.

4. ¿Qué ventaja tiene separar el código en varios archivos en un proyecto
real?
Con un código separado puedes reutilizarlo para otros proyectos, es más fácil de manterner y detectar los errores, falicita la colaboración entre desarrolladores sin interferirse unos y otros y mejora la productividad del equipo, además de facilitar la actualización y la escalabilidad del proyecto. 
