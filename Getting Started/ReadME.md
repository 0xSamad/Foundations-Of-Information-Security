# Tools & Workflows — Sync, Notes, Screenshots & Logging

_Short guide: Firefox Sync, Notion, XMind, Flameshot, Peek, and `script`._

---

## Firefox Sync
- Use a **dedicated pentest Firefox account** for bookmarks & add-ons.  
- Steps: Menu → **Sign in to Firefox** → enable **Bookmarks** & **Add-ons**.  
- Export bookmarks locally: Bookmarks → Show All Bookmarks → Import and Backup → **Export Bookmarks to HTML**.  
- **Do not** store client-sensitive URLs or credentials in a synced account.

---

## Notion.so
- Use for collaborative, non-sensitive notes. Layout: `ENG-YYYY-MM-DD-Client` → `Summary | Findings | Commands | Screenshots`.  
- Export for archive: File → Export → **Markdown & CSV**.  
- For sensitive/local notes prefer Obsidian or plain Markdown stored in your repo.

---

## XMind
- Use mind maps for planning: attack paths, checklists, phases.  
- Save `.xmind` files in `notes/` and export PDF/PNG for reports.

---

## Flameshot
- Lightweight screenshot + annotation tool.  
- Install (Debian/Ubuntu/Kali):
  ```bash
  sudo apt update && sudo apt install flameshot

