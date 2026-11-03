# Manual de usuario — LYNX IA KIT 🐾

*Versión 0.2.6 · octubre de 2026 · para Windows 10 y 11 (64 bits)*

Hola, soy **Lynx**, el lince que te acompaña. Este manual te cuenta qué hace
LYNX IA KIT y cómo usarlo, paso a paso y sin palabras raras.

---

## 1. ¿Qué es LYNX IA KIT?

Es una aplicación que **pone una inteligencia artificial (IA) dentro de tu
computador** y te deja usarla como **asistente de oficina**: escribir cartas,
resumir documentos, traducir, corregir textos o redactar correos.

La opción recomendada, **En tu PC**, trabaja **sin internet** una vez instalada:
lo que escribes **no sale de tu oficina**. Funciona en equipos de oficina
normales (8 a 16 GB de memoria) **sin tarjeta gráfica**.

Hace dos cosas:

1. **La instala por ti.** Un asistente de 5 pasos prepara todo solo: tú solo
   pulsas botones. No hace falta saber de computadores.
2. **Te da un panel de control** para hablar con tu IA, ver cómo está todo y
   arreglarlo con un botón si algo falla.

### Lo que el kit NO hace

- **No te pide permisos de administrador** ni contraseñas de Windows.
- **No te cobra nada ni te pide tarjeta.** Si algún día quieres un plan de pago
  de otra empresa, la app solo te abre su página oficial en tu navegador.
- **No abre ventanas negras** de comandos: todo pasa en segundo plano.

---

## 2. Antes de empezar

| Necesitas | Por qué |
|---|---|
| Windows 10 u 11 de 64 bits | Es el sistema para el que está hecha. |
| **Al menos 8 GB de memoria** (mejor 16 GB) | La IA en tu PC usa unos 4 GB mientras trabaja. Con 8 GB irá justa: cierra otros programas pesados. |
| **Unos 10 GB libres en el disco** | El programa de IA y su modelo de oficina ocupan unos 5 GB; el resto es margen. |
| **Internet solo para instalar** (o la memoria USB) | La primera vez se descargan unos **5 GB**. Después, la IA en tu PC funciona sin internet. Si tu oficina no tiene internet o la red lo bloquea, usa la **memoria USB del kit** (sección 3.1). |

> Al instalar, Lynx **revisa tu PC** (memoria, disco, procesador, Windows y qué
> deja pasar la red de tu oficina) y te dice si está lista antes de empezar.

> Si tu PC no tiene internet en ese momento, Lynx te lo dice al instante.
> Conéctate y pulsa **Reparar**: retoma lo que ya había descargado.

---

## 3. Instalar la aplicación

1. Descarga el archivo **`LYNX-IA-KIT-Setup-0.2.6.exe`** desde
   **https://github.com/lynxdev-ia/lynx-ia-kit-releases/releases/latest**
   (o desde donde te lo hayan compartido).
2. Haz doble clic en el archivo.
3. Puede salir una pantalla azul: **"Windows protegió tu PC"**. Es normal: el
   archivo no lleva una firma de pago. Son dos pasos:
   - pulsa **Más información** (abajo, a la izquierda);
   - pulsa **Ejecutar de todas formas** (abajo, a la derecha).
4. Elige la carpeta (o deja la que viene) y termina. Se instala **solo para tu
   cuenta**, sin pedir permisos.

> Si alguna vez se abre una ventana pidiendo **permiso de administrador**, no es
> de esta app: ciérrala.

### 3.1 Instalar sin internet (memoria USB)

Si la red de tu oficina no deja descargar, quien te instala el kit puede
traerte una **memoria USB** con la carpeta **`LYNX-IA-KIT-USB`**. Trae el
instalador del kit, el de la IA local (Ollama) y su modelo de oficina.

1. Conecta la memoria USB.
2. Abre la carpeta `LYNX-IA-KIT-USB` y haz doble clic en el instalador del kit.
3. En el asistente elige **En tu PC**. Lynx encuentra la memoria solo e instala
   tu IA **desde ahí, sin descargar nada**.
4. **No quites la memoria** hasta que el asistente diga **¡Listo!**.

