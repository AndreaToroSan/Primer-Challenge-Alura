# Amigo Secreto

Una aplicación web sencilla para gestionar un sorteo de "amigo secreto". Con esta herramienta podrás agregar nombres, visualizar una lista de participantes y realizar un sorteo aleatorio para asignar a cada persona su amigo secreto, ideal para intercambios de regalos o actividades lúdicas.

---

## Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Instalación y Uso](#instalación-y-uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Autor](#autor)

---

## Descripción

Esta aplicación permite a los usuarios ingresar nombres de amigos, los cuales se muestran en una lista. Posteriormente, mediante un sorteo aleatorio, se selecciona un nombre de la lista para determinar quién será el "amigo secreto". La interfaz se ha diseñado con HTML y CSS para ofrecer una experiencia visual agradable, y se usa JavaScript para la lógica del sorteo.

---

## Características

- **Agregar Nombres:**  
  Permite añadir nombres de amigos a través de un campo de texto.
  
- **Validación de Entrada:**  
  Se evita agregar entradas vacías, mostrando una alerta si el campo está sin rellenar.

- **Visualización de la Lista:**  
  Los nombres ingresados se actualizan y muestran en una lista visible en la página.

- **Sorteo Aleatorio:**  
  Con un solo clic, se realiza un sorteo aleatorio que selecciona un nombre de la lista y lo muestra en pantalla.

---

## Instalación y Uso

1. **Clonar el repositorio:**

    ```bash
    git clone https://github.com/tuusuario/amigo-secreto.git
    ```

2. **Navegar al directorio del proyecto:**

    ```bash
    cd amigo-secreto
    ```

3. **Ejecutar la aplicación:**

   Abre el archivo `index.html` en tu navegador favorito, o utiliza un servidor local (por ejemplo, Live Server en VS Code) para ver la aplicación en funcionamiento.

---

## Estructura del Proyecto

```plaintext
amigo-secreto/
├── index.html      # Estructura y contenido de la página
├── style.css       # Estilos de la aplicación
└── app.js          # Lógica para agregar amigos y realizar el sorteo
