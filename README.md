# 🍅 Salsa de Tomate — Frontend

Aplicación web de recetas construida con **React + Vite** y **Tailwind CSS**.

---

## 🔗 Enlaces del proyecto

| Recurso | URL |
|---------|-----|
| 🖥️ Frontend (este repo) | `https://github.com/alessdi/team-2` |
| ⚙️ Backend | `https://github.com/alessdi/salsadetomate-backend` |
| 🌐 Sitio desplegado | `https://team-2-seven.vercel.app` |

---

## ⚙️ Requisitos

- Node.js 18+
- npm

---

## 🚀 Instalación y ejecución

```bash
# 1. Clona el repositorio
git clone https://github.com/alessdi/team-2
cd team-2

# 2. Instala dependencias
npm install

# 3. Crea el archivo de configuración
cp .env.example .env
# Edita .env y pon la URL del backend

# 4. Ejecuta el servidor de desarrollo
npm run dev
```

El frontend corre en `http://localhost:5173`.

---

## 🔧 Configuración

Crea un archivo `.env` en la raíz del proyecto con:

```
VITE_API_URL=http://localhost:8000
```

Para producción usa la URL del backend desplegado:

```
VITE_API_URL=https://salsadetomate-backend-production.up.railway.app
```

---

## 📄 Páginas

| Ruta | Descripción | Auth |
|------|-------------|------|
| `/` | Landing page | — |
| `/explore` | Explorar recetas con filtros | — |
| `/recipe/:id` | Detalle de receta | — |
| `/login` | Iniciar sesión | — |
| `/register` | Registro de usuario | — |
| `/my-recipes` | Mis recetas | ✅ |
| `/create` | Crear receta | ✅ |
| `/edit/:id` | Editar receta | ✅ |
| `/edit/:id/media` | Galería de fotos | ✅ |
| `/categories` | Administrar categorías | ✅ |

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| React 18 | Framework UI |
| Vite | Build tool |
| Tailwind CSS | Estilos |
| Axios | Peticiones HTTP |
| React Router | Navegación |
| React Quill | Editor de texto enriquecido |

---

## 🌐 Backend

Este frontend consume la API REST del backend en .NET 8 Web API. El repositorio del backend se encuentra en:

`https://github.com/alessdi/salsadetomate-backend`