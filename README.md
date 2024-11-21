# Evaluador de Expresiones Matemáticas

## Descripción

Este proyecto implementa un evaluador de expresiones matemáticas en notación infija utilizando una pila. El evaluador soporta operaciones de adición, resta, multiplicación, y división, incluyendo el uso de paréntesis para alterar el orden de las operaciones.

## Estructura del Proyecto


## Instrucciones para ejecutar

1. Clona el repositorio:
2. Navega al directorio del proyecto:
3. Instala las dependencias necesarias (si es necesario):
4. Ejecuta el script para probar el evaluador:

## Ejemplo de uso

```python
expresion = "3 + 5 * (2 - 8)"
resultado = evaluar_expresion(expresion)
print(f"El resultado de la expresión '{expresion}' es: {resultado}")


--

python -m unittest tests/test_evaluador.py


---

### Paso 5: **Publicación en GitHub**

1. Crea un nuevo repositorio en GitHub con el nombre `evaluador_de_expresiones`.
2. Sube el código fuente, el archivo `README.md`, y las pruebas al repositorio.
3. Asegúrate de tener un historial de commits adecuado y bien estructurado. Usa mensajes claros y significativos al hacer commits.

---

### Paso 6: **Pruebas y Validación**

Realiza pruebas adicionales para cubrir diferentes escenarios de expresiones. Aquí hay algunos ejemplos de expresiones a probar:
- `"10 + 2 * 6"` → `22`
- `"100 * 2 + 12"` → `212`
- `"3 + 5 * (2 - 8)"` → `-13`

---

Con esta estructura organizada y profesional, tu proyecto estará bien documentado y fácil de entender para cualquier persona que lo vea o lo use.
