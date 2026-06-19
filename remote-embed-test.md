# Remote Embed — test note

Open this in **Reading view** (not Live Preview) after enabling the
**Remote Embed** plugin. Each section below should render inline.

---

## 0. Desktop screenshot — absolute path (wiki embed)

![[/Users/yk/Desktop/Screenshot 2026-06-03 at 09.29.06.png]]

## 1. Local image — absolute path (wiki embed)

![[/Users/yk/core/second_brain/gdrive/Polish legalisation/list od docs.png]]

## 2. Local PDF — absolute path (markdown syntax)

![](/Users/yk/core/second_brain/gdrive/fort_wola12a-32.pdf)

## 3. Local PDF — absolute path (wiki embed)

![[/Users/yk/core/second_brain/gdrive/Scanned 10 Jun 2024 at 20:28:59.pdf]]

## 4. Remote PDF over HTTPS

![](https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf)

## 5. Remote image over HTTPS (handled natively by Obsidian)

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/PNG_transparency_demonstration_1.png/320px-PNG_transparency_demonstration_1.png)

## 6. Remote markdown rendered inline

![](https://raw.githubusercontent.com/obsidianmd/obsidian-api/master/README.md)

## 7. Failure case — should show a friendly error box

![[/this/path/does/not/exist.png]]

---

### Notes
- Sections 2–4, 6, 7 exercise the plugin's own loading path (`fs` + `requestUrl`).
- Section 5 is a remote image; Obsidian renders these natively, so the plugin
  intentionally leaves it alone.
- If a section stays blank, switch to Reading view and confirm the plugin is
  enabled under Settings → Community plugins.
