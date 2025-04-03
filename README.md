# TFG-mvergarato
# 🎵 BambiLab

## 📌 Descripción

BambiLab es una aplicación web diseñada para ofrecer un entorno sencillo donde los usuarios puedan explorar y adquirir recursos musicales utilizando un sistema de monedero virtual. Los usuarios pueden registrarse, iniciar sesión y gestionar su saldo ficticio para realizar compras dentro de la plataforma. En el futuro, se añadirá una pasarela de pago real para monetizar los productos.

## 🚀 Características

- 🔑 **Registro e Inicio de Sesión**: Permite a los usuarios acceder de forma segura.
- 📄 **Navegación entre secciones**: Interfaz intuitiva para explorar los productos.
- 💰 **Monedero Virtual**: Cada usuario tiene saldo ficticio que puede recargar y utilizar.
- 🛒 **Compra de Productos**: Los usuarios pueden gastar su saldo en los recursos disponibles.
- 📊 **Historial de Transacciones**: Registro de los movimientos de saldo dentro de la plataforma.
- ⚙️ **Panel de Administración** *(futuro desarrollo)*: Para gestionar productos y usuarios.

## 🛠️ Tecnologías Utilizadas

### **Frontend**
- React.js (Para la interfaz de usuario)
- Tailwind CSS (Para los estilos)
- React Router (Para la navegación)

### **Backend**
- Node.js + Express.js (Para gestionar la API)
- PostgreSQL + Sequelize (Para la base de datos)
- JWT (Para la autenticación de usuarios)
- Dotenv (Para gestionar variables de entorno)

## 📂 Estructura del Proyecto

```
/bambi-lab
├── /frontend
│   ├── /public
│   ├── /src
│   │   ├── /assets
│   │   ├── /components
│   │   ├── /pages
│   │   ├── /services
│   │   ├── App.js
│   │   ├── index.js
├── /backend
│   ├── /controllers
│   ├── /models
│   ├── /routes
│   ├── /middlewares
│   ├── /config
│   ├── /database
│   ├── server.js
│   ├── .env
│   ├── package.json
└── README.md
```

## 🏗️ Instalación y Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/usuario/bambi-lab.git
```

### 2️⃣ Instalar dependencias

#### Frontend
```bash
cd frontend
npm install
```

#### Backend
```bash
cd backend
npm install
```

### 3️⃣ Configurar variables de entorno
Crea un archivo `.env` en la carpeta `backend` con los siguientes valores:
```env
PORT=5000
DATABASE_URL=postgres://usuario:contraseña@localhost:5432/bambi_lab
JWT_SECRET=clave_secreta
```

### 4️⃣ Iniciar el servidor backend
```bash
cd backend
npm run dev
```

### 5️⃣ Iniciar el frontend
```bash
cd frontend
npm start
```

Esto abrirá la aplicación en `http://localhost:3000`.

## 📌 Estado del Proyecto

🚧 En desarrollo. Próximas funciones: mejoras en la UI y sistema de administración.

## 📝 Contribuir

1. Haz un fork del repositorio.
2. Crea una nueva rama: `git checkout -b feature/nueva-funcionalidad`.
3. Realiza los cambios y haz commit: `git commit -m "Descripción del cambio"`.
4. Sube los cambios: `git push origin feature/nueva-funcionalidad`.
5. Abre un Pull Request.

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

## 📬 Contacto

- **Correo**: contacto@bambilab.com
- **GitHub**: [Repositorio Oficial](https://github.com/usuario/bambi-lab)
- **LinkedIn**: [Perfil del Desarrollador](https://linkedin.com/in/usuario)

