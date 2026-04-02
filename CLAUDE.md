# worktalk Admin Dashboard Mockup

## Overview
worktalk 管理画面（企業管理画面・運営管理画面）のHTMLモックアップ

## Tech Stack
- Pure HTML/CSS (no build step)
- Google Fonts: Noto Sans JP, Inter
- Minimal inline JavaScript (sidebar toggle, query params)

## Pages
- `index.html` — Landing page (links to all views)
- `company-top.html` — 企業管理画面（カードあり）
- `company-top-nocard.html` — 企業管理画面（カードなし）
- `admin-top.html` — 運営管理画面（カードあり）
- `admin-top-nocard.html` — 運営管理画面（カードなし）

## Development
```bash
npx serve . -l 8767
```

## Publishing
- GitHub: https://github.com/onotaisei-create/worktalk-admin-mockup
- GitHub Pages: https://onotaisei-create.github.io/worktalk-admin-mockup/

## Conventions
- ASCII-only file/folder names
- Japanese text in HTML content only
- Commit messages in English
