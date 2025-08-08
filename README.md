## Design System Overviews:

Theory and Workflow for the day to day front-end design. Also https://material.io/ for best practices

### Typography:
Differne important aspects
> Golden Ration : 1.62 // difference between font-size lavel

> Font Sizing: Use rounded values and keep those with 8 or 4 scale. Like if h1 = 68.024448px (16*1.62*1.62.1.62) , where base is 16px., make it 64px or 68px

Variants:
```txt
# Title/h1 => h2 * 1.62 (bold) + letter speacing (-2%)
# h2 (title) => h3 * 1.62 (bold) + letter speacing (-2%)
# h3 (title) => base * 1.62 (bold) + letter speacing (-2%)
# Subtitle (Big copy) => base * 1.62
# Strong (bold/semi-bold) => base (bold)
# Em (emphasized) =>
# Body (copy) => 16px (base)
# Small (copy) => 12px
# Button text =>
# Pre title => uppercase, 12px, letter speacing * 2%
```
> Batch Styler Plugin for changing multiple text style (Font Family, Size, Style, etc)

> Choose 2 Font family max (Those complement each other and not too-much decorative)

### Color palette
Palette Elements (Also give it a color name, like "Flemingo Red / Sky Blue" etc):
- Primary
- Secondary
- Accent
- Dark/Background with contrast
- Gradient from Primary + Secondary/Accent Colors

> Use Plugin like "color palettes"and or 'color designer' or something else

> keep your Base Colours to a minimum where possible (ie; Primary, Secondary, and TertiaryAccent , Dark elements/background).

> Plus standard Red (Error), Green (Success), and Yellow (Warning) Base Colours for usage within Notifications, Badges, and Input Field Borders for example.

> Black and varying shades of Grey and white for dark mode.

> Black and varying shades of Grey

> a healthy selection of Gradients

### Elevations & Shadows:


### Icons:


### Spacing:
Gutenberg Systematise Spacing:
- leading: base-font * line-height
- h1:
 - line-height : 2 * leading
 - margin-top : 3 * leading
 - margin-bottom : 1 * leading

- h2:
 - line-height : 1.5 * leading
 - margin-top : 2 * leading
 - margin-bottom : 1 * leading

- h3:
 - line-height : 1.5 * leading
 - margin-top : 2 * leading
 - margin-bottom : 0 * leading

- h4/h5/h6/p (like body p with bold ):
 - line-height : 1 * leading
 - margin-top : 1 * leading
 - margin-bottom : 0 * leading

 [  line-height: 1; // If font size is 10px, line height will be 10px, same for line-height: 1em/100%/10px ]


