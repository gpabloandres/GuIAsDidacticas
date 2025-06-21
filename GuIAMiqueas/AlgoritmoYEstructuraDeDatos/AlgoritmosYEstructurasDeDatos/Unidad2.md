¡Hola, Miqueas! 👋

Continuando nuestra aventura de exploración sobre cómo organizar cosas y crear "recetas" paso a paso (¡esos son los algoritmos!), vamos a descubrir una nueva forma de guardar y encontrar información, ¡como si fuera un catálogo mágico con etiquetas para todo! Usaremos muchos dibujos, colores y ejemplos con las cosas que te gustan, como tus autos, camiones y countryballs.

¿Listo para seguir explorando el mundo de la organización digital? 🚀

---

### **MÓDULO 4: ¡Mis Colecciones con Etiquetas Mágicas! (Diccionarios)**

**Objetivo:** Aprender a guardar información usando "etiquetas" (o nombres especiales) para encontrarla rápidamente, como en un libro de direcciones o un catálogo.

**¿Cómo usaremos esta guía?**
*   **Leeremos juntos**.
*   **Veremos imágenes** y dibujaremos para entender mejor.
*   **Usaremos objetos** si nos ayudan a entender.
*   **Probaremos cosas juntos en la computadora**, ¡yo te mostraré!.
*   **¡Lo más importante es probar y divertirse aprendiendo!**.

---

#### **¿Qué es una "Etiqueta Mágica"? (Clave y Valor en Diccionarios)** 🤔

Recuerdas nuestro "Garaje Numerado" (Arreglo) donde cada auto estaba en un espacio con un número fijo (1, 2, 3...)? Ahora, imagina que tenemos un **baúl especial** 📦 donde, en lugar de números, cada cosa tiene una **etiqueta escrita** o un **nombre único**. ¡Eso es un "Diccionario"!

*   **Piensa en un Diccionario como una ficha de información:**
    *   Para un **Camión** 🚚:
        *   **Etiqueta (Clave):** "Color", **Información (Valor):** "Rojo"
        *   **Etiqueta (Clave):** "Marca", **Información (Valor):** "Volvo"
        *   **Etiqueta (Clave):** "Capacidad", **Información (Valor):** "20 Toneladas"
    *   Para una **Countryball** 🗺️:
        *   **Etiqueta (Clave):** "Nombre", **Información (Valor):** "Argentina"
        *   **Etiqueta (Clave):** "Colores", **Información (Valor):** "Celeste y Blanco"
        *   **Etiqueta (Clave):** "Saludo", **Información (Valor):** "¡Hola!"

**Idea Clave:** En un diccionario, cada pedacito de información tiene una **etiqueta (clave)** única para que lo encuentres fácil, y esa etiqueta tiene la **información (valor)** que te interesa.

---

#### **Actividad 4.1: ¡Mi Caja de Información de Camiones! (Concepto Concreto)**

Vamos a crear una "ficha" para tu camión favorito usando papel o dibujos 📝🎨.

1.  **Dibuja un camión** 🚚 en el centro de tu hoja.
2.  Ahora, alrededor del camión, **dibuja 3 cajas pequeñas** 🗃️.
3.  Dentro de cada caja, escribe una **"Etiqueta" (Clave)** y luego, al lado, la **"Información" (Valor)**.
    *   **Caja 1:** Etiqueta: `Color` 🖌️, Información: `Azul` 🔵
    *   **Caja 2:** Etiqueta: `Ruedas` ⚙️, Información: `8`
    *   **Caja 3:** Etiqueta: `Tipo` 🚛, Información: `Volcador`

[ _Espacio para que Miqueas dibuje su camión y sus cajas de información_ ]

**Pregunta:** Si te pregunto: "¿Qué `Tipo` de camión es?", ¿qué información encuentras mirando la etiqueta? ¡Exacto, **"Volcador"**!

---

#### **Actividad 4.2: ¡Creando Nuestras Fichas Digitales en Python!** 💻🖱

