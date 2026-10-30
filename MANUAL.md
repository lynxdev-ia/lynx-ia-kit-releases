# Manual de usuario — LYNX IA KIT 🐾

*Versión 0.2.2 · octubre de 2026 · para Windows 10 y 11 (64 bits)*

Hola, soy **Lynx**, el lince que te acompaña. Este manual te cuenta qué hace
LYNX IA KIT y cómo usarlo, paso a paso y sin palabras raras.

---

## 1. ¿Qué es LYNX IA KIT?

Es una aplicación que **pone una inteligencia artificial (IA) en tu computador**
y te deja usarla como **asistente de oficina**: escribir cartas, resumir
documentos, traducir, corregir textos o redactar correos.

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
| **Conexión a internet** | La instalación descarga lo que necesita (unos **2 GB**). Sin internet no puede terminar. |
| Unos 3 GB libres en el disco | Para el programa de IA. Si eliges la IA en tu PC (Ollama), cada modelo ocupa entre 2 y 20 GB más. |

> Si tu PC no tiene internet en ese momento, Lynx te lo dice al instante.
> Conéctate y pulsa **Reparar**: retoma lo que ya había descargado.

---

## 3. Instalar la aplicación

1. Descarga el archivo **`LYNX-IA-KIT-Setup-0.2.2.exe`** desde
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

---

## 4. El asistente de instalación (la primera vez)

Al abrir la app, Lynx te guía por estas pantallas:

### Paso 1 · Bienvenida
"Hola, soy Lynx 🐾". Pulsa **EMPEZAR**.

### Paso 1.5 · ¿Cómo quieres tu IA?
Elige una de estas opciones (si dudas, la **Híbrida** es la que mejor le va a
casi todos):

| Opción | Cómo funciona | Ten en cuenta |
|---|---|---|
| ☁️ **OmniRoute** | La IA está en internet. | Los modelos sin costo tienen **límites de uso**: si un día se acaban, esperas un poco o pruebas otro. |
| 🖥️ **Ollama local** | Todo pasa en tu PC: nada sale de casa. | Ocupa varios GB, usa tu PC encendida y va más lento sin tarjeta gráfica. Lynx mide tu PC y te recomienda un modelo. |
| 🔀 **Híbrida** ★ | La nube y tu PC juntas: si una falla, responde la otra. | Suma los límites de las dos. |
| 🗝️ **FreeLLMAPI** | Una sola llave para muchos modelos en internet. | Sin costo **con límites** (aprox. 2.000.000 de fragmentos de texto al mes y 40 consultas por minuto). **Verifícalos en su web oficial.** |

### Paso 2 · Reviso tu PC
Lynx comprueba **7 cosas** y te las muestra con un símbolo:
**✓** está bien · **⚠** aviso · **✗** falta.

1. Node (el motor que usa la app)
2. OmniRoute (el programa de IA)
3. Servidor de IA encendido
4. Llave de IA
5. Configuración de OpenCode (opcional)
6. Llave guardada en tu PC
7. Arrancar solo al encender Windows

### Paso 3 · Instalo tu asistente
Lynx instala **solo lo que falta**, con una barra de progreso real. Si tu PC no
tiene Node, **lo descarga y lo deja listo sin pedirte nada**. Si algo falla, te
explica qué pasó y qué hacer, con palabras normales.

> Puedes repetir la instalación las veces que quieras: lo que ya está bien no se
> toca.

### Paso 4 · ¡Probemos que funciona!
Escribe un mensaje y pulsa **ENVIAR**. Si la IA te contesta, todo está listo.

### Paso 5 · ¡Ya tienes tu IA lista! 🎉
- **USAR AHORA** o **VER PANEL**: abren tu asistente de oficina (el panel).
- **¿Y si Windows me pregunta?**: te explica el aviso azul de Windows.
- **¿Y si quiero la nube de Ollama?**: te ayuda a crear una cuenta de Ollama en
  internet (ver sección 7).

---

## 5. El panel de control

Es la ventana que usarás cada día. Tiene 7 pestañas arriba.

> 🧭 **La primera vez que lo abras, Lynx te hace una visita guiada** de 9 pasos
> por todas las pestañas. Usa **Siguiente ▶** y **◀ Atrás** (o las flechas del
> teclado), o **Saltar guía** (o la tecla Esc) si ya lo conoces. Al terminar te
> deja en 💬 Probar. Para verla otra vez, pulsa **❓ Guía** arriba a la derecha.
>
> 📖 **Este manual también está dentro de la app**: pulsa **📖 Manual** (junto a
> ❓ Guía) y se abre en su propia ventana, sin necesidad de internet.

### 🏠 Estado
Muestra las 7 comprobaciones con su símbolo ✓ / ⚠ / ✗.

- **REPARAR**: arregla lo que falte. Si todo está bien, el mismo botón vuelve a
  comprobar.
- **Reiniciar servicio**: aparece si el servidor de IA no responde.
- **📋 Copiar informe para soporte**: copia un resumen del estado de tu PC para
  que lo pegues (**Ctrl+V**) en un mensaje a quien te ayuda. **No lleva tu
  clave, ni tus conversaciones, ni tu nombre de usuario.** No se envía a
  ningún sitio: solo se copia.

### 💬 Probar — tu asistente de oficina
Aquí hablas con tu IA.

- **Elige el modelo** arriba (o deja *auto*: Lynx lo elige por ti).
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

> 🐾 **Un consejo de Lynx:** lo que escribe cualquier IA puede traer errores.
> Léelo con calma y dale tu visto bueno antes de usarlo. Tú tienes la última
> palabra.

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
