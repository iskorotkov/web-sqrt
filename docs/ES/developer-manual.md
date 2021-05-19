**Descripción de las variables globales**:

*config* - diccionario que almacena la configuración de la aplicación.

*dictRu* - diccionario, almacenando la traducción de la UI al ruso.

*dictEn* - diccionario que almacena la traducción de la UI al inglés.

*dictDe* - diccionario que almacena la traducción de la UI al alemán.

*dictEs* - diccionario que almacena la traducción de la UI al español.

*dictFr* - diccionario que almacena la traducción de la UI al francés.

*allDicts* - diccionario, que almacena los diccionarios de todo el conjunto de idiomas.

*valueInput* - Elemento de la UI, donde se almacena el valor introducido por el usuario.

*resultInput* - Elemento de la interfaz de usuario que almacena el valor del resultado del cálculo de la raíz cuadrada.

*precisionInput* - Elemento de la interfaz de usuario que almacena el valor de los dígitos significativos.

*precisionSlider* - Elemento de interfaz de usuario, que se asocia con el deslizador para cambiar el valor de los dígitos significativos.

*digitsAfterPointInput* - el elemento de la UI que almacena el valor de los dígitos después del punto decimal.

*digitsAfterPointSlider* - el elemento de interfaz de usuario vinculado al deslizador para cambiar el valor de los dígitos después del punto decimal.

*languageSelect* - Elemento de la interfaz de usuario que almacena el idioma seleccionado actualmente.

**Descripción de la función**:

*clampDigits*

- Descripción: recorta el número de dígitos después del punto decimal para la salida al
- Parámetros de entrada:
  - *valor* - número para el que se fija el número de decimales

*clamp*

- Descripción: limita el número de dígitos en el rango especificado
- Parámetros de entrada:
  - *precisión* - número
  - *min* - valor mínimo
  - *max* - valor máximo

*setPrecision*

- Descripción: establece el valor de la precisión del número resultante 
- Parámetros de entrada:
  - *precisión* - valor de exactitud

*setDigitsAfterPoint*

- Descripción: determina el valor del número de decimales para el número resultante 
- Parámetros de entrada:
  - *digits* - valor del número de decimales

*setPrecisionSupported*

- Descripción: establece el soporte de la precisión, en función del valor de la bandera 
- Parámetros de entrada:
  - *valor* - el valor lógico de la bandera

*actualizarResultado*

- Descripción: calcula el valor de la raíz cuadrada y actualiza el valor de la variable de salida

*Actualización de la lengua*

- Descripción: actualiza la descripción del texto de los elementos de la interfaz de usuario cuando se cambia el idioma