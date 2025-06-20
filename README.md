# Cupones API

## Equipo 2

### Integrantes:

- **Francisco Leiva**
- **Guillermo Torres**

## Preguntas finales

1. **¿Por qué fue difícil detectar la regresión sin pruebas?**  
   Pueden ocurrir pequeños cambiops en el códigopque al parecer del desarrollador no tendrá efectos colaterales, ejemplos de esto es el cambio de un path, una ruta, una constante, etc.

   El error puede no verse reflejado a simple vista, pero al realizar una acción específica, como crear un cupón, se puede observar que el sistema no responde como se esperaba. Sin pruebas automatizadas, estos errores pueden pasar desapercibidos hasta que un usuario los encuentra en producción, lo que puede llevar a una mala experiencia del usuario y a la pérdida de confianza en el sistema.

2. **¿Cómo te ayuda el testing automatizado a mantener calidad?**  
   El testing automatizado permite detectar errores rápidamente después de cada cambio, asegurando que las funcionalidades existentes sigan funcionando correctamente. Esto reduce el riesgo de introducir bugs y facilita el mantenimiento del código.

3. **¿Qué otras partes del código deberías cubrir con pruebas?**  
   Debería cubrirse con pruebas cualquier parte crítica del negocio, validaciones de entrada, manejo de errores, integración con servicios externos y cualquier función que procese datos importantes.

4. **¿Cómo evitarías errores similares en el futuro?**  
   Implementando pruebas automatizadas para todas las funcionalidades clave y utilizando integración continua para ejecutar los tests en cada cambio. Además, revisando el código y promoviendo buenas prácticas de desarrollo.
