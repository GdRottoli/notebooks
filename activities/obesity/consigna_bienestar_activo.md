# Actividad: Hábitos y obesidad en estudiantes

---

## Situación

El **Servicio de Salud Universitario** realiza un relevamiento a quienes ingresan al programa *Bienestar Activo*. El proceso tiene dos pasos:

1. **Cuestionario online** que cada estudiante completa *antes* de ir al consultorio: hábitos de alimentación, actividad física, transporte y antecedentes familiares.
2. **Visita al consultorio**, donde enfermería mide peso y talla y asigna una categoría de peso.

El servicio de salud desea:
- diseñar talleres para distintos alumnos en funcion de sus hábitos.
- detectar de antemano quienes probablemente tengan obesidad, para poder tomar medidas adecuadas, como consultas nutricionales. 

## Datos

`estudiantes_salud.csv` posee datos de distintos estudiantes que fueron cargados en tres sedes universitarias. Los datos fueron cargados de forma manual así que pueden tener errores. 

| Columna | Descripción |
|---|---|
| `id_estudiante`, `sede` | Identificador y sede de carga (Central, Norte, Sur) |
| `genero`, `edad` | Datos demográficos |
| `talla_m`, `peso_kg` | Talla y peso (medidos en el consultorio) |
| `antec_familiar` | Antecedentes familiares de sobrepeso |
| `come_calorico` | Consume con frecuencia comida de alto contenido calórico |
| `verduras` | Frecuencia de consumo de verduras (1 = nunca ... 3 = siempre) |
| `comidas_principales` | Comidas principales por día (1 a 4) |
| `picoteo` | Come entre comidas (Nunca / A veces / Frecuente / Siempre) |
| `fuma` | Fuma |
| `agua` | Consumo diario de agua (1 = menos de 1 L ... 3 = más de 2 L) |
| `controla_calorias` | Controla las calorías que consume |
| `actividad_fisica` | Frecuencia semanal (0 = nunca ... 3 = 4-5 días) |
| `pantallas` | Tiempo diario en dispositivos (0 = 0-2 h, 1 = 3-5 h, 2 = más de 5 h) |
| `alcohol` | Consumo de alcohol (Nunca / A veces / Frecuente / Siempre) |
| `transporte` | Medio de transporte habitual |
| `categoria_peso` | Categoría asignada en consultorio (de Peso_insuficiente a Obesidad_III) |

## Consignas

En un notebook vayan respondiendo los siguientes incisos.

### 1. Conociento de los datos

Exploren el dataset y detecten problemas. Anoten cada problema y qué decidieron hacer.

### 2. Determinen como abordar cada problema

- Preparar los datos para solucionar cada objetivo planteado
- Modelar el conocimiento en los datos para hacerlo.
- Validar la solución
- Brindar una respuesta. 

## Entrega

Notebook con código y comentarios breves.