Antes de usar cada archivo de la memoria, Lynx comprueba su **huella**: si algo
está dañado, no lo usa y te lo dice. Con **En tu PC** no se instala nada de la
nube, así que no hace falta internet en ningún momento.

---

## 4. El asistente de instalación (la primera vez)

Al abrir la app, Lynx te guía por estas pantallas:

### Paso 1 · Bienvenida
"Hola, soy Lynx 🐾". Pulsa **EMPEZAR**.

### Paso 1.5 · ¿Cómo quieres tu IA?
Elige una de estas opciones. Si dudas, elige **En tu PC**: es privada y es la
que mejor le va a una oficina.

| Opción | Cómo funciona | Ten en cuenta |
|---|---|---|
| 🖥️ **En tu PC** ★ | Todo pasa en tu PC: lo que escribes no sale de tu oficina. | Sin costo y sin límites de uso, pero usa tu PC encendida, la primera vez descarga unos **5 GB** y necesita al menos **8 GB de memoria**. Funciona sin tarjeta gráfica; **la primera respuesta del día tarda un minuto**. |
| 🔀 **Híbrida** | La nube y tu PC juntas: si una falla, responde la otra. | Suma los límites de las dos. |
| ☁️ **OmniRoute** | La IA está en internet. | Los modelos sin costo tienen **límites de uso**: si un día se acaban, esperas un poco o pruebas otro. |
| 🔑 **OpenRouter** | Una llave para cientos de modelos en internet. | Los sin costo tienen límites; los de pago solo se pagan en su web oficial. **Consulta el precio actual en su web.** |
| 🗝️ **FreeLLMAPI** | Una sola llave para muchos modelos en internet. | Sin costo **con límites** (aprox. 2.000.000 de fragmentos de texto al mes y 40 consultas por minuto). **Verifícalos en su web oficial.** |

### Paso 2 · Reviso tu PC
Arriba verás una tarjeta con el **diagnóstico de tu equipo**: si tu PC está
**✓ lista**, **⚠ sirve con límites** (por ejemplo, "con 8 GB irá justo") o
**✗ tiene algo que impide instalar**. Lynx mira la memoria, el espacio en el
disco, el procesador, la versión de Windows, **qué deja pasar la red** de tu
oficina y si la IA local ya está. Pulsa **Ver el diagnóstico completo** para el
detalle, o **📋 Copiar diagnóstico** para enviárselo a quien te instala el kit.

Si elegiste **En tu PC**, eso es todo: Lynx te dice que tu IA se instalará en el
paso siguiente y pulsas **CONTINUAR**. La nube **viene apagada** y no se instala.

Si elegiste una opción con **nube** (OmniRoute, OpenRouter, FreeLLMAPI o
Híbrida), debajo Lynx comprueba **7 piezas** de la conexión a la nube y te las
muestra con un símbolo: **✓** está bien · **⚠** aviso · **✗** falta:

1. Node (el motor que usa la app)
2. OmniRoute (el programa de IA)
3. Servidor de IA encendido
4. Llave de IA
5. Configuración de OpenCode (opcional)
6. Llave guardada en tu PC
7. Arrancar solo al encender Windows

### Paso 3 · Instalo tu asistente
Lynx instala **solo lo que falta**, con una barra de progreso real.

- Con **En tu PC**, instala **solo tu IA de oficina** (nada de la nube).
- Con una opción de **nube**, instala la conexión a la nube; si tu PC no tiene
  Node, **lo descarga y lo deja listo sin pedirte nada**. Con **Híbrida**, las
  dos cosas.

Para tu IA de oficina (**En tu PC** o **Híbrida**), Lynx:
descarga el programa **Ollama** (comprobando que el archivo es el oficial), lo
deja **solo para tu cuenta, sin pedir permisos ni abrir ninguna ventana** (la IA
trabaja en segundo plano: no verás la aplicación de Ollama ni te pedirá iniciar
sesión), y baja su modelo de oficina
(**gemma3:4b**, unos 3 GB). Es la parte más larga: según tu internet, de unos
minutos a media hora.

Si algo falla, te explica qué pasó y qué hacer, con palabras normales.

