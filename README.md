# SanForum Theme 2.0 – Star of Life

Discourse-Theme für sanforum.at. Farbwelt: klassisches Star-of-Life-Blau (#0057A8) als Primärfarbe, Tagesleuchtgelb (#E9FF00) als sparsamer Akzent (aktiver Tab, ungelesen, Moderator-Badge, Fokus-Ring).

## Installation

1. Ordner `theme/` als Theme hochladen (oder Repo als Theme-Quelle eintragen).
2. **Admin › Themes & components**: Farbpalette wählen
   - `sanforum-hell` → Variante Hell (weißer Header)
   - `sanforum-blau` → **empfohlen**: blauer Header + Bannerfläche, Kategorien als breite Karten mit Farbkante. Die Variante schaltet sich automatisch über `header_background` um.
   - `sanforum-dunkel` als Dark color palette.
3. **Admin › Interface & layout**: Top menu `categories, latest, unread, top`; Desktop category page style `Boxes with Subcategories`.
4. **Admin › Welcome banner**: für dieses Theme aktivieren, Homepage only, Below site header.
5. Logo: `assets/logo-light.png` (hell) bzw. `assets/logo-dark.png` (blau/dunkel) unter **Admin › Branding** als Logo / Dark-Logo hochladen.

## Hinweise

- Schriften: Barlow (Überschriften) + Source Sans 3 (Fließtext) via Google Fonts. Falls die CSP das blockiert, `@import url(...)` in `common/common.scss` entfernen und die Fonts als Theme-Assets einbinden.
- Discourse-Selektoren ändern sich gelegentlich; die Blöcke sind nach Seitenbereich gruppiert und einzeln anpassbar.
