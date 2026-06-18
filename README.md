# Calculadora Tkinter

Ejercicio práctico de interfaz gráfica con Python y Tkinter.

## Funcionalidades

- Suma, resta, multiplicación y división
- Validación de campos vacíos y datos no numéricos
- Validación de división entre cero
- Botón para limpiar campos
- Nombre del estudiante en la ventana
- Ventana con color de fondo personalizado
- Ícono personalizado (opcional, requiere `icono.ico`)

## Cómo ejecutar

```bash
python calculadora.py
```

## Preguntas de Análisis

1. **¿Qué función cumple el componente Label dentro de una interfaz gráfica?**  
   Muestra texto estático o información al usuario, como etiquetas, títulos o resultados.

2. **¿Qué función cumple el componente Entry?**  
   Permite al usuario ingresar texto o datos desde el teclado.

3. **¿Qué función cumple el componente Button?**  
   Ejecuta una acción cuando el usuario hace clic sobre él.

4. **¿Qué sucede cuando el usuario hace clic sobre un botón?**  
   Se dispara el evento asociado (command), ejecutando la función correspondiente.

5. **¿Por qué es necesario utilizar una función para realizar la suma?**  
   Para encapsular la lógica y asociarla al evento del botón, manteniendo el código modular.

6. **¿Qué ocurre si el usuario ingresa texto en lugar de números?**  
   El programa lanza una excepción ValueError; en esta implementación se muestra un mensaje de error.

7. **¿Qué modificaciones realizaría para permitir realizar una resta?**  
   Agregar un botón para resta y una función que reste los valores de los Entry.

8. **¿Qué ventajas tiene una interfaz gráfica frente a un programa de consola?**  
   Es más intuitiva, fácil de usar para personas no técnicas, y permite interacción visual.

9. **¿Qué validaciones deberían implementarse antes de realizar la suma?**  
   Verificar que los campos no estén vacíos, que contengan solo números, y que sean valores válidos.

10. **¿De qué manera podría mejorar la apariencia de la aplicación?**  
    Usando colores, fuentes, botones con estilo, íconos, organización con frames y padding.
