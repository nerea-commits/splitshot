# SplitShot

**Divide los gastos del ticket de la compra con IA — gratis.**

Haz una foto del ticket, subraya con colores quién compró cada cosa, y la IA calcula automáticamente cuánto paga cada persona.

## Funcionalidades

- 📸 **Escaneo con IA** — Sube o haz foto del ticket, la IA lee los productos
- 🎨 **Subrayador por colores** — Un color por persona (hasta 6 personas)
- 🔍 **Modo zoom** — Amplía tickets largos para marcar con precisión en móvil
- 📝 **Lista de la compra** — Estilo Recordatorios de iPhone, con autocompletado
- 📊 **Histórico mensual** — Estadísticas, gráficos de reparto, exportar CSV
- 💰 **Balance automático** — Quién debe a quién, actualizado en tiempo real
- 🧠 **Memoria** — Recuerda productos y los marca automáticamente
- 🖼️ **Miniaturas** — Guarda la imagen del ticket en el histórico

## 100% Gratis con Gemini

La app usa **Google Gemini Flash** como motor de IA por defecto — completamente gratis.

### Configuración en 2 minutos:

1. Ve a [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Inicia sesión con tu cuenta de Google
3. Pulsa **"Crear clave de API"**
4. Copia la clave y pégala en la app (pestaña Ticket → 🔑 Configurar IA)

Sin tarjeta de crédito, sin límite de tiempo, 15 peticiones/minuto.

> También puedes usar **Claude** como opción premium si prefieres mayor precisión (~0,02€/ticket).

## Instalación en GitHub Pages

1. Crea un repositorio nuevo en [github.com/new](https://github.com/new) (público)
2. Sube los archivos `index.html` y `README.md`
3. Ve a **Settings → Pages → Source: main / root** → Save
4. En 1-2 minutos tu app estará en `https://tu-usuario.github.io/nombre-repo/`

No necesitas servidor, base de datos, ni nada más.

## Privacidad

- Todos los datos se guardan en el navegador (localStorage)
- Las imágenes solo se envían a Google/Anthropic para análisis
- La API Key se guarda localmente, nunca pasa por servidores intermedios
- Sin analytics, sin cookies, sin tracking

## Tecnología

HTML + CSS + JS vanilla · Google Gemini Flash API · Anthropic Claude API (opcional) · localStorage · Mobile-first · Tema oscuro
