# README-inspired portfolio design

## Source and scope

The identity and facts come from `~/adyshavefear/README.md`: Black Reaper, Oracle/PLSQL/APEX, red/cyan accents, UMTI/PMJP, IFPB, João Pessoa, and the existing contact URLs. Preserve existing portfolio projects and add the README's Oracle PL/SQL Toolkit. No changes to project repositories or profile README.

Three design concepts generated with the built-in Image Gen tool are the implementation references: `hero-concept.png`, `projects-concept.png`, `about-contact-concept.png`.

## Design system

- Background: dark navy black `#07090f`, not green or warm gray. Surface `#0a0d13`.
- Text `#e6edf3`, secondary `#a5acb6`, borders `#303641`.
- Accent red `#e50914`; cyan `#00d5e8` for code flags and contact.
- Inter, weights 400–800; JetBrains Mono for terminal and metadata. Self-hosted Latin fonts with OFL licenses.
- Open sections, no card grids. Header 100px. Desktop gutters 54px at 1488px; max container 1380px. Section spacing 100–120px.
- H1 108px desktop; H2 58–64px; hero subheading 42px; body 18–20px; mono metadata 12–16px. Scale down for mobile.
- Header: wordmark, Projetos / Sobre / Contato, outlined GitHub action. One red primary button; quiet secondary action. Corners 4px, hairline dividers.
- Arrows: 24x24 SVG, 1.6px stroke, currentColor; no symbol-font substitutions.
- Hero image: no tint or overlay. Caption beneath with a short red rule. Native text remains HTML.
- Projects: featured terminal + ABZSS copy; three unboxed supporting columns with vertical separators.
- About: two columns, facts and technology lines. Contact: open band, email and two social links. Footer: mark, phrase, back-to-top.
- Mobile: stacked hero, terminal and projects; no horizontal overflow or hidden essential links. Reduced motion: no smooth scroll, static image instead of animated GIF.

## Allowed hero copy (English localization)

ADONES. / Projects / About / Contact / GitHub / Adones Neto. / Databases. / Code with purpose. / Development with Oracle, PL/SQL, and APEX. Clear business logic and tools that simplify everyday work in the terminal. / Explore projects / Let's talk / THE BLACK REAPER / ADYSHAVEFEAR / DATABASE & DEVELOPMENT / Oracle / PL/SQL / APEX / Java / TypeScript / Python.

The user requested English after the visual redesign. Original concept images retain Portuguese lettering as historical visual references; all visible text, accessibility labels, page language and metadata are localized in HTML. Layout, identity assets and contact/repository destinations are preserved.

## Intentional adaptations

- Reuse the original Black Reaper GIF from the user's README instead of the concept's generated character portrait; preserve the real identity asset. A still frame is used for reduced motion.
- Terminal shows commands and an explicit illustrative caption, without the generated concept's fictional successful execution results.
- Small red text uses `#f52230` for contrast; decorative red and primary buttons retain `#e50914`.
- Responsive breakpoints stack the same content rather than inventing additional mobile components.

## Interaction scope

Native anchors navigate to projects/about/contact/top. External links open the actual repositories, GitHub and LinkedIn. Email opens mailto. No forms, tracking, backend, simulated live terminal or extra dependencies in the site.
