# Collegiate Academies Brand Template

A one-stop reference for colors, logos, and UI components across all CA schools. Open `index.html` in any browser, or visit the live site:

🔗 **[ca-brand-template — GitHub Pages link here]**

---

## What's in it

The template covers all 8 schools/programs in the CA network:

| School | Also known as |
|---|---|
| Collegiate Academies | Network |
| Abramson Sci Academy | ASA, Abe |
| Walter L. Cohen High School | WLC, Cohen |
| Collegiate Baton Rouge | CBR |
| G.W. Carver High School | GWC, Carver |
| Livingston Collegiate Academy | LCA, Livingston |
| Opportunities Academy | OA |
| Next Level NOLA | NLN |

For each school you'll find:
- **Official hex color codes** with one-click copy buttons
- **Logo previews** on dark, colored, and light backgrounds
- **Google Drive IDs** with copy-URL buttons for embedding logos in dashboards
- **Reusable UI components** — header bars, buttons, badge chips, and a table example — all in brand colors

The **CSS Variables** section at the bottom has a complete `:root {}` block you can copy directly into any new project.

---

## How to use it

### In a Google Apps Script / Sheets dashboard

Logos are served from Google Drive using this URL pattern:

```
https://drive.google.com/thumbnail?id=DRIVE_ID&sz=w200
```

Change `w200` to any width you need (e.g. `w50`, `w80`, `w400`). These load automatically for users who are signed into Google — no extra setup needed.

### In any HTML project

Copy the `:root {}` block from the CSS Variables section into your stylesheet, then reference variables like:

```css
header {
  background: var(--ca-blue);
}

.asa-button {
  background: var(--asa-red);
}
```

### Fonts

Per the CA Branding Guidelines:
- **Century Gothic** — preferred for all documents and external-facing materials
- **Helvetica** — use for long blocks of text where Century Gothic hurts readability
- **League Spartan / Avant Garde / Glacial Indifference** — for Canva designs

---

## Drive logo IDs

| School | Drive ID |
|---|---|
| Collegiate Academies | `1i13F1N3ygS5PIdP-biGSjzbdCrHeimGp` |
| Abramson Sci Academy | `1kB10pfBS6xoWvXlBjTrSDsIqNksTt5Md` |
| Walter L. Cohen | `1Zr_lwRpDoEW1RMlF38rQUATnDP5jaqcM` |
| Collegiate Baton Rouge | `1lEcQ-8KPpbJB7aAbniaRsMSiLQ55WstX` |
| G.W. Carver | `1XP35COaRQxc4JHGgBjtHfRc2AaxdsEQG` |
| Livingston Collegiate | `1R5-koraKmMovDxPsfL1FT-vVqnHtnltd` |
| Opportunities Academy | `1hTjXqiWAMbTDtli6H2PoTF_pRdlmwVCx` |
| Next Level NOLA | `1z0L93rMis7S148r5JGycz6G6nsTXG2GR` |

> **Note:** Logo images load from Google Drive and require viewers to be signed into a Google account with access. To make logos visible to anyone (including outside CA), set each Drive file to **"Anyone with the link can view"** — right-click the file in Drive → Share → change access.
>
> **Tip:** If logos look wrong after an update, do a hard reset in your browser (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows) to clear the cache.

---

## Updating this template

1. Edit `index.html` directly in GitHub, or clone the repo and edit locally
2. Commit changes to `main` — GitHub Pages will redeploy automatically within a minute or two
3. If a school gets new branding, update both the hex values in the `:root {}` block and the Drive ID in the logo showcase section
4. When updating a Drive ID, replace all occurrences — each school's ID appears 7 times in the file (badge, 3 logo variant tiles, drive-ref line, header bar component, and the reference table)

---

## Related resources

- [CA Branding Guidelines (PDF)](https://drive.google.com) — update this link
- [CA Google Slides Template](https://drive.google.com) — update this link
- [CA Google Docs Letterhead](https://drive.google.com) — update this link

---

*Maintained by the CA Data & Operations team*
