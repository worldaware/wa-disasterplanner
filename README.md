# Disaster-Plan-Generator
A business focused risk assessment and disaster plan generator

## Brand and Word output

- Design system: World Aware tokens (`css/tokens.css`), self-hosted Space Grotesk and Poppins (`css/fonts.css`, `fonts/`), app styles in `css/brand.css`, Lucide icons in `js/icons.js` (source SVGs in `icons/`), logos in `assets/`.
- The generated .docx uses Calibri with brand colors, the logo (fetched from `assets/wa-lockup-full-color.png` at generation time) on the cover and in every header, and beworldaware.com in every footer.
- **Fields to complete in Word**: any `[BRACKETED]` text, plus fields left blank in the content library, is set in the **WA Placeholder** character style: italic dark amber on a pale amber highlight. It replaces the old orange bold `[PLACEHOLDER]` text. In Word, select the field and type over it. To find any left over, use Find for `[`.
