## Tarea2.2 Diego Quintos Cabeza

## Expresion_saludo:
**expresion_saludo = re.compile(r"hello|hi|hey|hola", re.IGNORECASE)** Esta expresión valida cualquier tipo de saludo en cualquier idioma como se puede ver en el ejemplo:

![saludo_expr.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/saludo_expr.JPG)
## Expresion_estado:
**expresion_estado = re.compile(r"(?:¿)?c[oó]mo est[aá]s\??", re.IGNORECASE)**: Aquí las expresiones regulares hacen que cualquier forma de la pregunta "¿Cómo estás?" sea valido para el bot, incluyendo acentos.
![estado_expr.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/estado_expr.JPG)

## Expresion_hora:
**expresion_hora = re.compile(r"dame la hora", re.IGNORECASE)**: Aquí el bot responde con la hora validando la expresion regular "dame la hora".

![hora_expr.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/hora_expr.JPG)

## Expresion_operacion:
****expresion_operacion =re.compile(r"cu[aá]nto es (\d+)\s*\+\s*(\d+)", re.IGNORECASE)** : Esta expresion valida dos numeros y con ello hace la suma.

![operacion_expr.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/operacion_expr.JPG)

## Expresion_cancion:
**expresion_cancion = re.compile(r"recomiendame una cancion", re.IGNORECASE)**: Al preguntar esto al bot regresa una recomendación músical.

![operacion_cancion.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/cancion_expr.JPG)

## Expresion_estoy_bien y Expresion_estoy_mal:
**expresion_estoy_bien = re.compile(r"estoy bien", re.IGNORECASE)**
![operacion_animo.JPG](https://github.com/diegoquintos/LengAutomatas/blob/main/animo_expr.JPG)

## Codigo en Python

[Codigo Funcionamiento](https://github.com/diegoquintos/LengAutomatas/blob/main/bot_test.py)