> Puedes repetir la instalación las veces que quieras: lo que ya está bien no se
> toca.

### Paso 4 · ¡Probemos que funciona!
Escribe un mensaje y pulsa **ENVIAR**. Si la IA te contesta, todo está listo.
Con la IA en tu PC, **la primera respuesta puede tardar un minuto** mientras se
despierta; las siguientes salen más rápido.

### Paso 5 · ¡Ya tienes tu IA lista! 🎉
- **USAR AHORA** o **VER PANEL**: abren tu asistente de oficina (el panel).
- Desde ahora, el **acceso directo «LYNX IA KIT»** del escritorio (y del menú
  Inicio) **abre directamente el panel**: la instalación no se repite.
- **¿Y si Windows me pregunta?**: te explica el aviso azul de Windows.
- **¿Y si quiero la nube de Ollama?**: te ayuda a crear una cuenta de Ollama en
  internet (ver sección 7).

---

## 5. El panel de control

Es la ventana que usarás cada día. Arriba tiene **3 pestañas de uso diario**:
🏠 Estado, 💬 Probar y 🖥️ Modelos locales.

Las pestañas de la **nube** (📦 Proveedores, 📊 Uso, ⚙️ Ajustes y
🔌 Plataformas) van escondidas porque no hacen falta para trabajar con la IA de
tu PC. Para verlas, pulsa **☁️ Nube** arriba a la derecha; para esconderlas otra
vez, **☁️ Ocultar nube**. La app recuerda lo que elegiste. Si al instalar
elegiste una opción con nube, esas pestañas ya salen visibles.

> 🧭 **La primera vez que lo abras, Lynx te hace una visita guiada** de 6 pasos
> por las pestañas de uso diario. Usa **Siguiente ▶** y **◀ Atrás** (o las flechas del
> teclado), o **Saltar guía** (o la tecla Esc) si ya lo conoces. Al terminar te
> deja en 💬 Probar. Para verla otra vez, pulsa **❓ Guía** arriba a la derecha.
>
> 📖 **Este manual también está dentro de la app**: pulsa **📖 Manual** (junto a
> ❓ Guía) y se abre en su propia ventana, sin necesidad de internet.

### 🏠 Estado
Revisa **solo lo que usas**:

- Con **En tu PC**: una fila, **Tu IA en tu PC (gemma3:4b)**, ✓ si está
  instalada y lista. La nube no se revisa (no está instalada).
- Con una opción de **nube**: las 7 comprobaciones de la conexión a la nube.
- Con **Híbrida**, o si abres **☁️ Nube**: las dos, con el rótulo
  **Conexión a la nube (opcional)** separándolas.

Cada fila lleva su símbolo ✓ / ⚠ / ✗.

- **REPARAR**: arregla lo que falte. Si falta tu IA de oficina, **la instala**
  (la primera vez descarga unos 5 GB, o la copia de la memoria USB); si la nube
  está en la revisión, también la repara. Si todo está bien, el mismo botón
  vuelve a comprobar.
- **Reiniciar servicio**: aparece si la conexión a la nube (OmniRoute) no
  responde. Tu IA en tu PC no depende de ella.
- **📋 Copiar informe para soporte**: copia un resumen del estado de tu PC, y
  de los últimos problemas que Lynx te mostró, para que lo pegues (**Ctrl+V**)
  en un mensaje a quien te ayuda. **No lleva tu clave, ni tus conversaciones,
  ni tu nombre de usuario.** No se envía a ningún sitio: solo se copia.

### 💬 Probar — tu asistente de oficina
Aquí hablas con tu IA.

- **Tu IA** ya viene elegida: con **En tu PC** o **Híbrida**, **gemma3:4b
  (recomendado, en tu PC)**; con una opción de nube, la IA de esa nube. Si tienes
  otros modelos, puedes cambiarla arriba.
- **Atajos de tarea**: ✍️ Escribir carta · 📄 Resumir · 🌍 Traducir ·
  ✅ Corregir · ✉️ Redactar correo. Rellenan el mensaje con un ejemplo que
  completas tú.
