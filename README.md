# DCM Dashboard - Visualización de Portafolios Crypto

![Banner DCM Dashboard](public/dcm-dashboard.png)

## 📊 Descripción

DCM Dashboard es una aplicación web moderna que permite visualizar, analizar y gestionar portafolios de inversiones en criptomonedas. Diseñada con una interfaz elegante y funcional, esta herramienta facilita el seguimiento de rendimientos, comparación de activos y análisis de tendencias en tiempo real.

## ✨ Características

- **Visualización en tiempo real**: Sigue el rendimiento de tus activos crypto con gráficos interactivos
- **Análisis de portafolio**: Estadísticas detalladas sobre rendimiento, volatilidad y correlación
- **Diversificación**: Métricas de distribución de activos y recomendaciones
- **Comparativas**: Contrasta el rendimiento de diferentes criptomonedas
- **Modo oscuro/claro**: Interfaz adaptable a tus preferencias visuales
- **Diseño responsivo**: Experiencia optimizada en dispositivos móviles y de escritorio

## 🚀 Tecnologías

- **Frontend**: Next.js, React, TypeScript
- **Gráficos**: Recharts
- **Estilos**: TailwindCSS
- **Gestión de estado**: React Hooks
- **Backend**: Supabase
- **Autenticación**: Supabase Auth

## 🛠️ Instalación

```bash
# Clonar el repositorio
git clone https://github.com/tucuenta/dcm-dashboard.git

# Navegar al directorio
cd dcm-dashboard

# Instalar dependencias
npm install
# o con pnpm
pnpm install

# Configurar variables de entorno
cp .env.example .env.local
# Editar .env.local con tus credenciales

# Iniciar servidor de desarrollo
npm run dev
# o con pnpm
pnpm dev
```

## 🖥️ Uso

Accede a la aplicación en `http://localhost:3000` después de iniciar el servidor de desarrollo.

1. Inicia sesión o crea una cuenta
2. Importa tu portafolio o añade activos manualmente
3. Explora las distintas secciones del dashboard
4. Personaliza widgets y visualizaciones según tus necesidades

## 🔒 Seguridad

DCM Dashboard implementa estrictas medidas de seguridad:

- No almacena claves privadas de monederos (wallets)
- Conexiones cifradas mediante HTTPS
- Autenticación segura a través de Supabase Auth
- Almacenamiento encriptado de datos sensibles

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 💬 Contacto

Para soporte, sugerencias o colaboraciones, contáctanos en:
- Email: [soporte@dcm-dashboard.com](mailto:soporte@dcm-dashboard.com)
- Twitter: [@DCMDashboard](https://twitter.com/DCMDashboard)
- GitHub: [github.com/tucuenta/dcm-dashboard](https://github.com/tucuenta/dcm-dashboard)