Ahora vamos a crear estas "fichas con etiquetas" dentro de la computadora, usando Python. ¡Lo haremos **JUNTOS** paso a paso!

1.  **Yo te muestro:** Abriremos un programa simple en la compu, ¡como la última vez!.
2.  **Escribimos Juntos:** Vamos a crear la ficha de tu camión favorito. Nota que usamos `{}` para el diccionario y `:` para separar la etiqueta del valor.
    ```python
    # Creamos una ficha para mi camión de bomberos
    mi_camion_bomberos = {
        "Marca": "Mercedes",
        "Color": "Rojo",
        "Escalera": "Sí",
        "Sirena": "Fuerte"
    }
    ```
3.  **Vemos el Resultado:** Le pedimos a la compu que nos muestre la ficha completa.
    ```python
    print(mi_camion_bomberos)
    ```
    *Veremos en pantalla algo como:* `{'Marca': 'Mercedes', 'Color': 'Rojo', 'Escalera': 'Sí', 'Sirena': 'Fuerte'}`

**¡Tu Turno (con mi ayuda)!**
*   Intenta **añadir una nueva "etiqueta" y su "información"** a la ficha `mi_camion_bomberos`. Por ejemplo, ¿tiene "Luces" o es "Grande"?
    *   Así lo harías (¡yo te ayudo a escribirlo!): `mi_camion_bomberos["Luces"] = "Azules"`
*   Vamos a pedirle a la computadora que nos muestre la ficha de nuevo con `print(mi_camion_bomberos)`. ¿Apareció tu nueva información? ¡**Excelente**!

---

#### **Actividad 4.3: ¡Encontrando Información en Nuestras Fichas! (Acceder Valores)**

Así como en nuestra caja de papel buscamos la información por la etiqueta, ¡en Python es igual!

1.  **Yo te muestro:** Para saber el `Color` del camión de bomberos, usamos la etiqueta dentro de corchetes `[]`.
    ```python
    # ¿De qué color es mi camión de bomberos?
    print(mi_camion_bomberos["Color"])
    ```
    *Veremos en pantalla:* `Rojo`

**¡Tu Turno (con mi ayuda)!**
*   ¿Qué escribirías para ver si el camión tiene `Escalera`? Prueba: `print(mi_camion_bomberos["Escalera"])`
*   ¿Y para saber la `Marca`? ¡Inténtalo!

---

#### **Actividad 4.4: ¡Actualizando Nuestras Fichas! (Modificar y Añadir)**

Si la información de un camión cambia, ¡podemos actualizarla en nuestra ficha digital! O si descubrimos algo nuevo, ¡lo podemos añadir!

1.  **Yo te muestro:** Nuestro camión de bomberos ahora tiene la sirena "Muy Fuerte".
    ```python
    # Cambiamos la información de la sirena
    mi_camion_bomberos["Sirena"] = "Muy Fuerte"
    print(mi_camion_bomberos)
    ```
    *Veremos que `Sirena` ahora dice "Muy Fuerte".*

**¡Tu Turno (con mi ayuda)!**
*   Imagina que el camión de bomberos ahora tiene `2000` `Litros_Agua`. **Vamos a añadir esta nueva información** a la ficha:
    *   `mi_camion_bomberos["Litros_Agua"] = 2000`
*   Ahora, pedimos que nos muestre la ficha completa con `print(mi_camion_bomberos)`. ¿Aparece la nueva información? ¡**Fantástico**!

---

**Checkpoint Módulo 4:** 👍👎
*   ¿Entiendes que un "diccionario" es como una ficha con **etiquetas y su información**? (Puedes responder sí/no o con un gesto).
*   ¿Pudiste **crear** tu propia ficha digital de camión/countryball en Python (con ayuda)?.
*   ¿Lograste **encontrar** información en la ficha usando su etiqueta (con ayuda)?.
*   ¿Pudimos **cambiar o añadir** información a la ficha (con ayuda)?.

---

### **PROYECTO FINAL: ¡Mi Colección Organizada con Etiquetas!** 🏆