- **📎 Adjuntar un archivo** para que la IA lo lea:
  - Word (`.docx`), PDF (`.pdf`), Excel (`.xlsx`) y textos (`.txt`, `.md`,
    `.csv`, `.json`, `.log`, `.tsv`).
  - Hasta **10 MB**.
  - Un PDF **escaneado** (solo imágenes) todavía no se puede leer.
  - Lynx te avisa dónde va tu archivo: con un modelo **local** no sale de tu PC;
    con un modelo **en la nube** se envía a ese proveedor.
- **NUEVA CONVERSACIÓN**: empieza de cero.

#### 📝 Corregir un documento

En 💬 Probar, pulsa **📝 Corregir un documento**:

1. Pulsa **📎 Elegir documento** (Word, PDF o texto) o **pega el texto** en el
   recuadro, y pulsa **CORREGIR**. Lynx revisa la ortografía, las tildes, la
   puntuación y la redacción. Un documento largo se revisa por partes; verás el
   avance.
2. Verás **dos columnas**: a la izquierda el **Original** (lo que se quita,
   **tachado**) y a la derecha el **Corregido** (lo que se pone, **subrayado**,
   con **✓**).
3. **Tú decides cada cambio**: pulsa uno de la derecha para **rechazarlo** (✗,
   vuelve lo que tenías) o para aceptarlo otra vez. También hay **✓ Aceptar
   todos** y **✗ Rechazar todos**.
4. Cuando estés de acuerdo:
   - **📋 COPIAR TEXTO FINAL**: copia el texto con solo los cambios que
     aceptaste. Ve a tu documento, selecciona el texto viejo y pega (**Ctrl+V**):
     así **conservas tu formato**.
   - **💾 Guardar como Word**: guarda un Word **nuevo** con el texto final. Lleva
     el texto, pero **no el formato del original** (tipos de letra, tablas,
     imágenes).

Tu documento original **nunca se modifica**. La IA puede equivocarse: revisa
cada cambio antes de aceptarlo.

> 🐾 **Un consejo de Lynx:** lo que escribe cualquier IA puede traer errores.
> Léelo con calma y dale tu visto bueno antes de usarlo. Tú tienes la última
> palabra.

### ☁️ Pestañas de la nube (opcionales)

Solo se ven si pulsas **☁️ Nube**. Sirven si algún día quieres usar IA de
internet además de la de tu PC.

### 📦 Proveedores
Lista las conexiones de IA que tienes (por ejemplo, las cuentas en internet) con
su símbolo ✓ / ⚠ / ✗. **VER DASHBOARD** abre el panel avanzado de OmniRoute en
tu navegador.

### 📊 Uso
Cuánto has usado tu IA: peticiones hechas, *tokens* (los trocitos de texto que
cuenta la IA), porcentaje de respuestas correctas, tiempo medio de respuesta, el
coste que registra tu servidor, los modelos que más usas y los límites de cada
cuenta. Elige el periodo (último día, 7, 30 o 90
días, este año o desde el principio) y pulsa **ACTUALIZAR**. Lynx solo te
enseña cifras que puede comprobar: nunca inventa números.

### ⚙️ Ajustes
- **Que la app arranque sola** al encender Windows (**ACTIVAR**).
- **Tu modelo por defecto**: el que se usa si no eliges otro.
- **Versión de tu motor** y **ACTUALIZAR** para poner al día el programa de IA.
  Lynx te dice si había algo que actualizar o no.

### 🖥️ Modelos locales (Ollama)
Para la IA que funciona **dentro de tu PC**.

- Ves los modelos que tienes, cuánto ocupan, y puedes **BORRAR** los que no uses
  (el botón cambia a **CONFIRMAR BORRADO** para que no lo hagas sin querer).
- **DESCARGAR** uno nuevo: de 2 GB (PC justa) a 20 GB (equipos muy potentes).
- Lynx mira tu memoria y tu tarjeta gráfica y marca con **★ recomendado para tu
  PC** el que mejor te va. Es solo una sugerencia: puedes elegir otro.
- También te muestra si tienes la nube de Ollama conectada.

