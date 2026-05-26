---
name: Tolopani Unified Digital Service
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#3f4944'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6f7973'
  outline-variant: '#bec9c2'
  surface-tint: '#1b6b51'
  primary: '#004532'
  on-primary: '#ffffff'
  primary-container: '#065f46'
  on-primary-container: '#8bd6b7'
  inverse-primary: '#8bd6b6'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#1e4334'
  on-tertiary: '#ffffff'
  tertiary-container: '#365a4a'
  on-tertiary-container: '#a8d0bc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a6f2d1'
  primary-fixed-dim: '#8bd6b6'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#00513b'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#c3ecd7'
  tertiary-fixed-dim: '#a8cfbc'
  on-tertiary-fixed: '#002115'
  on-tertiary-fixed-variant: '#294e3f'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Poppins
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Poppins
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Poppins
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Poppins
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Poppins
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Poppins
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Poppins
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Poppins
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-margin: 20px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The design system is crafted to represent the Ministry of Religious Affairs (Kemenag) of Gorontalo City with a sense of modern authority, spiritual serenity, and professional efficiency. The brand personality is **Trustworthy, Accessible, and Harmonious**, bridging traditional institutional values with a forward-thinking digital experience.

The visual style follows a **Corporate Modern** aesthetic with a **Tactile** touch. It prioritizes clarity and ease of navigation for a diverse demographic, utilizing high-quality whitespace, crisp iconography, and a subtle layering system that gives the interface a tangible, premium feel. The emotional response should be one of reliability and calm, ensuring citizens feel supported when accessing religious and administrative services.

## Colors

The palette is rooted in the Islamic identity of Kemenag, utilizing a monochromatic green spectrum to establish hierarchy and brand recognition.

- **Primary (Emerald Green):** Used for top app bars, primary action buttons, and active states. It represents stability and institutional growth.
- **Secondary (Mint Green):** Used for accents, success states, and highlighting specific features within the service cards.
- **Tertiary (Pale Mint):** Used for subtle backgrounds, chip containers, and non-intrusive separators.
- **Surface & Background:** A clean, slightly cool white (`#FFFFFF`) for cards and a very light gray (`#F9FAFB`) for the global background to distinguish layered elements.
- **Status Colors:** Standardized red for errors and amber for warnings, specifically adjusted to maintain harmony with the green primary palette.

## Typography

This design system uses **Poppins** exclusively to ensure a friendly yet geometric and professional appearance. 

- **Headlines:** Use Semi-Bold (600) or Bold (700) weights to establish clear information hierarchy, particularly in the Hero section and card titles.
- **Body Text:** Use Regular (400) weight for descriptions and forms to maximize readability.
- **Labels:** Use Medium (500) for button text and functional labels. Small labels (caps) use a slightly increased letter spacing for clarity on small mobile screens.
- **Scale:** Large display sizes are reserved for the Hero section welcoming users, while headlines scale down slightly for internal page titles to maximize content space on mobile devices.

## Layout & Spacing

The layout is designed for a **Native Mobile** experience, following a 4px baseline grid. 

- **Margins:** A standard 20px horizontal margin is applied to all main screens to prevent content from feeling cramped against the screen edges.
- **Hero Section:** The top section uses a 24px vertical padding, often featuring a slight background bleed to the top of the device.
- **Card Spacing:** Elements within service cards use a 16px internal padding (gutter). 
- **Reflow:** On larger mobile screens (tablets), the service grid transitions from a 1-column layout to a 2-column layout, maintaining consistent 16px spacing between cards.

## Elevation & Depth

To achieve a "Native" feel, the system uses **Ambient Shadows** to define hierarchy without creating visual clutter.

- **Level 0 (Background):** Surface color `#F9FAFB`.
- **Level 1 (Cards/Inputs):** White surface with a soft, diffused shadow (0px 4px 20px, 5% opacity black) to suggest a subtle lift.
- **Level 2 (Active Elements/Modals):** Increased shadow spread (0px 8px 30px, 8% opacity) to indicate temporary priority.
- **Interaction:** Buttons utilize a slight inner shadow when pressed to mimic physical displacement, enhancing the tactile feedback of the interface.

## Shapes

The design system adopts a **2xl rounded corner** philosophy (1rem/16px for standard elements) to soften the institutional nature of the app and make it feel more approachable.

- **Service Cards:** Use 16px (1rem) corner radius for a friendly, modern look.
- **Buttons:** Use 12px (0.75rem) or fully pill-shaped (3rem) for primary actions to distinguish them from content containers.
- **Input Fields:** Use 12px (0.75rem) to maintain consistency with the button language.
- **Hero Section:** The bottom edges of the Hero container use a 24px (1.5rem) radius to create a distinct "header" zone.

## Components

### Hero Section
The Hero section features the 'Emerald Green' primary color. It contains a "Display-lg" greeting, a quick search bar for services, and a decorative, high-quality icon or pattern inspired by Islamic geometry in the background at low opacity.

### Service Cards
Cards are the primary navigation tool. They feature a white background, Level 1 elevation, and a 16px radius. Icons within cards should use a Mint Green container with 15% opacity to highlight the category.

### Buttons
- **Primary:** Emerald Green background, White Poppins Bold text.
- **Secondary:** Mint Green stroke (2px) with Emerald Green text.
- **States:** Hover/Tap states should darken the background by 10%.

### Input Fields
Inputs use a light gray border (`#E5E7EB`) that turns Primary Green on focus. Labels are positioned above the field in 'Label-md' typography.

### Chips & Badges
Small, rounded pills used for status indicators (e.g., "Selesai", "Proses"). These use the Tertiary Green background with a dark green text to ensure high legibility and a soft visual impact.

### Bottom Navigation
A clean, white bar with a subtle top border and 0 elevation. Active icons use the Primary Green color, while inactive icons use a medium gray. Icons should be line-art style with a 2px stroke width.