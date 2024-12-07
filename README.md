# ics# Generador de Eventos ICS

Este proyecto es una herramienta web que permite crear archivos ICS (eventos de calendario) de forma sencilla. Ofrece una interfaz intuitiva para ingresar información sobre eventos, seleccionar fechas y configurar horarios, y finalmente descargar el archivo ICS resultante.

## Características

- **Agregar nombre y descripción** al evento.
- **Seleccionar uno o varios meses** a visualizar en el calendario.
- **Marcar las fechas** de los eventos directamente en el calendario.
- Configurar el tipo de evento:
  - **Horario regular**: Una hora de inicio obligatoria y una hora de fin o una duración.
  - **Horario no regular**: Configurar horarios individuales para cada fecha seleccionada.
- **Generar y descargar** el archivo ICS resultante.
- **Visualizar el contenido** del ICS antes de descargarlo.
- **Restablecer el formulario** en cualquier momento.
- Instrucciones disponibles en una **ventana emergente**.

## Guía de Estilo de NamasData

Este proyecto implementa la guía de estilo de NamasData, utilizando la paleta de colores, tipografías y estilos de botones indicados:

### Colores

- Fondo principal: `#FAF9F9`
- Titulares (Headings): `#E63946`
- Subtitulares (Subheadings): `#18A4E6`
- Texto cuerpo: `#074983`
- Botones primarios: Fondo `#E63946`, texto `#FAF9F9`, contorno `#074983`
- Botones secundarios: Fondo `#FFFFFF`, texto `#074983`, contorno `#074983`
- Enlaces: `#18A4E6`

### Tipografías

- **Montserrat**: Para banners, headings, subheadings y cuerpo del texto.
- **Roboto**: Para el texto de los botones.

### Tamaños y Pesos

- Heading principal: ~36px (`text-3xl` en Tailwind), peso Medium.
- Subheading: ~22px (`text-2xl`), peso Regular.
- Cuerpo: 16px (`text-base`), peso Regular.
- Botones: 16px (`text-base`), peso Regular (Roboto).

## Tecnologías Utilizadas

- **HTML5 y CSS3**: Para la estructura y el estilo.
- **Tailwind CSS**: Para el diseño responsivo y la aplicación de la guía de estilo.
- **JavaScript**: Para la lógica del calendario, la generación del ICS y la manipulación del DOM.
- Fuentes desde **Google Fonts** (Montserrat y Roboto).

## Uso

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Ingresa el nombre del evento y la descripción.
4. Ajusta el número de meses a mostrar y selecciona las fechas del evento.
5. Configura el tipo de evento y horario.
6. Genera el archivo ICS o visualiza el texto antes de descargarlo.

## Personalización

- Puedes modificar la paleta de colores y la tipografía en el archivo `<style>` del `index.html`.
- Para cambiar el comportamiento o la lógica del calendario, edita el script incrustado en el `index.html`.

## Contribución

Las contribuciones son bienvenidas. Si encuentras algún error o deseas añadir nuevas funcionalidades, puedes abrir un **issue** o enviar un **pull request**.

## Licencia

Este proyecto se publica bajo la [MIT License](LICENSE).
