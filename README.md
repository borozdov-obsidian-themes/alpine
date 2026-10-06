# Borozdov Alpine

A theme from the Borozdov collection. Two faces — dark **Summit**, alpine banking at blue
hour, and light **Snowline**, the same valley at noon. A navy-graphite night, ivory type,
light wide headlines, ghost pill buttons and one cobalt for what you act on.

![Borozdov Alpine in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/alpine/main/screenshots/dark.png)

![Borozdov Alpine in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/alpine/main/screenshots/light.png)

## Principles

- **Blue hour, not black.** The canvas is a navy-tinted onyx and cards are graphite, one
  value step above it; separation comes from that step alone — no borders, no shadows.
- **One cobalt, only for action.** Cobalt fills the main button, a checked task and a
  toggle, and nothing else. Links stay ivory with a fine underline and turn cobalt under
  the pointer.
- **A light, wide voice.** Alpine Sans Light for the title and headings, tracked open rather
  than tight, the calm of a mountain view; the platform's own sans for the text.
- **Pills for everything you press.** Buttons are ghost pills with an ivory rim, fields are
  pills on the obsidian surface, tags are pills with a slate rim.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Callouts as graphite cards with the title in the type's colour
- Tables with tabular figures, a hairline grid and 12px corners
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Alpine** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/alpine/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Alpine/`, then choose Borozdov Alpine under
Settings → Appearance → Themes.

## Font

Alpine Sans is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Fira Sans
Light (© 2012–2018 The Mozilla Foundation and Telefonica S.A.), renamed because a modified
copy may not use the original's Reserved Font Name. One weight, for the title and headings
only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Вершина» — альпийский банк в
синий час, и светлый «Снеговая линия» — та же долина в полдень. Сине-графитовая ночь, текст
цвета слоновой кости, лёгкие широкие заголовки (Alpine Sans Light), кнопки-пилюли без
заливки и один кобальтовый для того, что вы делаете. В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Alpine в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
