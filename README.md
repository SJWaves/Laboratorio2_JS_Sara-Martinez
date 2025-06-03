# Laboratorio2_JS_Sara-Martinez

Documentación

Descripción
Este laboratorio tiene como objetivo practicar el uso de JavaScript. La interfaz fue desarrollada con HTML y estilos integrados en un bloque <style> en el mismo archivo, ya que no se proporcionó un archivo CSS externo.
El diseño visual se realizó con ayuda de inteligencia artificial para lograr una presentación minimalista, centrada y clara, que facilite la visualización de los resultados sin distracciones.

Estructura y organización del código
    • Se utilizó una estructura básica HTML con etiquetas como <fieldset>, <legend>, <input>, <button> y <div>.
    • Cada ejercicio está separado por un <fieldset>, lo cual mejora la organización visual y la accesibilidad.
    • Se usaron etiquetas <br> para separar visualmente los bloques en la interfaz.
    • Los resultados se muestran en contenedores <div> con la clase resultado, centrados con CSS y tipografía sans-serif para facilitar la lectura.
      
Estilo (CSS)
    • El CSS se colocó en la etiqueta <style> dentro del <head>.
    • El diseño se centró usando display: flex, flex-direction: column y align-items: center en el body.
    • Se usaron colores neutros (#fdfdfd y #f0f0f0) y bordes redondeados.
    • Los campos de entrada y botones tienen un diseño uniforme, con padding, border-radius, y box-sizing: border-box.
    • El CSS fue generado y ajustado con el apoyo de una herramienta de inteligencia artificial (IA), para asegurar claridad y consistencia visual.
    • 
Ejercicio 1: Detectar si una cadena es un palíndromo
Objetivo: Verificar si una palabra o frase se lee igual al derecho y al revés.
Lógica aplicada:
    1. Convertir el texto a minúsculas.
    2. Eliminar espacios con .replace(/\s/g, "").
    3. Invertir la cadena y compararla con la original.
Función:verificarPalindromo()
Resultado: Se muestra un mensaje según la validación.
       
Ejercicio 2: Comparar dos números
Objetivo: Pedir dos números y determinar cuál es el mayor.
Lógica aplicada:
    1. Convertir los valores con parseFloat().
    2. Usar condicionales if-else para comparar.
    3. Mostrar el resultado directamente en el HTML.
Función:compararNumeros()
Resultado: Se indica cuál número es mayor, o si son iguales.

Ejercicio 3: Mostrar vocales presentes en una frase
Objetivo: Detectar todas las vocales en una frase.
Lógica aplicada:
    1. Convertir la frase a minúsculas.
    2. Utilizar una expresión regular: /[aeiou]/g.
    3. Mostrar las vocales encontradas como lista separada por comas.
Función:mostrarVocales()
Resultado: Muestra vocales o un mensaje si no hay.

Ejercicio 4: Contar cuántas veces aparece cada vocal
Objetivo: Contar la cantidad de veces que aparece cada vocal (a, e, i, o, u) en una frase.
Lógica aplicada:
    1. Se crea un objeto conteo con claves para cada vocal.
    2. Se recorre la frase con un ciclo for-of.
    3. Se incrementan los contadores de cada vocal si está presente.
Función: contarVocales()
Resultado: Se muestra el conteo de cada vocal en una frase como texto.
Diseño final de la interfaz
    • Todos los campos y botones están alineados verticalmente en el centro de la pantalla.
    • Cada bloque funcional está encapsulado en un fieldset con su legend correspondiente.
    • El diseño es responsive de  un forma muy básica gracias al uso de max-width y box-sizing.
    • Se priorizó la claridad visual y simplicidad sobre el uso de gráficos.

Entrega y ejecución
    • El archivo entregado es un único .html con JavaScript y CSS juntos.
    • No se utilizó ningún framework ni librería externa (como jQuery o Bootstrap).
    • El código es totalmente funcional, probando con diferentes entradas y mostrando resultados al instante.
    • Se entregará un PDF con esta documentación y el enlace o archivo HTML correspondiente.
