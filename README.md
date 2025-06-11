# Adeidad
Adeidad es un software en sistema operativo android que implementa las mejores practicas de programación, patrones de diseño.

# 📱 Aplicación Android: Actividades Didácticas Interactivas

Este proyecto es una **aplicación Android desarrollada en Java y XML**, centrada en ofrecer un entorno interactivo de aprendizaje mediante un conjunto de actividades didácticas accesibles desde un menú principal. El objetivo principal de esta aplicación es **demostrar y aplicar las mejores prácticas de programación**, siguiendo principios de escalabilidad, limpieza de código y arquitectura modular.

---

## ✨ Objetivos del Proyecto

- 🧱 **Estructuración clara del código**: Separación de responsabilidades siguiendo buenas prácticas de arquitectura (paquetes bien definidos, recursos organizados, ViewModel por fragmento).
- 🎯 **Escalabilidad**: El proyecto está diseñado para crecer fácilmente añadiendo nuevas actividades sin comprometer la mantenibilidad del código.
- 🧑‍🏫 **Enfoque didáctico**: Cada módulo de la aplicación representa una actividad educativa con interacción directa, útil tanto para enseñar como para aprender desarrollo Android.
- 💡 **Buenas prácticas en Java y XML**: Se implementa una lógica clara con Java y una interfaz limpia con XML, utilizando componentes tanto desde la paleta como programáticamente.

---

## 🧩 Arquitectura del Proyecto

El proyecto sigue una organización limpia en paquetes y recursos:

📦 com.example.adedidad
┣ 📂 ui → Fragmentos y actividades
┣ 📂 viewmodel → ViewModels por pantalla (MVVM)
┣ 📂 utils → Utilidades reutilizables
┣ 📂 model → Estructuras de datos si aplica

🗂️ res/
┣ 📁 layout → Archivos XML de diseño
┣ 📁 menu → Menús de navegación y acciones
┣ 📁 navigation → Navigation Graphs (Jetpack Navigation)
┣ 📁 values → Strings, estilos, colores y temas


---

## 🛠️ Tecnologías Utilizadas

- **Lenguaje**: Java
- **UI/UX**: XML (Componentes visuales desde paleta o por código)
- **Arquitectura**: MVVM (Model-View-ViewModel)
- **Android Jetpack Components**: Navigation, ViewModel, LiveData (si aplica)
- **IDE**: Android Studio
![image](https://github.com/user-attachments/assets/30d4d840-501a-4440-a5c4-d2b6170df16a)
![image](https://github.com/user-attachments/assets/2f8d5741-bdc3-4daa-b844-c28509d8e81c)
![image](https://github.com/user-attachments/assets/ce32c240-e6b2-48a3-8ba3-c426650f4a38)



---

## 🧪 Actividades Didácticas

Cada fragmento dentro de la app representa una **actividad interactiva** accesible desde un menú principal. El usuario podrá:

- Mostrar/Ocultar elementos dinámicamente
- Interactuar con entradas de texto
- Realizar acciones que refuerzan conceptos clave del desarrollo Android

---

## 📌 Contribución y Escalabilidad

El proyecto está diseñado para facilitar la **colaboración y extensión**. Puedes crear nuevas actividades como fragmentos independientes, conectar sus ViewModel, y agregarlas al gráfico de navegación sin afectar la estructura existente.

---

## 📷 Vista de Estructura (Android View)

![Estructura del proyecto](https://github.com/tuusuario/tu-repo/raw/main/capturas/estructura.png)
<!-- Reemplaza el enlace con la ruta correcta si subes una captura -->

---

## ✅ Conclusión

Este proyecto no solo funciona como una aplicación funcional, sino también como un recurso educativo, mostrando cómo escribir código limpio, desacoplado y mantenible. Ideal para estudiantes, desarrolladores en formación o como base para proyectos más grandes.
