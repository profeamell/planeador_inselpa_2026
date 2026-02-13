# 📚 Generador de Planeaciones EPC - I.E. La Pascuala

Aplicación web para generar planeaciones educativas siguiendo el modelo de Enseñanza para la Comprensión (EPC) de David Perkins, adaptado al área de Tecnología e Informática.

## 🎯 Características

- ✅ Generación automática de planeaciones EPC completas
- 🤖 Integración con Claude Sonnet 4 (IA opcional)
- 📄 Exportación a Word, PDF e impresión
- 📋 Formulario completo con validaciones
- 🎨 Diseño profesional y responsive
- 🏫 Adaptado a I.E. La Pascuala

## 📦 Estructura del Proyecto

```
planeador-app/
├── index.html              # Aplicación principal
├── escudo_lapascuala.png   # Escudo institucional (100x100px)
├── api/
│   └── claude.js           # Función serverless para API de Claude
└── README.md               # Este archivo
```

## 🚀 Despliegue en Vercel

### Opción 1: Desde GitHub (Recomendado)

1. Sube este proyecto a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Conecta tu repositorio
4. Haz clic en "Deploy"
5. ¡Listo! Tu app estará en: `https://tu-proyecto.vercel.app`

### Opción 2: Vercel CLI

```bash
npm i -g vercel
cd planeador-app
vercel
```

### Opción 3: Arrastra y suelta

1. Ve a [vercel.com/new](https://vercel.com/new)
2. Arrastra la carpeta `planeador-app`
3. Espera el despliegue
4. ¡Listo!

## 🔑 Configuración de API Key

Para usar la funcionalidad de IA:

1. Obtén tu API Key en: [console.anthropic.com](https://console.anthropic.com)
2. Crea una cuenta y añade créditos ($5 USD mínimo)
3. Crea una API Key
4. En la app, pégala en el campo correspondiente
5. Selecciona "Con IA" en el modo de generación

**Nota:** Tu API Key se guarda solo en tu navegador (localStorage)

## 💡 Modo Sin IA

Si no quieres usar IA o no tienes API Key:

- Selecciona "Sin IA (Plantillas predefinidas)"
- Funciona perfectamente sin necesidad de API Key
- Genera planeaciones profesionales con plantillas

## 📋 Uso

1. Completa todos los campos del formulario
2. Ingresa tu API Key (opcional, solo para modo IA)
3. Haz clic en "Generar Planeación Completa"
4. Descarga en Word, PDF o imprime

## 🛠️ Tecnologías

- HTML5, CSS3, JavaScript (Vanilla)
- Claude Sonnet 4 API (Anthropic)
- Vercel Serverless Functions
- jsPDF + html2canvas

## 🏫 Institución

**Institución Educativa La Pascuala**
- Área: Tecnología e Informática
- Docente: Mag. Francisco Javier Amell
- Modelo: Enseñanza para la Comprensión (EPC)

## 📝 Licencia

Uso educativo - I.E. La Pascuala

## 🆘 Soporte

Si encuentras problemas:
1. Verifica que tienes créditos en Anthropic
2. Revisa que la API Key esté correcta
3. Usa el modo "Sin IA" como alternativa
4. Abre la consola del navegador (F12) para ver errores

---

Desarrollado para I.E. La Pascuala - 2025
