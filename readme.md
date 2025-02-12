# 🩺 Dra. Ane Simas - Plataforma Pediátrica [![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?style=flat&logo=vercel)](https://dra-gamma.vercel.app)
[![Security](https://img.shields.io/badge/Security-Level_4-4AA9D6?logo=securityscan)](https://owasp.org)


## 🚀 Recursos Técnicos

### Arquitetura Front-end
- **HTML5 Semântico** com SEO otimizado
- **CSS3 Moderno** (Grid/Flexbox/Animations)
- **JavaScript Vanilla** (ES6+ Modules)
- **Performance 98/100** (Lighthouse)

### Sistema de Segurança
```json:vercel.json
{
  "headers": [{
    "source": "/(.*)",
    "headers": [
      {"key": "Content-Security-Policy","value": "default-src 'self' https:..."},
      {"key": "X-Content-Type-Options","value": "nosniff"},
      {"key": "X-Frame-Options","value": "DENY"}
    ]
  }]
}
```

### Features Principais
```html:index.html
<!-- Sistema de Segurança Integrado -->
<script>
const security = {
  init() {
    this.blockDevTools();
    this.blockContextMenu();
  }
  // ... código de proteção ...
</script>

<!-- Easter Egg Interativo -->
<div class="mickey-magic" onclick="toggleMickey()">
  <!-- Implementação do Mickey animado -->
</div>
```

## 🛠 Tech Stack
**Core:**
```css:styles.css
:root {
  --primary: #6EC3F5;
  --secondary: #98E6B4;
  /* Design System completo */
}

@keyframes heartbeat {
  0%,100% { transform: scale(1); }
  50% { transform: scale(0.95); }
}
```

**Ferramentas:**
- Vercel (Deploy)
- Google Fonts (Otimização)
- Font Awesome (Ícones)
- CSS Grid (Layout)

## 📦 Instalação
```bash
git clone https://github.com/FuturoDevJunior/dra-ane-simas.git
cd dra-ane-simas && python3 -m http.server 8000
```

## 🌟 Destaques
- Bloqueio de DevTools/Click Direito
- 30+ Animações CSS performáticas
- Gradients CSS otimizados
- Mobile-first Responsivo
- Carregamento <1s

## 📄 Licença
MIT License - [Detalhes](LICENSE)
