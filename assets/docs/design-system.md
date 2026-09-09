# PatientPath Design System

The PatientPath design system provides a shared set of visual styles and reusable UI patterns for the frontend application. Its purpose is to keep the interface consistent, accessible, and easy for the development team to maintain.

---

## Color Palette

PatientPath uses a clean healthcare-focused palette built around blue, white, and neutral gray tones.

| Purpose | Color | Hex |
|---|---|---|
| Primary | Blue | `#2563EB` |
| Primary Light | Light Blue | `#3B82F6` |
| Text | Dark Navy | `#0F172A` |
| Secondary Text | Slate Gray | `#64748B` |
| Border | Light Gray | `#E2E8F0` |
| Background | Off White | `#F8FAFC` |
| Surface | White | `#FFFFFF` |
| Success | Green | `#16A34A` |
| Warning | Amber | `#F59E0B` |
| Danger | Red | `#DC2626` |

### Usage

- Primary blue should be used for major actions, links, and selected navigation items.
- Green should represent successful or accepted states.
- Amber should represent pending or warning states.
- Red should be reserved for errors, destructive actions, or validation problems.
- White and light gray should make up most page backgrounds and cards.

---

## Typography

PatientPath will use a simple sans-serif font for readability.

Preferred font:

`Inter`

Fallback:

`Arial, sans-serif`

### Type Scale

| Style | Size | Weight | Usage |
|---|---:|---|---|
| H1 | 32px | Bold | Page titles |
| H2 | 24px | Semi-bold | Main sections |
| H3 | 20px | Semi-bold | Subsections |
| Body | 16px | Regular | Standard content |
| Small | 14px | Regular | Helper text, captions, metadata |

Text should use dark navy as the default color and slate gray for secondary information.

---

## Spacing Scale

PatientPath will use an 8px-based spacing system to create consistency between components.

| Token | Size |
|---|---:|
| space-1 | 4px |
| space-2 | 8px |
| space-3 | 12px |
| space-4 | 16px |
| space-6 | 24px |
| space-8 | 32px |

Developers should use these values instead of creating random margins and padding.

Example:

```css
margin: var(--space-4);
padding: var(--space-3);