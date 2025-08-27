# 👥 Users CRUD App

Aplicación web CRUD para gestión de usuarios desarrollada con React. Permite crear, leer, actualizar y eliminar usuarios con una interfaz moderna que incluye modales CSS y formularios dinámicos.

## 🌟 Características

- **CRUD completo** - Crear, leer, actualizar y eliminar usuarios
- **Interfaz moderna** con modales CSS personalizados
- **Formularios dinámicos** que se adaptan para crear/editar
- **Validación de datos** en tiempo real
- **Diseño responsivo** que funciona en todos los dispositivos
- **Confirmaciones de eliminación** para evitar borrados accidentales
- **Integración con API REST** para persistencia de datos
- **Gestión de estado** con React Hooks

## 🚀 Demo en Vivo

🔗 **[https://00004-users-management.netlify.app](https://00004-users-management.netlify.app)**

## 🛠️ Tecnologías Utilizadas

- **React 17** - Biblioteca de JavaScript para interfaces de usuario
- **Axios** - Cliente HTTP para consumo de API
- **CSS3** - Estilos modernos con modales y animaciones
- **JavaScript ES6+** - Funcionalidades modernas del lenguaje
- **React Hooks** - useState y useEffect para gestión de estado
- **API REST** - Integración con backend para persistencia

## 📁 Estructura del Proyecto

```
00004-users-crud/
├── public/
│   ├── index.html
│   └── user.png              # Icono de usuario
├── src/
│   ├── components/
│   │   ├── UserForm.js       # Formulario para crear/editar usuarios
│   │   └── UsersList.js      # Lista de usuarios con acciones
│   ├── App.js                # Componente principal
│   ├── App.css               # Estilos principales
│   └── index.js              # Punto de entrada
├── package.json              # Dependencias y scripts
└── README.md                 # Documentación
```

## 🎨 Funcionalidades Principales

### Gestión de Usuarios
- **Crear usuario** - Formulario modal para agregar nuevos usuarios
- **Listar usuarios** - Vista de todos los usuarios registrados
- **Editar usuario** - Modificación de datos existentes
- **Eliminar usuario** - Borrado con confirmación

### Campos de Usuario
- **Nombre** - Primer nombre del usuario
- **Apellido** - Apellido del usuario
- **Email** - Dirección de correo electrónico
- **Contraseña** - Contraseña de acceso
- **Fecha de nacimiento** - Fecha de cumpleaños

### Interfaz de Usuario
- **Modales CSS** - Ventanas emergentes para formularios
- **Botones de acción** - Crear, editar y eliminar
- **Mensajes de confirmación** - Feedback visual para el usuario
- **Diseño limpio** - Interfaz intuitiva y fácil de usar

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/FROSTYLAN/00004-users-management.git
   ```

2. **Navega al directorio:**
   ```bash
   cd 00004-users-management
   ```

3. **Instala las dependencias:**
   ```bash
   npm install
   ```

4. **Inicia el servidor de desarrollo:**
   ```bash
   npm start
   ```

5. **Abre tu navegador:**
   Visita [http://localhost:3000](http://localhost:3000) para ver la aplicación.

## 📱 Scripts Disponibles

### `npm start`
Inicia la aplicación en modo desarrollo.
Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

### `npm test`
Ejecuta las pruebas en modo interactivo.

### `npm run build`
Construye la aplicación para producción en la carpeta `build`.
Optimiza la construcción para el mejor rendimiento.

### `npm run eject`
**Nota: Esta es una operación irreversible.**
Expone todos los archivos de configuración para personalización avanzada.

## 🌐 API Integration

La aplicación se conecta a una API REST para la gestión de usuarios:

- **Base URL:** `https://users-crud1.herokuapp.com/users/`
- **GET** `/users/` - Obtener todos los usuarios
- **POST** `/users/` - Crear nuevo usuario
- **PUT** `/users/:id/` - Actualizar usuario existente
- **DELETE** `/users/:id/` - Eliminar usuario

## 🎯 Objetivos del Proyecto

- Practicar **operaciones CRUD** con React
- Implementar **gestión de estado** con hooks
- Desarrollar **componentes reutilizables**
- Integrar **APIs REST** con Axios
- Crear **interfaces de usuario** modernas
- Manejar **formularios dinámicos** y validación

## 🔧 Posibles Mejoras

- [ ] Añadir autenticación de usuarios
- [ ] Implementar paginación para listas grandes
- [ ] Agregar filtros y búsqueda
- [ ] Validación de formularios más robusta
- [ ] Modo oscuro
- [ ] Notificaciones toast
- [ ] Carga de imágenes de perfil
- [ ] Exportar datos a CSV/PDF

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👨‍💻 Autor

**Charles Castillo**
- GitHub: [https://github.com/FROSTYLAN](https://github.com/FROSTYLAN)
- LinkedIn: [https://linkedin.com/in/charles-castillo-772968234](https://linkedin.com/in/charles-castillo-772968234)

---

⭐ ¡No olvides dar una estrella al proyecto si te gustó!
