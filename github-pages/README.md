# 💳 Gestor de Tarjetas - Demo

Página web interactiva para gestionar múltiples tarjetas de crédito/débito con un diseño cyberpunk/retro.

## ✨ Características

- **Múltiples tarjetas**: Guarda y gestiona varias tarjetas
- **Almacenamiento local**: Usa localStorage del navegador (no requiere backend)
- **Validación Luhn**: Verifica números de tarjeta válidos
- **Detección automática**: Identifica VISA, Mastercard, AMEX, Discover, Diners
- **Diseño cyberpunk**: Efectos Matrix, animaciones y diseño moderno
- **Responsive**: Funciona en desktop y móvil
- **Seguridad visual**: Oculta dígitos de tarjetas guardadas

## 🚀 Cómo subir a GitHub Pages

### Opción 1: Repositorio nuevo

1. **Crea un nuevo repositorio en GitHub**
   - Ve a https://github.com/new
   - Nombre: `gestor-tarjetas` (o el que prefieras)
   - Marca como público
   - No inicialices con README

2. **Sube el archivo**
   ```bash
   git init
   git add index.html
   git commit -m "Página de gestor de tarjetas"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/gestor-tarjetas.git
   git push -u origin main
   ```

3. **Activa GitHub Pages**
   - Ve a Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` → `/root` o `/` 
   - Guarda
   - Tu página estará en: `https://TU-USUARIO.github.io/gestor-tarjetas/`

### Opción 2: Usar tu repositorio existente

Como ya tienes el repositorio `https://github.com/c92470666-byte/Libreasociador`:

1. **Clona tu repositorio**
   ```bash
   git clone https://github.com/c92470666-byte/Libreasociador.git
   cd Libreasociador
   ```

2. **Reemplaza o actualiza el index.html**
   - Copia el nuevo archivo `index.html` a tu repositorio
   - O renómbralo (ej: `index-multiple.html`)

3. **Sube los cambios**
   ```bash
   git add .
   git commit -m "Actualización: soporte para múltiples tarjetas"
   git push origin main
   ```

4. **Verifica GitHub Pages**
   - Ve a Settings → Pages
   - Debería estar activo en: `https://c92470666-byte.github.io/Libreasociador/`

## 📝 Uso

1. **Primera vez**: Se mostrará el formulario para agregar tu primera tarjeta
2. **Agregar tarjeta**: Completa número y fecha de vencimiento
3. **Ver tarjetas**: Todas las tarjetas guardadas aparecen en la galería
4. **Eliminar**: Pasa el mouse sobre una tarjeta y haz clic en el botón "×"
5. **Seguridad**: Los números se ocultan automáticamente, mostrando solo los últimos 4 dígitos

## 🧪 Tarjetas de prueba

Para testing, usa estos números válidos:

- **VISA**: `4532015112830366`
- **Mastercard**: `5425233430109903`
- **American Express**: `378282246310005`
- **Discover**: `6011111111111117`

## 🛠️ Tecnologías

- HTML5
- CSS3 (animaciones, gradientes, glassmorphism)
- JavaScript vanilla (ES6+)
- Canvas API (efectos visuales)
- LocalStorage API

## 📱 Compatibilidad

- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Dispositivos móviles

## ⚠️ Nota importante

Esta es una **plantilla de demostración**. Los datos se guardan solo en tu navegador (localStorage) y no se envían a ningún servidor. No uses datos reales de tarjetas en producción.

## 📄 Licencia

Uso libre – Sin restricciones de uso personal o educativo

---

Hecho con ❤️ para demostración de UI/UX
