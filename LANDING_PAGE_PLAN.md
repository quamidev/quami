# Quami.dev Landing Page Plan

## Project Overview
- **Site**: quami.dev
- **Company**: Quami (owned by MIDI. SA)
- **Contact**: +502 3102-1287
- **Language**: Spanish
- **Framework**: Astro with React components

---

## Color Palette (Pastel Yellow & Blue)

### Primary Colors
- **Pastel Yellow**: `#FEF3C7` (background), `#FDE68A` (accent), `#F59E0B` (CTA)
- **Pastel Blue**: `#DBEAFE` (background), `#93C5FD` (accent), `#3B82F6` (CTA)

### Supporting Colors
- **Dark Text**: `#1E293B` (slate-800)
- **Light Text**: `#64748B` (slate-500)
- **White**: `#FFFFFF`
- **Near Black**: `#0F172A` (for contrast)

---

## Typography
- **Headings**: Inter (bold, modern, clean)
- **Body**: Inter (regular)
- **Code/Accent**: JetBrains Mono (if needed)

---

## Page Structure

### 1. Navigation (Fixed)
- Logo: "quami" (stylized)
- Links: Servicios, Proyectos, Nosotros, Contacto
- CTA Button: "Hablemos"

### 2. Hero Section (Full viewport)
**Inspiration**: bepurple.ai (bold headline with animated text)

- **Background**: Gradient mesh or Aurora effect (pastel yellow/blue blend)
- **Headline**: "Transformamos ideas en experiencias digitales"
- **Subheadline**: "Desarrollo web, apps y soluciones tecnológicas que impulsan tu negocio"
- **CTA Buttons**: "Ver Proyectos" (primary), "Contáctanos" (secondary)
- **Animation**: BlurText or SplitText effect on headline

### 3. Services Section
**Inspiration**: Vercel (cards with icons)

Cards with hover effects:
1. **Desarrollo Web** - Sitios web modernos y rápidos
2. **Aplicaciones Móviles** - Apps nativas y multiplataforma
3. **E-commerce** - Tiendas online que convierten
4. **Consultoría Tech** - Asesoría estratégica digital

### 4. Why Quami Section
**Inspiration**: Apple (clean, minimal, impactful)

3-column layout:
- **Innovación** - Tecnología de vanguardia
- **Calidad** - Código limpio y escalable
- **Compromiso** - Soporte continuo

### 5. Process Section
**Inspiration**: bepurple.ai (numbered steps)

Steps 01-04:
1. **Descubrimiento** - Entendemos tu visión
2. **Diseño** - Creamos la experiencia
3. **Desarrollo** - Construimos tu solución
4. **Lanzamiento** - Llevamos tu idea al mundo

### 6. CTA Section (Contact)
- **Headline**: "¿Listo para empezar tu proyecto?"
- **Contact Number**: +502 3102-1287
- **Button**: "Hablemos" → WhatsApp link

### 7. Footer
- Logo
- Copyright: © 2025 Quami. Propiedad de MIDI. SA
- Social links (optional)
- Contact info

---

## ReactBits Components to Use

### Text Animations
- **BlurText** - For hero headline reveal
- **SplitText** - For section titles
- **GradientText** - For accent words

### Backgrounds
- **Aurora** - For hero section (customized to yellow/blue)
- **DotGrid** - For services section background
- **GridMotion** - For subtle section dividers

### Animations
- **GradualBlur** - For image reveals
- **ShapeBlur** - For decorative elements

---

## Technical Implementation

### Dependencies to Add
```bash
npm install @astrojs/react react react-dom framer-motion
```

### File Structure
```
src/
├── components/
│   ├── Nav.astro
│   ├── Hero.astro
│   ├── Services.astro
│   ├── WhyQuami.astro
│   ├── Process.astro
│   ├── Contact.astro
│   ├── Footer.astro
│   └── ui/
│       ├── BlurText.tsx
│       ├── Aurora.tsx
│       └── ... (ReactBits components)
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

---

## Responsive Breakpoints
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

---

## Animations & Interactions
- Scroll-triggered section reveals
- Hover effects on cards
- Smooth scroll navigation
- Hero text animation on load

---

## Next Steps
1. Create HTML mockups for approval
2. Get feedback on design direction
3. Implement in Astro with React components
4. Add animations and interactivity
5. Optimize for performance
6. Deploy
