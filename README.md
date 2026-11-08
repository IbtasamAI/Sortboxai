# Sortbox

Sort any pile of files by what is in the photos, file type, extension, date, size or name. Live thumbnails for every file type, bulk rename, duplicate cleanup, and animated 3D scenes.

Everything runs in your browser. Your files are never uploaded.

Built by [Ibtasam](https://github.com/IbtasamAI).

## Host it on GitHub Pages

1. Put `index.html` in the root of a repository.
2. Open Settings, then Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
3. Your app appears at `https://ibtasamai.github.io/<repo-name>/` after a minute.

## Notes

- The fonts, ZIP library, PDF previews and 3D model previews load from public CDNs, so the page needs internet the first time.
- "What's in the photo" sorting uses an on-device estimate on GitHub Pages. Claude vision is only available when the page runs inside claude.ai.
