# 🩺 Dra. Ane Simas - Pediatria Especializada

[![Deploy](https://img.shields.io/badge/Deploy-Vercel-000?style=flat&logo=vercel&logoColor=white)](https://dra-gamma.vercel.app)
[![Security](https://img.shields.io/badge/Security-CSP%20Headers-4AA9D6?logo=securityscorecard)](https://dra-gamma.vercel.app)

Site profissional para clínica pediátrica com implementações modernas de front-end e configurações de segurança robustas.

## Stack Principal

- **Estrutura:** HTML5 Semântico
- **Estilização:** CSS3 Moderno (Variáveis CSS, Grid/Flexbox)
- **Performance:** Critical CSS Inline/Otimizado
- **Segurança:** Headers HTTP Restritivos (CSP, X-Content-Type)

## Funcionalidades Chave

- ⚡ Layout Responsivo com CSS Grid
- 🎨 Sistema de Cores Baseado em Variáveis CSS
- 🔒 Proteção contra DevTools/Context Menu
- 📱 Design Mobile-First
- 🖥️ Background Particles Animado
- 💬 Integração Direta com WhatsApp
- 🎉 Efeitos de Hover/Animações CSS

## Configurações Técnicas

```vercel.json
{
  "headers": [{
    "source": "/(.*)",
    "headers": [
      {"key": "Content-Security-Policy","value": "default-src 'self' https: 'unsafe-inline';..."},
      {"key": "X-Content-Type-Options","value": "nosniff"},
      {"key": "X-Frame-Options","value": "DENY"}
    ]
  }]
}
```

## Otimizações

- 🚀 Fontes Otimizadas (Google Fonts)
- 🌈 Gradients CSS Performáticos
- 📐 Media Queries para Dispositivos Móveis
- 🛡️ Prevenção contra Clickjacking
- 🔄 Transições Suaves CSS

**Repositório:** [GitHub](https://github.com/FuturoDevJunior/dra-ane-simas)