### 🔌 Plataformas
Conecta otras empresas de IA con tu propia clave. Hoy vienen preparadas:
**OpenRouter, OmniRoute, Ollama, Groq, LM Studio, Mistral, FreeLLMAPI y
Together.**

1. Pulsa **➕ AÑADIR PLATAFORMA** y elige una.
2. Si te la pide, **pega tu clave**. Se guarda **solo en tu PC** y nunca se
   enseña entera.
3. Lynx la conecta paso a paso y te muestra el resultado.

- Cada plataforma muestra sus **límites** y un enlace a su web. Algunas tienen
  modelos sin costo **con límites**; otras son **de pago** (Lynx te lo dice).
  **Verifica siempre el precio actual en su web oficial.**
- **DESCONECTAR** quita una plataforma (pide confirmar).
- **↻ ACTUALIZAR CATÁLOGO** trae la lista de plataformas más reciente. Por
  seguridad, solo acepta plataformas que no instalen programas desconocidos.
- **Modo experto**: si alguien de confianza te da una "receta" de plataforma,
  pégala aquí (**GUARDAR MI RECETA**). Se suma a tu lista sin borrar nada.

---

## 6. Actualizaciones

Desde la versión **0.2.0** la app **se actualiza sola**:

1. Cuando hay una versión nueva, la descarga en segundo plano.
2. Te pregunta: **Instalar ahora** o **Más tarde**.
   - **Instalar ahora**: la app se cierra un momento y vuelve a abrirse.
   - **Más tarde**: se instala sola la próxima vez que cierres la app.

Sin internet no pasa nada: lo intentará la próxima vez.

> Si tienes la versión 0.1.0, instala la 0.2.0 a mano una vez (sección 3). A
> partir de ahí, se actualiza sola.

---

## 7. La nube de Ollama (opcional)

Si tu PC no da para los modelos grandes, puedes usar la **nube de Ollama**:

1. **ENTRAR EN MI CUENTA**: se abre la web oficial de Ollama en tu navegador.
   Crear la cuenta pide solo nombre y correo, sin tarjeta, y trae **créditos de
   prueba limitados**.
2. **COMPROBAR QUE FUNCIONA**: Lynx prueba la nube y te enseña su respuesta.
3. Si se acaban tus créditos, Lynx te avisa.

**Ver los planes** te muestra los planes de Ollama con su precio de referencia,
pero los precios cambian: **míralos siempre en ollama.com/pricing**. El pago,
si algún día lo quieres, se hace **solo en la web oficial**, nunca en esta app.

---

## 8. Si algo no funciona

| Lo que ves | Qué hacer |
|---|---|
| "No hay conexión a internet" | Conéctate y pulsa **REPARAR**. Retoma donde iba. |
| ✗ en alguna comprobación de 🏠 Estado | Pulsa **REPARAR**. |
| "El servicio no está respondiendo" | Pulsa **Reiniciar servicio** y espera un par de minutos (el servidor tarda en despertar). |
| La IA no contesta en 💬 Probar | Prueba otro modelo o pulsa **REINTENTAR**. Si usas un modelo con límites, puede que se hayan agotado por hoy. |
| "Windows protegió tu PC" al abrir el archivo | **Más información → Ejecutar de todas formas** (sección 3). |
| Nada de lo anterior | En 🏠 Estado pulsa **📋 Copiar informe para soporte** y envíaselo a quien te ayuda. |

---

## 9. Tu privacidad

- Tu **clave de IA** se guarda solo en tu cuenta de Windows. Nunca se enseña
  entera ni va en el informe de soporte.
- Con un modelo **local** (Ollama), tus mensajes y archivos **no salen de tu
  PC**. Con un modelo **en la nube**, se envían a ese proveedor: Lynx te lo
  avisa antes.
- La app **no recoge datos tuyos** ni los envía a nadie. Solo se conecta a
  internet para instalar lo que necesita, buscar actualizaciones y traer la
  lista de plataformas (todo desde páginas oficiales).

---

## 10. Desinstalar

Ve a **Configuración de Windows → Aplicaciones**, busca **LYNX IA KIT** y pulsa
**Desinstalar**. Tus ajustes se conservan por si vuelves a instalarla.

---

*Desarrollado por Carlos Lince.*
