<h1>Sorteo Regina Boutique</h1>

# Sorteo Regina Boutique App

## Descripción
La aplicación "Sorteo Regina Boutique" permite a los usuarios ingresar nombres de amigos en una lista o desde la carga de un archivo en Excel y realizar un sorteo aleatorio para determinar quién es el "Ganador". Los usuarios pueden agregar nombres, visualizar la lista y se seleccionará un nombre aleatoriamente al dar clic en el botón "Sortear amigo".

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

```
amigo-secreto-app
├── src
│   ├── index.html      # Estructura principal de la aplicación
│   ├── styles.css      # Estilos CSS para la aplicación
│   └── app.js          # Lógica de la aplicación
└── README.md            # Documentación del proyecto
```

## Instalación
1. Clona el repositorio en tu máquina local.
2. Navega al directorio del proyecto.

## Ejecución
Para ejecutar la aplicación, abre el archivo `/index.html` en tu navegador web.

## Funcionalidades
- **Agregar nombres**: Los usuarios pueden ingresar el nombre de un amigo en un campo de texto y agregarlo a la lista visible al hacer clic en "Adicionar" o desde un archivo en Excel.
- **Validar entrada**: Si el campo de texto está vacío, se mostrará una alerta pidiendo un nombre válido.
- **Validar participantes para sorteo**: Si la lista de amigos no cuenta con un mínimo de dos participantes, se mostrará una alerta indicando que no se cuenta con los participantes necesarios para realizar el sorteo.
- **Validar nombre duplicado**: Si el nombre del amigo ya se encuentra y tenemos un amigo con el mismo nombre, se nos mencionará que se agrega un número para distinguir al nuevo amigo con nombre similar.
- **Visualizar la lista**: Los nombres ingresados aparecerán en una lista debajo del campo de entrada.
- **Sorteo aleatorio**: Al hacer clic en el botón "Sortear Amigo", se seleccionará aleatoriamente un nombre de la lista y se mostrará en la página.
- **Eliminar amigo sorteado**: Después del sorteo se elimina de la lista el nombre del amigo sorteado y se actualiza la lista con los amigos restantes para proceder a un nuevo sorteo.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia
Este proyecto está bajo la Licencia MIT.