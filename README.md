#  📦 MiniPedidos & BaristaApp

Este repositorio contiene dos proyectos de ejemplo en Kotlin:

MiniPedidos → Gestión básica de pedidos con formulario y lógica de negocio.

BaristaApp → Interfaz de configuración de café con componentes de Material Design.

#  🚀 Compatibilidad

✅ Android Studio (recomendado)
✅ IntelliJ IDEA (modo consola para la parte de MiniPedidos)

En Android Studio, para una correcta previsualización de la interfaz, se recomienda usar un emulador Pixel 6 con Android 12 o superior.

#  📂 Estructura del proyecto

La siguiente captura representa la organización de archivos y carpetas del proyecto en Android Studio:

<img width="590" height="604" alt="Captura de pantalla 2025-09-29 110414" src="https://github.com/user-attachments/assets/40fd516c-19c4-460b-8096-cc0de273b653" />


#  📱 Android (BaristaApp)

Construido con View Binding.

Incluye:

TextView, Button, CheckBox, ChipGroup + Chip, Slider (Material), MaterialDivider.

Cálculo automático del total del café.

Snackbar/Toast al realizar el pedido.

#  💻 Consola (MiniPedidos en IntelliJ IDEA)

Gestión de pedidos en Kotlin con:

Creación de pedidos (Pedido e Item).

Estados de pedido (En preparación → Listo → Cobrado).

Parseo de texto para crear pedidos (Pedido.desdeTexto(...)).

Ejecución en consola con función main().

#  ⚙️ Requisitos

Android Studio Ladybug (2024 o superior)

Gradle 8+

Kotlin 1.9+

Material Components

#  ▶️ Ejecución
#  En Android Studio:

Abrir la carpeta del proyecto.

Sincronizar Gradle.

Seleccionar Pixel 6 (API 33 o superior) como dispositivo virtual.

Ejecutar el proyecto desde MainActivity.

#  En IntelliJ IDEA (MiniPedidos):

Abrir la carpeta minipedidos.

Ejecutar la clase Main.kt.

Ver resultados en consola.
