# platzi-datehelper

Una utilidad para manejar fechas en formato timestamp y long time.

# Instalación

```bash
npm install platzi-datehelper
```

# Ejemplos de uso

```javascript
const dateFormatter = require("platzi-datehelper");

console.log("Timestamp", dateFormatter.getTimestamp());
console.log("Fecha en Español:", dateFormatter.getLongTime());
console.log("Fecha en Inglés:", dateFormatter.getLongTime("en-US"));
```

# Licencia

MIT

# Reconocimientos

Se agradece a la plataforma de aprendizaje [Platzi](https://platzi.com/home/) por el [Curso de Fundamentos de Node.js](https://platzi.com/cursos/nodejs/) por la guía sobre la construcción de éste paquete y cómo publicarlo en NPM
