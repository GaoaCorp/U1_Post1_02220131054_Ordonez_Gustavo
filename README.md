# Ecosistema Móvil – Aplicación Android

Este proyecto corresponde a una aplicación Android desarrollada en **Kotlin** como parte del laboratorio/práctica de la asignatura **Aplicaciones Móviles – Ecosistema Móvil**.  
La aplicación presenta información sobre distintos paradigmas del desarrollo móvil y demuestra el uso del sistema de logs de Android (Logcat).

---

## 📋 Requisitos

- Android Studio (versión reciente recomendada)
- JDK 17 o superior
- Emulador Android o dispositivo físico
- API mínima: Android 8.0 (API 26)

---

## ▶️ Instrucciones para ejecutar el proyecto

1. Abrir **Android Studio**
2. Seleccionar **Open an existing project**
3. Abrir la carpeta del proyecto **EcosistemaMovil**
4. Esperar a que Gradle sincronice automáticamente
5. Seleccionar un emulador o dispositivo físico
6. Presionar el botón **Run (▶)**

La aplicación se ejecutará mostrando la interfaz con la información del ecosistema móvil.

---

## 🖥️ Funcionalidades principales

- Creación de interfaz de usuario mediante código (sin XML)
- Uso de `LinearLayout` y `ScrollView`
- Visualización de tarjetas informativas
- Implementación de logs con distintos niveles:
  - `Log.d` (Debug)
  - `Log.w` (Warning)
  - `Log.e` (Error)

---

## 🧪 Uso de Logcat

Durante la ejecución de la aplicación se generan mensajes visibles en **Logcat**:

- 🔵 Azul: mensajes de depuración (`Log.d`)
- 🟡 Amarillo: advertencias (`Log.w`)
- 🔴 Rojo: errores (`Log.e`)

Estos logs permiten analizar el comportamiento interno de la aplicación durante su ejecución.

---

## 🖼️ Capturas de la aplicación

### Interfaz principal
![Interfaz principal](capturas/interfaz_principal.png)

### Logs en Logcat
![Logs en Logcat](capturas/logcat.png)

---

## ⚠️ Problemas encontrados

- Se presentó un error inicial por el uso de `AppCompatActivity` sin la dependencia correspondiente.
- El problema se resolvió utilizando `ComponentActivity`.
- Algunas advertencias del sistema Android aparecen en Logcat, pero no afectan el funcionamiento de la aplicación.

---

## ✅ Estado del proyecto

✔ Proyecto funcional  
✔ Compilación exitosa  
✔ Ejecución correcta en emulador  
✔ Logs visibles en Logcat

---

## 👤 Autor

- **Nombre:** Gustavo Ordoñez
- **Programa:** Ingeniería de Sistemas
- **Asignatura:** Aplicaciones Móviles  