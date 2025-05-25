# generator-js-footer
Paquete sencillo de JavaScript para generar una línea de derechos de autor con el año actual y un nombre personalizado. Este paquete fue creado como parte de un proyecto educativo del curso DevCamp, enfocado en el uso de NPM y Node.js, incluyendo la creación, publicación y uso de paquetes propios.

---
## Descripción  
```generator-js-footer``` es una pequeña biblioteca diseñada para añadir un pie de página con la fecha actual y una nota de derechos de autor. Es ideal para integrarlo en el footer de aplicaciones web, donde se desea que el año se actualice automáticamente.

Ejemplo del resultado:  
**© 2025 YourName. All rights reserved.**  
El año se actualiza automáticamente mediante la biblioteca ```moment```.

---
## Instalación
Ejecuta el siguiente comando en la terminal:
```bash
npm install --save generator-js-footer
```
---
## Instrucciones de uso  
Agrega el siguiente código JavaScript al proyecto:
```javascript
import { footer } from 'generator-js-footer';

footer('YourName');
```
---
## Publicación
El paquete está disponible en el registro de NPM:
[https://www.npmjs.com/package/devcamp-js-footer](https://www.npmjs.com/package/devcamp-js-footer)

