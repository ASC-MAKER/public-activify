# 🤖 Activify - Discord Activity Tracking Bot

**© 2026 Todos los derechos reservados / All rights reserved**

Bot de Discord que rastrea y muestra estadísticas completas de actividad de los usuarios en tu servidor. Responde automáticamente en español o inglés según el idioma de Discord del usuario.

## 📊 Características

El bot registra automáticamente:
- 💬 **Mensajes**: totales, del mes (últimos 30 días) y del día
- 🎤 **Tiempo en canales de voz**: anual, mensual (últimos 30 días) y diario
- ⭐ **Reacciones totales** a mensajes
- 🧵 **Hilos públicos creados**
- 🗑️ **Limpieza automática**: elimina datos de más de 1 año
- 👋 **Sistema de abandono**: elimina datos de usuarios que abandonan el servidor después de 3 días

## 🌐 Multilingüe

- **Comandos universales en inglés** (estándar internacional)
- **Respuestas automáticas en tu idioma** (español/inglés)
- Detección automática según la configuración de idioma de Discord del usuario

## 🎯 Comandos Slash

### `/activity [@user]`
Muestra las estadísticas completas de un usuario en un embed.
- Si no mencionas a nadie, muestra tus propias estadísticas
- Responde en español o inglés automáticamente

### `/top [category]`
Muestra el ranking de los 10 mejores usuarios en una categoría.
- Categorías: `mensajes/messages`, `voz/voice`, `reacciones/reactions`, `hilos/threads`
- El ranking de voz muestra solo datos del último mes

### `/help`
Muestra la lista de comandos disponibles con descripciones en tu idioma.

**Desarrollado con ❤️ para la comunidad de Discord**
