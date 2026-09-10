# Landing Page Asesoramiento Energético - Grupo EMAX

Proyecto desarrollado como prueba técnica para la posición de **Diseñadora Web / Frontend** en **Grupo EMAX**. 

El objetivo principal es captar clientes del mercado español interesados en optimizar y reducir sus facturas de luz y gas mediante un estudio gratuito.

---

## Enlaces de Interés
- **Demo en vivo:** [https://emax-landing.vercel.app](https://emax-landing.vercel.app)
- **Repositorio:** [https://github.com/MagaliBelen/emax-landing](https://github.com/MagaliBelen/emax-landing)

---

## Tecnologías Utilizadas

- **Framework:** [Astro](https://astro.build) (Elegido por su alto rendimiento, carga ultra rápida y arquitectura *Zero JS by default*).
- **Lenguajes:** HTML5 Semántico, CSS3 moderno (Variables CSS, Flexbox, Grid, Keyframe Animations).
- **Librerías / Scripts:** [AOS - Animate On Scroll](https://michalsnik.github.io/aos/) para revelado progresivo de elementos.
- **Despliegue:** Vercel.

---

## Organización del Proyecto

```text
src/
├── components/       # Componentes independientes y reutilizables
│   ├── Benefits.astro
│   ├── Footer.astro
│   ├── Form.astro
│   ├── Hero.astro
│   ├── Problem.astro
│   ├── ScrollToTop.astro
│   ├── Solution.astro
│   └── Steps.astro
├── layouts/          # Layout principal de la aplicación
│   └── Layout.astro
├── pages/            # Rutas de la página
│   └── index.astro
└── styles/           # Estilos globales y reset
    └── global.css

---

## Decisiones de Diseño
- **Simulador de Ahorro Visual:** Gráficos para una comparación directa de consumo mensual (145 € vs. 87 €) y el impacto del ahorro anual estimado (696 €/año).
- **Jerarquía Visual y Accesibilidad:** Uso de tipografía legible, contrastes accesibles y llamadas a la acción (CTA) con sombras y animaciones de pulso para guiar la atención del usuario.
- **Navegación Fluida:** Header Sticky con desenfoque de fondo (backdrop-filter), enlaces directos a las secciones y botón flotante Back-to-Top para mejorar la usabilidad en dispositivos móviles.
- **Formulario Sin Fricción:** Campos estructurados para captar leads cualificados (tipo de cliente, teléfono, email) con validaciones nativas.
- **Paleta Cromática Estratégica:** Uso de azul corporativo para aportar seguridad y profesionalidad, combinado con tonos verdes en precios e indicadores de ahorro para evocar sostenibilidad y eficiencia financiera.

---

## Uso de Inteligencia Artificial como Apoyo
De acuerdo con las pautas de la prueba, se empleó IA como herramienta de apoyo para:
- **Copywriting:** Optimización de textos orientados a la propuesta de valor y los dolores específicos del consumidor energético español.
- **Estructuración:** Maquetación inicial de la plantilla para acelerar el desarrollo.
- **Refactorización:** Revisión de accesibilidad y optimización de animaciones CSS.

---

## Autora
Desarrollado por Magalí Borrello