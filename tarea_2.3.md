# Tarea 2.3 Expresiones regulares

### 1.-Expresion Regular para validar Contraseña
```markdown
^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[^\da-zA-Z]).{8,}$
```
![screenshot](https://github.com/diegoquintos/LengAutomatas/blob/main/imgautomatas/img1.JPG)

Los requerimientos para validar esta contraseña son:
- Debe contener al menos 1 letra minúscula.
- Debe contener al menos 1 letra mayúscula.
- Debe contener al menos 1 número.
- Debe contener al menos 1 carácter especial.
- Debe tener una longitud mínima de 8 caracteres.

### 2.-Expresión Regular para validar username

```markdown
^[a-zA-Z0-9_-]{3,16}$
```
![screenshot](https://github.com/diegoquintos/LengAutomatas/blob/main/imgautomatas/img2.JPG)

Para validar el username se necesita cumplir :
- Debe tener una longitud de entre 3 y 16 caracteres.
- Puede contener letras (mayúsculas o minúsculas), números, guiones medios o guiones bajos.

### Quintos Cabeza Diego-21200625
