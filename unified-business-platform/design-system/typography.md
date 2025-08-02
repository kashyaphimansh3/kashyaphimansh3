# Typography System - Unified Business Regulatory Platform

## Font Families

### Primary Font
**Inter** - Modern, highly legible sans-serif font
- Usage: Body text, UI elements, forms
- Languages: Latin, Devanagari (for Hindi support)
- Weight range: 300-700
- Variable font support: Yes

### Secondary Font
**Noto Sans Devanagari** - For Hindi and regional language support
- Usage: Hindi text, regional language content
- Weight range: 300-700
- Specifically designed for Indian languages

### Monospace Font
**JetBrains Mono** - For code, IDs, reference numbers
- Usage: Application IDs, reference codes, technical data
- Weight range: 400-600

## Typography Scale

### Headings

#### H1 - Page Titles
- **Size**: 32px (2rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.25 (40px)
- **Letter Spacing**: -0.025em
- **Usage**: Main page headings, primary titles

#### H2 - Section Titles  
- **Size**: 24px (1.5rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.33 (32px)
- **Letter Spacing**: -0.025em
- **Usage**: Section headers, card titles

#### H3 - Subsection Titles
- **Size**: 20px (1.25rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.4 (28px)
- **Letter Spacing**: -0.025em
- **Usage**: Subsection headers, component titles

#### H4 - Component Titles
- **Size**: 18px (1.125rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.44 (26px)
- **Letter Spacing**: -0.025em
- **Usage**: Widget titles, form section headers

#### H5 - Small Headings
- **Size**: 16px (1rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.5 (24px)
- **Letter Spacing**: -0.025em
- **Usage**: List headers, small component titles

#### H6 - Micro Headings
- **Size**: 14px (0.875rem)
- **Weight**: 600 (Semi-bold)
- **Line Height**: 1.57 (22px)
- **Letter Spacing**: -0.025em
- **Usage**: Field labels, micro headings

### Body Text

#### Large Body
- **Size**: 18px (1.125rem)
- **Weight**: 400 (Regular)
- **Line Height**: 1.67 (30px)
- **Usage**: Important descriptions, intro text

#### Regular Body
- **Size**: 16px (1rem)
- **Weight**: 400 (Regular)
- **Line Height**: 1.5 (24px)
- **Usage**: Standard body text, descriptions

#### Small Body
- **Size**: 14px (0.875rem)
- **Weight**: 400 (Regular)
- **Line Height**: 1.57 (22px)
- **Usage**: Secondary information, captions

#### Micro Text
- **Size**: 12px (0.75rem)
- **Weight**: 400 (Regular)
- **Line Height**: 1.67 (20px)
- **Usage**: Timestamps, fine print, legal text

### Interactive Text

#### Links
- **Size**: Inherits from parent
- **Weight**: 500 (Medium)
- **Color**: Secondary Blue (#3B82F6)
- **Hover**: Primary Blue (#1E3A8A)
- **Underline**: On hover and focus

#### Buttons
- **Size**: 16px (1rem)
- **Weight**: 500 (Medium)
- **Line Height**: 1.5 (24px)
- **Letter Spacing**: 0.025em

#### Labels
- **Size**: 14px (0.875rem)
- **Weight**: 500 (Medium)
- **Line Height**: 1.57 (22px)
- **Color**: Gray 700 (#374151)

## Multilingual Typography

### Hindi (Devanagari)
- **Font**: Noto Sans Devanagari
- **Size**: +2px larger than English equivalent
- **Line Height**: +0.1 multiplier for better readability
- **Weight**: Same as English equivalent

### Regional Languages
- **Fallback**: Noto Sans (supports 800+ languages)
- **Size**: Adjusted per language requirements
- **Direction**: RTL support for Urdu and Arabic

## Accessibility Guidelines

### Minimum Sizes
- **Body text**: Minimum 16px for accessibility
- **Touch targets**: Minimum 44px height for mobile
- **Line spacing**: Minimum 1.5x font size
- **Paragraph spacing**: Minimum 2x font size

### Color Contrast
- **Normal text**: 4.5:1 contrast ratio minimum
- **Large text** (18px+): 3:1 contrast ratio minimum
- **Focus indicators**: 3:1 contrast with background

### Responsive Scaling
- **Base**: 16px (1rem)
- **Small screens**: Scale down 10-15%
- **Large screens**: Scale up 10-15%
- **User zoom**: Support up to 200% without horizontal scroll

## Usage Guidelines

### Hierarchy
1. Use consistent heading levels (don't skip levels)
2. Maintain visual hierarchy through size and weight
3. Use color sparingly for emphasis
4. Ensure adequate spacing between elements

### Readability
- **Line length**: 45-75 characters for optimal reading
- **Paragraph spacing**: Use margin-bottom for separation
- **Text alignment**: Left-aligned for LTR languages
- **Justification**: Avoid justified text in UI

### Performance
- **Font loading**: Use font-display: swap
- **Subsetting**: Include only required character sets
- **Preloading**: Critical fonts loaded first

## CSS Implementation

```css
/* Font families */
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
--font-hindi: 'Noto Sans Devanagari', 'Inter', sans-serif;
--font-mono: 'JetBrains Mono', 'Fira Code', monospace;

/* Typography scale */
--text-xs: 12px;
--text-sm: 14px;
--text-base: 16px;
--text-lg: 18px;
--text-xl: 20px;
--text-2xl: 24px;
--text-3xl: 32px;

/* Line heights */
--leading-tight: 1.25;
--leading-normal: 1.5;
--leading-relaxed: 1.67;

/* Font weights */
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
```

## Implementation Notes
- All typography classes available as utility classes
- Responsive typography built into component system
- Automatic language detection switches font families
- Font loading optimized for performance
- Consistent vertical rhythm maintained across all text elements