# Cliente de aplicación de gestión de películas

Este proyecto es la interfaz de usuario de una aplicación de gestión de películas que permite realizar operaciones de creación, lectura, actualización y eliminación (CRUD) sobre un conjunto de películas. La aplicación está desarrollada en React y utiliza Axios para comunicarse con un servidor backend.

---

## Características

- **Agregar películas**: Permite ingresar el nombre, director, descripción y año de una película.
- **Listar películas**: Muestra todas las películas almacenadas en la base de datos.
- **Editar películas**: Actualiza los detalles de una película existente.
- **Eliminar películas**: Elimina una película seleccionada de la base de datos.

---

## Requisitos previos

Asegúrate de tener instalados los siguientes componentes antes de comenzar:

- [Node.js](https://nodejs.org/) (v14 o superior recomendado)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)
- Un servidor backend en funcionamiento (consulta el repositorio del servidor si lo tienes disponible).

---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd client
   ```

3. Instala las dependencias necesarias:
   ```bash
   npm install
   ```
   o, si usas Yarn:
   ```bash
   yarn install
   ```

---

## Dependencias utilizadas

El proyecto utiliza las siguientes dependencias principales:

- **React**: Biblioteca para construir la interfaz de usuario.
- **Axios**: Librería para realizar solicitudes HTTP.
- **Bootstrap**: Framework CSS para el diseño de la interfaz.

Estas dependencias se pueden instalar automáticamente al ejecutar `npm install` o `yarn install`.

---

## Configuración

1. Asegúrate de que tu servidor backend esté funcionando y que esté configurado para escuchar en el puerto `3001` (o ajusta las URLs en el código fuente de este cliente).

2. Verifica las rutas utilizadas en el backend:
   - `POST http://localhost:3001/create`: Crear una nueva película.
   - `PUT http://localhost:3001/update`: Actualizar una película existente.
   - `DELETE http://localhost:3001/delete/:id`: Eliminar una película por su ID.
   - `GET http://localhost:3001/peliculas`: Listar todas las películas.

---

## Ejecución

1. Inicia la aplicación cliente:
   ```bash
   npm start
   ```
   o, si usas Yarn:
   ```bash
   yarn start
   ```

2. Abre tu navegador en `http://localhost:3000` para ver la aplicación en funcionamiento.

---

## Uso

1. Completa el formulario con los detalles de la película y haz clic en **Guardar** para agregarla.
2. Usa los botones **Editar** y **Eliminar** en la tabla para actualizar o borrar películas.
3. La lista de películas se actualiza automáticamente después de cada operación.

---

## Estructura del proyecto

```plaintext
client/
├── public/              # Archivos públicos
├── src/                 # Código fuente
│   ├── App.css          # Estilos principales
│   ├── App.js           # Componente principal
│   ├── index.js         # Punto de entrada de React
│   └── ...
├── package.json         # Dependencias y scripts
└── ...
```

---

## Tecnologías utilizadas

- **React**: Para la construcción de la interfaz de usuario.
- **Axios**: Para la comunicación con el backend.
- **Bootstrap**: Para el diseño y estilos.

---

## Contribuciones

Si deseas contribuir, abre un Issue o realiza un Pull Request en este repositorio.

---

## Licencia

Este proyecto está licenciado bajo los términos de la [MIT License](LICENSE).