¡Ahora vamos a usar lo que aprendimos para organizar una pequeña colección de tus cosas favoritas usando "etiquetas" en Python! ¡Tú eliges qué quieres organizar!

**¡Tu Misión!**
1.  **Elige tu Colección:** ¿Quieres organizar 3 countryballs favoritas, 4 autos de carrera, o información sobre tus camiones?.
2.  **Piensa en las "Etiquetas" (Claves) y su "Información" (Valores):**
    *   Por ejemplo, para una countryball: `{"Nombre": "...", "Colores": "...", "Capital": "..."}`
3.  **Creamos Juntos tu Ficha Digital en Python:** Yo te ayudaré a escribir el código para crear tu diccionario.
    ```python
    # Mi colección de [tu elección]
    mi_coleccion = {
        "Etiqueta1": "Valor1",
        "Etiqueta2": "Valor2",
        "Etiqueta3": "Valor3"
    }
    ```
4.  **Encuentra Algo:** Vamos a usar `print(mi_coleccion["Etiqueta que quieres ver"])` para encontrar una información específica.
5.  **Añade o Cambia Algo:** ¡Vamos a modificar una información existente o añadir una nueva etiqueta y su valor a tu ficha!
    *   Por ejemplo: `mi_coleccion["Nueva_Etiqueta"] = "Nuevo_Valor"`

**¡Lo Haremos Paso a Paso y Juntos!** No te preocupes si algo no sale a la primera, ¡lo importante es intentarlo y aprender de los intentos!

[ _Espacio para realizar el pequeño proyecto con Miqueas, adaptando el soporte y la complejidad según su progreso y comodidad._ ]

---

**¡FELICITACIONES, MIQUEAS!** 🎉

¡Has explorado cómo organizar tus colecciones de una forma muy especial, usando **etiquetas (claves)** para guardar y encontrar información!

Aprendiste:
*   Que los **diccionarios** son como fichas con "etiquetas" (claves) y "información" (valores).
*   Cómo **crear** estas fichas en Python.
*   Cómo **buscar** y **actualizar** información usando las etiquetas.

Sigue practicando con tus colecciones y pensando en cómo podrías usar estas "etiquetas mágicas" para organizar más cosas. ¡Eres un gran resolviendo problemas y organizando información!

---

**Notas para el Facilitador/Profesor:**

*   **Adaptabilidad:** Ajuste la complejidad y el ritmo según la respuesta y el interés de Miqueas. Si un concepto es difícil, simplifíquelo aún más o pase más tiempo con ejemplos concretos.
*   **Visual Siempre:** Refuerce CADA concepto con imágenes claras, dibujos hechos en el momento, o los objetos concretos (autos, bloques, etc.). Use colores vivos.
*   **Intereses:** Integre constantemente sus intereses (autos, camiones, countryballs) en todos los ejemplos y actividades.
*   **Python con Andamiaje:** La parte de Python debe ser muy guiada ("scaffolding"). Modele cada paso, use "copy-paste" si es necesario al principio, enfóquese en la *idea* de dar instrucciones, no en la sintaxis perfecta. El objetivo es la comprensión conceptual, no la programación autónoma en esta etapa.
*   **Evaluación:** Observe su participación, sus intentos (incluso si no son perfectos), su capacidad para seguir instrucciones visuales/cortas, y si puede aplicar los conceptos con objetos concretos. Use los indicadores provistos como guía, enfocándose en el progreso gradual. Celebre los pequeños logros.
*   **Paciencia y Positivismo:** Cree un ambiente de aprendizaje seguro y motivador. La frustración es normal, guíe a Miqueas a través de ella con calma y ánimo.
*   **Consignas:** Mantenga las consignas cortas, enumeradas y concretas. Distribuya las tareas en pasos secuenciales con incremento gradual de la dificultad.
*   **Comunicación:** Utilice comunicación clara y concisa, evitando lenguaje figurado.
*   **Apoyo:** Brinde ayuda directa y demostraciones o modelado en lugar de largas explicaciones verbales, ya que estas suelen abrumarlo.